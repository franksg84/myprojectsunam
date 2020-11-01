# myprojectsunam
  import 'package:flutter/material.dart';

void main() => runApp(MyApp());

class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
        home: Scaffold(
          body: Column(
            crossAxisAlignment: CrossAxisAlignment.center,
            mainAxisAlignment: MainAxisAlignment.spaceEvenly,
            children: <Widget>[
              Flexible(
                child: Container(color: Colors.black, height: 100, width: 100),
              ),
              Flexible(
                child: Container(color: Colors.grey, height: 200),
              ),
              Flexible(
                child: Container(color: Colors.orange, height: 100,),
              )
            ],
          ),
        ));
  }
}
