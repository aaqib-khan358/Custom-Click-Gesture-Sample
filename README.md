# Custom-Click-Gesture-Sample
The project demonstrates custom click gesture functionality of google ads

It uses test ad unit "/6499/example/native"

Steps to test:
1. Load the app (This would request native ad using test ad unit and enable custom click gesture)
2. Click on "Click AD" button (This will invoke recordCustomClickGesture())

Issues:
1. After invoking recordCustomClickGesture(), the AdListner->onAdClicked() is not called