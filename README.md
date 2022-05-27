O Jockey Clube está organizando uma competição de hipismo e criou as seguintes categorias:

INFANTIL – competidores entre 7 e 12 anos;

JUVENIL – competidores entre 13 e 17 anos;

ADULTO – competidores entre 18 e 49 anos;

SENIOR – competidores com 50 anos ou mais.

Para ajudar na classificação correta, crie um código capaz de informar a categoria do competidor a partir de sua idade.


programa

{

  funcao inicio()

  {

    inteiro idade

    escreva("Idade do competidor: ")

    leia(idade)

    se (idade>=7 e idade<=12)

    {

      escreva("Categoria: INFANTIL")

    }

    senao se (idade>=13 e idade<=17)

    {

      escreva("Categoria: JUVENIL")

    }

    senao se (idade>=18 e idade<=49)

    {

      escreva("Categoria: ADULTO")

    }

    senao se (idade>=50)

    {

      escreva("Categoria: SENIOR")

    }

    senao

    {

      escreva("Idade inválida!")

    }

  }

}

