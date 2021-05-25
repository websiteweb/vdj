.. container:: code

    .. code-block:: dart

        class RouteGenerator {
            static Route<dynamic> generateRoute(RouteSettings settings) {
            final args = settings.arguments;
            switch (settings.name) {
                case '/':
                    return MaterialPageRoute(
                        builder: (context) => MainPage(),
                        );
                default:
                    return MaterialPageRoute(
                        builder: (context) => MainPage(),
                        );
        }   

    
