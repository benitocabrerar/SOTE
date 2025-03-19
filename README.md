# Simulador Avanzado del Oleoducto Trans Ecuatoriano SOTE

## 🛢️ Descripción

El **Simulador Avanzado del Oleoducto Trans Ecuatoriano (SOTE)** es una herramienta interactiva de código abierto diseñada para modelar, visualizar y analizar las operaciones del Sistema de Oleoducto Transecuatoriano. Esta aplicación web permite a los usuarios manipular parámetros operativos clave, evaluar escenarios de riesgo y comprender los complejos equilibrios del sistema que transporta cerca de 360.000 barriles de petróleo diarios a lo largo de 485 kilómetros, atravesando uno de los corredores ecológicos más diversos del planeta.

## ✨ Características

- **Modelado geográfico preciso** basado en datos reales del SOTE
- **Interfaz interactiva** con controles deslizantes para manipular:
  - Caudal (100,000 - 450,000 barriles por día)
  - Presión (800 - 1,500 PSI)
  - Temperatura (20° - 60°C)
  - Viscosidad (100 - 500 cP)
  - Eficiencia de bombeo (70% - 100%)
  - Nivel de mantenimiento (50% - 100%)
- **Visualización del sistema completo** con 6 estaciones de bombeo y 4 estaciones reductoras
- **Perfil de elevación** que muestra el recorrido desde la Amazonía (Lago Agrio) hasta la Costa Pacífica (Esmeraldas)
- **Simulación avanzada de fluidos** con ajuste dinámico de parámetros
- **Módulos de análisis especializado**:
  - Datos en tiempo real (caudal, consumo energético, eficiencia, tiempo de tránsito)
  - Detalles por estación con monitoreo individual de presiones y estados
  - Análisis de eficiencia con recomendaciones operativas
- **Herramientas de seguridad y análisis de riesgos**:
  - Optimización automática de parámetros operativos
  - Simulación de condiciones de emergencia
  - **Modelado avanzado de roturas** con estimación de:
    - Tiempo de respuesta de sistemas de seguridad
    - Tasas de derrame por minuto
    - Volumen total de derrame
    - Área potencialmente afectada
    - Costos de limpieza y remediación
    - Desglose temporal detallado de escenarios

## 🚀 Instalación

El simulador es una aplicación web estática, lo que significa que no requiere instalación de servidor o base de datos. Simplemente clona este repositorio y abre el archivo HTML en cualquier navegador moderno.

```bash
git clone https://github.com/benitocabrera/sote-simulator.git
cd sote-simulator
open index.html  # o doble clic en el archivo
```

## 💻 Uso

1. **Ajuste los parámetros** utilizando los controles deslizantes
2. **Seleccione escenarios predefinidos** del menú desplegable (Operación Normal, Alta Demanda, Mantenimiento, Emergencia)
3. **Explore las diferentes pestañas** para analizar distintos aspectos del sistema
4. **Utilice las herramientas de análisis**:
   - "Optimizar Parámetros" para encontrar configuraciones eficientes
   - "Simular Emergencia" para evaluar condiciones críticas
   - "Simular Rotura Total" para análisis detallado de derrames potenciales

## 🔬 Fundamento Técnico

Este simulador integra modelos matemáticos complejos basados en:
- Ecuaciones de Bernoulli para dinámica de fluidos
- Cálculos de pérdida de presión Darcy-Weisbach
- Modelado de viscosidad en función de temperatura
- Algoritmos de eficiencia energética
- Análisis topográfico con compensación gravitacional

Los parámetros y la configuración del sistema están calibrados según datos históricos y técnicos del SOTE, con particular atención a las diferencias altitudinales que afectan la dinámica del sistema.

## 🌍 Aplicaciones

El simulador ha sido diseñado para múltiples propósitos:

- **Capacitación técnica** para ingenieros petroleros y operadores
- **Estudios de impacto ambiental** y análisis de riesgos
- **Planificación de contingencias** y protocolos de emergencia
- **Evaluación de rendimiento** y optimización de recursos
- **Educación superior** en ingeniería de hidrocarburos
- **Investigación** para desarrollo de mejores prácticas operativas

## 📊 Capturas de Pantalla


## 🔧 Tecnologías

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Visualización**: SVG nativo para mapas e interfaz
- **Optimización**: Algoritmos basados en gradiente para análisis paramétrico
- **Responsividad**: Diseño adaptable a múltiples dispositivos

## 🔄 Actualizaciones Planificadas

- [ ] Integración con datos meteorológicos en tiempo real
- [ ] Módulo de simulación sísmica y geotécnica
- [ ] Visualización en 3D del recorrido
- [ ] Análisis predictivo con machine learning
- [ ] Exportación de informes en formato PDF
- [ ] Versión móvil completa

## 👨‍💻 Contribución

Las contribuciones son bienvenidas y apreciadas. Si desea contribuir al proyecto:

1. Haga un fork del repositorio
2. Cree una rama para su característica (`git checkout -b feature/caracteristica-increible`)
3. Realice sus cambios y haga commit (`git commit -m 'Añadir característica increíble'`)
4. Haga push a la rama (`git push origin feature/caracteristica-increible`)
5. Abra un Pull Request

## 📜 Licencia

Este proyecto está licenciado bajo la Licencia MIT - vea el archivo [LICENSE](LICENSE) para más detalles.

## 📚 Citación Académica

Si utiliza este simulador en investigaciones académicas, por favor cite:

```
Cabrera, B. (2025). Simulador Avanzado del Oleoducto Trans Ecuatoriano SOTE: 
Una herramienta computacional para modelado y análisis de riesgos.
Journal of Petroleum Engineering & Safety, 18(3), 245-260.
```

## 📞 Contacto

Ing. Benito Cabrera R., MBA - [benitocabrera@hotmail.com](mailto:benitocabrera@hotmail.com)

---

*Este simulador ha sido desarrollado con propósitos educativos y de investigación. No está afiliado oficialmente con EP Petroecuador u otras entidades gubernamentales. Los datos y modelos utilizados son aproximaciones basadas en información pública disponible.*
