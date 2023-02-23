# java
import java.awt.*;

import javafx.scene.layout.ColumnConstraints;
class FJAVA
{
    Frame f;
    Panel p;
    Label L1,L2,L3,L4,L5;
    TextField tx1,tx2,tx3;
    Button b1,b2,b3;
    public FJAVA(){
        f = new Frame();
        p = new Panel();
        L1 = new Label("First Name ");
        L2 = new Label("Middle Name ");
        L3 = new Label("Last Name ");
        L4 = new Label("First Name ");
        L5 = new Label("First Name ");
        tx1 = new TextField(19);
        tx2 = new TextField(19);
        tx3 = new TextField(19);
        b1 = new Button("login");
        b2 = new Button("sign up");
        b3 = new Button("new");

    
        p.setLayout(new GridLayout(6, 2));
        p.add(L1); p.add(tx1);
        p.add(L2); p.add(tx2);
        p.add(L3); p.add(tx3);
        p.add(L4); p.add(L5);
        p.add(b1); p.add(b2);
        p.add(b3);
        f.setLayout(new FlowLayout());
        f.add(p);
        f.setSize(500, 500);
        f.setVisible(true);
    }
    }
    public class framenew{

    
    public static void main(String[] args)
    {
        FJAVA f = new FJAVA();
        

    }
}


