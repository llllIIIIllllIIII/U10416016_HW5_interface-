import javafx.application.Application;
import javafx.scene.Scene;
import javafx.scene.layout.Pane;
import javafx.scene.shape.Polyline;
import javafx.stage.Stage;

public class BeanGame extends Application{
	@Override
		public void start(Stage primaryStage){
			//Create main Pane
			Pane pane1= new Pane();
			
			Polyline polyline = new Polyline();
			polyline.getPoints().addAll(new Double[]{
					50.0, 100.0,
					50.0, 350.0,
					350.0,350.0,
					350.0,100.0});
			
			pane1.getChildren().add(polyline);
			//Create main Scene
			Scene bean = new Scene(pane1,400,400);
			
			//Stage settings
			primaryStage.setTitle("U10416016 BeanGame");
			primaryStage.setScene(bean);
			primaryStage.show();
	}
    public static void main(String[] args) {
        launch(args);
    }
    
}
