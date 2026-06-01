# The-Numbers
**The numbers… what do they mean?**

Se nos proporciona la siguiente imagen:

<img width="387" height="217" alt="the_numbers" src="https://github.com/user-attachments/assets/f69040e6-6b30-47ca-9fc1-779b5a984a54" />


A primera vista los números tienen la típica forma de flag de pico que es picoctf{…}, si vemos el primero numero que es 16 y buscamos que letra del abecedario, sin la ñ, es la el numero 16 encontramos que es la letra p, si vemos a cual letra corresponde el numero 9 encontramos que es la i por lo que cada numero es una letra del abecedario.

Se realizo un pequeño código en Python para sacar las letras:

**Codigo = [16, 9, 3, 15, 3, 20, 6, 20, 8, 5, 14, 21, 13, 2, 5, 18, 19, 13, 1, 19, 15, 14]**

**Abecedario = "abcdefghijklmnopqrstuvwxyz"**

**def desencriptar(codigo):**
    **resultado= ""**
    **for i in codigo:**
        **resultado +=Abecedario[i-1]**
    **return resultado**

**desencriptado = desencriptar(Codigo)**

**print(desencriptado)**

**El resultado es: picoctfthenumbersmason**

Agregamos las llaves y tenemos:

**picoctft{henumbersmason}**

Subimos la flag a picoctf y listo.

<img width="758" height="111" alt="Captura de pantalla 2026-05-31 182530" src="https://github.com/user-attachments/assets/6c412739-3acd-484e-8e52-dc2a922c0b69" />
