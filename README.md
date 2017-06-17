# Score Keep

Simple web application which allows the user to keep track of scores of any tournament players.
It has been developed using the Meteor platform (www.meteor.com) with the sole purpose of learning and practicing technologies such as JavaScript, MongoDB and React.

**To see it in action, [click here!](https://score-keep-dg.herokuapp.com)**

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

In order to run this software you will need to install the Meteor platform. For this, you will need to download it from the following link:

https://www.meteor.com/install

The installation instructions will be determined by your operating system. Please refer to the aforementioned link for more information.

You can verify that Meteor has been successfully installed by running the following terminal command:

 ```
 meteor --version
 ```

### Running the app

To run the application on your machine, you will need to open a Terminal (OSX/Linux) or a Powershell window (Windows) and head to the directory where you have downloaded and extracted the application (your "score-keep-master" folder).

After that, you will need to install all the necessary dependencies with this command:

```
meteor npm install
```

The complete list of dependencies is listed in the **package.json** file.

Once all the dependencies are installed, you are ready to go. You can run the web application with the following command:

```
meteor --release 1.5
```

Since Score Keep was developed using version 1.5 of Meteor, the --release flag has been explicitly included in the command.

If everything has been done correctly, you will see something like this:

```
=> App running at: http://localhost:3000/
   Type Control-C twice to stop.
```

Type the web address in the web browser of your choice and you will enter the application!

## Author

* **Daniel García** - [GitHub](https://github.com/dandev237)

## License

```
The MIT License (MIT)

Copyright (c) 2017-present Daniel García

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated
documentation files (the "Software"), to deal in the Software without restriction, including without limitation
the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and
to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of
the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO
THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## Acknowledgments

* **Andrew Mead** - [Mead.io](http://www.mead.io/)

  Full-Stack dev & Teacher, creator of the course ["Full-Stack Web Apps with Meteor and React"](https://www.udemy.com/meteor-react/)

