# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 2 correctas de 9 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.36 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 3: Error
- **Descripción**: 'NoneType' object is not iterable


## ❌ Query 4: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,12 @@
-nombre | precio_eur | precio_usd
-Disco duro SATA3 1TB | 86.99 | 86.99
-Memoria RAM DDR4 8GB | 120.00 | 120.00
-Disco SSD 1 TB | 150.99 | 150.99
-GeForce GTX 1050Ti | 185.00 | 185.00
-GeForce GTX 1080 Xtreme | 755.00 | 755.00
-Monitor 24 LED Full HD | 202.00 | 202.00
-Monitor 27 LED Full HD | 245.99 | 245.99
-Portátil Yoga 520 | 559.00 | 559.00
-Portátil Ideapd 320 | 444.00 | 444.00
-Impresora HP Deskjet 3720 | 59.99 | 59.99
-Impresora HP Laserjet Pro M26nw | 180.00 | 180.00
+codigo | nombre | precio | codigo_fabricante
+1.00 | Disco duro SATA3 1TB | 86.99 | 5.00
+2.00 | Memoria RAM DDR4 8GB | 120.00 | 6.00
+3.00 | Disco SSD 1 TB | 150.99 | 4.00
+4.00 | GeForce GTX 1050Ti | 185.00 | 7.00
+5.00 | GeForce GTX 1080 Xtreme | 755.00 | 6.00
+6.00 | Monitor 24 LED Full HD | 202.00 | 1.00
+7.00 | Monitor 27 LED Full HD | 245.99 | 1.00
+8.00 | Portátil Yoga 520 | 559.00 | 2.00
+9.00 | Portátil Ideapd 320 | 444.00 | 2.00
+10.00 | Impresora HP Deskjet 3720 | 59.99 | 3.00
+11.00 | Impresora HP Laserjet Pro M26nw | 180.00 | 3.00
```

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 5: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,12 @@
-nom del producte | euros | dòlars
-Disco duro SATA3 1TB | 86.99 | 95.69
-Memoria RAM DDR4 8GB | 120.00 | 132.00
-Disco SSD 1 TB | 150.99 | 166.09
-GeForce GTX 1050Ti | 185.00 | 203.50
-GeForce GTX 1080 Xtreme | 755.00 | 830.50
-Monitor 24 LED Full HD | 202.00 | 222.20
-Monitor 27 LED Full HD | 245.99 | 270.59
-Portátil Yoga 520 | 559.00 | 614.90
-Portátil Ideapd 320 | 444.00 | 488.40
-Impresora HP Deskjet 3720 | 59.99 | 65.99
-Impresora HP Laserjet Pro M26nw | 180.00 | 198.00
+nombre | precio_eur | precio_usd
+Disco duro SATA3 1TB | 86.99 | 86.99
+Memoria RAM DDR4 8GB | 120.00 | 120.00
+Disco SSD 1 TB | 150.99 | 150.99
+GeForce GTX 1050Ti | 185.00 | 185.00
+GeForce GTX 1080 Xtreme | 755.00 | 755.00
+Monitor 24 LED Full HD | 202.00 | 202.00
+Monitor 27 LED Full HD | 245.99 | 245.99
+Portátil Yoga 520 | 559.00 | 559.00
+Portátil Ideapd 320 | 444.00 | 444.00
+Impresora HP Deskjet 3720 | 59.99 | 59.99
+Impresora HP Laserjet Pro M26nw | 180.00 | 180.00
```

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 6: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,12 @@
-nombre | precio
-DISCO DURO SATA3 1TB | 86.99
-MEMORIA RAM DDR4 8GB | 120.00
-DISCO SSD 1 TB | 150.99
-GEFORCE GTX 1050TI | 185.00
-GEFORCE GTX 1080 XTREME | 755.00
-MONITOR 24 LED FULL HD | 202.00
-MONITOR 27 LED FULL HD | 245.99
-PORTÁTIL YOGA 520 | 559.00
-PORTÁTIL IDEAPD 320 | 444.00
-IMPRESORA HP DESKJET 3720 | 59.99
-IMPRESORA HP LASERJET PRO M26NW | 180.00
+nombre | precio_eur | precio_usd
+Disco duro SATA3 1TB | 86.99 | 95.69
+Memoria RAM DDR4 8GB | 120.00 | 132.00
+Disco SSD 1 TB | 150.99 | 166.09
+GeForce GTX 1050Ti | 185.00 | 203.50
+GeForce GTX 1080 Xtreme | 755.00 | 830.50
+Monitor 24 LED Full HD | 202.00 | 222.20
+Monitor 27 LED Full HD | 245.99 | 270.59
+Portátil Yoga 520 | 559.00 | 614.90
+Portátil Ideapd 320 | 444.00 | 488.40
+Impresora HP Deskjet 3720 | 59.99 | 65.99
+Impresora HP Laserjet Pro M26nw | 180.00 | 198.00
```

⏱ Tiempo: 0.31 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 7: Incorrecto
```diff
--- 
+++ 
@@ -1,12 +1,12 @@
-nombre | precio
-disco duro sata3 1tb | 86.99
-memoria ram ddr4 8gb | 120.00
-disco ssd 1 tb | 150.99
-geforce gtx 1050ti | 185.00
-geforce gtx 1080 xtreme | 755.00
-monitor 24 led full hd | 202.00
-monitor 27 led full hd | 245.99
-portátil yoga 520 | 559.00
-portátil ideapd 320 | 444.00
-impresora hp deskjet 3720 | 59.99
-impresora hp laserjet pro m26nw | 180.00
+UPPER(p.nombre) | precio
+DISCO DURO SATA3 1TB | 86.99
+MEMORIA RAM DDR4 8GB | 120.00
+DISCO SSD 1 TB | 150.99
+GEFORCE GTX 1050TI | 185.00
+GEFORCE GTX 1080 XTREME | 755.00
+MONITOR 24 LED FULL HD | 202.00
+MONITOR 27 LED FULL HD | 245.99
+PORTÁTIL YOGA 520 | 559.00
+PORTÁTIL IDEAPD 320 | 444.00
+IMPRESORA HP DESKJET 3720 | 59.99
+IMPRESORA HP LASERJET PRO M26NW | 180.00
```

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 8: Incorrecto
```diff
--- 
+++ 
@@ -1,10 +1,12 @@
-nombre | iniciales
-Asus | AS
-Lenovo | LE
-Hewlett-Packard | HE
-Samsung | SA
-Seagate | SE
-Crucial | CR
-Gigabyte | GI
-Huawei | HU
-Xiaomi | XI
+LOWER(nombre) | precio
+disco duro sata3 1tb | 86.99
+memoria ram ddr4 8gb | 120.00
+disco ssd 1 tb | 150.99
+geforce gtx 1050ti | 185.00
+geforce gtx 1080 xtreme | 755.00
+monitor 24 led full hd | 202.00
+monitor 27 led full hd | 245.99
+portátil yoga 520 | 559.00
+portátil ideapd 320 | 444.00
+impresora hp deskjet 3720 | 59.99
+impresora hp laserjet pro m26nw | 180.00
```

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 9: Error
- **Descripción**: 'NoneType' object is not iterable

