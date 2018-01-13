#React Native Questions

1. What makes React Native apps different from hybrid apps built with Cordova and the like?
  - React Native transpiles to Native C (Android) or Swift (iOS) code and has no auxilary purpose.
  - Hybrids like Cordova often use a wrapper to wrap the web app onto the native app.
  - React Native often has better and more optimal performance since the goal is only Native 
    (no webview). 
    - This can be experienced both with loading and also component responsiveness.
    - React Native in itself is a hybrid app since it doesn't actually use Native C or Swift and is
      still built upon React.
  - React Native is known for having better documentation.

2. In what ways is React Native different syntactically from React?
  - Different imports, setup, and installation
  - Different components
  - React Native has... 
     - More in-line styling similar but DIFFERENT than CSS.
     - An animated API for animation.
     - Uses PanResponder instead of touch events.
     - Navigator vs react-router.
     - iOS and Android specific code.
     - Apps published via XCode (iOS) and Android Studio (Android).

3. What are some draw backs of writing a mobile app in React Native versus the other native languages?
  - Limited library interaction.
  - Requires JNI plugin to use C. 
  - Possibility of slower JavaScript code in the phone's VM.

4. What are some of the strengths of writing a mobile app in React Native versus the other native languages?
  - Similar synatx in styling.
  - Similar backend.
  - Rapid prototyping.
  - Can easily apply Redux/Flux/etc for state management.
  - Better documentation. 
  - Easier to back-translate to ReactJS for web apps.