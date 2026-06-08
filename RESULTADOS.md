# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 23 correctas de 28 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.38 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 6: Correcto

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 7: Correcto

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 8: Correcto

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 9: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 10: Correcto

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 11: Correcto

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 12: Correcto

⏱ Tiempo: 0.30 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ✅ Query 13: Correcto

⏱ Tiempo: 0.26 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 14: Correcto

⏱ Tiempo: 0.26 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 15: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 16: Correcto

⏱ Tiempo: 0.25 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 17: Correcto

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 18: Correcto

⏱ Tiempo: 0.26 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 19: Correcto

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 20: Correcto

⏱ Tiempo: 0.28 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ✅ Query 21: Correcto

⏱ Tiempo: 0.31 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---

## ✅ Query 22: Correcto

⏱ Tiempo: 0.31 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---

## ❌ Query 23: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-codigo | nombre | codigo fabricante | nombre fabricante
+codigo | nombre | codigo fabricante | nombre del fabricante
 1.00 | Disco duro SATA3 1TB | 5.00 | Seagate
 2.00 | Memoria RAM DDR4 8GB | 6.00 | Crucial
 3.00 | Disco SSD 1 TB | 4.00 | Samsung
```

⏱ Tiempo: 0.31 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---

## ❌ Query 24: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,2 @@
-nombre | precio | fabricant
+nombre | precio | fabricante
 Impresora HP Deskjet 3720 | 59.99 | Hewlett-Packard
```

⏱ Tiempo: 0.31 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---

## ✅ Query 25: Correcto

⏱ Tiempo: 0.29 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante, PRIMARY

---

## ❌ Query 26: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'FROM producto p
JOIN fabricante f
ON p.codigo_fabricante = f.codigo
WHERE f.nomb' at line 4


## ❌ Query 27: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'FROM producto p
JOIN fabricante f
ON p.codigo_fabricante = f.codigo
WHERE f.nomb' at line 4


## ❌ Query 28: Error
- **Descripción**: 'NoneType' object is not iterable

