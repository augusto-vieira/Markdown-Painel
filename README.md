# Exemplos de Paneil

## UML com Markdown:
```mermaid
graph LR
A[Square Rect] -- Link text --> B((Circle))
A --> C(Round Rect)
B --> D{Rhombus}
C --> D
```
---
## Painel Simples (1 | 1)
<div style="display: flex;">

  <div style="flex: 1; margin-right: 20px;">
    Seção 1: Resumo

    **Indicadores Principais**
    - **Vendas Totais:** $10,000
    - **Clientes Novos:** 50
    - **Taxa de Conversão:** 5%

    ## Seção 2: Gráficos

    ![Gráfico de Vendas](path/to/sales-chart.png)
  </div>

  <div style="flex: 1;">
    Seção 3: Tabelas

    | Mês       | Vendas | Clientes Novos |
    |-----------|--------|----------------|
    | Janeiro   | $1,000 | 10             |
    | Fevereiro | $1,200 | 12             |
    | Março     | $1,500 | 15             |
  </div>

</div>

---
## Painel divido em 3  (1 | 1/1)
<div style="display: flex;">
  <div style="width: 33%;">
    <h2>Coluna 1</h2>
    <p>Conteúdo da Coluna 1
    </p>
  </div>
  <div style="width: 66%;">
    <h2>Coluna 2</h2>
    <p>Conteúdo da Coluna 2</p>
    <h2>Coluna 3</h2>
    <p>Conteúdo da Coluna 3</p>
  </div>
</div>

---
##  Painel divido em 4 (2|2)
<div style="display: flex;">
  <div style="width: 33%;">
    <h2>C</h2>
    <pre><code>
#include <stdio.h>

int main() {
  printf("Olá, mundo!\n");
  return 0;
}
    </code></pre>
  </div>
  <div style="width: 66%;">
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
  </div>
</div>

---
## Painel divido em 3  (1 | 1/1)
<div style="display: flex;">
  <div style="width: 50%;">
    <h2>C</h2>
    <pre><code>
#include <stdio.h>

int main() {
  printf("Olá, mundo!\n");
  return 0;
}
    </code></pre>
  </div>
  <div style="width: 50%;">
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
  </div>
</div>

---
## Painel horizontal em 4 (1|1|1|1)
<div style="display: flex;">
  <div style="width: 25%;">
    <h2>C</h2>
    <pre><code>
#include <stdio.h>

int main() {
  printf("Olá, mundo!\n");
  return 0;
}
    </code></pre>
  </div>
  <div style="width: 25%;">
    <h2>Java</h2>
    <pre><code>
public class Main {
  public static void main(String[] args) {
    System.out.println("Olá, mundo!");
  }
}
    </code></pre>
  </div>
  <div style="width: 25%;">
    <h2>Python</h2>
    <pre><code>
print("Olá, mundo!")
    </code></pre>
  </div>
  <div style="width: 25%;">
    <h2>JavaScript</h2>
    <pre><code>
console.log("Olá, mundo!");
    </code></pre>
  </div>
</div>

--- 
## Painel com espaçamento horizontal em 4 (2/2)
<div style="display: flex;">
  <div style="width: 50%;">
    <div style="width: 50%;">
      <h2>C</h2>
      <pre><code>
#include <stdio.h>

int main() {
  printf("Olá, mundo!\n");
  return 0;
}
      </code></pre>
    </div>
    <div style="width: 50%;">
      <h2>Java</h2>
      <pre><code>
public class Main {
  public static void main(String[] args) {
    System.out.println("Olá, mundo!");
  }
}
      </code></pre>
    </div>
  </div>
  <div style="width: 50%;">
    <div style="width: 50%;">
      <h2>Python</h2>
      <pre><code>
print("Olá, mundo!")
      </code></pre>
    </div>
    <div style="width: 50%;">
      <h2>JavaScript</h2>
      <pre><code>
console.log("Olá, mundo!");
      </code></pre>
    </div>
  </div>
</div>

---
## Painel sem espaçamento horizontal em 4 (2/2)
<div style="display: flex;">
  <div style="width: 50%;">
    <div style="width: 100%;">
      <h2>C</h2>
      <pre><code>
#include <stdio.h>

int main() {
  printf("Olá, mundo!\n");
  return 0;
}
      </code></pre>
    </div>
    <div style="width: 100%;">
      <h2>Java</h2>
      <pre><code>
public class Main {
  public static void main(String[] args) {
    System.out.println("Olá, mundo!");
  }
}
      </code></pre>
    </div>
  </div>
  <div style="width: 50%;">
    <div style="width: 100%;">
      <h2>Python</h2>
      <pre><code>
print("Olá, mundo!")
      </code></pre>
    </div>
    <div style="width: 100%;">
      <h2>JavaScript</h2>
      <pre><code>
console.log("Olá, mundo!");
      </code></pre>
    </div>
  </div>
</div>

---
## Painel com espaçamento horizontal em 3 (1|1|1)
<div style="display: flex;">
  <div style="width: 50%; padding: 10px;">
    <h2 style="color: #f0f0f0;">C</h2>
    <hr style="border-top: 1px solid #555;">
    <pre style="color: #ddd; font-size: 16px;"><code>
#include <stdio.h>

int main() {
  printf("Olá, mundo!\n");
  return 0;
}
    </code></pre>
  </div>
  <div style="width: 50%; padding: 10px;">
    <h2 style="color: #f0f0f0;">Python</h2>
    <hr style="border-top: 1px solid #555;">
    <pre style="color: #ddd; font-size: 16px;"><code>
print("Olá, mundo!")
    </code></pre>
  </div>
  <div style="width: 50%; padding: 10px;">
    <h2 style="color: #f0f0f0;">Java</h2>
    <hr style="border-top: 1px solid #555;">
    <pre style="color: #ddd; font-size: 16px;"><code>
public class Main {
  public static void main(String[] args) {
    System.out.println("Olá, mundo!");
  }
}
    </code></pre>
  </div>
  <div style="width: 50%; padding: 10px;">
    <h2 style="color: #f0f0f0;">JavaScript</h2>
    <hr style="border-top: 1px solid #555;">
    <pre style="color: #ddd; font-size: 16px;"><code>
console.log("Olá, mundo!");
    </code></pre>
  </div>
</div>

---
## Painel horizontal em 4 (1|1|1|1)
<div style="display: flex; flex-wrap: wrap; justify-content: space-around;">
  <div class="card">
    <h2>C</h2>
    <pre><code>
#include <stdio.h>

int main() {
  printf("Olá, mundo!\n");
  return 0;
}
    </code></pre>
  </div>
  <div class="card">
    <h2>Python</h2>
    <pre><code>
print("Olá, mundo!")
    </code></pre>
  </div>
  <div class="card">
    <h2>Java</h2>
    <pre><code>
public class Main {
  public static void main(String[] args) {
    System.out.println("Olá, mundo!");
  }
}
    </code></pre>
  </div>
  <div class="card">
    <h2>JavaScript</h2>
    <pre><code>
console.log("Olá, mundo!");
    </code></pre>
  </div>
</div>

---
## Painel com borda divido em 4 (2/2)
<div style="display: flex;">
  <div style="width: 50%; padding: 10px;">
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
  </div>
  <div style="width: 50%; padding: 10px;">
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
  </div>
</div>

---
# Painel com borda em colunas
<div style="display: flex; flex-wrap: wrap; justify-content: space-around;">
  <div style="width: 48%; margin-bottom: 10px; padding: 10px; border: 1px solid #ccc;">
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
  <div style="width: 48%; margin-bottom: 10px; padding: 10px; border: 1px solid #ccc;">
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
  <div style="width: 48%; margin-bottom: 10px; padding: 10px; border: 1px solid #ccc;">
    <h2>Python</h2>
    <p>Este é um pequeno texto sobre a linguagem Python.</p>
    <pre><code>
print("Olá, mundo!")
    </code></pre>
  </div>
  <div style="width: 48%; margin-bottom: 10px; padding: 10px; border: 1px solid #ccc;">
    <h2>JavaScript</h2>
    <p>Este é um pequeno texto sobre a linguagem JavaScript.</p>
    <pre><code>
console.log("Olá, mundo!");
    </code></pre>
  </div>
</div>
