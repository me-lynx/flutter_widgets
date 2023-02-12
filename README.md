
# Widgets 
## Segundo a documentação do Flutter:

> Os widgets são a hierarquia de classe central na estrutura do Flutter. Um widget é uma descrição imutável de parte de uma interface de usuário. Os widgets podem ser inflados em elementos, que gerenciam a árvore de renderização subjacente.  [Saiba mais sobre Widgets aqui](https://api.flutter.dev/flutter/widgets/Widget-class.html#)

# No Flutter tudo é Widget

### Um widget pode ser entendido como um componente visual, dentro do seu aplicativo. 

Imagine que seu aplicativo é uma casa, cada widget é um tijolo que fará parte da construção. 

###### Na [documentação do Flutter](https://docs.flutter.dev/development/ui/widgets) temos vários Widgets que podem ser utilizados. 

## Entendendo como funcionam os widgets na aplicação

#### No seu projeto Flutter, dentro do arquivo main.dart está a primeira página do seu projeto, que é criada automaticamente como exemplo pelo Flutter. 

Essa função é a raíz. 

```
void main() {
  runApp(const MyApp());
}
```

Nela temos a função runApp que é a função padrão do Flutter para iniciar sua aplicação. 

A classe que é utilizada como parâmetro nessa função terá o contexto da nossa aplicação e é nela que teremos a árvore de widgets da nossa tela, que nesse caso é a arvore:

````
 Widget build(BuildContext context){}
 ````

 Dentro desse Widget, começamos a implementar os Widgets da nossa tela.
 No caso do exemplo, temos o MaterialApp.

 ````
Widget build(BuildContext context) 
{
    return MaterialApp();
}
````

Dentro dele, temos várias propriedades que poderão ser utilizadas, você pode vê-las na integra na [documentação oficial](https://api.flutter.dev/flutter/material/MaterialApp-class.html)

