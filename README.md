#  CheckStyle - Ferramenta de Qualidade de Código Java

##  Sobre o Projeto

Este projeto foi desenvolvido para a disciplina de **Qualidade de Software** na **UFC - Campus Itapajé**, ministrada pelo professor **Anderson Goncalves Uchoa**.  
O **CheckStyle** é uma ferramenta de análise estática para código Java. Ela verifica automaticamente se o código segue padrões de estilo e boas práticas, ajudando a manter a **qualidade**, **padronização** e **legibilidade** do projeto.


---
##  Identificação

- **Site oficial:** [https://checkstyle.sourceforge.io](https://checkstyle.sourceforge.io)  
- **Repositório oficial:** [https://github.com/checkstyle/checkstyle](https://github.com/checkstyle/checkstyle)

---

##  Instalação e Configuração

###  Requisitos mínimos

- **Linguagem:** Java (Java 8 ou superior)
- **Sistemas compatíveis:** Windows, Linux (Ubuntu), macOS  
- **Dependência:** Java Runtime Environment (JRE)

---

###  Instalação no Ubuntu

```bash
sudo apt update
sudo apt install default-jre -y
wget https://github.com/checkstyle/checkstyle/releases/download/checkstyle-10.15.0/checkstyle-10.15.0-all.jar -O checkstyle.jar
```

---

###  Instalação no Windows

1. Verifique se o Java está instalado:
   ```cmd
   java -version
   ```
   Se não estiver, baixe em: [https://www.oracle.com/java/technologies/javase-downloads.html](https://www.oracle.com/java/technologies/javase-downloads.html)

2. Baixe o JAR do CheckStyle pelo repositório oficial:  
   [https://github.com/checkstyle/checkstyle/releases](https://github.com/checkstyle/checkstyle/releases)

3. Salve o arquivo `checkstyle.jar` em uma pasta acessível.

---

###  Execução (exemplo básico)

```bash
java -jar checkstyle.jar -c /google_checks.xml src/
```

- `-c`: Caminho para o arquivo de configuração (ex: `google_checks.xml`)
- `src/`: Pasta com os arquivos Java a serem analisados

---

##  Referências

- [Documentação oficial](https://checkstyle.sourceforge.io/)
- [Guia de configuração](https://checkstyle.sourceforge.io/config.html)
- [Estilo Google para CheckStyle](https://checkstyle.sourceforge.io/google_style.html)
- [Releases (downloads)](https://github.com/checkstyle/checkstyle/releases)

---

## 📜 Licença  
Este projeto está licenciado sob a [MIT License](LICENSE).  

---

## 🎓 **Agradecimentos**
###
- **Anderson Goncalves Uchoa**: Orientador do projeto e professor da disciplina de Quaalidade de Software na UFC Itapajé
###
- **Equipe do Projeto:** Carlos Kaique Rosa Silva ([Kaique Silva](https://github.com/hoyalles)) e Paulo Matheus Cardoso Viana ([Paulo Cardoso](https://github.com/Paulim18))
