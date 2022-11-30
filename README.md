# aaaaaaa-yo-pense-en-usar-privado-y-luego-un-publico-que-tomara-el-privado
lo que sea que diga el titulo, a decir verdad ya me olvide de lo que decia el titulo;



main

public class Main {
        public static void main(String[] args) {
                Singleton miUnicaInstancia = Singleton.getInstance();
                System.out.println(miUnicaInstancia);
                Singleton aaaaaaaaaaa = Singleton.getInstance();
                System.out.println(aaaaaaaaaaa);






        }
}

la secundaria


public class Singleton {
        private Singleton() {
        }
        private static Singleton instance = null;
        public static Singleton getInstance() {
                if (instance == null) {
                        // desde aqui si que puedo acceder al constructor
                        // porque estoy en la misma clase
                        instance = new Singleton();
                }
                return instance;
        }
}
