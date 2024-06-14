package application;

import javafx.application.Application;
import javafx.fxml.FXMLLoader;
import javafx.scene.Parent;
import javafx.scene.Scene;
import javafx.stage.Stage;

public class Main extends Application {

    @Override
    public void start(Stage primaryStage) throws Exception {
        Parent root = FXMLLoader.load(getClass().getResource("allControls.fxml"));
        primaryStage.setTitle("Formulario de Controles");
        primaryStage.setScene(new Scene(root, 600, 400));
        primaryStage.show();
    }

    public static void main(String[] args) {
        launch(args);
    }
}


# FormularioJavaFx

Este es un proyecto JavaFX que demuestra el uso de varios controles.

![screenshot](https://github.com/Timador/FormularioFx/assets/168133781/7d4666ef-5f2c-456f-b862-07911e0fdd2c)

