/**
* @author Joshua Levi Flores Rankin -- Lesson from Arend Peter Teachest @ https://www.youtube.com/watch?v=ZDw18yUwz6I
* @version 0.1
* Learning how to create a frame, a panel, and a button.
*  Put a button in a panel, and the panel into the frame.
*/

import javax.swing.JFrame;
import javax.swing.JPanel;

import javax.swing.JButton;

public class BasicSwing extends JFrame{
   
   JPanel p = new JPanel();
   JButton b = new JButton("Hello");
   
   public static void main(String[] args) {
      new BasicSwing();
   }
   
   public BasicSwing() {
      super("Basic Swing App"); //Title
      setDefaultCloseOperation(EXIT_ON_CLOSE);
      
      setSize(400, 300);
      setResizable(true);
      
      p.add(b);
      add(p);
      
      setVisible(true);
   }
}
