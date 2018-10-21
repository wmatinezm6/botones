# botones
package botones;

/**
 *
 * @author alumno
 */
public class Botones {
    
    private static Busqueda Formulario;
    private static persona persona[];
    private static int contador;
    

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        
        Formulario =  new Busqueda ();
        persona = new persona();
        
    }
    
}


package botones;

/**
 *
 * @author alumno
 */
public class persona {

    public persona() {
        this.nombre = "";
        this.apellido = "";
        this.correo = "";
     
    }
 String nombre;
 String apellido;
 String correo;
    
    int celular;
    
    public String getNombre() {
        return nombre;
    }

    public void setNombre(String nombre) {
        this.nombre = nombre;
    }

    public String getApellido() {
        return apellido;
    }

    public void setApellido(String apellido) {
        this.apellido = apellido;
    }

    public String getCorreo() {
        return correo;
    }

    public void setCorreo(String correo) {
        this.correo = correo;
    }

    public int getCelular() {
        return celular;
    }

    public void setCelular(int celular) {
        this.celular = celular;
    }
   
    
    
}
