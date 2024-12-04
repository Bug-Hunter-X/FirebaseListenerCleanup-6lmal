# Firebase Unsubscribe Bug

This repository demonstrates a common error in Firebase applications: forgetting to unsubscribe from Realtime Database or Authentication listeners when a component unmounts.  Failure to unsubscribe results in memory leaks, potentially affecting application performance and stability.

The `firebaseUnsub.js` file showcases the problematic code.  `firebaseUnsubSolution.js` provides the corrected version with proper unsubscribe handling.