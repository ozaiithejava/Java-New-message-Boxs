# Java-New-message-Boxs
a new messagebox on using Fx


## Usage :
```Java
import javafx.application.Application;
import javafx.stage.Stage;

public class Main extends Application {

    public static void main(String[] args) {
        launch(args);
    }

    @Override
    public void start(Stage primaryStage) {
        DarkMessageBoxExample darkMessageBoxExample = new DarkMessageBoxExample();
        darkMessageBoxExample.start(primaryStage);
    }
}
```

## Css
```Css
.root {
    -fx-base: #333333;
    -fx-background: #333333;
    -fx-control-inner-background: #333333;
    -fx-accent: #0066cc;
    -fx-focus-color: #0066cc;
    -fx-faint-focus-color: #0066cc;
    -fx-selection-bar: #0066cc;
    -fx-text-box-border: #0066cc;
    -fx-control-inner-background-alt: #0066cc;
    -fx-control-inner-background-alt2: #0066cc;
}

.dialog-pane {
    -fx-background-color: #333333;
}

.information-dialog .dialog-pane {
    -fx-background-color: #333333;
}

.warning-dialog .dialog-pane {
    -fx-background-color: #333333;
}

.error-dialog .dialog-pane {
    -fx-background-color: #333333;
}

.confirmation-dialog .dialog-pane {
    -fx-background-color: #333333;
}
```
