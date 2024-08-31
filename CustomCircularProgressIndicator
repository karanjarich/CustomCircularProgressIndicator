import 'package:flutter/material.dart';

class  CustomCircularProgressIndicator extends StatelessWidget {
  const CustomCircularProgressIndicator({Key? key}) : super(key: key);

  // Add properties for customization (e.g., hint text, border color)

  @override
  Widget build(BuildContext context) {
    return Center(child:Container(
      height: 150,
      width: 150,
      padding: const EdgeInsets.all(8.0),
      child:  TweenAnimationBuilder<double>(
        tween: Tween<double>(begin: 3.0, end: 1),
        duration: const Duration(milliseconds: 3500),
        builder: (context, value, _) => CircularProgressIndicator(value: value),
      ),
    ));
  }
}
