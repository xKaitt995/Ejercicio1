# Ejercicio1
package ejercicioempleados;

import javax.swing.JDialog;
import javax.swing.JOptionPane;
import java.util.ArrayList;

public class Ejercicioempleados {

	private String nombre;
	private String dni;
	static double sueldobase = 1095;
	private String puesto;
	private double complemento;

	public Ejercicioempleados() {
	}

	public static ArrayList<Ejercicioempleados> Empleados = new ArrayList<Ejercicioempleados>();
	private static Ejercicioempleados emp;
	private double montosueldo;
	private double totalnominas = +montosueldo;

	public Ejercicioempleados(String dn, String nom, String puest, double sueldo, double complem) {
		// INICIAMOS
		this.dni = dn;
		this.nombre = nom;
		this.puesto = puest;
		this.complemento = complem;
		this.sueldobase = sueldobase;
	}

	// METODOS PARA OBTENER

	public void SetDni(String dni) {
		this.dni = dni;
	}

	public void SetNombre(String nombre) {
		this.nombre = nombre;
	}

	public void SetPuesto(String puesto) {
		this.puesto = puesto;
	}
