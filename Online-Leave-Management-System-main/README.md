

https://github.com/BODDUSRIPAVAN/Online-Leave-Management-System/assets/104664633/700f53f4-ad00-4444-a646-14f42dbc437d

# Online Leave Management System
<h4>Technologies</h4>
<ol>
  <li>Frontend: HTML, CSS, Bootstrap, JavaScript(JQuery)</li>
  <li>Backend: Python Flask server</li>
  <li>Database: MySQL relational database</li>
</ol>
OLMS is an online leave application platform for students with user authentication, student and faculty portals, leave status dashboard.
<h5>Description:</h5>
<ol>
<li>static: this folder conatains all static files such as images.</li>
<li>templates: this folder contains all html files which includes index.html, navigation_bar.html, and footer.html</li>
<li>application.py: this acts as python flask server where frontend and database are connected.</li>
<li>database.sql: this includes relational database management operations</li>
</ol>
<h5>Features:</h5>
<ul>
  <li>User authentication system</li>
  <li>Auto-emailing system</li>
  <li>Dual -level leave approval</li>
  <li>Responsive & user-friendly design</li>
  <li>Student - Faculty - HoD portals</li>
  <li>Status dashboards</li>
</ul>
<h5>Advantages:</h5>
<ul>
  <li>Paperless applications</li>
  <li>Remotely accessible</li>
  <li>Efficient</li>
</ul>
About the author: <a href="https://www.linkedin.com/in/boddu-sri-pavan-19a58b239/">Boddu Sri Pavan</a>
#

install:
pip install -r requirements.txt

# to run backend:
python -m venv venv
venv\Scripts\activate
python application.py


# to run db :
mysql -u root -p

password: mentioned in application.py