## IMPORT PACKAGE-
In Flutter, import is a keyword used to include libraries or packages in  Dart code.It allows us to access predefined functions, classes, and features provided by Flutter, third-party packages, or your own code files.

## StatelessWidget -
In Flutter, a StatelessWidget is a widget that does not have any mutable state. This means its appearance and behavior remain the same throughout its lifecycle.

## class AuthController extends GetxController
In Flutter, when using the GetX package for state management, a class like AuthController extending GetxController is used to manage the state and logic related to authentication. Here's an explanation of each component.

## await auth.signInWithCredential(credential);
This is a Firebase Authentication method.
 
## successMessage('Login Success');
This is a custom function (not part of GetX or Firebase) used to display a success notification or message to the user.

## Get.offAll(HomePage());
A GetX navigation method.
Replaces the current navigation stack with the HomePage.

## padding: const EdgeInsets.symmetric(vertical: 40,horizontal: 20),
              color: Theme.of(context).colorScheme.primary,
              child: Row(mainAxisAlignment: MainAxisAlignment.center), 
                
                  children: [Expanded(
                    child: Column(
                      mainAxisAlignment: MainAxisAlignment.center)
                  )
                  ]

-Adds padding equally on both sides for vertical (40) and horizontal (20) directions.
-Dynamically retrieves the primary color defined in the app’s current theme.
-A horizontal layout widget that arranges its children in a row.
-Centers the children horizontally within the available space.
-Ensures the child widget (here, the Column) takes up all available horizontal space in the row.
-Centers the children vertically within the available space of the column.

## Sizedbox(height:20)
This particular SizedBox is used to create vertical space of 20 pixels between widgets in a layout. It's often used in a Column or other vertical layouts to separate items.

## onPressed: () {
          Get.offAll(AddNewBook());}

-The provided function defines what should happen when the button is tapped.
-Navigates to the specified page (AddNewBook() in this case).          



