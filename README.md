# 371.-Configura-o-do-Projeto_1
Caixa de Botoes
package basico;

import javafx.application.Application;
import javafx.scene.Scene;
import javafx.scene.control.Button;
import javafx.scene.layout.VBox;
import javafx.stage.Stage;

public class PrimeiroFX extends Application{
	
	@Override
	public void start(Stage primaryStage) throws Exception {
		
		Button botaoA = new Button("A");
		Button botaoB = new Button("B");
		Button botaoC = new Button("C");
		
		VBox box = new VBox(10);
		box.getChildren().add(botaoA);
		box.getChildren().add(botaoB);
		box.getChildren().add(botaoC);
		
		Scene unicaCena = new Scene(box);
		
		primaryStage.setScene(unicaCena);
		primaryStage.show();
	}
	public static void main(String[] args) {
		launch(args);
		
	}
}

![image](https://user-images.githubusercontent.com/95525963/152683408-9c6d4937-ddea-4e38-9916-74f9c47eeb58.png)
