### Doodle Drawing App
For the first part of the assignment, I have designed and implemented a custom doodle prototype for an Android Phone or Tablet. My goal is to have a broad understanding of how to build/programming UIs and general knowledge of common UI programming paradigms/approaches.

So for this, I first require a Canvas to work upon. So, in this app, I created a canvas where the user can draw their drawings. And for that, A custom view is created where the user could simply drag the pen and the cursor to draw the strokes. In order to achieve this, the Drawing View class is created which extends the View class from the standard Android SDK. A brush that acts as a tool is required to help us draw on the canvas and we need different brushes for different colors and different widths of the stroke, we will have a class that represents the distinct brush that draws a unique stroke on the canvas.

Now, at the end when the user is done with the drawing, he might want to clear the canvas and erase everything. So, the delete option is provided for this, which will allow the user to clear the drawings from the canvas.

For the second part,I have added the features like UNDO, REDO, working with the eraser mode and added the stroke cap and stroke Join as the properties of the stroke.
Also added circle colour picker instead of static colour bar at the bottom

How to Run the app
1. Just clone the repo and you can run it from your local machine.
2. Open thr folder in android studio
3. Choose appropriate emulator, for this I have used Pixel 31 API arm64-v8a
4. Install the packages if any issues and let the gradle build
5. Hit the green button for run from the top menu and you are all set to go.


References Used

https://www.geeksforgeeks.org/how-to-create-a-paint-application-in-android/

https://www.youtube.com/watch?v=JsNM6k32aKs

https://www.youtube.com/watch?v=83-j3K4cta8&list=PLW98DQDDUrRhUf167J9K8KmwoK6iUA4Gi

https://www.youtube.com/watch?v=xGrOHLk60q8

https://developer.android.com/develop/ui/views/layout/custom-views/custom-drawing

https://google-developer-training.github.io/android-developer-advanced-course-practicals/unit-5-advanced-graphics-and-views/lesson-11-canvas/11-1a-p-create-a-simple-canvas/11-1a-p-create-a-simple-canvas.html
