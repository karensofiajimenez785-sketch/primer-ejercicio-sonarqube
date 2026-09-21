# primer-ejercicio-sonarqube
## 📊 Evidencia de Calidad y Quality Gate (SonarQube)

Como parte de las buenas prácticas de integración y aseguramiento de calidad, el código del proyecto es evaluado mediante análisis estático con **SonarQube** y pruebas de cobertura con **JaCoCo**.

- **Estado del Quality Gate:** Aprobado (Passed) 🟢
- **Herramientas utilizadas:** Spring Boot, Maven, JaCoCo, SonarQube y GitHub Actions.
**Caso extraordimario:** Maven y el plugin de SonarQube en el pipeline se ejecutaron a la perfección, pero el servidor virtual de GitHub Actions intentó buscar SonarQube en su propio localhost y, obviamente, no encontró nada porque tu servidor está instalado localmente en tu computador.
### Captura del Quality Gate:
![Quality Gate SonarQube](./docs/quality-gate-status.png)