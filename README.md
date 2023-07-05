body: SafeArea(
        child: Container(
            // children: [
            color: Colors.blueAccent,
            child: Row(
              // mainAxisAlignment: MainAxisAlignment.center,
              children: [
                Container(
                  color: Colors.amber,
                  width: 90.0,
                  child: Column(
                    children: <Widget>[
                      Row(
                        children: <Widget>[
                          Expanded(
                            child: Container(
                              color: Colors.indigo,
                              height: 60.0,
                              child: Center(
                                child: Text(
                                  "1st Column",
                                  // textDirection: TextDirection.ltr,
                                  textAlign: TextAlign.center,
                                  style: TextStyle(
                                    decoration: TextDecoration.none,
                                    fontSize: 12.0,
                                    color: Colors.white,
                                  ),
                                ),
                              ),
                            ),
                          ),
                        ],
                      ),
                    ],
                  ),
                ),
                Expanded(
                  child: Column(
                    mainAxisAlignment: MainAxisAlignment.start,
                    crossAxisAlignment: CrossAxisAlignment.start,
                    children: [
                      SingleChildScrollView(
                        scrollDirection: Axis.horizontal,
                        child: Expanded(
                          child: Container(
                            color: Colors.cyan,
                            height: 60.0,
                            child: Row(
                              children: <Widget>[
                                Padding(
                                  padding: const EdgeInsets.all(8.0),
                                  child: Text(
                                    "Flight 1",
                                    textDirection: TextDirection.ltr,
                                    style: TextStyle(
                                      decoration: TextDecoration.none,
                                      fontSize: 20.0,
                                      color: Colors.white,
                                    ),
                                  ),
                                ),
                                Padding(
                                  padding: const EdgeInsets.all(8.0),
                                  child: Text(
                                    "Flight 2",
                                    textDirection: TextDirection.ltr,
                                    style: TextStyle(
                                      decoration: TextDecoration.none,
                                      fontSize: 20.0,
                                      color: Colors.white,
                                    ),
                                  ),
                                ),
                                Padding(
                                  padding: const EdgeInsets.all(8.0),
                                  child: Text(
                                    "Flight 3",
                                    textDirection: TextDirection.ltr,
                                    style: TextStyle(
                                      decoration: TextDecoration.none,
                                      fontSize: 20.0,
                                      color: Colors.white,
                                    ),
                                  ),
                                ),
                                Padding(
                                  padding: const EdgeInsets.all(8.0),
                                  child: Text(
                                    "Flight 4",
                                    textDirection: TextDirection.ltr,
                                    style: TextStyle(
                                      decoration: TextDecoration.none,
                                      fontSize: 20.0,
                                      color: Colors.white,
                                    ),
                                  ),
                                ),
                                Padding(
                                  padding: const EdgeInsets.all(8.0),
                                  child: Text(
                                    "Flight 5",
                                    textDirection: TextDirection.ltr,
                                    style: TextStyle(
                                      decoration: TextDecoration.none,
                                      fontSize: 20.0,
                                      color: Colors.white,
                                    ),
                                  ),
                                ),
                                Padding(
                                  padding: const EdgeInsets.all(8.0),
                                  child: Text(
                                    "Flight 6",
                                    textDirection: TextDirection.ltr,
                                    style: TextStyle(
                                      decoration: TextDecoration.none,
                                      fontSize: 20.0,
                                      color: Colors.white,
                                    ),
                                  ),
                                ),
                                Padding(
                                  padding: const EdgeInsets.all(8.0),
                                  child: Text(
                                    "Flight 7",
                                    textDirection: TextDirection.ltr,
                                    style: TextStyle(
                                      decoration: TextDecoration.none,
                                      fontSize: 20.0,
                                      color: Colors.white,
                                    ),
                                  ),
                                ),
                              ],
                            ),
                          ),
                        ),
                      ),
                      SingleChildScrollView(
                        scrollDirection: Axis.horizontal,
                        child: Expanded(
                          child: Container(
                            color: Colors.red,
                            height: 60.0,
                            child: Row(
                              children: <Widget>[
                                Padding(
                                  padding: const EdgeInsets.all(8.0),
                                  child: Text(
                                    "Flight 1",
                                    textDirection: TextDirection.ltr,
                                    style: TextStyle(
                                      decoration: TextDecoration.none,
                                      fontSize: 20.0,
                                      color: Colors.white,
                                    ),
                                  ),
                                ),
                                Padding(
                                  padding: const EdgeInsets.all(8.0),
                                  child: Text(
                                    "Flight 2",
                                    textDirection: TextDirection.ltr,
                                    style: TextStyle(
                                      decoration: TextDecoration.none,
                                      fontSize: 20.0,
                                      color: Colors.white,
                                    ),
                                  ),
                                ),
                                Padding(
                                  padding: const EdgeInsets.all(8.0),
                                  child: Text(
                                    "Flight 3",
                                    textDirection: TextDirection.ltr,
                                    style: TextStyle(
                                      decoration: TextDecoration.none,
                                      fontSize: 20.0,
                                      color: Colors.white,
                                    ),
                                  ),
                                ),
                                Padding(
                                  padding: const EdgeInsets.all(8.0),
                                  child: Text(
                                    "Flight 4",
                                    textDirection: TextDirection.ltr,
                                    style: TextStyle(
                                      decoration: TextDecoration.none,
                                      fontSize: 20.0,
                                      color: Colors.white,
                                    ),
                                  ),
                                ),
                                Padding(
                                  padding: const EdgeInsets.all(8.0),
                                  child: Text(
                                    "Flight 5",
                                    textDirection: TextDirection.ltr,
                                    style: TextStyle(
                                      decoration: TextDecoration.none,
                                      fontSize: 20.0,
                                      color: Colors.white,
                                    ),
                                  ),
                                ),
                                Padding(
                                  padding: const EdgeInsets.all(8.0),
                                  child: Text(
                                    "Flight 6",
                                    textDirection: TextDirection.ltr,
                                    style: TextStyle(
                                      decoration: TextDecoration.none,
                                      fontSize: 20.0,
                                      color: Colors.white,
                                    ),
                                  ),
                                ),
                                Padding(
                                  padding: const EdgeInsets.all(8.0),
                                  child: Text(
                                    "Flight 7",
                                    textDirection: TextDirection.ltr,
                                    style: TextStyle(
                                      decoration: TextDecoration.none,
                                      fontSize: 20.0,
                                      color: Colors.white,
                                    ),
                                  ),
                                ),
                              ],
                            ),
                          ),
                        ),
                      ),
                    ],
                  ),
                ),
              ],
            )
            // tableContent(),
            // tableHeader(),
            // ],
            ),
      ),
