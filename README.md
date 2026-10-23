# 🎫 Showz - Análisis de LTV, CAC y ROMI para E-commerce de Boletos

> ¿Cuánto dinero deja cada cliente, cuándo recuperamos lo que pagamos por traerlo y en qué canal de marketing debemos invertir?

📊 **Datasets:** `visits` (sesiones) | `orders` (ingresos) | `costs` (gasto en ads)
🐍 **Stack:** Python | Pandas | Cohort Analysis | LTV | CAC | ROMI | Marketing Analytics

---

### 🎯 Contexto de Negocio

Showz vende boletos online y gasta dinero en 5 fuentes de adquisición. El equipo de marketing no sabe:
1. Cuánto tarda un usuario en comprar desde que entra.
2. Cuánto dinero trae cada cliente (LTV).
3. Si la inversión en ads es rentable y cuándo se recupera (ROMI).

**Mi rol:** Medir todo el embudo de marketing: de visita a cliente, de cliente a dinero, y de dinero a rentabilidad.

---

### 🔍 Qué hice - 3 Fases

**FASE 1: 
### Tenenmos un conteo por usuario en el cual diariamente de 364 sessiones, 54 semanales y 12 sesiones mensuales. 
### Tenenmos un promedio diario de sesiones de 987.3626373626373 .
### Tenemos un promedio semanal de sesiones de 6781.132075471698 .
### Y un promedio mensual de session de 29950.0 .
### El promedio de tiempo para un usuario nuevo  es de 8.442896 minutos.
### El promedio para un usuario recurrente es de 13.292469 minutos.
### Porcentaje de usuarios que regresan: 19.74% 

**FASE 2: Ventas**
#### 2.1 Se realizaron segmentos de tiempo juntando los Data Frame visitas y ordenes, para obtnenr listas diarias, semanales, mensuales, trimestrales y anuales, se tomaron en cuenta solo 4 de elllas, diaria, semanal, mensual y anual, ya que la trimestral no arrojaba datos tan relebantes.
#### En el registro diario obtubimos un relstado favorable:  25039 personas que registraron y compraron.
#### En el registro semanal:  4297 , En el mensual: 6550 y en el Anual 11482.
#### De los canales disponbles para el registro y compra (10 en total que se encuentran en el Data Frame), se determino que los canales 4,3 y 5 son los mas efectivos para captar usuarios, destaca el canal 5 en el segmento diario, el numero 4 en el semanal, mensual y anual, el canal numero 3 se mantiene con metricas que compiten, pero quiza un pequeño impulso mediante una promocion o veneficio, podria ponerlo a la para en procentajes.

**FASE 3: Marketing y Rentabilidad (Costs)**
-
### Tenemos un pormedio de compra de 4.89 
### La mayoría de usuarios tienen un promedio de compra muy bajo (cerca de $0-$5)
### Muy pocos usuarios tienen promedios de compra altos 
### Ingresos totales: 
### MISMO DIA : $147072.75 (el mas alto)
### SEMANAL: $35403.22
### MENSUAL: $65401.85
### Ingresos promedio por usuario:
### MISMO DIA: $5.87
### SEMANAL: $8.24
### MENSUAL: $9.99(el mas alto)
### Si bien es cierto que el ingreso por grupo demuestra diferencias bastante notables, al final el promedio por ususario revela algo contradictorio, es calro que tenener, un grupo que compra poco, en un perido corto puede ser algo bueno, tener un grupo pequeño que gasta mas y de manera recurrente puede reultar en mejores ingresos para la compañia, ya que queda claro que son usuarios leales y que se quedan por periodos largos de tiempo. Seria bueno paltear una estrategia enfocada a mantener a este tipo de udsuarios, y que se garantice una mejor 
retencion de usuaruios a largo plaso.

### Curiosamente el canal 3 es el mas caro y el que menos beneficio trae, pero aparece como de los mas efectivos al principio del analisis, Volumen vs Eficiencia, atrae mucho pero con un costo elevado, sus usuarios, compran mucho al principio, pero despues se van.
### Los canales 1 y dos tienen una relacion costo beneficio excelente, ya que ofrecen un costo moderado y una ganancia significativa
### los canales 4 y 5 se mantienen equilibrados y moderados.

## Estrategia sugerida:
### Reasignar presupuesto, y ajustar apara mejorar los canles que tienen verdadero venefio a la compañia, seguir apoyando el canal numero tres pero con un nuevo enfoque, quiza apuntar a beneficios y promociones que aseguren la permanencia y el flujo constante de compra. 

---

### 📊 Hallazgos Clave

**1. ### Se calcularon los costos totales, dando como resultado "Total gastado en marketing: $329,131.62"
### De igual manera se calcularon los gastos por fuente de adquisicion, ademas de calcularse por mes y tambien por año, resalta que el año  2017 fue el mas caro de la empresa, lo cual demuestra que los inicias siempre son complicados, pero con perseverancia se logra el equilibrio 

**2. ### Resaltan en costo por adquisicion de cliente, los mas caros son los canales 1, 2 y 3 y 4, 10 y nueve fueron los mas economicos de la lista.

---

### 💼 Recomendación Final para Marketing

> **Decisión: Reasignar presupuesto inmediatamente.**

### 👨‍💻 Autor
Cesar R. | Marketing & Data Analyst Jr. | GDL
