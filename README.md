# localizar-posicao-mouse
Um código utilizando a linguagem python, na biblioteca pyautogui que tem como função localizar a posição do mouse e informar no terminal. Usado principalmente para localizar posições na tela para futuras funções de automação usando a mesma biblioteca.

import pyautogui as pa
import time
import pyperclip

time.sleep(3)
print(pa.position())
