# Ex_AsyncTask
Example of AsyncTask.

AsyncTask is a generic class, which allows us to run task on background thread, while publishing results on the UI thread.

It has three primary methods:
	- onPreExecute [main thread]
	- doInBackground [background thread]
	- onProgressUpdate [main/background]
	- onPostExecute [main thread] 
	etc.

AsyncTask is a useful abstraction for threading and messaging between threads in Android.
