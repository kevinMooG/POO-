public class Principal {

    public static void main(String[] args) {

        // Instanciar 3 objetos Persona
        Persona persona1 = new Persona("Kevin", 17, "Masculino");
        Persona persona2 = new Persona("Ana", 20, "Femenino");
        Persona persona3 = new Persona("Luis", 25, "Masculino");

        // Simulación
        persona1.saludar();
        persona1.mostrarDatos();

        persona2.saludar();
        persona2.mostrarDatos();

        persona3.saludar();
        persona3.mostrarDatos();
    }
}
