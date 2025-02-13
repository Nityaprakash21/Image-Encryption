# Image-Encryption with Java

**Image Operation Tool**
==========================

**Overview**
------------

This Java-based tool allows users to perform a simple XOR operation on an image file. The tool provides a graphical user interface (GUI) for users to select an image file and input a key value. The tool then applies the XOR operation to the image file using the provided key.

**Features**
------------

*   **Image File Selection**: Users can select an image file using a file chooser dialog.
*   **Key Input**: Users can input a key value using a text field.
*   **XOR Operation**: The tool applies the XOR operation to the selected image file using the provided key.
*   **GUI**: The tool provides a simple GUI for users to interact with.

**Requirements**
---------------

*   **Java**: The tool requires Java to be installed on the system.
*   **Java Swing**: The tool uses Java Swing for the GUI, which is included in the Java Development Kit (JDK).

**Usage**
---------

1.  **Clone the Repository**: Clone the repository to your local machine using Git.
2.  **Compile the Code**: Compile the Java code using the `javac` command.
3.  **Run the Tool**: Run the tool using the `java` command.
4.  **Select an Image File**: Select an image file using the file chooser dialog.
5.  **Input a Key Value**: Input a key value using the text field.
6.  **Apply the XOR Operation**: Click the "Open Image" button to apply the XOR operation to the selected image file.

**Code Structure**
-----------------

The code is structured into two main classes:

*   **ImageOperation**: This class contains the main logic for the tool, including the XOR operation and the GUI.
*   **main**: This method is the entry point for the tool, where the GUI is created and the tool is launched.

**GUI Components**
------------------

The GUI consists of the following components:

*   **JFrame**: The main window for the tool.
*   **JButton**: The "Open Image" button that triggers the XOR operation.
*   **JTextField**: The text field for inputting the key value.
*   **JFileChooser**: The file chooser dialog for selecting the image file.

**XOR Operation**
----------------

The XOR operation is performed using the following steps:

1.  **Read the Image File**: The image file is read into a byte array using a `FileInputStream`.
2.  **Apply the XOR Operation**: The XOR operation is applied to each byte in the array using the provided key.
3.  **Write the Result**: The resulting byte array is written back to the image file using a `FileOutputStream`.

**Error Handling**
-----------------

The tool catches any exceptions that occur during the XOR operation and prints the error message to the console.


This tool was created using Java and Java Swing.
