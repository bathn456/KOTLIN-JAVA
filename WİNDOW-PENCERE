import javax.swing.*;
import java.awt.*;


class Batuhan {
    public static void main(String[] args) {
        JFrame frame = new JFrame("pencere-window");
        //SWİNG KÜTÜPHANESİNİN JFRAME SINIFINDAN NESNE OLUŞTURUYORUZ PENCERE OLUŞTURMAK İÇİN
        frame.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
        frame.setSize(300, 200); //PENCERENİN BOYUTLARI

        JButton playButton = new JButton("Play");
        playButton.addActionListener(_ -> {
//BU METHOD BUTONUN TEPKİ METHODU YANİ BUTONA TIKLANDIĞINDA NE OLUCAK ?? JBUTTON NESNESİ İÇİN GEREKİYOR
            System.out.println("Play butonuna tıklandı!");
        });

        frame.add(playButton, BorderLayout.CENTER);
        frame.setVisible(true);
    }
}
