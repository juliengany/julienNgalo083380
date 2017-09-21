package com.koko.armand.bbit3aproject;

import android.content.Intent;
import android.os.Bundle;
import android.support.design.widget.FloatingActionButton;
import android.support.design.widget.Snackbar;
import android.support.v7.app.AppCompatActivity;
import android.support.v7.widget.Toolbar;
import android.view.View;
import android.view.Menu;
import android.view.MenuItem;
import android.widget.Button;

public class loginPage extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_login_page);

        Button button1 = (Button) findViewById(R.id.btn1);
        button1.setOnClickListener(new View.OnClickListener() {
            public void onClick(View v) {
                Intent log = new Intent(loginPage.this, Home.class);
                startActivity(log);
            }
        });

        Button button2 = (Button) findViewById(R.id.btn2);
        button2.setOnClickListener((new View.OnClickListener(){
            public void onClick(View v){
                Intent sign = new Intent(loginPage.this, SignUp.class);
                startActivity(sign);

                }


        }));

    }}

