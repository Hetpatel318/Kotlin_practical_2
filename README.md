Practical-2: Activity Life Cycle & Basic UI
🎯 AIM & Objective
Create an Android Application to demonstrate Activity Life Cycle functions (onCreate, onStart, onPause, onRestart, etc.) and Basic UI styling.
Observe transitions using Logcat, Toast, and Snackbar.

📷 Output Screenshots
1. Application UI
<img width="433" height="915" alt="image" src="https://github.com/user-attachments/assets/de2f6f3f-9530-4c9d-9f38-0c5d48201b64" />

2. LogCat Output
<img width="1736" height="196" alt="image" src="https://github.com/user-attachments/assets/400c1a6d-dce3-4185-9cd2-f6d8b613e302" />

3. onCreate State
<img width="437" height="936" alt="image" src="https://github.com/user-attachments/assets/fede76d4-f52d-4a1f-a7d8-94448511891f" />

4. onResume State
<img width="466" height="952" alt="image" src="https://github.com/user-attachments/assets/83808de6-e5df-4792-96a2-fa0fe12db406" />

5. onRestart State
<img width="422" height="907" alt="image" src="https://github.com/user-attachments/assets/ec5f9606-5f32-461c-8a25-5350fef983d8" />

💻 Lifecycle Logic (MainActivity.kt)
private fun display(msg: String) {
    Log.i("MainActivity", msg) // Logcat
    Toast.makeText(this, msg, Toast.LENGTH_SHORT).show() // Toast
    Snackbar.make(findViewById(R.id.main), msg, Snackbar.LENGTH_SHORT).show() // Snackbar
}


