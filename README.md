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

4. Baixe o arquivo de configuração(ex: google_checks.xml): [https://github.com/checkstyle/checkstyle/blob/master/src/main/resources/google_checks.xml](https://github.com/checkstyle/checkstyle/blob/master/src/main/resources/google_checks.xml)


---

### Execução (exemplo básico)

- `-c`: Caminho para o arquivo de configuração (ex: `google_checks.xml`)
- `src/`: Pasta contendo os arquivos `.java` a serem analisados

> ℹ️ **Importante:** Este repositório não acompanha a pasta `src/`, pois não contém arquivos de exemplo.  
> Para utilizar este projeto no seu ambiente local, siga os passos abaixo:

####  Como preparar o projeto para análise:

1. Crie uma pasta chamada `src` na raiz do repositório:
   ```bash
   mkdir src
   ```

2. Coloque dentro dessa pasta os arquivos Java que você deseja analisar com o CheckStyle:
   ```
   src/
   ├── MeuCodigo1.java
   └── OutroArquivo.java
   ```

3. Execute o CheckStyle conforme mostrado:
   ```bash
   java -jar checkstyle.jar -c /google_checks.xml src/
   ```

---

##  Referências

- [Documentação oficial](https://checkstyle.sourceforge.io/)
- [Guia de configuração](https://checkstyle.sourceforge.io/config.html)
- [Estilo Google para CheckStyle](https://checkstyle.sourceforge.io/google_style.html)
- [Releases (downloads)](https://github.com/checkstyle/checkstyle/releases)

---

##  Licença  
Este projeto está licenciado sob a [MIT License](LICENSE).  

---

##  **Agradecimentos**
###
- **Anderson Goncalves Uchoa**: Orientador do projeto e professor da disciplina de Qualidade de Software na UFC Itapajé
###
- **Equipe do Projeto:** Carlos Kaique Rosa Silva ([Kaique Silva](https://github.com/hoyalles)) e Paulo Matheus Cardoso Viana ([Paulo Cardoso](https://github.com/Paulim18))
