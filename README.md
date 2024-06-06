# Desafio Stress-Test

   * Criei a imagem docker:
   ```bash
   docker build -t app .
   ```
   3. Execute a imagem local:
   ```bash
   docker run app --concurrency=<INT> --requests=<INT> --url=<URL>
   ```