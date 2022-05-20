
# Objetos en java
Recordar palabras claves[^1].
:whale2:
:rabbit2:

| nombre de opción a usar| funcion  | example |
|:---:   |---: | ---|
|void      | Se usa cuando no se espera que se retorne nada |  public **void** setNombre( String nombre){   this.nombre=nombre;}
| | cuando no se pone nada en la clas, quiere decir que retornará un valor  | public string getNombre(){ **return** nombre;} |



Se oscila tener una clase y que sus metodos esten en privado, para que así sea más seguro. por ello se usa get an set

```java
    public class persona {
    //definimos nuestros atributos- se recomienda que sean en privado

    private String nombre;
    private String apellido_materno;
    private String apellido_paterno;
    private String dni;
    private String edad;
    private String talla;
    private String peso;

    //creamos los get and set para que se pueda modificar nuestros atributos-
    //los get and set son metodos o funciones en java


    public String getNombre() {
        return nombre;
    }

    public void setNombre(String nombre) {
        this.nombre = nombre;
    }
```


[^1]: mi referencia