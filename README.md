public class AprendendoJava {

    public static void main(String[] args) {
        String primeiroNome = "Jorge";
        String segundoNome = " Antonio de Lima Figueredo";
        String nomeCompleto = nomeCompleto(primeiroNome, segundoNome);
        System.out.println(nomeCompleto);
    }

    public static String nomeCompleto(String primeiroNome, String segundoNome) {
        return "Seu nome completo é " + primeiroNome.concat("").concat(segundoNome);
    }
}
