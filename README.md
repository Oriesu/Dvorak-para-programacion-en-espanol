# Dvorak-para-programación-en-español

Distribución de teclado personalizada para Ubuntu/Linux basada en un teclado físico ISO español/QWERTY, pensada para escribir en español y programar con más comodidad.

El objetivo es mantener una escritura cómoda en español, facilitar símbolos de programación y conservar los atajos más comunes por posición física QWERTY cuando se usa la distribución personalizada.

---

## Características principales

- Base tipo Dvorak adaptada al español.
- Mantiene `ñ`, tildes, diéresis y signos españoles.
- Incluye símbolos de programación agrupados de forma intuitiva.
- Pensada para teclado físico ISO español.
- Los números pueden seguir usándose desde el teclado numérico.
- Usa `AltGr` para símbolos adicionales.
- Usa `keyd` para conservar atajos frecuentes por posición física QWERTY.
- El modo español normal queda intacto.

---

## Distribución principal

### Sin Shift

```text
┌────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┐
│ \  │ !  │ [  │ {  │ (  │ <  │ =  │ *  │ &  │ $  │ #  │ ^  │ `  │
├────┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴────┤
│   .   │  , │  ñ │  p │  y │  f │  g │  c │  h │  l │  ? │  -   │
├───────┴┬───┴┬───┴┬───┴┬───┴┬───┴┬───┴┬───┴┬───┴┬───┴┬───┴──────┤
│    a   │  o │  e │  u │  i │  d │  r │  t │  n │  s │   ´      │
├────────┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──────────┤
│     <     │  " │  q │  j │  k │  x │  b │  m │  w │  v │  z    │
└───────────┴────┴────┴────┴────┴────┴────┴────┴────┴────┴───────┘
```
### Con Shift
```text
┌────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┐
│ |  │ ¡  │ ]  │ }  │ )  │ >  │ +  │ /  │ @  │ €  │ %  │ √  │ ~  │
├────┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴────┤
│   :   │  ; │  Ñ │  P │  Y │  F │  G │  C │  H │  L │  ¿ │  _   │
├───────┴┬───┴┬───┴┬───┴┬───┴┬───┴┬───┴┬───┴┬───┴┬───┴┬───┴──────┤
│    A   │  O │  E │  U │  I │  D │  R │  T │  N │  S │   ¨      │
├────────┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──────────┤
│     >     │  ' │  Q │  J │  K │  X │  B │  M │  W │  V │  Z    │
└───────────┴────┴────┴────┴────┴────┴────┴────┴────┴────┴───────┘
```
### AltGr
```text
┌────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┬────┐
│ º  │ 1  │ 2  │ 3  │ 4  │ 5  │ 6  │ 7  │ 8  │ 9  │ 0  │ °  │ ´  │
├────┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴────┤
│   <   │  > │  [ │  ] │  { │  } │  ( │  ) │  / │  \ │  | │  _   │
├───────┴┬───┴┬───┴┬───┴┬───┴┬───┴┬───┴┬───┴┬───┴───┬───┴───────┤
│   @    │  # │  € │  _ │  | │  $ │  √ │  ~ │   :   │   ;       │
├────────┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬─┴──┬────┴┬───┴──────┤
│           │  ` │ ¿ │ ¡ │ % │ ^ │ ! │ — │ / │ « │ »            │
└───────────┴────┴───┴───┴───┴───┴───┴───┴──┴───┴───────────────┘
```
## Atajos conservados por posición física QWERTY

En modo programador, estos atajos funcionan como si el teclado siguiera siendo QWERTY físicamente.
```
Ctrl
Ctrl + A              Ctrl + C              Ctrl + S              Ctrl + G              Ctrl + V              Ctrl + X              Ctrl + F
Ctrl + Z              Ctrl + Y              Ctrl + T              Ctrl + W              Ctrl + N              Ctrl + O              Ctrl + P
Ctrl + L              Ctrl + R              Ctrl + H              Ctrl + Q              Ctrl + D              Ctrl + E              Ctrl + K
Ctrl + U              Ctrl + I              Ctrl + B              Ctrl + /              Ctrl + Space          Ctrl + +              Ctrl + -
Ctrl + 0              Ctrl + Shift          Ctrl + Shift + Z      Ctrl + Shift + C      Ctrl + Shift + V


Alt izquierdo         Alt + Tab             Alt + Shift + Tab     Alt + F2              Alt + F4              Alt + Enter           Alt + ←
Alt + →               Alt + letra


Ctrl + Alt            Ctrl + Alt + T


Super                 Super + L             Super + D             Super + Space         Super + A             Super + Tab
Super + ↑             Super + ↓             Super + ←             Super + →             Super + 1             Super + 2
Super + 3             Super + 4             Super + 5             Super + 6             Super + 7             Super + 8
Super + 9             Super + 0             Super + PageUp        Super + PageDown
```
El Alt usado para atajos es el izquierdo.
AltGr queda libre para escribir símbolos del layout.

