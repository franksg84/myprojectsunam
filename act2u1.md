# myprojectsunam
  import 'package:flutter/material.dart';

void main() => runApp(MyApp());

class MyApp extends StatelessWidget {
 
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      
      home: Scaffold(
        appBar: AppBar(
      title: const Text('titulo'),
      ),
        body:
          Center(
            child: Text('Francisco Sánchez Guerrero')
          ),
      )
    );
  }
}
