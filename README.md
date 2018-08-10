# Ex_AsyncTask
Example of AsyncTask.

AsyncTask is a generic class.

This class allows us to run task on background thread, while publishing results on the UI thread.

It has three primary methods:
	1)onPreExecute [main thread]
	2)doInBackground [background thread]
	3)onProgressUpdate [main/background]
	4)onPostExecute [main thread] 
	etc.

AsyncTask is a usefule abstraction for threading and messaging between threads in Android.
