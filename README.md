# Voltz Mini Web Framework
O Voltz Mini Web Framework é um framework web leve e fácil de usar, projetado para simplificar o desenvolvimento de aplicativos web em Python. Ele fornece uma estrutura simples e flexível para a criação de aplicativos web rápidos e eficientes.

## Características Principais
Leve e Rápido: O Voltz Mini Web Framework é projetado para ser leve e rápido, garantindo um desempenho eficiente em seus aplicativos web.

Simples de Usar: Com uma sintaxe intuitiva e uma estrutura de projeto descomplicada, o Voltz Mini Web Framework facilita o desenvolvimento de aplicativos web em Python.

Rotas Configuráveis: Defina facilmente rotas para suas páginas e endpoints de API, tornando a navegação em seu aplicativo simples e direta.

Suporte a Model-View-Controller (MVC): Organize seu código de forma limpa e estruturada com suporte integrado ao padrão de design Model-View-Controller.

## Instalação
Você pode instalar o Voltz Mini Web Framework usando o pip. Basta executar o seguinte comando:

```bash
pip install voltz-mini-web-framework
Exemplo de Uso
Aqui está um exemplo básico de como criar uma aplicação web simples usando o Voltz Mini Web Framework:

python
Copy code
from voltz import Voltz, JsonResponse

app = Voltz()

@app.route('/')
def index():
    return 'Bem-vindo ao Voltz Mini Web Framework!'

@app.route('/api/data')
def api_data():
    data = {'message': 'Isso é uma resposta da API!'}
    return JsonResponse(data)

if __name__ == '__main__':
    app.run(debug=True)
```

## Documentação
A documentação completa do Voltz Mini Web Framework está disponível aqui.

## Contribuindo
Se você encontrar algum problema ou tiver sugestões para melhorias, sinta-se à vontade para abrir uma issue ou enviar um pull request.
