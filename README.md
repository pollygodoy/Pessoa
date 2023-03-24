# Pessoa
public class Pessoa {
    //visibilidade private
    private String nome;

    //visibilidade Public
    private int idade;

    public Pessoa() {
   }

   //Métodos especiais do tipo acessiveis
   public String getNome() {
    return this.nome;
   }

   //Métodos especiais do tipo modificador
   public void setNome(String novoNome){
    this.nome = novoNome;
   }

   //Quando o método não tem retorno usamos void
   public void setIdade(int novaIdade){
    this.idade = novaIdade;
   }

   public int getIdade(){
    return this.idade;
   }
} 

//Vamos criar uma class Funcionario que Herda de Pessoa

class Funcionario extends Pessoa {
    }

    public class MyClass {
        public static void main(String args[]) {
            Funcionario novoFuncionario = new Funcionario();
            novoFuncionario.setNome("João");

            System.out.println(novoFuncionario.getNome());
        }
    }
