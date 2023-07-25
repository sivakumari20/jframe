# jframe\
package gui;

import javax.swing.JFrame;

public class jframe {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		JFrame frame=new JFrame();// creates a new frame
		frame.setTitle("frametitrle is siva");
		frame.setSize(420,300);
		frame.setVisible(true);
		
		
		// TODO Auto-generated method stub

	}

	public void setTitle(String str) {
		
		// TODO Auto-generated method stub
		
	}
public void setSize(int i,int j) {
		
		// TODO Auto-generated method stub
		
	}
public void setVisible(boolean b) {
	
	// TODO Auto-generated method stub
	
}


	}

** check the environment while running jframe
package gui;
import java.awt.Color;
import java.awt.Frame;
import java.awt.Image;

import javax.swing.ImageIcon;
import javax.swing.JFrame;
public class myframe extends jframe{
	myframe(){
		
	// creates a new this
	this.setTitle("siva this");
	this.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
	this.setResizable(false);//does not resizing after this
	this.setSize(420,309);
	this.setVisible(true);
	ImageIcon image =new ImageIcon("nabi.jpg"); // create an image icon
	this.setIconImage(image.getImage());
	this.getContentPane().setBackground( new Color(0,40,25));//  values
	
	
	


	}

	private void getContentPane() {
		// TODO Auto-generated method stub
		
	}

	private void setIconImage(Image image) {
		// TODO Auto-generated method stub
		
	}

	private void setVisible(boolean b) {
		// TODO Auto-generated method stub
		
	}

	private void setSize(int i, int j) {
		// TODO Auto-generated method stub
		
	}

	private void setResizable(boolean b) {
		// TODO Auto-generated method stub
		
	}

	private void setDefaultCloseOperation(int exitOnClose) {
		// TODO Auto-generated method stub
		
	}

	private void setTitle(String string) {
		// TODO Auto-generated method stub
		
	}

}
// check whether you uploaded image to main package ot=rnot 
if environment is not taking methods create a null method for every shoetmethod

package gui;

import java.awt.Color;
import java.awt.Font;

import javax.swing.BorderFactory;
import javax.swing.ImageIcon;
import javax.swing.JFrame;
import javax.swing.JLabel;
import javax.swing.border.Border;


public class jpanels {

	public static void main(String[] args) {
		Border border =BorderFactory.createLineBorder(Color.green,2);
		// TODO Auto-generated method stub
		
		JLabel label=new JLabel();
		label.setText("this is my label");
		
		ImageIcon image =new ImageIcon("nabi.jpg");
		label.setIcon(image);
		label.setHorizontalTextPosition(JLabel.CENTER);
		label.setVerticalTextPosition(JLabel.TOP);
		label.setForeground(Color.BLACK);
		label.setFont(new Font(" MV Boli",Font.BOLD,14));
		label.setIconTextGap(-25);// set gap of text to image 
		label.setBackground(Color.black);// set background color
		label.setOpaque(true);//display backgroud color
		label.setVerticalAlignment(JLabel.CENTER);
		label.setHorizontalAlignment(JLabel.CENTER);
		label.setBounds(100,120,250,250); 
		
		JFrame frame=new JFrame();// creates a new frame
		frame.setTitle("Sieve frame");
		frame.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
		frame.setLayout(null);
		//frame.setResizable(false);//does not resizing after this
		frame.setSize(100,100);
		frame.setIconImage(image.getImage());
		frame.setVisible(true);
		
		//frame.getContentPane().setBackground( new Color(255,0,0));// rgb values
		frame.add(label);
		label.setBorder(border);
		frame.pack();
	}

}
/// labelll


package gui;

import java.awt.BorderLayout;
import java.awt.Color;

import javax.swing.ImageIcon;
import javax.swing.JFrame;
import javax.swing.JLabel;
import javax.swing.JPanel;

public class panels {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		JLabel label =new JLabel(); // create a label 
		label.setText("glowing"); // set a text to this label
		ImageIcon icon =new ImageIcon("nabi.jpg"); //add a icon
		BorderLayout border=new BorderLayout(); // create a new border layout
		label.setIcon(icon);
		label.setVerticalAlignment(JLabel.CENTER);
		label.setHorizontalAlignment(JLabel.RIGHT);
		
		JPanel panel=new JPanel();
		panel.setBackground(Color.blue);
		panel.setBounds(0, 0, 250, 250);
		
		JPanel panel1=new JPanel();
		panel1.setBackground(Color.red);
		panel1.setBounds(250, 0, 250, 250);
		
		JPanel panel2=new JPanel();
		panel2.setBackground(Color.yellow);
		panel2.setBounds(250, 250, 250, 250);
		
		panel2.setLayout(border);
		 
		
		
		JFrame frame=new JFrame();// creates a new frame
		frame.setTitle("Sieve frame");//set frame title
		frame.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
		frame.setLayout(null);
		frame.setSize(100, 100); //set x and y coordinates of frame
		frame.setVisible(true);
		panel2.add(label);//add label to panel2
		frame.add(panel); //add panel to frame
		frame.add(panel1);// add panel1 to frame
		frame.add(panel2);
		
	}

}
******************jpanels
