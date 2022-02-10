# Curso de HTML 5

## Aula 05 - Criar Login em HTML e Formulários

1. Reestruturar o projeto
2. Renomear o arquivo index.html para o nome perfil.html
3. Atualizar o link Voltar da página projetos.html que deve ir para a página perfil.html e não mais para index.html
4. Criar outro arquivo index.html que será a nossa tela de login com formulário

### Tags utilizadas na aula

* h1
* div
* form
* label
* input
* button
* img
* br

### Atributos
* action
* method
* for
* id
* name
* type - email, password, submit, reset
* placeholder
* value

### Formulário

* É a principal estrutura utilizada para criar aplicações web.
* É formada por rótulos (labels), campos (inputs) e botões (buttons)
* Existem vários tipos de componentes nos formulários para manipularmos diferentes tipos de informações
* Devemos usar uma linguagem de programação para pegar os dados do formulário e manipular eles.
* No atributo action definimos qual arquivo irá processar nosso formulário
* No atributo method definimos qual método será utilizado para o envio.
* Os métodos podem ser POST ou GET

~~~html
<form action="perfil.html" method="POST">

            <div>
                <label for="email">E-mail</label>
                <input
                    type="email"
                    name="email"
                    id="email"
                    placeholder="email@provedor.com"
                />
            </div>

            <div>
                <label for="senha">Senha</label>
                <input
                    type="password"
                    name="senha"
                    id="senha"
                    placeholder="senha"
                />
            </div>

            <div>
                <input
                    type="submit"
                    name="btn-enviar"
                    id="btn-enviar"
                    value="Enviar"
                />
                <!-- 
                <button
                    type="submit"
                    name="btn-enviar"
                    id="btn-enviar">
                    Enviar
                </button>
                -->
                &nbsp;
                <input
                    type="reset"
                    name="btn-limpar"
                    id="btn-limpar"
                    value="Limpar"
                />
            </div>

        </form>
~~~
