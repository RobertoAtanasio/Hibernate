package com.luv2cod.jdbc;

import java.sql.Connection;
import java.sql.DriverManager;

public class Testejdbc {

	public static void main(String[] args) {

		String jdbcUrl = "jdbc:mysql://localhost:3306/cursojsf?useSSL=false";
		String user = "root";
		String pass = "";
		Connection con = null;
		try {
			System.out.println("Connecting to database: " + jdbcUrl);
			con = DriverManager.getConnection(jdbcUrl, user, pass);
			System.out.println("Connection succesful!");
		} catch (Exception exc) {
			exc.printStackTrace();
		}
		
	}

}
