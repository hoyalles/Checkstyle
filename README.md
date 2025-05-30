# CheckStyle Demo

Este é um projeto de exemplo para demonstrar o uso da ferramenta **CheckStyle**, que realiza análise estática de código em projetos Java.

## 🔧 Identificação da Ferramenta

- **Nome:** CheckStyle
- **Site Oficial:** [https://checkstyle.sourceforge.io/](https://checkstyle.sourceforge.io/)
- **Repositório GitHub:** [https://github.com/checkstyle/checkstyle](https://github.com/checkstyle/checkstyle)

## ⚙️ Instalação e Configuração

### Requisitos

- Java 8 ou superior
- Terminal/shell
- Git

### Passo a Passo

```bash
# Baixar o checkstyle.jar
wget https://github.com/checkstyle/checkstyle/releases/download/checkstyle-10.12.4/checkstyle-10.12.4-all.jar -O checkstyle.jar

# Baixar a configuração de estilo do Google
wget https://raw.githubusercontent.com/checkstyle/checkstyle/master/src/main/resources/google_checks.xml

# Executar a ferramenta
java -jar checkstyle.jar -c google_checks.xml src/
```

## 🔁 Integração com GitHub Actions

A ferramenta está integrada ao GitHub Actions através do arquivo `.github/workflows/checkstyle.yml`.

## 🧪 Demonstração Prática

### Código de exemplo:

```java
public class App {
    public static void main(String[] args) {
        String nome = "CheckStyle";
        System.out.println("Exemplo de projeto Java usando " + nome);
    }
}
```

### Execução e Resultados

Ao executar o CheckStyle, será gerado um relatório indicando os problemas de estilo no código conforme as regras do `google_checks.xml`.

## 💬 Reflexão Crítica

- **Pontos Fortes:** Fácil de configurar, integração com CI, compatível com estilos conhecidos.
- **Limitações:** Focado apenas em estilo; não detecta bugs ou vulnerabilidades.
- **Comparações:** Similar ao PMD, mas com foco mais específico em convenções de codificação.

## 📊 Exportação de Resultados

Os resultados podem ser exportados para o terminal e interpretados com base nos arquivos e linhas reportadas.

---

Este projeto serve como base para estudo e demonstração de boas práticas de análise estática com CheckStyle.
