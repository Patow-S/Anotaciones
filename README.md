# anotacion
solo anotacion

public class pruebaConstructor {
	public static void main(String[] args) {
		cuenta cuenta = new cuenta();
		cuenta.setAgencia(55);
		
	
		System.out.println(cuenta.getAgencia());
	}	

}


    
    
    public Cuenta (int agencia) {
    	if (agencia <= 0){ 
    		System.out.println("no se permite 0");
    	}else {
    		this.agencia = agencia;
    	}
    	System.out.println("Aqui se crea una nueva cuenta   ");
    }    
    
    
