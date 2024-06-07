# Desafio Stress-Test

   1. Criei a imagem docker:
   ```bash
   docker build -t stress-test .
   ```
   2. Execute a imagem local:
   ```bash
   docker run -rm stress-test --concurrency=10 --requests=100 --url=https://httpstat.us/Random/200,201,500-504
   ```