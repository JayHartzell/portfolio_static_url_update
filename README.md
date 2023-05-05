# alma portfolio url updater
Async python code that can be used to set the ```static_url``` field to the value found in ```static_url_override```in Ex Libris Alma electronic portfolios. Makes a ```GET``` request to pull the portfolio object, then a ```PUT``` request to send it back after modifying the url string.


Requires a spreadsheet containing the Portfolio Id, Collection Id, and Service Id of every portfolio you want to change. You will need to type the full name of the file in the following code cell:

```df = pd.read_excel('your_file_name_here.xlsx', dtype=str) ```


