# Exemplos de Paneil

## UML com Markdown:
#### Você pode encontrar mais informações sobre UML e a sintaxe Mermaid online.
```mermaid
graph LR
A[Square Rect] -- Link text --> B((Circle))
A --> C(Round Rect)
B --> D{Rhombus}
C --> D
```
---
## Painel Simples (1 | 1)
<table>
  <tr>
    <td>
      <strong>Indicadores Principais</strong><br>
      <strong>Vendas Totais:</strong> $10,000<br>
      <strong>Clientes Novos:</strong> 50<br>
      <strong>Taxa de Conversão:</strong> 5%
    </td>
    <td>
      <strong>Mês</strong> | <strong>Vendas</strong> | <strong>Clientes Novos</strong><br>
      Janeiro | $1,000 | 10<br>
      Fevereiro | $1,200 | 12<br>
      Março | $1,500 | 15
    </td>
  </tr>
</table>

---
## Painel divido em 3  (1 | 1/1)
<table>
  <tr>
    <td style="width: 33%;">
      <h2>Coluna 1</h2>
      <p>Conteúdo da Coluna 1</p>
    </td>
    <td style="width: 66%;">
      <h2>Coluna 2</h2>
      <p>Conteúdo da Coluna 2</p>
      <h2>Coluna 3</h2>
      <p>Conteúdo da Coluna 3</p>
    </td>
  </tr>
</table>

---
##  Painel divido em 3 (1|1|1)
<table>
  <tr>
    <td style="width: 33%;">
      <h2>C</h2>
      <pre><code>
#include <stdio.h>

int main() {
  printf("Olá, mundo!\n");
  return 0;
}
      </code></pre>
    </td>
    <td style="width: 33%;">
      <h2>Java</h2>
      <pre><code>
public class Main {
  public static void main(String[] args) {
    System.out.println("Olá, mundo!");
  }
}
      </code></pre>
    </td>
    <td style="width: 33%;">
      <h2>Python</h2>
      <pre><code>
print("Olá, mundo!")
      </code></pre>
    </td>
  </tr>
</table>

---
## Painel divido em 3  (1 | 1/1)
<table>
  <tr>
    <td style="width: 50%;">
      <h2>C</h2>
      <pre><code>
#include <stdio.h>

int main() {
  printf("Olá, mundo!\n");
  return 0;
}
      </code></pre>
    </td>
    <td style="width: 50%;">
      <h2>Java</h2>
      <pre><code>
public class Main {
  public static void main(String[] args) {
    System.out.println("Olá, mundo!");
  }
}
      </code></pre>
      <h2>Python</h2>
      <pre><code>
print("Olá, mundo!")
      </code></pre>
    </td>
  </tr>
</table>

---
## Painel horizontal em 4 (1|1|1|1)
<table>
  <tr>
    <td style="width: 25%;">
      <h2>C</h2>
      <pre><code>
#include <stdio.h>

int main() {
  printf("Olá, mundo!\n");
  return 0;
}
      </code></pre>
    </td>
    <td style="width: 25%;">
      <h2>Java</h2>
      <pre><code>
public class Main {
  public static void main(String[] args) {
    System.out.println("Olá, mundo!");
  }
}
      </code></pre>
    </td>
    <td style="width: 25%;">
      <h2>Python</h2>
      <pre><code>
print("Olá, mundo!")
      </code></pre>
    </td>
    <td style="width: 25%;">
      <h2>JavaScript</h2>
      <pre><code>
console.log("Olá, mundo!");
      </code></pre>
    </td>
  </tr>
</table>

--- 
## Painel com espaçamento horizontal em 4 (2/2)
<table>
  <tr>
    <td style="width: 50%; vertical-align: top;">
      <table>
        <tr>
          <td style="width: 50%;">
            <h2>C</h2>
            <pre><code>
#include <stdio.h>

int main() {
  printf("Olá, mundo!\n");
  return 0;
}
            </code></pre>
          </td>
          <td style="width: 50%;">
            <h2>Java</h2>
            <pre><code>
public class Main {
  public static void main(String[] args) {
    System.out.println("Olá, mundo!");
  }
}
            </code></pre>
          </td>
        </tr>
      </table>
    </td>
    <td style="width: 50%; vertical-align: top;">
      <table>
        <tr>
          <td style="width: 50%;">
            <h2>Python</h2>
            <pre><code>
print("Olá, mundo!")
            </code></pre>
          </td>
          <td style="width: 50%;">
            <h2>JavaScript</h2>
            <pre><code>
console.log("Olá, mundo!");
            </code></pre>
          </td>
        </tr>
      </table>
    </td>
  </tr>
</table>

---
## Painel sem espaçamento horizontal em 4 (2/2)
<table>
  <tr>
    <td style="width: 50%; vertical-align: top;">
      <h2>C</h2>
      <pre><code>
#include <stdio.h>

int main() {
  printf("Olá, mundo!\n");
  return 0;
}
      </code></pre>
      <h2>Java</h2>
      <pre><code>
public class Main {
  public static void main(String[] args) {
    System.out.println("Olá, mundo!");
  }
}
      </code></pre>
    </td>
    <td style="width: 50%; vertical-align: top;">
      <h2>Python</h2>
      <pre><code>
print("Olá, mundo!")
      </code></pre>
      <h2>JavaScript</h2>
      <pre><code>
console.log("Olá, mundo!");
      </code></pre>
    </td>
  </tr>
</table>

---
## Painel com espaçamento horizontal em 3 (1|1|1)
<table>
  <tr>
    <td style="width: 33%; padding: 10px; vertical-align: top; background-color: #333;">
      <h2 style="color: #f0f0f0;">C</h2>
      <hr style="border-top: 1px solid #555;">
      <pre style="color: #ddd; font-size: 16px;"><code>
#include <stdio.h>

int main() {
  printf("Olá, mundo!\n");
  return 0;
}
      </code></pre>
    </td>
    <td style="width: 33%; padding: 10px; vertical-align: top; background-color: #333;">
      <h2 style="color: #f0f0f0;">Python</h2>
      <hr style="border-top: 1px solid #555;">
      <pre style="color: #ddd; font-size: 16px;"><code>
print("Olá, mundo!")
      </code></pre>
    </td>
    <td style="width: 33%; padding: 10px; vertical-align: top; background-color: #333;">
      <h2 style="color: #f0f0f0;">Java</h2>
      <hr style="border-top: 1px solid #555;">
      <pre style="color: #ddd; font-size: 16px;"><code>
public class Main {
  public static void main(String[] args) {
    System.out.println("Olá, mundo!");
  }
}
      </code></pre>
    </td>
    <td style="width: 33%; padding: 10px; vertical-align: top; background-color: #333;">
      <h2 style="color: #f0f0f0;">JavaScript</h2>
      <hr style="border-top: 1px solid #555;">
      <pre style="color: #ddd; font-size: 16px;"><code>
console.log("Olá, mundo!");
      </code></pre>
    </td>
  </tr>
</table>

---
## Painel horizontal em 4 (1|1|1|1)
<table>
  <tr>
    <td style="width: 25%; padding: 10px; vertical-align: top;">
      <h2>C</h2>
      <pre><code>
#include <stdio.h>

int main() {
  printf("Olá, mundo!\n");
  return 0;
}
      </code></pre>
    </td>
    <td style="width: 25%; padding: 10px; vertical-align: top;">
      <h2>Python</h2>
      <pre><code>
print("Olá, mundo!")
      </code></pre>
    </td>
    <td style="width: 25%; padding: 10px; vertical-align: top;">
      <h2>Java</h2>
      <pre><code>
public class Main {
  public static void main(String[] args) {
    System.out.println("Olá, mundo!");
  }
}
      </code></pre>
    </td>
    <td style="width: 25%; padding: 10px; vertical-align: top;">
      <h2>JavaScript</h2>
      <pre><code>
console.log("Olá, mundo!");
      </code></pre>
    </td>
  </tr>
</table>

---
## Painel com borda divido em 4 (2/2)
<table>
  <tr>
    <td style="width: 50%; padding: 10px; vertical-align: top;">
      <div style="border: 1px solid #ccc; padding: 10px;">
        <h2>C</h2>
        <p>Este é um pequeno texto sobre a linguagem C.</p>
        <pre><code>
#include <stdio.h>

int main() {
  printf("Olá, mundo!\n");
  return 0;
}
        </code></pre>
      </div>
      <div style="border: 1px solid #ccc; padding: 10px; margin-top: 10px;">
        <h2>Java</h2>
        <p>Este é um pequeno texto sobre a linguagem Java.</p>
        <pre><code>
public class Main {
  public static void main(String[] args) {
    System.out.println("Olá, mundo!");
  }
}
        </code></pre>
      </div>
    </td>
    <td style="width: 50%; padding: 10px; vertical-align: top;">
      <div style="border: 1px solid #ccc; padding: 10px;">
        <h2>Python</h2>
        <p>Este é um pequeno texto sobre a linguagem Python.</p>
        <pre><code>
print("Olá, mundo!")
        </code></pre>
      </div>
      <div style="border: 1px solid #ccc; padding: 10px; margin-top: 10px;">
        <h2>JavaScript</h2>
        <p>Este é um pequeno texto sobre a linguagem JavaScript.</p>
        <pre><code>
console.log("Olá, mundo!");
        </code></pre>
      </div>
    </td>
  </tr>
</table>

---
# Painel com borda em colunas
<table style="width: 100%; border-collapse: collapse;">
  <tr>
    <td style="width: 48%; padding: 10px; border: 1px solid #ccc; vertical-align: top;">
      <h2>C</h2>
      <p>Este é um pequeno texto sobre a linguagem C.</p>
      <pre><code>
#include <stdio.h>

int main() {
  printf("Olá, mundo!\n");
  return 0;
}
      </code></pre>
    </td>
    <td style="width: 48%; padding: 10px; border: 1px solid #ccc; vertical-align: top;">
      <h2>Java</h2>
      <p>Este é um pequeno texto sobre a linguagem Java.</p>
      <pre><code>
public class Main {
  public static void main(String[] args) {
    System.out.println("Olá, mundo!");
  }
}
      </code></pre>
    </td>
  </tr>
  <tr>
    <td style="width: 48%; padding: 10px; border: 1px solid #ccc; vertical-align: top;">
      <h2>Python</h2>
      <p>Este é um pequeno texto sobre a linguagem Python.</p>
      <pre><code>
print("Olá, mundo!")
      </code></pre>
    </td>
    <td style="width: 48%; padding: 10px; border: 1px solid #ccc; vertical-align: top;">
      <h2>JavaScript</h2>
      <p>Este é um pequeno texto sobre a linguagem JavaScript.</p>
      <pre><code>
console.log("Olá, mundo!");
      </code></pre>
    </td>
  </tr>
</table>
