# cooler


package testeCooler;

public class cooler{ 
	
    String marca;
    String tamanho;
    String dataDeFabricação;

     cooler (String marca,String tamanho,String dataDeFabricação){
	this.marca=marca;
    this.tamanho=tamanho;
    this.dataDeFabricação=dataDeFabricação;
}
public boolean estadoCooler=false;

public void ligadoCooler(){
	 estadoCooler=true;}

public void desligadoCooler(){
	 estadoCooler=false;}
			 
public boolean EstadoCooler(){
	 return estadoCooler;
}

}


??????????????????????????????????????????????????????????????????????

package testeCooler;

public class teste {
	
	public static void main(String[] args) {
		cooler c1 = new cooler("deep cool","8x8","17/10/2013");
		
		c1.ligadoCooler();
	
		if(c1.EstadoCooler())
			System.out.println("cooler ligado");
		else
			System.out.println("cooler desligado");
		}}
