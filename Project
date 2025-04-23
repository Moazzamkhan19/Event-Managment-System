package com.example.demo;

import javafx.application.Platform;
import javafx.collections.FXCollections;
import javafx.geometry.Insets;
import javafx.scene.control.*;
import javafx.application.Application;
import javafx.geometry.Pos;
import javafx.scene.Scene;
import javafx.scene.control.Button;
import javafx.scene.control.Label;
import javafx.scene.control.TextField;
import javafx.scene.layout.*;
import javafx.scene.paint.Color;
import javafx.scene.shape.Rectangle;
import javafx.scene.text.Font;
import javafx.scene.text.FontWeight;
import javafx.scene.text.Text;
import javafx.stage.Stage;
import javafx.scene.image.Image;
import javafx.scene.image.ImageView;
import javafx.fxml.FXML;
import javafx.fxml.Initializable;
import javafx.scene.layout.AnchorPane;

import java.net.URL;
import java.util.Arrays;
import java.util.ResourceBundle;


import java.io.*;
import java.util.ArrayList;

public class HelloApplication extends Application implements Initializable {
    @Override
    public void start(Stage stage) throws IOException, ClassNotFoundException {

         var manager=readEventManagerFromFile();
        if (manager.vip == null) {
            System.out.println("vip list is null, reinitializing...");
            manager.vip = new ArrayList<>();
        }if (manager.executive == null) {
            System.out.println("vip list is null, reinitializing...");
            manager.executive = new ArrayList<>();
        }if (manager.regular == null) {
            System.out.println("vip list is null, reinitializing...");
            manager.regular = new ArrayList<>();
        }
        // ----------------Left Menu Buttons
        String buttonStyle = "-fx-background-color: DARKSLATEGREY; -fx-text-fill: white; -fx-padding: 10px 20px; -fx-background-radius: 10px;";

        Button addPersonButton = new Button("Add Person Info");
        addPersonButton.setStyle(buttonStyle);

        Button findPersonButton = new Button("Find Person");
        findPersonButton.setStyle(buttonStyle);

        Button addMatchDetailsButton = new Button("Add Match Details");
        addMatchDetailsButton.setStyle(buttonStyle);

        Button addSecurityDetailsButton = new Button("Add Security Details");
        addSecurityDetailsButton.setStyle(buttonStyle);

        Button addUmpireInfoButton = new Button("Add Umpire Info");
        addUmpireInfoButton.setStyle(buttonStyle);

        Button refundTicketButton = new Button("Refund Ticket");
        refundTicketButton.setStyle(buttonStyle);

        Button ticketSoldInfoButton = new Button("Ticket Sold Info");
        ticketSoldInfoButton.setStyle(buttonStyle);

        Button showMatchDetailsButton = new Button("Show Match Details");
        showMatchDetailsButton.setStyle(buttonStyle);

        Button displayRevenueButton = new Button("Display Revenue");
        displayRevenueButton.setStyle(buttonStyle);

        Button displaySecurityInfoButton = new Button("Display Security Info");
        displaySecurityInfoButton.setStyle(buttonStyle);

        Button displayUmpireInfoButton = new Button("Display Umpire Info");
        displayUmpireInfoButton.setStyle(buttonStyle);

        Button replaceSecurityGuardButton = new Button("Replace Security Guard");
        replaceSecurityGuardButton.setStyle(buttonStyle);

        Button exitButton = new Button("Exit");
        exitButton.setStyle(buttonStyle);

        VBox buttons = new VBox();
        buttons.getChildren().addAll(addPersonButton, findPersonButton, addMatchDetailsButton, addSecurityDetailsButton, addUmpireInfoButton
                , refundTicketButton, ticketSoldInfoButton, showMatchDetailsButton, displayRevenueButton, displaySecurityInfoButton, displayUmpireInfoButton
                , replaceSecurityGuardButton, exitButton);
        buttons.setSpacing(2);
        // ----------------Left Menu Buttons

        //---------------Menu Structure and BG
        Rectangle left = new Rectangle(200, 550);
        left.setFill(Color.DARKSLATEGREY);
        left.setArcHeight(50);
        left.setArcWidth(50);

        Rectangle center = new Rectangle(500, 550);
        center.setFill(Color.DARKSEAGREEN);
        center.setArcHeight(50);
        center.setArcWidth(50);
        //---------------Menu Structure and BG

        Button addPersonButton1 = new Button("Add Person Info");
        addPersonButton1.setStyle(buttonStyle);

        Button findPersonButton1 = new Button("Find Person");
        findPersonButton1.setStyle(buttonStyle);

        Button addMatchDetailsButton1 = new Button("Add Match Details");
        addMatchDetailsButton1.setStyle(buttonStyle);

        Button addSecurityDetailsButton1 = new Button("Add Security Details");
        addSecurityDetailsButton1.setStyle(buttonStyle);

        Button addUmpireInfoButton1 = new Button("Add Umpire Info");
        addUmpireInfoButton1.setStyle(buttonStyle);

        Button refundTicketButton1 = new Button("Refund Ticket");
        refundTicketButton1.setStyle(buttonStyle);

        Button ticketSoldInfoButton1 = new Button("Ticket Sold Info");
        ticketSoldInfoButton1.setStyle(buttonStyle);

        Button showMatchDetailsButton1 = new Button("Show Match Details");
        showMatchDetailsButton1.setStyle(buttonStyle);

        Button displayRevenueButton1 = new Button("Display Revenue");
        displayRevenueButton1.setStyle(buttonStyle);

        Button displaySecurityInfoButton1 = new Button("Display Security Info");
        displaySecurityInfoButton1.setStyle(buttonStyle);

        Button displayUmpireInfoButton1 = new Button("Display Umpire Info");
        displayUmpireInfoButton1.setStyle(buttonStyle);

        Button replaceSecurityGuardButton1 = new Button("Replace Security Guard");
        replaceSecurityGuardButton1.setStyle(buttonStyle);

        Button exitButton1 = new Button("Exit");
        exitButton1.setStyle(buttonStyle);

        VBox buttons1 = new VBox();
        buttons1.getChildren().addAll(addPersonButton1, findPersonButton1, addMatchDetailsButton1, addSecurityDetailsButton1, addUmpireInfoButton1
                , refundTicketButton1, ticketSoldInfoButton1, showMatchDetailsButton1, displayRevenueButton1, displaySecurityInfoButton1, displayUmpireInfoButton1
                , replaceSecurityGuardButton1, exitButton1);
        buttons1.setSpacing(2);
        // ----------------Left Menu Buttons

        //---------------Menu Structure and BG
        Rectangle left1 = new Rectangle(200, 550);
        left1.setFill(Color.DARKSLATEGREY);
        left1.setArcHeight(50);
        left1.setArcWidth(50);

        Rectangle center1 = new Rectangle(500, 550);
        center1.setFill(Color.DARKSEAGREEN);
        center1.setArcHeight(50);
        center1.setArcWidth(50);
        //---------------Menu Structure and BG

        Button addPersonButton2 = new Button("Add Person Info");
        addPersonButton2.setStyle(buttonStyle);

        Button findPersonButton2 = new Button("Find Person");
        findPersonButton2.setStyle(buttonStyle);

        Button addMatchDetailsButton2 = new Button("Add Match Details");
        addMatchDetailsButton2.setStyle(buttonStyle);

        Button addSecurityDetailsButton2 = new Button("Add Security Details");
        addSecurityDetailsButton2.setStyle(buttonStyle);

        Button addUmpireInfoButton2 = new Button("Add Umpire Info");
        addUmpireInfoButton2.setStyle(buttonStyle);

        Button refundTicketButton2 = new Button("Refund Ticket");
        refundTicketButton2.setStyle(buttonStyle);

        Button ticketSoldInfoButton2 = new Button("Ticket Sold Info");
        ticketSoldInfoButton2.setStyle(buttonStyle);

        Button showMatchDetailsButton2 = new Button("Show Match Details");
        showMatchDetailsButton2.setStyle(buttonStyle);

        Button displayRevenueButton2 = new Button("Display Revenue");
        displayRevenueButton2.setStyle(buttonStyle);

        Button displaySecurityInfoButton2 = new Button("Display Security Info");
        displaySecurityInfoButton2.setStyle(buttonStyle);

        Button displayUmpireInfoButton2 = new Button("Display Umpire Info");
        displayUmpireInfoButton2.setStyle(buttonStyle);

        Button replaceSecurityGuardButton2 = new Button("Replace Security Guard");
        replaceSecurityGuardButton2.setStyle(buttonStyle);

        Button exitButton2 = new Button("Exit");
        exitButton2.setStyle(buttonStyle);

        VBox buttons2 = new VBox();
        buttons2.getChildren().addAll(addPersonButton2, findPersonButton2, addMatchDetailsButton2, addSecurityDetailsButton2, addUmpireInfoButton2
                , refundTicketButton2, ticketSoldInfoButton2, showMatchDetailsButton2, displayRevenueButton2, displaySecurityInfoButton2, displayUmpireInfoButton2
                , replaceSecurityGuardButton2, exitButton2);
        buttons2.setSpacing(2);
        // ----------------Left Menu Buttons

        //---------------Menu Structure and BG
        Rectangle left2 = new Rectangle(200, 550);
        left2.setFill(Color.DARKSLATEGREY);
        left2.setArcHeight(50);
        left2.setArcWidth(50);

        Rectangle center2 = new Rectangle(500, 550);
        center2.setFill(Color.DARKSEAGREEN);
        center2.setArcHeight(50);
        center2.setArcWidth(50);
        //---------------Menu Structure and BG


        //Login Screen
        Rectangle center0  = new Rectangle(500, 550);
        center0.setFill(Color.DARKSEAGREEN);
        center0.setArcHeight(50);
        center0.setArcWidth(50);

        Rectangle loginRectangle = new Rectangle(300, 300);
        loginRectangle.setArcWidth(50);
        loginRectangle.setArcHeight(50);
        loginRectangle.setFill(Color.HONEYDEW);

        Text loginText = new Text("   Sign in");
        loginText.setFont(Font.font("Roboto", 30));
        Label blank = new Label("");

        var userNameField = new TextField();
        userNameField.setPromptText("User Name/ Email");

        PasswordField passwordField = new PasswordField();
        Label passwordLabel = new Label("   Password");
        passwordLabel.setStyle("-fx-text-fill: lightgray");
        passwordField.textProperty().addListener((observable, oldValue, newValue) -> {
            passwordLabel.setVisible(newValue.isEmpty());
        });

        Button signinButton = new Button("Sign in");
        signinButton.setStyle(buttonStyle);

        Label loginErrorMessage = new Label("");
        loginErrorMessage.setStyle("-fx-text-fill: red");

        var loginLayout = new GridPane();
        loginLayout.add(loginText, 0, 1);
        loginLayout.add(userNameField, 0, 3);
        loginLayout.add(passwordField, 0, 5);
        loginLayout.add(passwordLabel, 0, 5);
        loginLayout.add(signinButton, 0, 7);
        loginLayout.add(loginErrorMessage, 0, 8);
        loginLayout.setVgap(10);
        loginLayout.setAlignment(Pos.CENTER);

        var loginStack = new StackPane();
        loginStack.getChildren().add(center0);
        loginStack.getChildren().add(loginRectangle);
        loginStack.getChildren().add(loginLayout);
        loginStack.setAlignment(Pos.CENTER);

        Image leftImage = new Image("9.jpg");
        ImageView leftImageView = new ImageView(leftImage);

        Rectangle clipRectangle = new Rectangle(600, 600);
        clipRectangle.setArcWidth(50);
        clipRectangle.setArcHeight(50);
        leftImageView.setClip(clipRectangle);

        StackPane leftImageLayout = new StackPane();
        leftImageLayout.getChildren().add(leftImageView);

        GridPane login = new GridPane();
        login.add(leftImageLayout, 0, 0);
        login.add(loginStack, 1, 0);
        login.setAlignment(Pos.CENTER);
        login.setStyle("-fx-background-color: #1F2D3D;");

        Scene loginScene = new Scene(login);
        //Login

        //------------------------------------------------Scene0------------------------------------------------------//
        Image base=new Image("8.jpg");
        ImageView baseView=new ImageView(base);
        GridPane layout=new GridPane(); //Base layout Scene

        Button addPersonButton3 = new Button("Add Person Info");
        addPersonButton3.setStyle(buttonStyle);

        Button findPersonButton3 = new Button("Find Person");
        findPersonButton3.setStyle(buttonStyle);

        Button addMatchDetailsButton3 = new Button("Add Match Details");
        addMatchDetailsButton3.setStyle(buttonStyle);

        Button addSecurityDetailsButton3 = new Button("Add Security Details");
        addSecurityDetailsButton3.setStyle(buttonStyle);

        Button addUmpireInfoButton3 = new Button("Add Umpire Info");
        addUmpireInfoButton3.setStyle(buttonStyle);

        Button refundTicketButton3 = new Button("Refund Ticket");
        refundTicketButton3.setStyle(buttonStyle);

        Button ticketSoldInfoButton3 = new Button("Ticket Sold Info");
        ticketSoldInfoButton3.setStyle(buttonStyle);

        Button showMatchDetailsButton3 = new Button("Show Match Details");
        showMatchDetailsButton3.setStyle(buttonStyle);

        Button displayRevenueButton3 = new Button("Display Revenue");
        displayRevenueButton3.setStyle(buttonStyle);

        Button displaySecurityInfoButton3 = new Button("Display Security Info");
        displaySecurityInfoButton3.setStyle(buttonStyle);

        Button displayUmpireInfoButton3 = new Button("Display Umpire Info");
        displayUmpireInfoButton3.setStyle(buttonStyle);

        Button replaceSecurityGuardButton3 = new Button("Replace Security Guard");
        replaceSecurityGuardButton3.setStyle(buttonStyle);

        Button exitButton3 = new Button("Exit");
        exitButton3.setStyle(buttonStyle);

        layout.add(addPersonButton3,2,1);
        layout.add(findPersonButton3,2,3);
        layout.add(addMatchDetailsButton3,2,5);
        layout.add(addSecurityDetailsButton3,2,7);
        layout.add(addUmpireInfoButton3,2,9);
        layout.add(refundTicketButton3,2,11);
        layout.add(ticketSoldInfoButton3,8,1);
        layout.add(showMatchDetailsButton3,8,3);
        layout.add(displayRevenueButton3,8,5);
        layout.add(displaySecurityInfoButton3,8,7);
        layout.add(displayUmpireInfoButton3,8,9);
        layout.add(replaceSecurityGuardButton3,8,11);
        layout.add(exitButton3,5,5);
        layout.setAlignment(Pos.CENTER_LEFT);

        layout.setHgap(120);
        layout.setVgap(5);

        StackPane baseImage=new StackPane(baseView,layout);
        Scene scene0=new Scene(baseImage);
        //------------------------------------------------Scene 1-----------------------------------------------------//working add person info
        GridPane layout1=new GridPane();
        layout1.setVgap(10);
        layout1.setHgap(10);
        layout1.setMaxSize(Region.USE_COMPUTED_SIZE,Region.USE_COMPUTED_SIZE);
        layout1.setAlignment(Pos.CENTER);

        Label l1=new Label("Enter Name :");
        Label l2=new Label("Enter Cnic :");
        Label l3=new Label("Select Seat class :");

        TextField tf1=new TextField();
        TextField tf2=new TextField();
        tf1.setPromptText("Name");
        tf2.setPromptText("cnic");

        ComboBox<String>cbx1=new ComboBox<>();
        cbx1.getItems().addAll("VIP","Executive","Regular");
        cbx1.setPromptText("Select");
        cbx1.setValue("Regular");

        Button b200=new Button("Submit");

        b200.setStyle("-fx-background-color:Lightblue");


        l1.setFont(Font.font("Helvetica", 16));
        l1.setTextFill(Color.BLACK);

        l2.setFont(Font.font("Helvetica", 16));
        l2.setTextFill(Color.BLACK);

        l3.setFont(Font.font("Helvetica", 16));
        l3.setTextFill(Color.BLACK);

        ColumnConstraints columnConstraints=new ColumnConstraints();
        columnConstraints.setPercentWidth(50);

        layout1.add(l1,0,0);
        layout1.add(l2,0,2);
        layout1.add(l3,0,4);
        layout1.add(tf1,0,1);
        layout1.add(tf2,0,3);
        layout1.add(cbx1,0,5);
        layout1.add(b200,1,6);

        //---------------------------------------------BACKEND SCENE1------------------------------------------------------------------//
        Label el1=new Label("Name cannot be empty");
        Label el2=new Label("Cnic cannot be empty");
        Label ela=new Label("No ticket available");
        Label elb=new Label("Capacity Full");
        Label elc=new Label("Invalid Cnic");
        el1.setTextFill(Color.RED);
        el2.setTextFill(Color.RED);
        ela.setTextFill(Color.RED);
        elb.setTextFill(Color.RED);
        elc.setTextFill(Color.RED);
        el1.setVisible(false);
        el2.setVisible(false);
        ela.setVisible(false);
        elb.setVisible(false);
        elc.setVisible(false);

        layout1.add(el1,1,1);
        layout1.add(el2,1,3);
        layout1.add(ela,1,4);
        layout1.add(elb,1,5);
        layout1.add(elc,1,7);

        
        b200.setOnAction(e-> {

            Seat seat = manager.seat;
            int ticketsSold1 = 0;
            int total = 500;//total seats
            int totalVipSeats = 150;//total vip seats
            int totalExecutiveSeats = 50;//total executive seats
            int totalRegularSeats = 300;//total regular seats
            double price = 0.0;

            String personName = tf1.getText();
            String cnic = tf2.getText();
            String seatclass = cbx1.getValue();
            //----------------------------------------validation-------------------------//
            boolean valid = false;

            if (personName.isEmpty()) {
                el1.setVisible(true);

            }
            if (cnic.isEmpty()) {
                el2.setVisible(true);

            }
            if (isValidCNICFormat(cnic)&&!isCnicRepeated(cnic, manager.vip)&&!isCnicRepeated(cnic, manager.executive)&&!isCnicRepeated(cnic, manager.regular)) {
                Person person = new Person(personName, cnic, seatclass);
                if (seat.getTotalOccupiedSeats() >= 500) {
                    elb.setVisible(true);
                }

                //IF THE cbx1 choose Vip THEN HIS INFORMATION IS ENTERED IN VIP ARRAY
                if (seatclass.equals("VIP")) {
                        if (seat.getVipOccupied() < totalVipSeats) {
                            seat.setVipOccupied(seat.getVipOccupied() + 1);
                            seat.setVipAvailable(totalVipSeats - seat.getVipOccupied());
                            price = 8000.0;
                            seat.setTotalOccupiedSeats(seat.getTotalOccupiedSeats() + 1);
                            seat.setTotalAvailableSeats(total - seat.getTotalOccupiedSeats());
                            manager.vip.add(person);
                            System.out.println("Success");

                        } else {
                            ela.setVisible(true);//this will allow the label to show error
                        }
                }
                //IF THE cbx1 chooses Executive THEN HIS INFORMATION IS ENTERED IN EXECUTIVE ARRAY
                else if (seatclass.equals("Executive")) {
                        if (seat.getExecutiveOccupied() < totalExecutiveSeats) {
                            seat.setExecutiveOccupied(seat.getExecutiveOccupied() + 1);
                            seat.setExecutiveAvailable(totalExecutiveSeats - seat.getExecutiveOccupied());
                            price = 12000.0;
                            seat.setTotalOccupiedSeats(seat.getTotalOccupiedSeats() + 1);
                            seat.setTotalAvailableSeats(total - seat.getTotalOccupiedSeats());
                            manager.executive.add(person);
                        } else {
                            ela.setVisible(true);
                        }
                }
                //IF THE cbx1 chooses Regular THEN HIS INFORMATION IS ENTERED IN REGULAR ARRAY
                else if (seatclass.equals("Regular")) {
                        if (seat.getRegularOccupied() < totalRegularSeats) {
                            seat.setRegularOccupied(seat.getRegularOccupied() + 1);
                            seat.setRegularAvailable(totalRegularSeats - seat.getRegularOccupied());
                            price = 4000.0;
                            seat.setTotalOccupiedSeats(seat.getTotalOccupiedSeats() + 1);
                            seat.setTotalAvailableSeats(total - seat.getTotalOccupiedSeats());

                            manager.regular.add(person);
                        } else {
                            elb.setVisible(true);
                        }
                    }
                ticketsSold1++;
                manager.setSeat(seat);
                manager.setRevenue(manager.getRevenue() + price);
                manager.setTicketsSold(ticketsSold1);
                try {
                    writeEventManagerToFile(manager);
                } catch (IOException ex) {
                    throw new RuntimeException(ex);
                }

                tf1.clear();
                tf2.clear();
                el1.setVisible(false);
                el2.setVisible(false);
                ela.setVisible(false);
                elb.setVisible(false);
                elc.setVisible(false);
            } else {
                elc.setVisible(true);
            }
        });

        //---------------------------------------------scene1 design----------------------------------------------------//
        Button b1 = new Button("Add Person Info");
        Button b2 = new Button("Find Person");
        Button b3 = new Button("Add Match Details");
        Button b4 = new Button("Add Security Details");
        Button b5 = new Button("Add Umpire Info");
        Button b6 = new Button("Refund Ticket");
        Button b7 = new Button("Ticket Sold Info");
        Button b8 = new Button("Show Match Details");
        Button b9 = new Button("Display Revenue");
        Button b10 = new Button("Display Security Info");
        Button b11 = new Button("Display Umpire Info");
        Button b12 = new Button("Replace Security Guard");
        Button b13 = new Button("Exit");

        b1.setStyle(buttonStyle);
        b2.setStyle(buttonStyle);
        b3.setStyle(buttonStyle);
        b4.setStyle(buttonStyle);
        b5.setStyle(buttonStyle);
        b6.setStyle(buttonStyle);
        b7.setStyle(buttonStyle);
        b8.setStyle(buttonStyle);
        b9.setStyle(buttonStyle);
        b10.setStyle(buttonStyle);
        b11.setStyle(buttonStyle);
        b12.setStyle(buttonStyle);
        b13.setStyle(buttonStyle);

        VBox buttons3=new VBox();
        buttons3.getChildren().addAll(b1, b2, b3, b4, b5,b6, b7, b8, b9, b10, b11, b12, b13);
        buttons3.setSpacing(2);

        Rectangle left3=new Rectangle(200,550);
        left3.setFill(Color.DARKSLATEGREY);
        left3.setArcHeight(50);
        left3.setArcWidth(50);

        Rectangle center3=new Rectangle(500, 550);
        center3.setFill(Color.DARKSEAGREEN);
        center3.setArcHeight(50);
        center3.setArcWidth(50);

        Rectangle incenter=new Rectangle(350,350);//this rectangle is inside the center one
        incenter.setFill(Color.HONEYDEW);
        incenter.setArcWidth(50);
        incenter.setArcHeight(50);



        StackPane sp1=new StackPane(incenter,layout1);
        sp1.setAlignment(Pos.CENTER);

        StackPane sp2=new StackPane(center3,sp1);
        sp2.setAlignment(Pos.CENTER);


        GridPane menu =new GridPane();
        menu.add(left3, 0,0);
        menu.add(buttons3, 0, 0);
        menu.add(sp2, 1, 0);
        menu.setAlignment(Pos.CENTER);
        menu.setStyle("-fx-background-color: #1F2D3D ;");

        Scene scene1=new Scene(menu);
        //-------------------------------------------SCENE2----------------------------------------------------------//working find person
        GridPane layout2=new GridPane();
        layout2.setVgap(5);
        layout2.setHgap(10);
        layout2.setAlignment(Pos.CENTER);

        Label l5=new Label("Select class :");
        Label l6=new Label("ID :");


        l5.setFont(Font.font("Helvetica", 16));
        l5.setTextFill(Color.BLACK);

        l6.setFont(Font.font("Helvetica", 16));
        l6.setTextFill(Color.BLACK);

        ComboBox<String>cbx2=new ComboBox<>();
        cbx2.getItems().addAll("VIP","Executive","Regular");
        cbx2.setValue("Regular");


        TextField tf4=new TextField();
        tf4.setPromptText("Enter ID");

        Button bB=new Button("Submit");
        bB.setStyle("-fx-background-color:Lightblue");


        Label el3=new Label("cannot be null");
        Label eld=new Label("exceeding ");

        el3.setTextFill(Color.RED);
        eld.setTextFill(Color.RED);

        el3.setVisible(false);
        eld.setVisible(false);

        tf4.setOnAction(a->validatetf(tf4,el3));
        layout2.add(el3,1,3);
        layout2.add(eld,1,2);


        layout2.add(l5,0,0);
        layout2.add(l6,0,2);
        layout2.add(cbx2,0,1);
        layout2.add(tf4,0,3);
        layout2.add(bB,1,8);

        layout2.setAlignment(Pos.CENTER);
        //---------------------------------------------BACKEND WORK-----------------------------------------------------//
        bB.setOnAction(b-> {

            layout2.getChildren().removeIf(node -> {
                if (node instanceof Label) {
                    String labelText = ((Label) node).getText();
                    return labelText.startsWith("ID :") || labelText.startsWith("Name :") || labelText.startsWith("Cnic :") || labelText.startsWith("Ticket :");
                }
                return false;
            });
            //----------------------------------------validation-------------------------//

            int id = Integer.parseInt(tf4.getText());
            String seatype=cbx2.getValue();

            if(seatype.equals("Executive"))
            {
                if (id <= manager.executive.size() - 1)
                {
                    String ID1=Integer.toString(id);
                    Label l7=new Label("ID :"+ID1);
                    Label l8=new Label("Name :"+manager.executive.get(id).getName());
                    Label l9=new Label("Cnic :"+manager.executive.get(id).getCnic());
                    Label l10=new Label("Ticket :"+manager.executive.get(id).getSeatclass());

                    layout2.add(l7,0,4);
                    layout2.add(l8,0,5);
                    layout2.add(l9,0,6);
                    layout2.add(l10,0,7);

                    tf4.clear();

                    el3.setVisible(false);
                    eld.setVisible(false);
                }
                else
                {
                    eld.setVisible(true);
                }


            }
            if(seatype.equals("VIP"))
            {
                if(manager.vip==null){
                    eld.setVisible(true);
                }
                else {
                    if (id <= manager.vip.size() - 1) {
                        String ID2 = Integer.toString(id);
                        Label l105 = new Label("ID :" + ID2);
                        Label l106 = new Label("Name :" + manager.vip.get(id).getName());
                        Label l107 = new Label("Cnic :" + manager.vip.get(id).getCnic());
                        Label l108 = new Label("Ticket :" + manager.vip.get(id).getSeatclass());

                        layout2.add(l105, 0, 4);
                        layout2.add(l106, 0, 5);
                        layout2.add(l107, 0, 6);
                        layout2.add(l108, 0, 7);

                        tf4.clear();

                        el3.setVisible(false);
                        eld.setVisible(false);
                    } else {
                        eld.setVisible(true);
                    }
                }
            }

            if(seatype.equals("Regular"))
            {
                if(id<=manager.regular.size()-1)
                {
                    String ID3=Integer.toString(id);
                    Label l109=new Label("ID :"+ID3);
                    Label l110=new Label("Name :"+manager.regular.get(id).getName());
                    Label l111=new Label("Cnic :"+manager.regular.get(id).getCnic());
                    Label l112=new Label("Ticket :"+manager.regular.get(id).getSeatclass());

                    layout2.add(l109,0,4);
                    layout2.add(l110,0,5);
                    layout2.add(l111,0,6);
                    layout2.add(l112,0,7);

                    tf4.clear();

                    el3.setVisible(false);
                    eld.setVisible(false);
                }
                else {
                    eld.setVisible(true);
                }

            }
        });
        //------------------------------------------SCENE2 design------------------------------------------------------//
        Button b14 = new Button("Add Person Info");
        Button b15 = new Button("Find Person");
        Button b16 = new Button("Add Match Details");
        Button b17 = new Button("Add Security Details");
        Button b18 = new Button("Add Umpire Info");
        Button b19 = new Button("Refund Ticket");
        Button b20 = new Button("Ticket Sold Info");
        Button b21 = new Button("Show Match Details");
        Button b22 = new Button("Display Revenue");
        Button b23 = new Button("Display Security Info");
        Button b24 = new Button("Display Umpire Info");
        Button b25 = new Button("Replace Security Guard");
        Button b26 = new Button("Exit");

        b14.setStyle(buttonStyle);
        b15.setStyle(buttonStyle);
        b16.setStyle(buttonStyle);
        b17.setStyle(buttonStyle);
        b18.setStyle(buttonStyle);
        b19.setStyle(buttonStyle);
        b20.setStyle(buttonStyle);
        b21.setStyle(buttonStyle);
        b22.setStyle(buttonStyle);
        b23.setStyle(buttonStyle);
        b24.setStyle(buttonStyle);
        b25.setStyle(buttonStyle);
        b26.setStyle(buttonStyle);

        VBox buttons4 = new VBox();
        buttons4.getChildren().addAll(b14, b15, b16, b17, b18, b19, b20, b21, b22, b23, b24, b25, b26);
        buttons4.setSpacing(2);

        Rectangle left4=new Rectangle(200,550);
        left4.setFill(Color.DARKSLATEGREY);
        left4.setArcHeight(50);
        left4.setArcWidth(50);

        Rectangle center4=new Rectangle(500, 550);
        center4.setFill(Color.DARKSEAGREEN);
        center4.setArcHeight(50);
        center4.setArcWidth(50);

        Rectangle incenter2=new Rectangle(350,350);//this rectangle is inside the center one
        incenter2.setFill(Color.HONEYDEW);
        incenter2.setArcWidth(50);
        incenter2.setArcHeight(50);

        StackPane sp3=new StackPane(incenter2,layout2);
        sp3.setAlignment(Pos.CENTER);

        StackPane sp4=new StackPane(center4,sp3);
        sp4.setAlignment(Pos.CENTER);

        GridPane menu1 =new GridPane();
        menu1.add(left4, 0,0);
        menu1.add(buttons4, 0, 0);
        menu1.add(sp4, 1, 0);
        menu1.setAlignment(Pos.CENTER);
        menu1.setStyle("-fx-background-color: #1F2D3D ;");

        Scene scene2=new Scene(menu1);
        //-----------------------------------------SCENE3---------------------------------------------------------------//working Match details
        GridPane layout3=new GridPane();

        layout3.setVgap(10);
        layout3.setHgap(10);

        Label l12=new Label("Stadium Name");
        Label l13=new Label("Match Ending time");
        Label l14=new Label("Match starting time");
        Label l15=new Label("Date of match");

        TextField tf5=new TextField();
        TextField tf6=new TextField();
        TextField tf7=new TextField();
        TextField tf8=new TextField("dd/mm/yy");

        Button b126=new Button("Next");
        b126.setStyle("-fx-background-color:Lightblue");


        layout3.add(l12,0,0);
        layout3.add(l13,0,2);
        layout3.add(l14,0,4);
        layout3.add(l15,0,6);


        layout3.add(tf5,0,1);
        layout3.add(tf6,0,3);
        layout3.add(tf7,0,5);
        layout3.add(tf8,0,7);

        layout3.add(b126,6,8);


        l12.setFont(Font.font("Helvetica", 16));
        l12.setTextFill(Color.BLACK);

        l13.setFont(Font.font("Helvetica", 16));
        l13.setTextFill(Color.BLACK);

        l14.setFont(Font.font("Helvetica", 16));
        l14.setTextFill(Color.BLACK);

        l15.setFont(Font.font("Helvetica", 16));
        l15.setTextFill(Color.BLACK);
        //----------------------------------------validation-------------------------//

        Label el7=new Label("cannot be empty");
        Label el8=new Label("cannot be empty");
        Label el6=new Label("cannot be empty");

        el7.setTextFill(Color.RED);
        el8.setTextFill(Color.RED);
        el6.setTextFill(Color.RED);

        el7.setVisible(false);
        el8.setVisible(false);
        el6.setVisible(false);

        tf5.setOnAction(e->validatetf(tf5,el7));
        tf6.setOnAction(e->validatetf(tf6,el8));
        tf7.setOnAction(e->validatetf(tf7,el6));



        layout3.add(el7,3,1);
        layout3.add(el8,3,3);
        layout3.add(el6,3,5);

        layout3.setAlignment(Pos.CENTER);
        //---------------------------------------BACKEND PROGRAM-------------------------------------------------------------------------//
        MatchDetails matchDetail=new MatchDetails();

        b126.setOnAction(b->{
            String stadiumNam=tf5.getText();
            String endTim=tf6.getText();
            String startTim=tf7.getText();
            String dat=tf8.getText();

            matchDetail.startingTime = startTim;
            matchDetail.endingTime = endTim;
            matchDetail.stadiumName = stadiumNam;
            matchDetail.date = dat;


        });

        //-----------------------------------------SCENE3 DESIGN--------------------------------------------------------//=
        Button b27 = new Button("Add Person Info");
        Button b28 = new Button("Find Person");
        Button b29 = new Button("Add Match Details");
        Button b30 = new Button("Add Security Details");
        Button b31 = new Button("Add Umpire Info");
        Button b32 = new Button("Refund Ticket");
        Button b33 = new Button("Ticket Sold Info");
        Button b34 = new Button("Show Match Details");
        Button b35 = new Button("Display Revenue");
        Button b36 = new Button("Display Security Info");
        Button b37 = new Button("Display Umpire Info");
        Button b38 = new Button("Replace Security Guard");
        Button b39 = new Button("Exit");

        b27.setStyle(buttonStyle);
        b28.setStyle(buttonStyle);
        b29.setStyle(buttonStyle);
        b30.setStyle(buttonStyle);
        b31.setStyle(buttonStyle);
        b32.setStyle(buttonStyle);
        b33.setStyle(buttonStyle);
        b34.setStyle(buttonStyle);
        b35.setStyle(buttonStyle);
        b36.setStyle(buttonStyle);
        b37.setStyle(buttonStyle);
        b38.setStyle(buttonStyle);
        b39.setStyle(buttonStyle);

        VBox buttons5 = new VBox();
        buttons5.getChildren().addAll(b27, b28, b29, b30, b31, b32, b33, b34, b35, b36, b37, b38, b39);
        buttons5.setSpacing(2);


        Rectangle left5=new Rectangle(200,550);
        left5.setFill(Color.DARKSLATEGREY);
        left5.setArcHeight(50);
        left5.setArcWidth(50);

        Rectangle center5=new Rectangle(500, 550);
        center5.setFill(Color.DARKSEAGREEN);
        center5.setArcHeight(50);
        center5.setArcWidth(50);

        Rectangle incenter3=new Rectangle(350,350);//this rectangle is inside the center one
        incenter3.setFill(Color.HONEYDEW);
        incenter3.setArcWidth(50);
        incenter3.setArcHeight(50);

        StackPane sp5=new StackPane(incenter3,layout3);
        sp5.setAlignment(Pos.CENTER);

        StackPane sp6=new StackPane(center5,sp5);
        sp6.setAlignment(Pos.CENTER);

        GridPane menu2 =new GridPane();
        menu2.add(left5, 0,0);
        menu2.add(buttons5, 0, 0);
        menu2.add(sp6, 1, 0);
        menu2.setAlignment(Pos.CENTER);
        menu2.setStyle("-fx-background-color: #1F2D3D ;");

        Scene scene3=new Scene(menu2);
        //-----------------------------------------SCENE3A--------------------------------------------------------------//working Match detail
        GridPane layout4=new GridPane();
        layout4.setVgap(5);
        layout4.setHgap(5);
        layout4.setAlignment(Pos.CENTER);

        Label l16=new Label("Player number");
        Label l150=new Label("Coach name");
        Label l18=new Label("Team name");
        Label l19=new Label("Substitue");


        TextField tf13=new TextField();
        TextField tf14=new TextField();
        TextField tf15=new TextField();
        TextField tf12=new TextField();


        Button b124=new Button("Next");
        Button b127=new Button("Previous");
        b124.setStyle("-fx-background-color:Lightblue");
        b127.setStyle("-fx-background-color:Lightblue");


        layout4.add(l16,0,0);
        layout4.add(l150,0,2);
        layout4.add(l18,0,4);
        layout4.add(l19,0,6);


        layout4.add(tf13,0,1);
        layout4.add(tf14,0,3);
        layout4.add(tf15,0,5);
        layout4.add(tf12,0,7);


        layout4.add(b124,6,8);
        layout4.add(b127,5,8);


        l16.setFont(Font.font("Helvetica", 16));
        l16.setTextFill(Color.BLACK);
        l150.setFont(Font.font("Helvetica", 16));
        l150.setTextFill(Color.BLACK);
        l18.setFont(Font.font("Helvetica", 16));
        l18.setTextFill(Color.BLACK);
        l19.setFont(Font.font("Helvetica", 16));
        l19.setTextFill(Color.BLACK);

        //----------------------------------------validation-------------------------//

        Label el9=new Label("required");
        Label el10=new Label("required");
        Label el11=new Label("required");
        Label el12=new Label("required");


        el9.setTextFill(Color.RED);
        el11.setTextFill(Color.RED);
        el12.setTextFill(Color.RED);
        el10.setTextFill(Color.RED);


        el9.setVisible(false);
        el10.setVisible(false);
        el11.setVisible(false);
        el12.setVisible(false);


        tf13.setOnAction(e->validatetf(tf13,el9));
        tf14.setOnAction(e->validatetf(tf14,el10));
        tf15.setOnAction(e->validatetf(tf15,el11));
        tf12.setOnAction(e->validatetf(tf12,el12));


        layout4.add(el9,5,1);
        layout4.add(el10,5,3);
        layout4.add(el11,5,5);
        layout4.add(el12,5,7);


        //--------------------------------------------------------------------------------------------------------------//
        b124.setOnAction(c->{
            int playerNo=Integer.parseInt(tf13.getText());
            String coachName=tf14.getText();
            String teamName=tf15.getText();
            String substitutePlayer=tf12.getText();
            String sponsor=tf13.getText();

            matchDetail.team1 = new Team(playerNo, coachName, teamName, substitutePlayer,sponsor);
            matchDetail.team2 = new Team(11, "Usman", "Gladiators", "Ali", "Toyota");
            manager.setMatchDetails(matchDetail);
            try {
                writeEventManagerToFile(manager);
            } catch (IOException e) {
                throw new RuntimeException(e);
            }
        });

        //------------------------------------------SCENE3A design-----------------------------------------------------//
        Button b40 = new Button("Add Person Info");
        Button b41 = new Button("Find Person");
        Button b42 = new Button("Add Match Details");
        Button b43 = new Button("Add Security Details");
        Button b44 = new Button("Add Umpire Info");
        Button b45 = new Button("Refund Ticket");
        Button b46 = new Button("Ticket Sold Info");
        Button b47 = new Button("Show Match Details");
        Button b48 = new Button("Display Revenue");
        Button b49 = new Button("Display Security Info");
        Button b50 = new Button("Display Umpire Info");
        Button b51 = new Button("Replace Security Guard");
        Button b52 = new Button("Exit");

        b40.setStyle(buttonStyle);
        b41.setStyle(buttonStyle);
        b42.setStyle(buttonStyle);
        b43.setStyle(buttonStyle);
        b44.setStyle(buttonStyle);
        b45.setStyle(buttonStyle);
        b46.setStyle(buttonStyle);
        b47.setStyle(buttonStyle);
        b48.setStyle(buttonStyle);
        b49.setStyle(buttonStyle);
        b50.setStyle(buttonStyle);
        b51.setStyle(buttonStyle);
        b52.setStyle(buttonStyle);

        VBox buttons6 = new VBox();
        buttons6.getChildren().addAll(b40, b41, b42, b43, b44, b45, b46, b47, b48, b49, b50, b51, b52);
        buttons6.setSpacing(2);

        Rectangle left6=new Rectangle(200,550);
        left6.setFill(Color.DARKSLATEGREY);
        left6.setArcHeight(50);
        left6.setArcWidth(50);

        Rectangle center6 =new Rectangle(500, 550);
        center6.setFill(Color.DARKSEAGREEN);
        center6.setArcHeight(50);
        center6.setArcWidth(50);

        Rectangle incenter4=new Rectangle(350,350);//this rectangle is inside the center one
        incenter4.setFill(Color.HONEYDEW);
        incenter4.setArcWidth(50);
        incenter4.setArcHeight(50);

        StackPane sp7=new StackPane(incenter4,layout4);
        sp7.setAlignment(Pos.CENTER);

        StackPane sp8=new StackPane(center6,sp7);
        sp8.setAlignment(Pos.CENTER);

        GridPane menu3 =new GridPane();
        menu3.add(left6, 0,0);
        menu3.add(buttons6, 0, 0);
        menu3.add(sp8, 1, 0);
        menu3.setAlignment(Pos.CENTER);
        menu3.setStyle("-fx-background-color: #1F2D3D ;");
        Scene scene3A=new Scene(menu3);
        //---------------------------------------------SCENE3B--------------------------------------------------------//working
        GridPane layout5=new GridPane();

        Label l20=new Label("Sponsor");
        Label l100=new Label("League");
        Label l101=new Label("Overs");


        TextField tf20=new TextField();
        TextField tf20A=new TextField();
        TextField tf19=new TextField();



        Button b129A=new Button("Previous");
        Button b129B=new Button("Submit");
        b129A.setStyle("-fx-background-color:Lightblue");
        b129B.setStyle("-fx-background-color:Lightblue");

        layout5.add(l20,0,1);
        layout5.add(l100,0,3);
        layout5.add(l101,0,5);

        layout5.add(tf19,0,2);
        layout5.add(tf20,0,4);
        layout5.add(tf20A,0,6);

        layout5.add(b129A,8,15);
        layout5.add(b129B,8,14);

        l20.setFont(Font.font("Helvetica", 16));
        l20.setTextFill(Color.BLACK);
        l100.setFont(Font.font("Helvetica", 16));
        l100.setTextFill(Color.BLACK);
        l101.setFont(Font.font("Helvetica", 16));
        l101.setTextFill(Color.BLACK);
        l20.setFont(Font.font("Helvetica", 16));
        l20.setTextFill(Color.BLACK);

        //----------------------------------------validation-------------------------//
        Label el14=new Label("required");
        Label el15=new Label("required");
        Label el13=new Label("required");

        el14.setTextFill(Color.RED);
        el15.setTextFill(Color.RED);
        el13.setTextFill(Color.RED);

        el14.setVisible(false);
        el15.setVisible(false);
        el13.setVisible(false);

        tf20.setOnAction(e->validatetf(tf20,el14));
        tf20A.setOnAction(e->validatetf(tf20A,el15));
        tf19.setOnAction(e->validatetf(tf19,el13));

        layout5.add(el13,5,2);
        layout5.add(el14,5,4);
        layout5.add(el15,5,6);
        
        layout5.setVgap(10);
        layout5.setAlignment(Pos.CENTER);
        //-------------------------------------------------------------------------------------------------------------//
        b129B.setOnAction(d->{

            String league=tf20.getText();
            double overs=Double.parseDouble(tf20A.getText());
            matchDetail.matchtype = new Matchtype(league, overs);

            tf19.clear();
            tf20.clear();
            tf20A.clear();

            el13.setVisible(false);
            el14.setVisible(false);
            el15.setVisible(false);

            tf12.clear();
            tf13.clear();
            tf14.clear();
            tf15.clear();

            el9.setVisible(false);
            el10.setVisible(false);
            el11.setVisible(false);
            el12.setVisible(false);

            tf5.clear();
            tf6.clear();
            tf7.clear();
            tf8.clear();

            el7.setVisible(false);
            el8.setVisible(false);
            el6.setVisible(false);

            manager.matchDetails=matchDetail;
            try {
                writeEventManagerToFile(manager);
            } catch (IOException e) {
                throw new RuntimeException(e);
            }

        });
        //----------------------------------------------SCENE3B DESIGN-------------------------------------------------//working
        Button b53 = new Button("Add Person Info");
        Button b54 = new Button("Find Person");
        Button b55 = new Button("Add Match Details");
        Button b56 = new Button("Add Security Details");
        Button b57 = new Button("Add Umpire Info");
        Button b58 = new Button("Refund Ticket");
        Button b59 = new Button("Ticket Sold Info");
        Button b60 = new Button("Show Match Details");
        Button b61 = new Button("Display Revenue");
        Button b62 = new Button("Display Security Info");
        Button b63 = new Button("Display Umpire Info");
        Button b64 = new Button("Replace Security Guard");
        Button b65 = new Button("Exit");

        b53.setStyle(buttonStyle);
        b54.setStyle(buttonStyle);
        b55.setStyle(buttonStyle);
        b56.setStyle(buttonStyle);
        b57.setStyle(buttonStyle);
        b58.setStyle(buttonStyle);
        b59.setStyle(buttonStyle);
        b60.setStyle(buttonStyle);
        b61.setStyle(buttonStyle);
        b62.setStyle(buttonStyle);
        b63.setStyle(buttonStyle);
        b64.setStyle(buttonStyle);
        b65.setStyle(buttonStyle);

        VBox buttons7 = new VBox();
        buttons7.getChildren().addAll(b53, b54, b55, b56, b57, b58, b59, b60, b61, b62, b63, b64, b65);
        buttons7.setSpacing(2);

        Rectangle left7=new Rectangle(200,550);
        left7.setFill(Color.DARKSLATEGREY);
        left7.setArcWidth(50);
        left7.setArcHeight(50);

        Rectangle center7=new Rectangle(500,550);
        center7.setFill(Color.DARKSEAGREEN);
        center7.setArcHeight(50);
        center7.setArcWidth(50);

        Rectangle incenter7=new Rectangle(350,350);
        incenter7.setFill(Color.HONEYDEW);
        incenter7.setArcWidth(50);
        incenter7.setArcHeight(50);

        StackPane sp15=new StackPane(incenter7,layout5);
        sp15.setAlignment(Pos.CENTER);

        StackPane sp16=new StackPane(center7,sp15);
        sp16.setAlignment(Pos.CENTER);

        GridPane menu7=new GridPane();
        menu7.add(left7,0,0);
        menu7.add(buttons7,0,0);
        menu7.add(sp16,1,0);
        menu7.setAlignment(Pos.CENTER);
        menu7.setStyle("-fx-background-color: #1F2D3D ;");


        Scene scene3B=new Scene(menu7);

        //--------------------------------------------scene4------------------------------------------------------------------//
        GridPane layout6=new GridPane();
        layout6.setHgap(10);
        layout6.setVgap(10);

        Label l102=new Label("Name :");
        Label l103=new Label("Cnic :");
        Label l104=new Label("Badge no :");

        TextField tf20B=new TextField();
        TextField tf20C=new TextField();
        TextField tf20D=new TextField();

        Button bA=new Button("Submit");
        bA.setStyle("-fx-background-color:Lightblue");

        l102.setFont(Font.font("Helvetica", 16));
        l102.setTextFill(Color.BLACK);
        l103.setFont(Font.font("Helvetica", 16));
        l103.setTextFill(Color.BLACK) ;
        l104.setFont(Font.font("Helvetica", 16));
        l104.setTextFill(Color.BLACK);

        layout6.add(l102,0,0);
        layout6.add(l103,0,2);
        layout6.add(l104,0,4);

        layout6.add(tf20B,0,1);
        layout6.add(tf20C,0,3);
        layout6.add(tf20D,0,5);
        layout6.add(bA,5,7);

        //----------------------------------------validation-------------------------//
        Label el16=new Label("required");
        Label el17=new Label("required");
        Label el18=new Label("required");

        el16.setTextFill(Color.RED);
        el17.setTextFill(Color.RED);
        el18.setTextFill(Color.RED);

        el16.setVisible(false);
        el17.setVisible(false);
        el18.setVisible(false);

        tf20B.setOnAction(e->validatetf(tf20B,el16));
        tf20C.setOnAction(e->validatetf(tf20C,el17));
        tf20D.setOnAction(e->validatetf(tf20D,el18));

        elc.setVisible(false);
        layout6.add(el16,5,1);
        layout6.add(el17,5,3);
        layout6.add(el18,5,5);
        layout6.add(elc,0,7);

        layout6.setAlignment(Pos.CENTER);
        //---------------------------------------------------------------------------------------------------------------------//
        bA.setOnAction(g->{
            String  name=tf20B.getText();
            String  cnic=tf20C.getText();
            String  badgeNumber=tf20D.getText();

            if(isValidCNICFormat(cnic) && !cnicRepeated(cnic, manager.securityTeam))
            {
                manager.securityTeam.add(new SecurityOfficers(name,cnic,badgeNumber));
                System.out.println("success");
                elc.setVisible(false);
            }
            else
            {
                elc.setVisible(true);
            }
            tf20B.clear();
            tf20C.clear();
            tf20D.clear();

            el16.setVisible(false);
            el17.setVisible(false);
            el18.setVisible(false);
            try {
                writeEventManagerToFile(manager);
            } catch (IOException e) {
                throw new RuntimeException(e);
            }
        });
        //-------------------------------------------Design--------------------------------------------------------------------//
        Button b66 = new Button("Add Person Info");
        Button b67 = new Button("Find Person");
        Button b68 = new Button("Add Match Details");
        Button b69 = new Button("Add Security Details");
        Button b70 = new Button("Add Umpire Info");
        Button b71 = new Button("Refund Ticket");
        Button b72 = new Button("Ticket Sold Info");
        Button b73 = new Button("Show Match Details");
        Button b74 = new Button("Display Revenue");
        Button b75 = new Button("Display Security Info");
        Button b76 = new Button("Display Umpire Info");
        Button b77 = new Button("Replace Security Guard");
        Button b78 = new Button("Exit");

        b66.setStyle(buttonStyle);
        b67.setStyle(buttonStyle);
        b68.setStyle(buttonStyle);
        b69.setStyle(buttonStyle);
        b70.setStyle(buttonStyle);
        b71.setStyle(buttonStyle);
        b72.setStyle(buttonStyle);
        b73.setStyle(buttonStyle);
        b74.setStyle(buttonStyle);
        b75.setStyle(buttonStyle);
        b76.setStyle(buttonStyle);
        b77.setStyle(buttonStyle);
        b78.setStyle(buttonStyle);

        VBox buttons8 = new VBox();
        buttons8.getChildren().addAll(b66, b67, b68, b69, b70, b71, b72, b73, b74, b75, b76, b77, b78);
        buttons8.setSpacing(2);

        Rectangle left8=new Rectangle(200,550);
        left8.setFill(Color.DARKSLATEGREY);
        left8.setArcWidth(50);
        left8.setArcHeight(50);

        Rectangle center8=new Rectangle(500,550);
        center8.setFill(Color.DARKSEAGREEN);
        center8.setArcHeight(50);
        center8.setArcWidth(50);

        Rectangle incenter6=new Rectangle(350,350);
        incenter6.setFill(Color.HONEYDEW);
        incenter6.setArcWidth(50);
        incenter6.setArcHeight(50);

        StackPane sp13=new StackPane(incenter6,layout6);
        sp13.setAlignment(Pos.CENTER);

        StackPane sp14=new StackPane(center8,sp13);
        sp14.setAlignment(Pos.CENTER);

        GridPane menu6=new GridPane();
        menu6.add(left8,0,0);
        menu6.add(buttons8,0,0);
        menu6.add(sp14,1,0);
        menu6.setAlignment(Pos.CENTER);
        menu6.setStyle("-fx-background-color: #1F2D3D ;");

        Scene scene4=new Scene(menu6);

        //Scene5
        GridPane layout25 = new GridPane();
        layout25.setHgap(30);
        layout25.setVgap(20);

        TextField txf10 = new TextField();
        TextField txf11 = new TextField();

        Text t3 = new Text("Enter Information of Umpire");

        Label lb10 = new Label("Name");
        Label lb11 = new Label("CNIC");
        Label lb12 = new Label("Umpire");

        RadioButton r1 = new RadioButton("ON-field Umpire");
        RadioButton r2 = new RadioButton("Third Umpire");
        r1.setUserData("ON-field Umpire");
        r2.setUserData("Third Umpire");

        Button bt28 = new Button("Submit");

        t3.setFont(Font.font("Arial", FontWeight.BOLD,18));
        lb10.setFont(Font.font("Helvetica", 16));
        lb10.setTextFill(Color.BLACK);
        lb11.setFont(Font.font("Helvetica", 16));
        lb11.setTextFill(Color.BLACK);
        lb12.setFont(Font.font("Helvetica", 16));
        lb12.setTextFill(Color.BLACK);

        layout25.setMargin(lb10,new Insets(20));
        layout25.setMargin(txf10,new Insets(20));
        layout25.setMargin(lb11,new Insets(20));
        layout25.setMargin(txf11,new Insets(20));
        layout25.setMargin(lb12,new Insets(20));


        ToggleGroup tg1 = new ToggleGroup();
        r1.setToggleGroup(tg1);
        r2.setToggleGroup(tg1);

        layout25.setMargin(r1,new Insets(20));
        layout25.setMargin(r2,new Insets(20));


        layout25.add(lb10,0,1);
        layout25.add(lb11,0,2);
        layout25.add(lb12,0,3);

        layout25.add(txf10,1,1);
        layout25.add(txf11,1,2);

        layout25.add(t3,1,0);
        layout25.add(bt28,2,4);

        layout25.add(r1,1,3);
        layout25.add(r2,2,3);

        //----------------------------------------Validation--------------------------------------------//
        Label elA=new Label("required");
        Label elB=new Label("required");
        Label elc3=new Label("Invalid");

        elA.setTextFill(Color.RED);
        elB.setTextFill(Color.RED);
        elc3.setTextFill(Color.RED);

        elA.setVisible(false);
        elB.setVisible(false);
        elc3.setVisible(false);

        txf10.setOnAction(e->validatetf(txf10,elA));
        txf11.setOnAction(e->validatetf(txf11,elB));

        layout25.add(elA,2,1);
        layout25.add(elB,2,2);
        layout25.add(elc3,2,2);
        layout25.setAlignment(Pos.CENTER);
        //------------------------------------BACKEND--------------------------------------------------------------------\\
        ArrayList <Umpire> umpire=new ArrayList<>(Arrays.asList(manager.getUmpire()));
        //-----------------------------------------------------------------------------------------------------------------\\
        bt28.setOnAction(h->{

            String name=txf10.getText();
            String CNIC=txf11.getText();
            Toggle selectedtoggle= tg1.getSelectedToggle();

            if(selectedtoggle!=null)
            {
                String type = selectedtoggle.getUserData().toString();

                if (isValidCNICFormat(CNIC) && !cnicRepeatedUmpire(CNIC, umpire))
                {
                    umpire.add(new Umpire(name, CNIC, type));


                    txf10.clear();
                    txf11.clear();
                    elA.setVisible(false);
                    elB.setVisible(false);
                    elc3.setVisible(false);
                    manager.setUmpire(umpire.toArray(new Umpire[umpire.size()]));
                    try {
                        writeEventManagerToFile(manager);
                    } catch (IOException e) {
                        throw new RuntimeException(e);
                    }
                }
                else
                {
                    elc3.setVisible(true);
                }
            }});
//-------------------------------------------------SCENE 5 DESIGN----------------------------------------------------------//
        Button bt539 = new Button("Add Person Info");
        Button bt540 = new Button("Find Person");
        Button bt541 = new Button("Add Match Details");
        Button bt542 = new Button("Add Security Details");
        Button bt543 = new Button("Add Umpire Info");
        Button bt544 = new Button("Refund Ticket");
        Button bt545 = new Button("Ticket Sold Info");
        Button bt546 = new Button("Show Match Details");
        Button bt547 = new Button("Display Revenue");
        Button bt548 = new Button("Display Security Info");
        Button bt549 = new Button("Display Umpire Info");
        Button bt550= new Button("Replace Security Guard");
        Button bt551= new Button("Exit");

        bt539.setStyle(buttonStyle);
        bt540.setStyle(buttonStyle);
        bt541.setStyle(buttonStyle);
        bt542.setStyle(buttonStyle);
        bt543.setStyle(buttonStyle);
        bt544.setStyle(buttonStyle);
        bt545.setStyle(buttonStyle);
        bt546.setStyle(buttonStyle);
        bt547.setStyle(buttonStyle);
        bt548.setStyle(buttonStyle);
        bt549.setStyle(buttonStyle);
        bt550.setStyle(buttonStyle);
        bt551.setStyle(buttonStyle);

        VBox buttonA=new VBox();
        buttonA.getChildren().addAll(bt539,bt540,bt541,bt542,bt543,bt544,bt545,bt546,bt547,bt548,bt549,bt550,bt551);
        buttonA.setSpacing(2);

        Rectangle rect9=new Rectangle(150,550);
        rect9.setFill(Color.DARKSLATEGREY);
        rect9.setArcHeight(50);
        rect9.setArcWidth(50);

        Rectangle rect10 = new Rectangle(700, 550);
        rect10.setFill(Color.DARKSEAGREEN);
        rect10.setArcHeight(50);
        rect10.setArcWidth(50);

        Rectangle inc5=new Rectangle(600,350);//this rectangle is inside the center one
        inc5.setFill(Color.HONEYDEW);
        inc5.setArcWidth(50);
        inc5.setArcHeight(50);

        StackPane stackPane4=new StackPane(inc5,layout25);
        stackPane4.setAlignment(Pos.CENTER);

        StackPane spA = new StackPane(rect10,stackPane4);
        spA.setAlignment(Pos.CENTER);

        GridPane menuA =new GridPane();
        menuA.add(rect9, 0,0);
        menuA.add(buttonA, 0, 0);
        menuA.add(spA, 1, 0);
        menuA.setAlignment(Pos.CENTER);
        menuA.setStyle("-fx-background-color: #1F2D3D ;");


        Scene scene5 = new Scene(menuA);


        //Refund
        GridPane layout21 = new GridPane();
        layout21.setVgap(5);
        layout21.setHgap(10);

        Label lb1 = new Label("Class");
        lb1.setFont(Font.font("Arial", FontWeight.BOLD,16));
        layout21.add(lb1,0,1);
        layout21.setMargin(lb1,new Insets(20));
        final ComboBox<String> cb1 = new ComboBox<>();
        cb1.setItems(FXCollections.observableArrayList("Regular", "Vip", "Executive"));
        layout21.add(cb1, 1, 1);
        layout21.setMargin(cb1,new Insets(20));
        cb1.setPromptText("Select");

        Label lb2= new Label("ID");
        lb2.setFont(Font.font("Arial", FontWeight.BOLD,16));
        layout21.add(lb2,0,2);
        layout21.setMargin(lb2,new Insets(20));
        TextField txf2 = new TextField();
        layout21.add(txf2, 1, 2); // Add the TextField to the second column and second row (row index adjusted to 2)
        layout21.setMargin(txf2,new Insets(20));


        layout21.setAlignment(Pos.CENTER);
        layout21.setHgap(30);
        layout21.setVgap(20);

        Label refundLabel=new Label();
        refundLabel.setStyle("-fx-font-size: 16");
        Text t1 = new Text("                    Refund Ticket");
        t1.setFont(Font.font("Arial", FontWeight.BOLD,16));
        HBox h1 = new HBox(t1);
        layout21.setMargin(t1,new Insets(20));
        h1.setSpacing(50);
        h1.setAlignment(Pos.TOP_CENTER);
        layout21.getChildren().add(t1);
        Button bt22 = new Button("Enter");
        bt22.setStyle("-fx-background-color:Lightblue");

        HBox hbox = new HBox(bt22);
        hbox.setSpacing(10);
        layout21.add(hbox, 1, 4);
        layout21.add(refundLabel,0,4);

        Button bt19 = new Button("Add Person Info");
        Button bt20 = new Button("Find Person");
        Button bt100 = new Button("Add Match Details");
        Button bt101 = new Button("Add Security Details");
        Button bt102 = new Button("Add Umpire Info");
        Button bt103 = new Button("Refund Ticket");
        Button bt104 = new Button("Ticket Sold Info");
        Button bt105 = new Button("Show Match Details");
        Button bt106 = new Button("Display Revenue");
        Button bt107 = new Button("Display Security Info");
        Button bt108 = new Button("Display Umpire Info");
        Button bt109= new Button("Replace Security Guard");
        Button bt110= new Button("Exit");

        //

        //
        bt19.setStyle(buttonStyle);
        bt20.setStyle(buttonStyle);
        bt100.setStyle(buttonStyle);
        bt101.setStyle(buttonStyle);
        bt102.setStyle(buttonStyle);
        bt103.setStyle(buttonStyle);
        bt104.setStyle(buttonStyle);
        bt105.setStyle(buttonStyle);
        bt106.setStyle(buttonStyle);
        bt107.setStyle(buttonStyle);
        bt108.setStyle(buttonStyle);
        bt109.setStyle(buttonStyle);
        bt110.setStyle(buttonStyle);

        VBox but1=new VBox();
        but1.getChildren().addAll(bt19,bt20,bt100,bt101,bt102,bt103,bt104,bt105,bt106,bt107,bt108,bt109,bt110);
        but1.setSpacing(2);


        Rectangle rect1=new Rectangle(200,550);
        rect1.setFill(Color.DARKSLATEGREY);
        rect1.setArcHeight(50);
        rect1.setArcWidth(50);

        Rectangle rect2=new Rectangle(700, 550);
        rect2.setFill(Color.DARKSEAGREEN);
        rect2.setArcHeight(50);
        rect2.setArcWidth(50);

        Rectangle inc1=new Rectangle(600,350);//this rectangle is inside the center one
        inc1.setFill(Color.HONEYDEW);
        inc1.setArcWidth(50);
        inc1.setArcHeight(50);

        StackPane stackPane=new StackPane(inc1,layout21);
        stackPane.setAlignment(Pos.CENTER);

        StackPane sp = new StackPane(rect2,stackPane);

        GridPane men =new GridPane();
        men.add(rect1, 0,0);
        men.add(but1, 0, 0);
        men.add(sp, 1, 0);
        men.setAlignment(Pos.CENTER);
        men.setStyle("-fx-background-color: #1F2D3D ;");
        Scene s21=new Scene(men);


        bt22.setOnAction(e-> {

            int givenId=Integer.parseInt(txf2.getText());
            String chosenOption= cb1.getValue();
            if(chosenOption.equals("Vip")){
                if(givenId>manager.vip.size()){
                    refundLabel.setText("Id not found");
                    refundLabel.setTextFill(Color.RED);
                }
                else{
                    for(Person person:manager.vip){
                        double refundedAmount=8000.0;
                        manager.setRevenue(manager.getRevenue()-refundedAmount);
                        manager.vip.remove(person);
                        refundLabel.setText("Ticket refunded");
                        refundLabel.setTextFill(Color.GREEN);
                    }
                    try {
                        writeEventManagerToFile(manager);
                    } catch (IOException e3) {
                        throw new RuntimeException(e3);
                    }
                }
            }
            else if(chosenOption.equals("Executive")){
                if(givenId>manager.executive.size()){
                    refundLabel.setText("Id not found");
                    refundLabel.setTextFill(Color.RED);
                }
                else {
                    for (Person person : manager.executive) {
                        double refundedAmount = 12000.0;
                        manager.setRevenue(manager.getRevenue() - refundedAmount);
                        manager.executive.remove(person);
                        refundLabel.setText("Ticket refunded");
                        refundLabel.setTextFill(Color.GREEN);
                    }
                    try {
                        writeEventManagerToFile(manager);
                    } catch (IOException e1) {
                        throw new RuntimeException(e1);
                    }
                }
            }
            else if(chosenOption.equals("Regular")){
                if(givenId>manager.regular.size()){
                    refundLabel.setText("Id not found");
                    refundLabel.setTextFill(Color.RED);
                }
                else{
                    for(Person person:manager.regular){
                        double refundedAmount = 4000.0;
                        manager.setRevenue(manager.getRevenue()-refundedAmount);
                        manager.regular.remove(person);
                        refundLabel.setText("Ticket refunded");
                        refundLabel.setTextFill(Color.GREEN);
                    }
                    try {
                        writeEventManagerToFile(manager);
                    } catch (IOException e2) {
                        throw new RuntimeException(e2);
                    }
                }
            }
        });
        //Refund

        //Ticket Sold Scene
        Rectangle ticketSoldRectangle = new Rectangle(300, 300);
        ticketSoldRectangle.setArcWidth(50);
        ticketSoldRectangle.setArcHeight(50);
        ticketSoldRectangle.setFill(Color.HONEYDEW);

        Label ticketsSoldLabel = new Label("Tickets Sold:-");
        ticketsSoldLabel.setFont(Font.font("Verdana",FontWeight.BOLD,18));


        Label ticketSoldResult=new Label("");
        ticketSoldResult.setFont(Font.font("Verdana",FontWeight.BOLD,18));

        HBox sold=new HBox();
        sold.getChildren().addAll(ticketsSoldLabel, ticketSoldResult);
        sold.setAlignment(Pos.CENTER);

        GridPane ticketSoldGrid = new GridPane();
        ticketSoldGrid.add(ticketSoldRectangle, 0, 0);
        ticketSoldGrid.add(sold, 0, 0);
        ticketsSoldLabel.setPadding(new Insets(30));
        ticketSoldGrid.setAlignment(Pos.CENTER);

        StackPane ticketSoldStack = new StackPane();
        ticketSoldStack.getChildren().add(center);
        ticketSoldStack.getChildren().add(ticketSoldGrid);


        GridPane ticketSoldLayout = new GridPane();
        ticketSoldLayout.add(left, 0, 0);
        ticketSoldLayout.add(buttons, 0, 0);
        ticketSoldLayout.add(ticketSoldStack, 1, 0);
        ticketSoldLayout.setStyle("-fx-background-color: #1F2D3D;");
        ticketSoldLayout.setAlignment(Pos.CENTER);
        ticketSoldLayout.setPadding(new Insets(50));

        ticketSoldResult.setText(Integer.toString(manager.seatsOccupied()));
        Scene ticketSoldScene = new Scene(ticketSoldLayout);

        //ShowMatchDetails
        Rectangle detailsRectangle = new Rectangle(430, 430);
        detailsRectangle.setArcWidth(50);
        detailsRectangle.setArcHeight(50);
        detailsRectangle.setFill(Color.HONEYDEW);

        Rectangle matchDetailsRectangle=new Rectangle(350,180);
        matchDetailsRectangle.setFill(Color.WHITESMOKE);
        matchDetailsRectangle.setStroke(Color.DARKSLATEGREY);
        matchDetailsRectangle.setArcHeight(40);
        matchDetailsRectangle.setArcWidth(40);
        Text matchDetails = new Text("Match Details");
        matchDetails.setFont(new Font(20));

        Label matchStartingTime = new Label("Match Starting Time:- ");
        Label matchStartingTimeResult=new Label();
        HBox startTime=new HBox(matchStartingTime, matchStartingTimeResult);
        startTime.setAlignment(Pos.CENTER);

        Label matchEndingTime = new Label("Match Ending Time:- ");
        Label matchEndingTimeResult=new Label();
        HBox endTime=new HBox(matchEndingTime, matchEndingTimeResult);
        endTime.setAlignment(Pos.CENTER);

        Label matchDate = new Label("Match Date:- ");
        Label matchDateResult=new Label();
        HBox date=new HBox(matchDate, matchDateResult);
        date.setAlignment(Pos.CENTER);

        Label stadiumName = new Label("Stadium Name:- ");
        Label stadiumNameResult=new Label();
        HBox stadium=new HBox(stadiumName, stadiumNameResult);
        stadium.setAlignment(Pos.CENTER);

        Label ticketsSold = new Label("Tickets Sold:- ");
        Label ticketsSoldResult=new Label();
        HBox tickets=new HBox(ticketsSold, ticketsSoldResult);
        tickets.setAlignment(Pos.CENTER);

        VBox matchDetailsBox=new VBox();
        matchDetailsBox.getChildren().addAll(matchDetails, startTime, endTime, date, stadium, tickets);
        matchDetailsBox.setSpacing(10);
        matchDetailsBox.setAlignment(Pos.TOP_CENTER);
//        matchDetailsBox.setPadding(new Insets(100));
        StackPane detailsPane=new StackPane();
        detailsPane.getChildren().add(matchDetailsRectangle);
        detailsPane.getChildren().add(matchDetailsBox);

        Text team1 = new Text("Team 1");
        team1.setFont(new Font(20));

        Label noOfPlayersT1 = new Label("Players:- ");
        Label noOfPlayersT1Result=new Label();
        HBox playersT1=new HBox(noOfPlayersT1, noOfPlayersT1Result);

        Label coachT1 = new Label("Coach:-");
        Label coachT1Result=new Label();
        HBox coach1=new HBox(coachT1, coachT1Result);

        Label clubT1 = new Label("Club:- ");
        Label clubT1Result=new Label();
        HBox club1=new HBox(clubT1, clubT1Result);

        Label substituteT1 = new Label("Substitute:- ");
        Label substituteT1Result=new Label();
        HBox substitute1=new HBox(substituteT1, substituteT1Result);


        Label sponsorT1 = new Label("Sponsor:- ");
        Label sponsorT1Result=new Label();
        HBox sponsor1=new HBox(sponsorT1, sponsorT1Result);

        VBox team1Box=new VBox();
        team1Box.getChildren().addAll(team1, playersT1, coach1, club1, substitute1, sponsor1);
        team1Box.setSpacing(10);

        Text team2 = new Text("Team 2");
        team2.setFont(new Font(20));

        Label noOfPlayersT2 = new Label("Players:- ");
        Label noOfPlayersT2Result=new Label();
        HBox playersT2=new HBox(noOfPlayersT2, noOfPlayersT2Result);

        Label coachT2 = new Label("Coach:-");
        Label coachT2Result=new Label();
        HBox coach2=new HBox(coachT2, coachT2Result);

        Label clubT2 = new Label("Club:- ");
        Label clubT2Result=new Label();
        HBox club2=new HBox(clubT2, clubT2Result);

        Label substituteT2 = new Label("Substitute:- ");
        Label substituteT2Result=new Label();
        HBox substitute2=new HBox(substituteT2, substituteT2Result);


        Label sponsorT2 = new Label("Sponsor:- ");
        Label sponsorT2Result=new Label();
        HBox sponsor2=new HBox(sponsorT2, sponsorT2Result);


        VBox team2Box=new VBox();
        team2Box.getChildren().addAll(team2, playersT2, coach2, club2, substitute2, sponsor2);
        team2Box.setSpacing(10);

        GridPane teams=new GridPane();
        teams.add(team1Box,0,0);
        teams.add(team2Box, 2,0);
        teams.setHgap(70);
        teams.setAlignment(Pos.CENTER);

        Rectangle teamsRectangle=new Rectangle(420, 190);
        teamsRectangle.setFill(Color.WHITESMOKE);
        teamsRectangle.setStroke(Color.DARKSLATEGREY);
        teamsRectangle.setArcWidth(50);
        teamsRectangle.setArcHeight(50);
        StackPane teamsPane=new StackPane();
        teamsPane.getChildren().add(teamsRectangle);
        teamsPane.getChildren().add(teams);


        VBox details = new VBox();
        details.getChildren().addAll(detailsPane, teamsPane);
        teams.setPadding(new Insets(20));
        details.setSpacing(5);

        GridPane matchDetailsPane = new GridPane();
        matchDetailsPane.add(detailsRectangle, 0, 0);
        matchDetailsPane.add(details, 0, 0);
        matchDetailsPane.setAlignment(Pos.CENTER);

        StackPane detailsStack = new StackPane();
        detailsStack.getChildren().add(center1);
        detailsStack.getChildren().add(matchDetailsPane);

        GridPane showDetailsGrid = new GridPane();
        showDetailsGrid.add(left1, 0, 0);
        showDetailsGrid.add(buttons1, 0, 0);
        showDetailsGrid.add(detailsStack, 1, 0);
        showDetailsGrid.setAlignment(Pos.CENTER);
        showDetailsGrid.setStyle("-fx-background-color: #1F2D3D;");


        matchStartingTimeResult.setText(manager.matchDetails.startingTime);
        matchEndingTimeResult.setText(manager.matchDetails.endingTime);
        matchDateResult.setText(manager.matchDetails.date);
        stadiumNameResult.setText(manager.matchDetails.stadiumName);
        ticketsSoldResult.setText(manager.matchDetails.stadiumName);

        noOfPlayersT1Result.setText(Integer.toString(manager.matchDetails.team1.playerNo));
        coachT1Result.setText(manager.matchDetails.team1.coachName);
        clubT1Result.setText(manager.matchDetails.team1.teamName);
        substituteT1Result.setText(manager.matchDetails.team1.substitutePlayer);
        sponsorT1Result.setText(manager.matchDetails.team1.Sponsor);

        noOfPlayersT2Result.setText(Integer.toString(manager.matchDetails.team2.playerNo));
        coachT2Result.setText(manager.matchDetails.team2.coachName);
        clubT2Result.setText(manager.matchDetails.team2.teamName);
        substituteT2Result.setText(manager.matchDetails.team2.substitutePlayer);
        sponsorT2Result.setText(manager.matchDetails.team2.Sponsor);
        Scene showMatchDetailsScene = new Scene(showDetailsGrid);
        //ShowMatchDetails

        //DisplayRevenue
        Rectangle revenueRectangle = new Rectangle(300, 300);
        revenueRectangle.setArcWidth(50);
        revenueRectangle.setArcHeight(50);
        revenueRectangle.setFill(Color.HONEYDEW);

        Label revenueLabel = new Label("Revenue:-");
        Label revenueResult=new Label("");
        revenueResult.setText(Double.toString(manager.getRevenue()));

        HBox revenue=new HBox();
        revenue.getChildren().addAll(revenueLabel, revenueResult);
        revenue.setAlignment(Pos.CENTER);

        revenueResult.setFont(Font.font("Verdana",FontWeight.BOLD,18));
        revenueLabel.setFont(Font.font("Verdana",FontWeight.BOLD,18));
        GridPane revenueGrid = new GridPane();
        revenueGrid.add(revenueRectangle, 0, 0);
        revenueGrid.add(revenue, 0, 0);
        revenueLabel.setPadding(new Insets(30));
        revenueGrid.setAlignment(Pos.CENTER);

        StackPane revenueStack = new StackPane();
        revenueStack.getChildren().add(center2);
        revenueStack.getChildren().add(revenueGrid);


        GridPane revenueLayout = new GridPane();
        revenueLayout.add(left2, 0, 0);
        revenueLayout.add(buttons2, 0, 0);
        revenueLayout.add(revenueStack, 1, 0);
        revenueLayout.setStyle("-fx-background-color: #1F2D3D;");
        revenueLayout.setAlignment(Pos.CENTER);

        Scene revenueScene = new Scene(revenueLayout);

        //DisplayRevenue

        //-------------------------------------------------SCENE6-----------------------------------------------------------------------//DISPLAY SECURITY
        GridPane layoutA=new GridPane();


        Label D=new Label("Enter the Cnic number");

        Button A=new Button("Submit");

        TextField tfA=new TextField();

        Label elc4=new Label("Invalid cnic");
        elc4.setTextFill(Color.RED);
        elc4.setVisible(false);

        layoutA.setHgap(10);
        layoutA.setVgap(10);

        layoutA.add(D,0,0);
        layoutA.add(tfA,0,1);
        layoutA.add(elc4,1,3);
        layoutA.add(A,3,5);

        layoutA.setAlignment(Pos.CENTER);
        //---------------------------------------------------Backend-----------------------------------------------------------//
        A.setOnAction(k->{

            String CNic=tfA.getText();
            //--------------------------------------output on gui------------------------------------------------------//
            for(int i=0;i<manager.securityTeam.size();i++)
            {
                if(CNic.equals(manager.securityTeam.get(i).getCnic()))
                {
                    Label E=new Label("Name :"+manager.securityTeam.get(i).getName()); //name
                    Label B=new Label("Cnic :"+manager.securityTeam.get(i).getCnic()); //cnic
                    Label C=new Label("Badge#:"+manager.securityTeam.get(i).badgeNumber); //badge number

                    layoutA.add(E,0,2);
                    layoutA.add(B,0,3);
                    layoutA.add(C,0,4);

                    tfA.clear();
                    elc4.setVisible(false);
                }
                else
                {
                    elc4.setVisible(true);
                }
            }
             //-------------------------------------------------------------------------------------------------//
        });


//---------------------------------------------------DESIGN SCENE6------------------------------------------------------------------------------------//
        Button b79 = new Button("Add Person Info");
        Button b80 = new Button("Find Person");
        Button b81 = new Button("Add Match Details");
        Button b82 = new Button("Add Security Details");
        Button b83 = new Button("Add Umpire Info");
        Button b84 = new Button("Refund Ticket");
        Button b85 = new Button("Ticket Sold Info");
        Button b86 = new Button("Show Match Details");
        Button b87 = new Button("Display Revenue");
        Button b88 = new Button("Display Security Info");
        Button b89 = new Button("Display Umpire Info");
        Button b90 = new Button("Replace Security Guard");
        Button b91 = new Button("Exit");

        b79.setStyle(buttonStyle);
        b80.setStyle(buttonStyle);
        b81.setStyle(buttonStyle);
        b82.setStyle(buttonStyle);
        b83.setStyle(buttonStyle);
        b84.setStyle(buttonStyle);
        b85.setStyle(buttonStyle);
        b86.setStyle(buttonStyle);
        b87.setStyle(buttonStyle);
        b88.setStyle(buttonStyle);
        b89.setStyle(buttonStyle);
        b90.setStyle(buttonStyle);
        b91.setStyle(buttonStyle);

        VBox buttonsA = new VBox();
        buttonsA.getChildren().addAll(b79, b80, b81, b82, b83, b84, b85, b86, b87, b88, b89, b90, b91);
        buttonsA.setSpacing(2);

        Rectangle leftA=new Rectangle(200,550);
        leftA.setFill(Color.DARKSLATEGREY);
        leftA.setArcHeight(50);
        leftA.setArcWidth(50);

        Rectangle centerA=new Rectangle(500, 550);
        centerA.setFill(Color.DARKSEAGREEN);
        centerA.setArcHeight(50);
        centerA.setArcWidth(50);

        Rectangle incenterA=new Rectangle(350,350);//this rectangle is inside the center one
        incenterA.setFill(Color.HONEYDEW);
        incenterA.setArcWidth(50);
        incenterA.setArcHeight(50);

        StackPane sp19=new StackPane(incenterA,layoutA);
        sp19.setAlignment(Pos.CENTER);

        StackPane sp20=new StackPane(centerA,sp19);
        sp20.setAlignment(Pos.CENTER);

        GridPane menu8 =new GridPane();
        menu8.add(leftA, 0,0);
        menu8.add(buttonsA, 0, 0);
        menu8.add(sp20, 1, 0);
        menu8.setAlignment(Pos.CENTER);
        menu8.setStyle("-fx-background-color: #1F2D3D ;");
        Scene scene6=new Scene(menu8);
        //------------------------------------------------------SCENE7-------------------------------------------------------------//DISPLAY UMPIRE
        GridPane layoutB=new GridPane();


        Label F=new Label("Enter the Cnic number");
        Label elc5=new Label("invalid Cnic");
        Button KK=new Button("Submit");

        TextField tfB=new TextField();

        layoutB.setHgap(10);
        layoutB.setVgap(10);

        elc5.setTextFill(Color.RED);
        elc5.setVisible(false);

        layoutB.add(F,0,0);
        layoutB.add(tfB,0,1);
        layoutB.add(elc5,1,3);
        layoutB.add(KK,3,5);

        layoutB.setAlignment(Pos.CENTER);
        //---------------------------------------------------Backend-----------------------------------------------------------//
        KK.setOnAction(k->{
            String CNic=tfB.getText();
            for(int i=0;i<umpire.size();i++)
            {
                if(CNic.equals(umpire.get(i).getCnic()))
                {
                    Label X=new Label("Name :"+umpire.get(i).getName()); //name
                    Label y=new Label("Cnic :"+umpire.get(i).getCnic()); //cnic
                    Label z=new Label("Badge#:"+umpire.get(i).Type); //type
                    layoutB.add(X,0,2);
                    layoutB.add(y,0,3);
                    layoutB.add(z,0,4);

                    tfB.clear();
                    elc5.setVisible(false);
                }
                else
                {
                    elc5.setVisible(true);
                }
            }

        });

//---------------------------------------------------DESIGN SCENE7------------------------------------------------------------------------------------//
        Button b92 = new Button("Add Person Info");
        Button b93 = new Button("Find Person");
        Button b94 = new Button("Add Match Details");
        Button b95 = new Button("Add Security Details");
        Button b96 = new Button("Add Umpire Info");
        Button b97 = new Button("Refund Ticket");
        Button b98 = new Button("Ticket Sold Info");
        Button b99 = new Button("Show Match Details");
        Button b100 = new Button("Display Revenue");
        Button b101 = new Button("Display Security Info");
        Button b102 = new Button("Display Umpire Info");
        Button b103 = new Button("Replace Security Guard");
        Button b104 = new Button("Exit");

        b92.setStyle(buttonStyle);
        b93.setStyle(buttonStyle);
        b94.setStyle(buttonStyle);
        b95.setStyle(buttonStyle);
        b96.setStyle(buttonStyle);
        b97.setStyle(buttonStyle);
        b98.setStyle(buttonStyle);
        b99.setStyle(buttonStyle);
        b100.setStyle(buttonStyle);
        b101.setStyle(buttonStyle);
        b102.setStyle(buttonStyle);
        b103.setStyle(buttonStyle);
        b104.setStyle(buttonStyle);

        VBox buttonsB = new VBox();
        buttonsB.getChildren().addAll(b92, b93, b94, b95, b96, b97, b98, b99, b100, b101, b102, b103, b104);
        buttonsB.setSpacing(2);

        Rectangle leftB=new Rectangle(200,550);
        leftB.setFill(Color.DARKSLATEGREY);
        leftB.setArcHeight(50);
        leftB.setArcWidth(50);

        Rectangle centerB=new Rectangle(500, 550);
        centerB.setFill(Color.DARKSEAGREEN);
        centerB.setArcHeight(50);
        centerB.setArcWidth(50);

        Rectangle incenterB=new Rectangle(350,350);//this rectangle is inside the center one
        incenterB.setFill(Color.HONEYDEW);
        incenterB.setArcWidth(50);
        incenterB.setArcHeight(50);

        StackPane sp25=new StackPane(incenterB,layoutB);
        sp25.setAlignment(Pos.CENTER);

        StackPane sp26=new StackPane(centerB,sp25);
        sp26.setAlignment(Pos.CENTER);

        GridPane menu9 =new GridPane();
        menu9.add(leftB, 0,0);
        menu9.add(buttonsB, 0, 0);
        menu9.add(sp26, 1, 0);
        menu9.setAlignment(Pos.CENTER);
        menu9.setStyle("-fx-background-color: #1F2D3D ;");
        Scene scene7=new Scene(menu9);

        ///  Replace Security Officer

        GridPane layout23 = new GridPane();

        Label replaceError=new Label();
        replaceError.setStyle("-fx-font-size: 15");

        Label lb6 = new Label("Badge Number");
        lb6.setFont(Font.font("Arial",FontWeight.BOLD,18));
        layout23.add(lb6,0,2);
        layout23.setMargin(lb6,new Insets(20));
        TextField txf6 = new TextField();
        layout23.add(txf6,1,2);
        layout23.setMargin(txf6,new Insets(20));


        Button bt26 = new Button("Enter");
        bt26.setStyle("-fx-background-color:Lightblue");



        HBox hbox2 = new HBox(bt26);
        hbox2.setSpacing(100);
        layout23.add(hbox2, 1,4);
        layout23.add(replaceError,0,5);
        hbox2.setAlignment(Pos.BOTTOM_RIGHT);

        layout23.setAlignment(Pos.CENTER);
        layout23.setHgap(30);
        layout23.setVgap(20);



        Button bt513 = new Button("Add Person Info");
        Button bt514 = new Button("Find Person");
        Button bt515 = new Button("Add Match Details");
        Button bt516 = new Button("Add Security Details");
        Button bt517 = new Button("Add Umpire Info");
        Button bt518 = new Button("Refund Ticket");
        Button bt519 = new Button("Ticket Sold Info");
        Button bt520 = new Button("Show Match Details");
        Button bt521 = new Button("Display Revenue");
        Button bt522 = new Button("Display Security Info");
        Button bt523 = new Button("Display Umpire Info");
        Button bt524= new Button("Replace Security Guard");
        Button bt525= new Button("Exit");

        String buttonStyle2 = "-fx-background-color: DARKSLATEGREY; -fx-text-fill: white; -fx-padding: 10px 20px; -fx-background-radius: 10px;";

        bt513.setStyle(buttonStyle2);

        bt514.setStyle(buttonStyle2);
        bt515.setStyle(buttonStyle2);
        bt516.setStyle(buttonStyle2);
        bt517.setStyle(buttonStyle2);
        bt518.setStyle(buttonStyle2);
        bt519.setStyle(buttonStyle2);
        bt520.setStyle(buttonStyle2);
        bt521.setStyle(buttonStyle2);
        bt522.setStyle(buttonStyle2);
        bt523.setStyle(buttonStyle2);
        bt524.setStyle(buttonStyle2);
        bt525.setStyle(buttonStyle2);


        VBox but3=new VBox();
        but3.getChildren().addAll(bt513,bt514,bt515,bt516,bt517,bt518,bt519,bt520,bt521,bt522,bt523,bt524,bt525);
        but3.setSpacing(2);

        Rectangle rect5=new Rectangle(200,550);
        rect5.setFill(Color.DARKSLATEGREY);
        rect5.setArcHeight(50);
        rect5.setArcWidth(50);

        Rectangle rect6=new Rectangle(700, 550);
        rect6.setFill(Color.DARKSEAGREEN);
        rect6.setArcHeight(50);
        rect6.setArcWidth(50);

        Rectangle inc3=new Rectangle(500,350);//this rectangle is inside the center one
        inc3.setFill(Color.HONEYDEW);
        inc3.setArcWidth(50);
        inc3.setArcHeight(50);

        StackPane stackPane2=new StackPane(inc3,layout23);
        stackPane2.setAlignment(Pos.CENTER);

        StackPane sp9 = new StackPane(rect6,stackPane2);

        GridPane menu4 =new GridPane();
        menu4.add(rect5, 0,0);
        menu4.add(but3, 0, 0);
        menu4.add(sp9, 1, 0);
        menu4.setAlignment(Pos.CENTER);
        menu4.setStyle("-fx-background-color: #1F2D3D ;");



        Scene s23 = new Scene(menu4);

        ///  information after matching the badge Number

        Label errorReplace=new Label();
        errorReplace.setStyle("-fx-font-size: 15");

        GridPane layout24 = new GridPane();
        Label lb7 = new Label("Name");
        layout24.add(lb7,1,1);
        layout24.setMargin(lb7,new Insets(20));
        TextField txf7 = new TextField();
        layout24.add(txf7,2,1);
        layout24.setMargin(txf7,new Insets(20));

        Label lb8 = new Label("CNIC");
        layout24.add(lb8,1,2);
        layout24.setMargin(lb8,new Insets(20));
        TextField txf8 = new TextField();
        layout24.add(txf8,2,2);
        layout24.setMargin(txf8,new Insets(20));

        Label lb9 = new Label("Badge Number");
        layout24.add(lb9,1,3);
        layout24.setMargin(lb9,new Insets(20));
        TextField txf9 = new TextField();
        layout24.add(txf9,2,3);
        layout24.setMargin(txf9,new Insets(20));

        layout24.add(errorReplace,2,4);

        Button bt27 = new Button("Previous");
        bt27.setStyle("-fx-background-color:Lightblue");

        Button bt29 = new Button("Submit");
        bt29.setStyle("-fx-background-color:Lightblue");

        HBox hbox3 = new HBox(bt27,bt29);
        hbox3.setSpacing(20);
        layout24.add(hbox3, 3,5);

        layout24.setAlignment(Pos.CENTER);
        layout24.setHgap(30);
        layout24.setVgap(20);


        Button bt526 = new Button("Add Person Info");
        Button bt527 = new Button("Find Person");
        Button bt528 = new Button("Add Match Details");
        Button bt529 = new Button("Add Security Details");
        Button bt530 = new Button("Add Umpire Info");
        Button bt531 = new Button("Refund Ticket");
        Button bt532 = new Button("Ticket Sold Info");
        Button bt533 = new Button("Show Match Details");
        Button bt534 = new Button("Display Revenue");
        Button bt535 = new Button("Display Security Info");
        Button bt536 = new Button("Display Umpire Info");
        Button bt537= new Button("Replace Security Guard");
        Button bt538= new Button("Exit");

        String buttonStyle3 = "-fx-background-color: DARKSLATEGREY; -fx-text-fill: white; -fx-padding: 10px 20px; -fx-background-radius: 10px;";

        bt526.setStyle(buttonStyle3);
        bt527.setStyle(buttonStyle3);
        bt528.setStyle(buttonStyle3);
        bt529.setStyle(buttonStyle3);
        bt530.setStyle(buttonStyle3);
        bt531.setStyle(buttonStyle3);
        bt532.setStyle(buttonStyle3);
        bt533.setStyle(buttonStyle3);
        bt534.setStyle(buttonStyle3);
        bt535.setStyle(buttonStyle3);
        bt536.setStyle(buttonStyle3);
        bt537.setStyle(buttonStyle3);
        bt538.setStyle(buttonStyle3);

        VBox but4=new VBox();
        but4.getChildren().addAll(bt526,bt527,bt528,bt529,bt530,bt531,bt532,bt533,bt534,bt535,bt536,bt537,bt538);
        but4.setSpacing(2);

        Rectangle rect7=new Rectangle(200,550);
        rect7.setFill(Color.DARKSLATEGREY);
        rect7.setArcHeight(50);
        rect7.setArcWidth(50);

        Rectangle rect8=new Rectangle(700, 550);
        rect8.setFill(Color.DARKSEAGREEN);
        rect8.setArcHeight(50);
        rect8.setArcWidth(50);

        Rectangle inc4=new Rectangle(600,350);//this rectangle is inside the center one
        inc4.setFill(Color.HONEYDEW);
        inc4.setArcWidth(50);
        inc4.setArcHeight(50);

        StackPane stackPane9=new StackPane(inc4,layout24);
        stackPane9.setAlignment(Pos.CENTER);

        StackPane sp10 = new StackPane(rect8,stackPane9);

        GridPane menu5 =new GridPane();
        menu5.add(rect7, 0,0);
        menu5.add(but4, 0, 0);
        menu5.add(sp10, 1, 0);
        menu5.setAlignment(Pos.CENTER);
        menu5.setStyle("-fx-background-color: #1F2D3D ;");


        Scene s24 = new Scene(menu5);
        String name = txf7.getText();
        String cnic = txf8.getText();
        String badgeNumber = txf9.getText();
        SecurityOfficers securityOfficers = new SecurityOfficers(name,cnic,badgeNumber);

        errorReplace.setText ("");
        errorReplace.setTextFill(Color.RED);
        int index=0;
        boolean doIt;
            if (!manager.isValidCNICFormat(cnic) || manager.cnicRepeated(cnic)) {
                doIt = false;
                errorReplace.setText("Cnic repeated or is invalid");
                errorReplace.setTextFill(Color.RED);
            } else if (manager.isBadgeRepeated(badgeNumber)) {
                doIt = false;
                errorReplace.setText("Badge no is repeated");
                errorReplace.setTextFill(Color.RED);
            }
            else{
                doIt=true;
            }

        //Replace

//------------------------------------------------SETTING ON ACTION of scene3------------------------------------------------------------------------//
        b126.setOnAction(e->stage.setScene(scene3A));
        b124.setOnAction(e->stage.setScene(scene3B));
        b127.setOnAction(e->stage.setScene(scene3));
        b129A.setOnAction(e->stage.setScene(scene3A));
        //------------------------------------------------Setting on action Scene1-----------------------------------------------------------------//
        b1.setOnAction(e->stage.setScene(scene1));
        b2.setOnAction(e-> stage.setScene(scene2));
        b3.setOnAction(e-> stage.setScene(scene3));
        b4.setOnAction(e->stage.setScene(scene4));
        b5.setOnAction(e->stage.setScene(scene5));
        b6.setOnAction(e->stage.setScene(s21));
        b7.setOnAction(e->stage.setScene(ticketSoldScene));
        b8.setOnAction(e->stage.setScene(showMatchDetailsScene));
        b9.setOnAction(e->stage.setScene(revenueScene));
        b10.setOnAction(e->stage.setScene(scene6));
        b11.setOnAction(e->stage.setScene(scene7));
        b12.setOnAction(e->stage.setScene(s23));
        b13.setOnAction(event -> Platform.exit());

//------------------------------------------------setting on action scene2-----------------------------------------------------------------//
        b14.setOnAction(e -> stage.setScene(scene1));
        b15.setOnAction(e -> stage.setScene(scene2));
        b16.setOnAction(e -> stage.setScene(scene3));
        b17.setOnAction(e -> stage.setScene(scene4));
        b18.setOnAction(e->stage.setScene(scene5));
        b19.setOnAction(e->stage.setScene(s21));
        b20.setOnAction(e->stage.setScene(ticketSoldScene));
        b21.setOnAction(e->stage.setScene(showMatchDetailsScene));
        b22.setOnAction(e->stage.setScene(revenueScene));
        b23.setOnAction(e->stage.setScene(scene6));
        b24.setOnAction(e->stage.setScene(scene7));
        b25.setOnAction(e->stage.setScene(s23));
        b26.setOnAction(event -> Platform.exit());
        //-----------------------------------------setting on action scene3------------------------------------------------------------------//
        b27.setOnAction(e -> stage.setScene(scene1));
        b28.setOnAction(e -> stage.setScene(scene2));
        b29.setOnAction(e -> stage.setScene(scene3));
        b30.setOnAction(e -> stage.setScene(scene4));
        b31.setOnAction(e->stage.setScene(scene5));
        b32.setOnAction(e->stage.setScene(s21));
        b33.setOnAction(e->stage.setScene(ticketSoldScene));
        b34.setOnAction(e->stage.setScene(showMatchDetailsScene));
        b35.setOnAction(e->stage.setScene(revenueScene));
        b36.setOnAction(e->stage.setScene(scene6));
        b37.setOnAction(e->stage.setScene(scene7));
        b38.setOnAction(e->stage.setScene(s23));
        b39.setOnAction(event -> Platform.exit());
//-------------------------------------------------setting on action scene3A-----------------------------------------------------------------//
        b40.setOnAction(e -> stage.setScene(scene1));
        b41.setOnAction(e -> stage.setScene(scene2));
        b42.setOnAction(e -> stage.setScene(scene3));
        b43.setOnAction(e -> stage.setScene(scene4));
        b44.setOnAction(e->stage.setScene(scene5));
        b45.setOnAction(e->stage.setScene(s21));
        b46.setOnAction(e->stage.setScene(ticketSoldScene));
        b47.setOnAction(e->stage.setScene(showMatchDetailsScene));
        b48.setOnAction(e->stage.setScene(revenueScene));
        b49.setOnAction(e->stage.setScene(scene6));
        b50.setOnAction(e->stage.setScene(scene7));
        b51.setOnAction(e->stage.setScene(s23));
        b52.setOnAction(event -> Platform.exit());
//-------------------------------------------------setting on action scene3B-----------------------------------------------------------------//
        b53.setOnAction(e -> stage.setScene(scene1));
        b54.setOnAction(e -> stage.setScene(scene2));
        b55.setOnAction(e -> stage.setScene(scene3));
        b56.setOnAction(e -> stage.setScene(scene4));
        b57.setOnAction(e->stage.setScene(scene5));
        b58.setOnAction(e->stage.setScene(s21));
        b59.setOnAction(e->stage.setScene(ticketSoldScene));
        b60.setOnAction(e->stage.setScene(showMatchDetailsScene));
        b61.setOnAction(e->stage.setScene(revenueScene));
        b62.setOnAction(e->stage.setScene(scene6));
        b63.setOnAction(e->stage.setScene(scene7));
        b64.setOnAction(e->stage.setScene(s23));
        b65.setOnAction(event -> Platform.exit());
//--------------------------------------------------setting on action scene4-------------------------------------------------------------------//
        b66.setOnAction(e -> stage.setScene(scene1));
        b67.setOnAction(e -> stage.setScene(scene2));
        b68.setOnAction(e -> stage.setScene(scene3));
        b69.setOnAction(e -> stage.setScene(scene4));
        b70.setOnAction(e->stage.setScene(scene5));
        b71.setOnAction(e->stage.setScene(s21));
        b72.setOnAction(e->stage.setScene(ticketSoldScene));
        b73.setOnAction(e->stage.setScene(showMatchDetailsScene));
        b74.setOnAction(e->stage.setScene(revenueScene));
        b75.setOnAction(e->stage.setScene(scene6));
        b76.setOnAction(e->stage.setScene(scene7));
        b77.setOnAction(e->stage.setScene(s23));
        b78.setOnAction(event -> Platform.exit());

//--------------------------------------------------setting on action scene5-------------------------------------------------------------------//
        bt539.setOnAction(e->stage.setScene(scene1));
        bt540.setOnAction(e->stage.setScene(scene2));
        bt541.setOnAction(e->stage.setScene(scene3));
        bt542.setOnAction(e->stage.setScene(scene4));
        bt543.setOnAction(e->stage.setScene(scene5));
        bt544.setOnAction(e->stage.setScene(s21));
        bt545.setOnAction(e->stage.setScene(ticketSoldScene));
        bt546.setOnAction(e->stage.setScene(showMatchDetailsScene));
        bt547.setOnAction(e->stage.setScene(revenueScene));
        bt548.setOnAction(e->stage.setScene(scene6));
        bt549.setOnAction(e->stage.setScene(scene7));
        bt550.setOnAction(e->stage.setScene(s23));
        bt551.setOnAction(event -> Platform.exit());
//--------------------------------------------------setting on action scene6-------------------------------------------------------------------//
        b79.setOnAction(e->stage.setScene(scene1));
        b80.setOnAction(e->stage.setScene(scene2));
        b81.setOnAction(e->stage.setScene(scene3));
        b82.setOnAction(e->stage.setScene(scene4));
        b83.setOnAction(e->stage.setScene(scene5));
        b84.setOnAction(e->stage.setScene(s21));
        b85.setOnAction(e->stage.setScene(ticketSoldScene));
        b86.setOnAction(e->stage.setScene(showMatchDetailsScene));
        b87.setOnAction(e->stage.setScene(revenueScene));
        b88.setOnAction(e->stage.setScene(scene6));
        b89.setOnAction(e->stage.setScene(scene7));
        b90.setOnAction(e->stage.setScene(s23));
        b91.setOnAction(event -> Platform.exit());
//--------------------------------------------------setting on action scene7-------------------------------------------------------------------//
        b92.setOnAction(e->stage.setScene(scene1));
        b93.setOnAction(e->stage.setScene(scene2));
        b94.setOnAction(e->stage.setScene(scene3));
        b95.setOnAction(e->stage.setScene(scene4));
        b96.setOnAction(e->stage.setScene(scene5));
        b97.setOnAction(e->stage.setScene(s21));
        b98.setOnAction(e->stage.setScene(ticketSoldScene));
        b99.setOnAction(e->stage.setScene(showMatchDetailsScene));
        b100.setOnAction(e->stage.setScene(revenueScene));
        b101.setOnAction(e->stage.setScene(scene6));
        b102.setOnAction(e->stage.setScene(scene7));
        b103.setOnAction(e->stage.setScene(s23));
        b104.setOnAction(event -> Platform.exit());
        //Moazzam



        //SetOnAction
        signinButton.setOnAction(e -> {
            if (userNameField.getText().isEmpty()) {
                loginErrorMessage.setText("User name field is empty");
            } else if (passwordField.getText().isEmpty()) {
                loginErrorMessage.setText("Password field is empty");
            } else {
                loginErrorMessage.setText("");
                String userName="Admin";
                String pass="admin123";
                if(userNameField.getText().equals(userName)&&passwordField.getText().equals(pass)){
                    stage.setScene(scene0);
                }
                else {
                    loginErrorMessage.setText("password and username doesn't match!");
                }
            }
        });
        ticketSoldInfoButton.setOnAction(e->{
            stage.setScene(ticketSoldScene);
        });
        ticketSoldInfoButton1.setOnAction(e->{
            stage.setScene(ticketSoldScene);
        });
        ticketSoldInfoButton2.setOnAction(e->{
            stage.setScene(ticketSoldScene);
        });
        ticketSoldInfoButton3.setOnAction(e->{
            stage.setScene(ticketSoldScene);
        });

        showMatchDetailsButton.setOnAction(e-> stage.setScene(showMatchDetailsScene));
        showMatchDetailsButton1.setOnAction(e->stage.setScene(showMatchDetailsScene));
        showMatchDetailsButton2.setOnAction(e->{
            stage.setScene(showMatchDetailsScene);
        });
        showMatchDetailsButton3.setOnAction(e->{
            stage.setScene(showMatchDetailsScene);
        });

        displaySecurityInfoButton.setOnAction(e->stage.setScene(scene6));
        displaySecurityInfoButton1.setOnAction(e->stage.setScene(scene6));
        displaySecurityInfoButton2.setOnAction(e->stage.setScene(scene6));
        displaySecurityInfoButton3.setOnAction(e->stage.setScene(scene6));

        displayUmpireInfoButton.setOnAction(e->stage.setScene(scene7));
        displayUmpireInfoButton1.setOnAction(e->stage.setScene(scene7));
        displayUmpireInfoButton2.setOnAction(e->stage.setScene(scene7));
        displayUmpireInfoButton3.setOnAction(e->stage.setScene(scene7));

        addUmpireInfoButton.setOnAction(e->stage.setScene(scene5));
        addUmpireInfoButton1.setOnAction(e->stage.setScene(scene5));
        addUmpireInfoButton2.setOnAction(e->stage.setScene(scene5));
        addUmpireInfoButton3.setOnAction(e->stage.setScene(scene5));


        displayRevenueButton.setOnAction(e->{
            stage.setScene(revenueScene);
        });
        displayRevenueButton1.setOnAction(e->{
            stage.setScene(revenueScene);
        });
        displayRevenueButton2.setOnAction(e->{
            stage.setScene(revenueScene);
        });
        displayRevenueButton3.setOnAction(e->{
            stage.setScene(revenueScene);
        });

        addPersonButton.setOnAction(e->stage.setScene(scene1));
        addPersonButton1.setOnAction(e->stage.setScene(scene1));
        addPersonButton2.setOnAction(e->stage.setScene(scene1));
        addPersonButton3.setOnAction(e->stage.setScene(scene1));

        findPersonButton.setOnAction(e->stage.setScene(scene2));
        findPersonButton1.setOnAction(e->stage.setScene(scene2));
        findPersonButton2.setOnAction(e->stage.setScene(scene2));
        findPersonButton3.setOnAction(e->stage.setScene(scene2));


        addMatchDetailsButton.setOnAction(e-> stage.setScene(scene3));
        addMatchDetailsButton1.setOnAction(e-> stage.setScene(scene3));
        addMatchDetailsButton2.setOnAction(e-> stage.setScene(scene3));
        addMatchDetailsButton3.setOnAction(e-> stage.setScene(scene3));


        addSecurityDetailsButton.setOnAction(e-> stage.setScene(scene4));
        addSecurityDetailsButton1.setOnAction(e-> stage.setScene(scene4));
        addSecurityDetailsButton2.setOnAction(e-> stage.setScene(scene4));
        addSecurityDetailsButton3.setOnAction(e-> stage.setScene(scene4));


        replaceSecurityGuardButton.setOnAction(e->{
                stage.setScene(s23);
        });
        replaceSecurityGuardButton1.setOnAction(e->{
                stage.setScene(s23);
        });
        replaceSecurityGuardButton2.setOnAction(e->{
                stage.setScene(s23);
        });
        replaceSecurityGuardButton3.setOnAction(e->{
            stage.setScene(s23);
        });

        refundTicketButton.setOnAction(e->{
            stage.setScene(s21);
        });

        refundTicketButton1.setOnAction(e->{
            stage.setScene(s21);
        });

        refundTicketButton2.setOnAction(e->{
            stage.setScene(s21);
        });
        refundTicketButton3.setOnAction(e->{
            stage.setScene(s21);
        });

        exitButton.setOnAction(event -> Platform.exit());
        exitButton1.setOnAction(event -> Platform.exit());
        exitButton2.setOnAction(event -> Platform.exit());
        exitButton3.setOnAction(event -> Platform.exit());

        //

        //3rd

        bt19.setOnAction(e->stage.setScene(scene1));
        bt20.setOnAction(e->stage.setScene(scene2));
        bt100.setOnAction(e->stage.setScene(scene3));
        bt101.setOnAction(e->stage.setScene(scene4));
        bt102.setOnAction(e->stage.setScene(scene5));
        bt103.setOnAction(e->stage.setScene(s21));
        bt104.setOnAction(e->stage.setScene(ticketSoldScene));
        bt105.setOnAction(e->stage.setScene(showMatchDetailsScene));
        bt106.setOnAction(e->stage.setScene(revenueScene));
        bt107.setOnAction(e->stage.setScene(scene6));
        bt108.setOnAction(e->stage.setScene(scene7));
        bt109.setOnAction(e->stage.setScene(s23));
        bt110.setOnAction(event -> Platform.exit());



        bt26.setOnAction(e->
        {
            if(manager.isBadgeRepeated(txf6.getText())){
                stage.setScene(s24);
            }
            else {
                replaceError.setText("Not Found");
                replaceError.setTextFill(Color.RED);
            }
        });

        bt513.setOnAction(e->stage.setScene(scene1));
        bt514.setOnAction(e->stage.setScene(scene2));
        bt515.setOnAction(e->stage.setScene(scene3));
        bt516.setOnAction(e->stage.setScene(scene4));
        bt517.setOnAction(e->stage.setScene(scene5));
        bt518.setOnAction(e->stage.setScene(s21));
        bt519.setOnAction(e->stage.setScene(ticketSoldScene));
        bt520.setOnAction(e->stage.setScene(showMatchDetailsScene));
        bt521.setOnAction(e->stage.setScene(revenueScene));
        bt522.setOnAction(e->stage.setScene(scene6));
        bt523.setOnAction(e->stage.setScene(scene7));
        bt524.setOnAction(e->stage.setScene(s23));
        bt525.setOnAction(event -> Platform.exit());



        bt29.setOnAction(e->{
            if(doIt){
                errorReplace.setText("");
                manager.securityTeam.set(index, new SecurityOfficers(name,cnic,badgeNumber));
                try {
                    writeEventManagerToFile(manager);
                } catch (IOException e5) {
                    throw new RuntimeException(e5);
                }
            }
        });
        bt526.setOnAction(e->stage.setScene(scene1));
        bt527.setOnAction(e->stage.setScene(scene2));
        bt528.setOnAction(e->stage.setScene(scene3));
        bt529.setOnAction(e->stage.setScene(scene4));
        bt530.setOnAction(e->stage.setScene(scene5));
        bt531.setOnAction(e->stage.setScene(s21));
        bt532.setOnAction(e->stage.setScene(ticketSoldScene));
        bt533.setOnAction(e->stage.setScene(showMatchDetailsScene));
        bt534.setOnAction(e->stage.setScene(revenueScene));
        bt535.setOnAction(e->stage.setScene(scene6));
        bt536.setOnAction(e->stage.setScene(scene7));
        bt537.setOnAction(e->stage.setScene(s23));
        bt538.setOnAction(event -> Platform.exit());

        //3rd



        stage.getIcons().add(leftImage);
        stage.setTitle("MMA");
        stage.setScene(scene1);
        stage.setFullScreen(true);
        stage.setHeight(800);
        stage.setWidth(1200);
        stage.setResizable(false);
        stage.fullScreenProperty().addListener((observable, oldValue, newValue) -> {
            if (newValue) {
                stage.setResizable(false);
            } else {
                stage.setResizable(true);
            }
        });
        stage.show();
    }
    @FXML
    private AnchorPane rootLayout;

    @FXML
    private Label label;

    @FXML
    private TextField textField;

    @FXML
    private Button button;

    @Override
    public void initialize(URL location, ResourceBundle resources) {
        button.setOnAction(e -> {
            label.setText("Hello, " + textField.getText() + "!");
        });
    }
    public boolean validatetf(TextField tf,Label l)//method to validate textfields
    {
        boolean isvalid=true;
        if(tf.getText().isEmpty())
        {
            l.setVisible(true);
            isvalid=false;
        }
        else
        {
            l.setVisible(false);
        }
        return isvalid;
    }
    private boolean isCnicRepeated(String cnic, ArrayList<Person> people) {
        if(people==null){
            return true;
        }
        else {
            for (Person person : people) {
                if (person.getCnic().equals(cnic)) {
                    System.out.println("Cnic is already present for another person");
                    return true;
                }
            }
        }
        return false;
    }

    private boolean cnicRepeated(String cnic, ArrayList<SecurityOfficers> people) {
        if(people.isEmpty()){
            return false;
        }
        else {
            for (Person person : people) {
                if (person.getCnic().equals(cnic)) {
                    System.out.println("Cnic is already present for another person");
                    return true;
                }
            }
        }
        return false;
    }
    private boolean isValidCNICFormat(String cnic) {
        String regex = "^[0-9]{13}$";
        if(!cnic.matches(regex)){
            System.out.println("Invalid CNIC");
        }
        return cnic.matches(regex);
    }
    private boolean cnicRepeatedUmpire(String cnic,ArrayList<Umpire>umpires) {
        for (Umpire umpire : umpires) {
            if (umpire != null && umpire.getCnic().equals(cnic)) {
                System.out.println("CNIC is already present for another Umpire");
                return true;
            }
        }
        return false;
    }

    public void writeEventManagerToFile(EventManager manager) throws IOException {
        File file = new File("D:\\demo\\src\\main\\resources\\manager.ser");
        if (!file.exists()) {
            file.createNewFile();
        }
        else{
            FileWriter fileWriter = new FileWriter(file);
            fileWriter.write("");
            fileWriter.close();
        }
        FileOutputStream fileOutputStream = new FileOutputStream(file);
        ObjectOutputStream objectOutputStream = new ObjectOutputStream(fileOutputStream);
        objectOutputStream.writeObject(manager);

        objectOutputStream.close();
        fileOutputStream.close();
    }
    public EventManager readEventManagerFromFile() throws IOException, ClassNotFoundException {
        File file = new File("D:\\demo\\src\\main\\resources\\manager.ser");
        FileInputStream fileInputStream = new FileInputStream(file);
        Object objRead=null;
        if (!file.exists()) {
            return new EventManager();
        }

        if(file.length()==0){
            return new EventManager();
        }
        else{
            ObjectInputStream objectInputStream = new ObjectInputStream(fileInputStream);
            objRead=objectInputStream.readObject();
            objectInputStream.close();
            fileInputStream.close();
        }

        if(objRead instanceof EventManager ){
            EventManager eventManager = (EventManager) objRead;
            return eventManager;
        }
        return new EventManager();
    }



}
package com.example.demo;

import java.io.Serializable;
import java.util.ArrayList;
import java.util.List;

public class EventManager implements Serializable {
    private static final long serialVersionUID = 1L;
    public MatchDetails matchDetails=new MatchDetails();
    private int ticketsSold;
    public Seat seat=new Seat();
    private double revenue;
    public  ArrayList <Person> vip=new ArrayList<>();
    public  ArrayList <Person> executive=new ArrayList<>();
    public  ArrayList <Person>  regular=new ArrayList<>();
    public  ArrayList<SecurityOfficers> securityTeam =new ArrayList<>();
    public  Umpire[] umpire=new Umpire[3];

    public EventManager(MatchDetails matchDetails) {
        this.matchDetails = matchDetails;
    }

    public EventManager() {
        vip = new ArrayList<>();
        executive = new ArrayList<>();
        regular = new ArrayList<>();
        securityTeam = new ArrayList<>();
    }

    public MatchDetails getMatchDetails() {
        return matchDetails;
    }

    public void setMatchDetails(MatchDetails matchDetails) {
        this.matchDetails = matchDetails;
    }

    public void setTicketsSold(int ticketsSold) {
        this.ticketsSold = ticketsSold;
    }

    public Seat getSeat() {
        return seat;
    }

    public ArrayList<SecurityOfficers> getSecurityTeam() {
        return securityTeam;
    }

    public Umpire[] getUmpire() {
        return umpire;
    }

    public void setUmpire(Umpire[] umpire) {
        this.umpire = umpire;
    }

    private int getTicketsSold() {
        return ticketsSold;
    }

    public void setSeat(Seat seat) {
        this.seat = seat;
    }
    public double getRevenue() {
        return revenue;
    }
    public void setRevenue(double revenue) {this.revenue = revenue;}
                                                    //METHODS//
    public int seatsOccupied()
    {
        return seat.getTotalOccupiedSeats();
    }
    public int seatsAvailable()
    {
        return seat.getTotalAvailableSeats();
    }

    public void matchDetails()
    {
        System.out.println("----MATCH DETAILS----");
        System.out.println("Match Starting time: "+ matchDetails.startingTime+" PM");
        System.out.println("Match Ending time: "+ matchDetails.endingTime+" PM");
        System.out.println("Date on which match will be held: "+ matchDetails.date);
        System.out.println("Stadium Name: "+ matchDetails.stadiumName);
        System.out.println("Tickets Sold: "+getTicketsSold());

        System.out.println("----TEAM 1----");
        System.out.println("The number of player in team : "+ matchDetails.team1.playerNo);
        System.out.println("The coach name is : "+ matchDetails.team1.coachName);
        System.out.println("The name of the Club is : "+ matchDetails.team1.teamName);
        System.out.println("The substitue player is : "+ matchDetails.team1.substitutePlayer);
        System.out.println("The Sponsors of the team "+matchDetails.team1.teamName+" is "+matchDetails.team1.Sponsor);

        System.out.println("----TEAM 2----");
        System.out.println("The number of player in team : "+ matchDetails.team2.playerNo);
        System.out.println("The coach name is : "+ matchDetails.team2.coachName);
        System.out.println("The name of the Club is : "+ matchDetails.team2.teamName);
        System.out.println("The substitue player is : "+ matchDetails.team2.substitutePlayer);
        System.out.println("The Sponsors of the team "+matchDetails.team2.teamName+" is "+matchDetails.team2.Sponsor);
    }

    public void revenue()
    {
        setRevenue(seat.getVipOccupied()*8000+seat.getExecutiveOccupied()*12000+seat.getRegularOccupied()*4000);

        System.out.println("The total revenue generated by selling tickets is : "+getRevenue()+"Pkr");
    }
    public Umpire displayUmpireInformation(String cnic){
        for (Umpire value : umpire) {
            if(value.cnic==null){
                value.setCnic("");
            }
            if(cnic.equals(value.cnic)){
                return value;
            }
        }
        return null;
    }

    public void displaySecurityInfo(){
        for (SecurityOfficers securityOfficers : securityTeam) {
            System.out.println("Name" + securityOfficers.name);
            System.out.println("Cnic" + securityOfficers.getCnic());
            System.out.println("Badge Number" + securityOfficers.badgeNumber);
        }
    }
    public boolean isValidCNICFormat(String cnic) {
        String regex = "^[0-9]{13}$";
        if(!cnic.matches(regex)){
            System.out.println("Invalid CNIC");
        }
        return cnic.matches(regex);
    }

    public boolean isCnicRepeated(String cnic, List<Person> people) {
        for (Person person:people) {
            if(person.getCnic().equals(cnic)){
                System.out.println("Cnic is already present for another person");
                return true;
            }
        }
        return false;
    }
    public boolean cnicRepeated(String cnic) {
        for (Person person: securityTeam) {
            if(person.getCnic().equals(cnic)){
                System.out.println("Cnic is already present for another person");
                return true;
            }
        }
        return false;
    }
   /* private boolean cnicRepeatedUmpire(String cnic, Umpire[] people) {
        for (Person person:people) {
            if(person.getCnic().equals(cnic)){
                System.out.println("Cnic is already present for another Umpire");
                return true;
            }
        }
        return false;
    }*/
   public boolean cnicRepeatedUmpire(String cnic, Umpire[] umpires) {
       for (Umpire umpire : umpires) {
           if (umpire != null && umpire.getCnic().equals(cnic)) {
               System.out.println("CNIC is already present for another Umpire");
               return true;
           }
       }
       return false;
   }
    public boolean isBadgeRepeated(String badgeNo){
        for(SecurityOfficers people: securityTeam){
            if(people.badgeNumber.equals(badgeNo)){
                return true;
            }
        }
        return false;
    }
}
package com.example.demo;

import java.io.Serializable;

public class MatchDetails implements Serializable {  String startingTime;
    String endingTime;
    String stadiumName;
    String date;
    Team team1=new Team();
    Team team2=new Team();
    Matchtype matchtype;

    public MatchDetails(){}

}
package com.example.demo;

import java.io.Serializable;

public class Matchtype implements Serializable
{
    String Leaguename;
    double overs;

    public Matchtype(String leaguename, double overs) {
        Leaguename = leaguename;
        this.overs = overs;
    }
}
package com.example.demo;

import java.io.Serializable;

public class Person implements Serializable
{
    String name;
    public String cnic;
    private String seatclass;


    public Person() {
    }

    public Person(String name, String cnic, String seatclass) {
        this.name = name;
        this.cnic = cnic;
        this.seatclass = seatclass;
    }

    public Person(String name, String cnic) {
        this.name = name;
        this.cnic = cnic;
    }
    public Person(String seatclass, Person p)
    {
        this.seatclass=seatclass;
        this.name=p.name;
        this.cnic=p.cnic;
    }


    public String getName() {
        return name;
    }

    public void setName(String name) {
        this.name = name;
    }

    public String getCnic() {
        return cnic;
    }

    public void setCnic(String cnic) {
        this.cnic = cnic;
    }

    public String getSeatclass() {
        return seatclass;
    }

    public void setSeatclass(String seatclass) {
        this.seatclass = seatclass;
    }
}
package com.example.demo;

import java.io.Serializable;

public class Seat implements Serializable {
    private  int totalOccupiedSeats;
    private  int totalAvailableSeats;
    private  int  vipOccupied;
    private  int vipAvailable;
    private  int executiveOccupied;
    private  int executiveAvailable;
    private  int regularOccupied;
    private  int regularAvailable;
    public Seat() {}

    public int getTotalOccupiedSeats() {
        return totalOccupiedSeats;
    }

    public void setTotalOccupiedSeats(int totalOccupiedSeats) {
        this.totalOccupiedSeats = totalOccupiedSeats;
    }

    public int getTotalAvailableSeats() {
        return totalAvailableSeats;
    }

    public void setTotalAvailableSeats(int totalAvailableSeats) {
        this.totalAvailableSeats = totalAvailableSeats;
    }

    public int getVipOccupied() {
        return vipOccupied;
    }

    public void setVipOccupied(int vipOccupied) {
        this.vipOccupied = vipOccupied;
    }

    public int getVipAvailable() {
        return vipAvailable;
    }

    public void setVipAvailable(int vipAvailable) {
        this.vipAvailable = vipAvailable;
    }

    public int getExecutiveOccupied() {
        return executiveOccupied;
    }

    public void setExecutiveOccupied(int executiveOccupied) {
        this.executiveOccupied = executiveOccupied;
    }

    public int getExecutiveAvailable() {
        return executiveAvailable;
    }

    public void setExecutiveAvailable(int executiveAvailable) {
        this.executiveAvailable = executiveAvailable;
    }

    public int getRegularOccupied() {
        return regularOccupied;
    }

    public void setRegularOccupied(int regularOccupied) {
        this.regularOccupied = regularOccupied;
    }

    public int getRegularAvailable() {
        return regularAvailable;
    }

    public void setRegularAvailable(int regularAvailable) {
        this.regularAvailable = regularAvailable;
    }
}
package com.example.demo;

import java.io.Serializable;

public class SecurityOfficers extends Person implements Serializable {
    String badgeNumber;

    public SecurityOfficers(String name, String cnic, String badgeNumber) {
        super(name, cnic);
        this.badgeNumber = badgeNumber;
    }
}
package com.example.demo;

import java.io.Serializable;

public class Sponsor implements Serializable {
    String Sponsorname;


    public Sponsor(String sponsorname) {
        Sponsorname = sponsorname;
    }
}
package com.example.demo;

import java.io.Serializable;

public class Team implements Serializable {
    int playerNo;
    String coachName;
    String teamName;

    String substitutePlayer;
    String Sponsor;

    public Team() {
    }

    public Team(int playerNo, String coachName, String teamName, String substitutePlayer, String sponsor) {
        this.playerNo = playerNo;
        this.coachName = coachName;
        this.teamName = teamName;
        this.substitutePlayer = substitutePlayer;
        Sponsor = sponsor;
    }
}
package com.example.demo;

import java.io.Serializable;

public class Umpire extends Person implements Serializable {
    String Type;

    public Umpire(String name, String cnic, String type) {
        super(name, cnic);
        Type = type;
    }
}
package com.example.demo;

import javafx.fxml.FXML;
import javafx.scene.control.Label;

public class HelloController {
    @FXML
    private Label welcomeText;

    @FXML
    protected void onHelloButtonClick() {
        welcomeText.setText("Welcome to JavaFX Application!");
    }
}
