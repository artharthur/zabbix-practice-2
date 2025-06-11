# zabbix-practice-2

---

## Задание 1. Создание собственного шаблона

**Задание:**  
Создайте свой шаблон, в котором будут элементы данных, мониторящие загрузку CPU и RAM хоста.

**Решение:**

1. Создан шаблон **Template CPU_RAM** в **Data collection → Templates**:  
   ![Template CPU_RAM](screenshots/template-cpu-ram.png)

2. Элемент данных для CPU (ключ `system.cpu.util[,user]`):
   ![Item CPU](screenshots/item-cpu.png)

3. Элемент данных для RAM:
   ![Item RAM](screenshots/item-ram.png)

---

## Задание 2. Добавление двух хостов

**Задание:**  
Добавьте в Zabbix два хоста и задайте им имена ishmakov-am-1 и ishmakov-am-2.

**Решение:**
1. Переименованы хосты:
   ![Hosts Names](screenshots/hosts-names.png)

---

## Задание 3. Привязка шаблонов к хостам

**Решение:**

1. Привязка шаблонов к `ishmakov-am-1`:  
   ![Bindings 1](screenshots/hosts-bindings-1.png)

2. Привязка шаблонов к `ishmakov-am-2`:  
   ![Bindings 2](screenshots/hosts-bindings-2.png)

## Задание 4. Кастомный дашборд

**Решение:**

![Dashboard](screenshots/dashboard-4.png)
