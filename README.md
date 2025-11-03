# 🐧 Respostas – Parte 6: Problemas para Resolver

## 1. Acessar Docs a partir de ~/ExerciciosSO/Scripts
- **Caminho relativo:** `cd ../Docs`  
- **Caminho absoluto:** `cd ~/ExerciciosSO/Docs`

---

## 2. Copiar texto.txt para Backup
- **Caminho absoluto:** `cp ~/ExerciciosSO/Docs/texto.txt ~/ExerciciosSO/Backup/`  
- **Caminho relativo:** `cp ../Docs/texto.txt ../Backup/`

---

## 3. Renomear aula.txt (em Imagens) para aula_final.txt
- `mv ~/ExerciciosSO/Imagens/aula.txt ~/ExerciciosSO/Imagens/aula_final.txt`

---

## 4. Arquivo relatorio.txt ficou vazio após redirecionamento
**Hipóteses:**
1. O diretório estava vazio ao executar o comando `ls`.  
2. O comando foi executado em outro diretório que não continha arquivos.

---

## 5. Explicações
- **Diferença entre `>` e `>>`:**  
  `>` sobrescreve o arquivo, `>>` adiciona conteúdo ao final.

- **Diferença entre caminho relativo e absoluto:**  
  O **absoluto** começa da raiz (`/home/...`), o **relativo** depende do diretório atual.

- **Diferença entre ping e traceroute:**  
  `ping` testa se o destino está acessível, enquanto `traceroute` mostra o caminho percorrido até ele.
