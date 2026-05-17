---
aliases:
tags:
  - архитектура
родитель:
  - "[[Grid]]"
---
Информация о наличии кораблей и их состоянии

Enum state
- NONE
- SHIP_ALIVE
- SHIP_HIT
- SHIP_DEAD

CreateShip(int x, int y)
AttackCell(int x, int y)

CheckCell(vector2i cell)
CheckAdjacentCells(vector2i cell)
CheckNextCell(vector2i cell, vector2i direction)