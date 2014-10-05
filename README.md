import javax.swing.*;
import java.awt.Graphics;
import java.awt.Color;

public class SimpleGraphicsApplet extends JApplet {

	public void paint(Graphics g) {
		g.drawLine(25, 25, 50, 50);
		g.drawLine(50, 0, 50, 50);
		g.drawLine(0, 50, 50, 50);
		g.drawLine(50, 0, 0, 50);
		
		
	
	}
}
