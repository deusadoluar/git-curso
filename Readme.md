# Curso Git

Repositório teste

É isso aí galerinha deixa o like no vídeo é nois.

Deixa o comment também pode cre
 método construtor precisa ter obrigatoriamente o nome da classe;

Toda as vezes que criar uma classe para serem instanciadas implicitamente a linguagem já está colocando um método construtor.
Todo método precisa ter [tiporetorno] [nome] ([parametro])

Qual e o tipo do parâmetro passado número do acelerar

O método construtor constrói uma instancia ou objeto, o método tem como retorno um instancia da própria classe.

O método construtor não tem tipo de retorno explicitamente definido, vc não expõe o tipo do método construto.

Para vc chamar um método você precisa de uma instancia utilizando a palavra NEW.

Eu não consigo chamar o método construtor depois que ela e criada a partir de uma instancia 

Você só chama o método construtor a partir da palavra NEW

Instancia não cria outra instancia.


Para que serve o método construtor, serve para definir coisas que devem ser feitas no momento que fizer as instancias algo que já esteja acontecendo.

This. Se faz a referência de um a instancia. Ele faz a busca em uma instancia aquilo que você manda ele buscas

Prova= quantos são os métodos utilizáveis pelas instâncias da classe definida linha 
Se estiver privado nenhuma instancia terá acesso

class Automovel{
  private string Marca;
  private string Modelo;
  private int    VelocidadeAtual;

  public Automovel(string marca, string Modelo){
    this.Marca = marca;
    this.Modelo = modelo;
  }
  /*
  [tipoRetorno] [nome] ([parametros]){ }  */
  int Acelerar(int qtosKmsHora){
    VelocidadeAtual = VelocidadeAtual + qtosKmsHora;
    if(VelocidadeAtual > 180){
      VelocidadeAtual = 180;
    }
    return VelocidadeAtual;
  }
  
  public int Frear(int qtosKmsHora){
    VelocidadeAtual = VelocidadeAtual - qtosKmsHora;
    if(VelocidadeAtual < 0){
      VelocidadeAtual = 0;
    }
    return VelocidadeAtual;
  }


