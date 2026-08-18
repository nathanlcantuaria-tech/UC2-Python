Aula 01 ====================================================================================

--------------------------------------------------------- Index.html


<!DOCTYPE html>
<html lang="pt-br">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Qualquer coisa</title>
</head>

<body>
  <header>
    <h1>Título Qualquer da Minha Página</h1>
    <h3>subtítulo</h3>
    <p>Aí sim eu posso escrever algo.</p>
  </header>
  <nav>
    <ul>
      <li><a href="#primeira">Link A</a></li>
      <li><a href="#segunda">Link B</a></li>
      <li><a href="#terceira">Link C</a></li>
    </ul>
  </nav>
  <hr>

  <main>

    <!-- Boto o meu comentário aqui -->


    <br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

    <section id="primeira">
      <h2>Primeira seção</h2>
      <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quas, excepturi reiciendis in quia earum esse alias
        itaque ratione tempore minima similique voluptas placeat eveniet? Consequatur mollitia repudiandae obcaecati
        corporis suscipit?</p>
    </section>

    <br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

    <section id="segunda">
      <h2>Segunda Seção</h2>
      <p>
        Lorem ipsum, dolor sit amet consectetur adipisicing elit.<br />Aperiam, ullam exercitationem. Modi, libero?
        <br />
        Qui, nihil debitis vel commodi quidem explicabo reiciendis officia aut cumque nesciunt tenetur aliquid harum cum
        earum!
      </p>
    </section>

    <br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

    <section id="terceira">
      <h2>Terceira Seção</h2>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Rem ipsa, eum similique deleniti natus cumque illum
        possimus at numquam! Laborum doloribus animi atque tempora reprehenderit. Expedita repellat aut hic. Magni.</p>
    </section>

    <br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
  </main>

</body>

</html>



--------------------------------------------------------- exercicio.md

### Aula 1: Atividade prática
# Currículo on-line

## ContextoVocê vai construir a primeira
 versão do seu currículo pessoal em HTML puro. Essa página vai servir de base para os próximos exercícios do curso.

## O que a página precisa ter

- Um `header` com seu nome e um subtítulo curto (ex.: profissão ou área de atuação).
- Um `nav` logo abaixo do `header`, com uma lista de links (`ul`/`li` + `a`) que levam, por âncora (`id`), até cada seção da página — ex.: "Resumo", "Experiência", "Contato".
- Um `main` contendo pelo menos três `section`, cada uma com um `id` correspondente a um link do menu:
  - Uma seção de resumo/apresentação (um parágrafo curto sobre você).
  - Uma seção de experiência ou projetos (pode usar uma lista, `ul`/`li`, para organizar).
  - Uma seção de contato, com pelo menos um link externo (ex.: LinkedIn ou portfólio) usando `target="_blank"`.
- Use `hr` para separar visualmente pelo menos duas seções.
- Use `br` em algum ponto onde faça sentido quebrar uma linha dentro de um mesmo parágrafo (ex.: endereço ou dados de contato).

## Critério de entrega
Ao clicar em cada item do menu (`nav`), a página deve rolar até a seção correspondente. Ao clicar no link externo, ele deve abrir em uma nova aba.