## Challenge Telecom X (Parte I) – Alura Latam

--------------------------------------------

## 📝 INTRODUCCIÓN
En este proyecto se trabajará con datos de clientes de la empresa de telecomunicaciones **Telecom X**, con el objetivo de comprender los factores que influyen en la cancelación del servicio (*churn*).

----------------------

## PASOS A SEGUIR:

1. **Extracción:** Obtención de los datos desde una fuente externa en formato JSON, ubicada en:  
   [TelecomX_Data.json](https://raw.githubusercontent.com/alura-cursos/challenge2-data-science-LATAM/main/TelecomX_Data.json)
   
2. **Transformación:** Limpieza, tratamiento y estandarización de la información, garantizando su calidad y consistencia para el análisis posterior.

3. **Exploración:** Identificar patrones, relaciones y posibles indicadores asociados a la cancelación del servicio, mediante gráficos, tablas, etc.

4. **Conclusiones:** Definir las posibles causas de CHURN, determinar cuáles son las mejores variables para predecir.
   
5. **Recomendaciones:** Indicar medidas para reducir y evitar el CHURN.

***Te invito a revisar el documento telecomX_ALURA.ipynb adjunto en el proyecto para visualizar los gráficos y sus respectivos análisis en detalle***

----------------------------------------

## 📝 CONCLUSIÓN:

El Churn se ve fuertemente influenciado por la duración del contrato, los métodos de pago, la edad del cliente y la contratación de servicios adicionales. Variables operativas o demográficas como género o servicios básicos tienen impacto limitado.

**Consideraciones para modelado:**
* Variables altamente correlacionadas (tenure y TotalCharges, StreamingTV y StreamingMovies) deben manejarse con cuidado para evitar multicolinealidad en modelos sensibles.
* Las variables más predictivas y relevantes para modelado son: Contract, PaymentMethod, OnlineSecurity, TechSupport, SeniorCitizen, Tenure, MonthlyCharges.

----------------------------------

## 🌟 RECOMENDACIONES PARA REDUCIR CHURN:

1. 📝 Fortalecer la fidelización mediante contratos.
2. 💳 Optimizar métodos de pago.
3. 🛡 Mejorar servicios de valor agregado.
4. ⚠ Atender a clientes de mayor riesgo.
5. 🎁 Incentivar la permanencia de clientes de largo plazo.
6. ⚙ Optimizar esfuerzos en servicios de bajo impacto.
7. 📊 Monitoreo y análisis continuo.

--------------------------

## TECNOLOGÍAS UTILIZADAS

- **Python**: Lenguaje para el análisis de datos.
  
------

## CARGAR EL PROYECTO O CLONAR:

   Abre tu terminal o línea de comandos y ejecuta el siguiente comando para clonar el proyecto:

   ```bash
   git clone https://github.com/frantholy/rendimiento_tiendas_ALURA
```

------------------
