# Trabalho - Comandos Linux (G2)

Este repositório contém exemplos de comandos utilizados para gerenciar arquivos e diretórios em um ambiente Linux, além de transferência de arquivos via SSH.

---

## Comando: ssh
**Descrição:** Estabelece uma conexão segura com outro computador via SSH (Secure Shell).  
**Exemplo:**  
```bash
ssh seu_usuario@ip_do_servidor
```

---

## Comando: mkdir
**Descrição:** Cria diretórios no sistema de arquivos.  
**Exemplo:**  
```bash
mkdir ~/trabalho
```

---

## Comando: mkdir (múltiplos diretórios)
**Descrição:** Cria vários diretórios em uma única linha de comando.  
**Exemplo:**  
```bash
mkdir ~/trabalho/relatorios ~/trabalho/documentos
```

---

## Comando: touch
**Descrição:** Cria arquivos vazios ou atualiza a data de modificação de arquivos existentes.  
**Exemplo:**  
```bash
touch ~/trabalho/relatorios/relatorio.txt
```

---

## Comando: touch (outro arquivo)
**Descrição:** Cria outro arquivo vazio no diretório especificado.  
**Exemplo:**  
```bash
touch ~/trabalho/documentos/notas.txt
```

---

## Comando: echo
**Descrição:** Escreve uma linha de texto em um arquivo.  
**Exemplo:**  
```bash
echo "Relatório de Trabalho\nData: 07/05/2025" > ~/trabalho/relatorios/relatorio.txt
```

---

## Comando: echo (outro uso)
**Descrição:** Escreve várias linhas de texto em outro arquivo.  
**Exemplo:**  
```bash
echo "Notas Finais:\n- Estudo de caso: 85\n- Performance: 90" > ~/trabalho/documentos/notas.txt
```

---

## Comando: chmod
**Descrição:** Altera permissões de arquivos ou diretórios.  
**Exemplo:**  
```bash
chmod 644 ~/trabalho/relatorios/relatorio.txt
```

---

## Comando: chmod (outra permissão)
**Descrição:** Define permissões de acesso mais restritas para um arquivo.  
**Exemplo:**  
```bash
chmod 700 ~/trabalho/documentos/notas.txt
```

---

## Comando: ls -l
**Descrição:** Lista detalhes dos arquivos, incluindo permissões, tamanho e data de modificação.  
**Exemplo:**  
```bash
ls -l ~/trabalho/relatorios/relatorio.txt ~/trabalho/documentos/notas.txt
```

---

## Comando: scp
**Descrição:** Copia arquivos entre computadores usando SSH.  
**Exemplo (upload):**  
```bash
scp ~/Downloads/arquivo_local.txt seu_usuario@ip_do_servidor:~/trabalho/
```

**Exemplo (download):**  
```bash
scp seu_usuario@ip_do_servidor:~/trabalho/documentos/notas.txt ~/Downloads/
```

---
```
