<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>RBU Admission Portal</title>

<!-- BOOTSTRAP CSS -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

<style>
body {
    background: #f1f4f9;
    font-family: Arial, sans-serif;
}

.navbar {
    background: #102c50;
}

.navbar-brand {
    font-size: 22px;
    font-weight: bold;
}

.hero {
    background: linear-gradient(120deg, #102c50, #1768a8);
    color: white;
    padding: 55px 15px;
    text-align: center;
}

.hero h1 {
    font-weight: bold;
    font-size: 38px;
}

.section-heading {
    background: #102c50;
    color: white;
    padding: 13px;
    border-radius: 5px;
    margin-top: 30px;
    margin-bottom: 20px;
    font-size: 20px;
}

.form-box {
    background: white;
    padding: 30px;
    border-radius: 10px;
    box-shadow: 0 3px 15px rgba(0,0,0,.08);
    margin-top: 30px;
    margin-bottom: 40px;
}

.form-label {
    font-weight: bold;
}

.form-control, .form-select {
    margin-bottom: 15px;
}

.footer {
    background: #102c50;
    color: white;
    text-align: center;
    padding: 30px;
}

.btn-primary {
    background: #102c50;
    border: none;
}

.btn-primary:hover {
    background: #1768a8;
}

.required {
    color: red;
}

</style>
</head>

<body>

<!-- NAVBAR -->
<nav class="navbar navbar-expand-lg navbar-dark">
<div class="container">

<a class="navbar-brand" href="#">RBU ADMISSION PORTAL</a>

<button class="navbar-toggler" type="button"
data-bs-toggle="collapse" data-bs-target="#menu">
<span class="navbar-toggler-icon"></span>
</button>

<div class="collapse navbar-collapse" id="menu">
<ul class="navbar-nav ms-auto">
<li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
<li class="nav-item"><a class="nav-link" href="#courses">Courses</a></li>
<li class="nav-item"><a class="nav-link" href="#admission">Admission</a></li>
<li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
</ul>
</div>

</div>
</nav>

<!-- HERO -->
<section class="hero" id="home">
<div class="container">
<span class="badge bg-warning text-dark mb-3">ADMISSIONS OPEN 2026-27</span>
<h1>RAMDEOBABA UNIVERSITY</h1>
<h4>Nagpur, Maharashtra</h4>
<p class="mt-3">Online Student Admission Registration Portal</p>
<p>Learn Today | Lead Tomorrow</p>
<a href="#admission" class="btn btn-light btn-lg mt-3">Apply Now</a>
</div>
</section>

<div class="container mt-4">

<!-- ALERT -->
<div class="alert alert-info alert-dismissible fade show">
<strong>Important!</strong> Fill in all details correctly before submitting your application.
<button type="button" class="btn-close" data-bs-dismiss="alert"></button>
</div>

<!-- CARDS -->
<div class="row g-3 text-center">

<div class="col-md-4">
<div class="card shadow-sm">
<div class="card-body">
<h4 class="text-primary">2026-27</h4>
<p>Academic Year</p>
</div>
</div>
</div>

<div class="col-md-4">
<div class="card shadow-sm">
<div class="card-body">
<h4 class="text-primary">UG / PG</h4>
<p>Available Programs</p>
</div>
</div>
</div>

<div class="col-md-4">
<div class="card shadow-sm">
<div class="card-body">
<h4 class="text-primary">Online</h4>
<p>Application Mode</p>
</div>
</div>
</div>

</div>

<!-- FORM START -->
<div class="form-box" id="admission">

<h2 class="text-center">COLLEGE ADMISSION FORM</h2>
<p class="text-center text-muted">Student Registration 2026-27</p>

<hr>

<form action="#" method="post">

<!-- 1 PERSONAL DETAILS -->
<h4 class="section-heading">1. Personal Information</h4>

<div class="row">

<div class="col-md-4">
<label class="form-label">First Name *</label>
<input type="text" class="form-control" placeholder="First Name" required>
</div>

<div class="col-md-4">
<label class="form-label">Middle Name</label>
<input type="text" class="form-control" placeholder="Middle Name">
</div>

<div class="col-md-4">
<label class="form-label">Last Name *</label>
<input type="text" class="form-control" placeholder="Last Name" required>
</div>

<div class="col-md-6">
<label class="form-label">Date of Birth *</label>
<input type="date" class="form-control" required>
</div>

<div class="col-md-6">
<label class="form-label">Gender *</label>
<select class="form-select" required>
<option value="">Select Gender</option>
<option>Male</option>
<option>Female</option>
<option>Other</option>
</select>
</div>

<div class="col-md-6">
<label class="form-label">Nationality</label>
<select class="form-select">
<option>Indian</option>
<option>Other</option>
</select>
</div>

<div class="col-md-6">
<label class="form-label">Blood Group</label>
<select class="form-select">
<option>Select Blood Group</option>
<option>A+</option>
<option>A-</option>
<option>B+</option>
<option>B-</option>
<option>O+</option>
<option>O-</option>
<option>AB+</option>
<option>AB-</option>
</select>
</div>

<div class="col-md-6">
<label class="form-label">Email Address *</label>
<input type="email" class="form-control" placeholder="example@gmail.com" required>
</div>

<div class="col-md-6">
<label class="form-label">Mobile Number *</label>
<input type="tel" class="form-control" placeholder="Mobile Number" required>
</div>

<div class="col-md-6">
<label class="form-label">Alternative Mobile Number</label>
<input type="tel" class="form-control">
</div>

<div class="col-md-6">
<label class="form-label">Aadhaar Number</label>
<input type="text" class="form-control" placeholder="Enter Aadhaar Number">
</div>

</div>

<!-- 2 ADDRESS -->
<h4 class="section-heading">2. Address Details</h4>

<div class="row">

<div class="col-md-12">
<label class="form-label">Permanent Address</label>
<textarea class="form-control" rows="3" placeholder="Enter complete address"></textarea>
</div>

<div class="col-md-4">
<label class="form-label">City</label>
<input type="text" class="form-control">
</div>

<div class="col-md-4">
<label class="form-label">District</label>
<input type="text" class="form-control">
</div>

<div class="col-md-4">
<label class="form-label">State</label>
<select class="form-select">
<option>Select State</option>
<option>Maharashtra</option>
<option>Madhya Pradesh</option>
<option>Gujarat</option>
<option>Rajasthan</option>
<option>Other</option>
</select>
</div>

<div class="col-md-6">
<label class="form-label">PIN Code</label>
<input type="text" class="form-control">
</div>

<div class="col-md-6">
<label class="form-label">Country</label>
<input type="text" class="form-control" value="India">
</div>

</div>

<!-- 3 PARENTS -->
<h4 class="section-heading">3. Parent / Guardian Details</h4>

<div class="row">

<div class="col-md-6">
<label class="form-label">Father's Full Name *</label>
<input type="text" class="form-control" required>
</div>

<div class="col-md-6">
<label class="form-label">Father's Occupation</label>
<input type="text" class="form-control">
</div>

<div class="col-md-6">
<label class="form-label">Father's Mobile Number</label>
<input type="tel" class="form-control">
</div>

<div class="col-md-6">
<label class="form-label">Father's Email</label>
<input type="email" class="form-control">
</div>

<div class="col-md-6">
<label class="form-label">Mother's Full Name *</label>
<input type="text" class="form-control" required>
</div>

<div class="col-md-6">
<label class="form-label">Mother's Occupation</label>
<input type="text" class="form-control">
</div>

<div class="col-md-6">
<label class="form-label">Mother's Mobile Number</label>
<input type="tel" class="form-control">
</div>

<div class="col-md-6">
<label class="form-label">Annual Family Income</label>
<select class="form-select">
<option>Select Income</option>
<option>Below 1 Lakh</option>
<option>1-3 Lakhs</option>
<option>3-5 Lakhs</option>
<option>5-10 Lakhs</option>
<option>Above 10 Lakhs</option>
</select>
</div>

<div class="col-md-6">
<label class="form-label">Guardian Name</label>
<input type="text" class="form-control">
</div>

<div class="col-md-6">
<label class="form-label">Relationship with Guardian</label>
<input type="text" class="form-control">
</div>

</div>

<!-- 4 ACADEMIC DETAILS -->
<h4 class="section-heading">4. Academic Information</h4>

<h5 class="text-primary">10th Standard Details</h5>

<div class="row">

<div class="col-md-6">
<label class="form-label">School Name</label>
<input type="text" class="form-control">
</div>

<div class="col-md-6">
<label class="form-label">Board</label>
<select class="form-select">
<option>Select Board</option>
<option>CBSE</option>
<option>ICSE</option>
<option>Maharashtra State Board</option>
<option>Other</option>
</select>
</div>

<div class="col-md-4">
<label class="form-label">Passing Year</label>
<input type="number" class="form-control">
</div>

<div class="col-md-4">
<label class="form-label">Total Marks</label>
<input type="number" class="form-control">
</div>

<div class="col-md-4">
<label class="form-label">Percentage</label>
<input type="number" step="0.01" class="form-control">
</div>

</div>

<hr>

<h5 class="text-primary">12th Standard Details</h5>

<div class="row">

<div class="col-md-6">
<label class="form-label">Junior College Name</label>
<input type="text" class="form-control">
</div>

<div class="col-md-6">
<label class="form-label">Board</label>
<select class="form-select">
<option>Select Board</option>
<option>Maharashtra State Board</option>
<option>CBSE</option>
<option>Other</option>
</select>
</div>

<div class="col-md-4">
<label class="form-label">Stream</label>
<select class="form-select">
<option>Select Stream</option>
<option>Science</option>
<option>Commerce</option>
<option>Arts</option>
</select>
</div>

<div class="col-md-4">
<label class="form-label">Passing Year</label>
<input type="number" class="form-control">
</div>

<div class="col-md-4">
<label class="form-label">Percentage</label>
<input type="number" step="0.01" class="form-control">
</div>

<div class="col-md-4">
<label class="form-label">Physics Marks</label>
<input type="number" class="form-control">
</div>

<div class="col-md-4">
<label class="form-label">Chemistry Marks</label>
<input type="number" class="form-control">
</div>

<div class="col-md-4">
<label class="form-label">Mathematics / Biology Marks</label>
<input type="number" class="form-control">
</div>

</div>

<!-- 5 ENTRANCE -->
<h4 class="section-heading">5. Entrance Examination Details</h4>

<div class="row">

<div class="col-md-6">
<label class="form-label">Entrance Examination</label>
<select class="form-select">
<option>Select Examination</option>
<option>MHT-CET</option>
<option>JEE Main</option>
<option>NEET</option>
<option>CUET</option>
<option>Other</option>
</select>
</div>

<div class="col-md-6">
<label class="form-label">Examination Year</label>
<input type="number" class="form-control" placeholder="2026">
</div>

<div class="col-md-6">
<label class="form-label">Application Number</label>
<input type="text" class="form-control">
</div>

<div class="col-md-6">
<label class="form-label">Roll Number</label>
<input type="text" class="form-control">
</div>

<div class="col-md-6">
<label class="form-label">Entrance Exam Score</label>
<input type="number" step="0.01" class="form-control">
</div>

<div class="col-md-6">
<label class="form-label">Entrance Exam Percentile</label>
<input type="number" step="0.01" class="form-control">
</div>

<div class="col-md-6">
<label class="form-label">All India Rank</label>
<input type="number" class="form-control">
</div>

<div class="col-md-6">
<label class="form-label">Category Rank</label>
<input type="number" class="form-control">
</div>

</div>

<!-- 6 COURSE -->
<h4 class="section-heading" id="courses">6. Course Selection</h4>

<div class="row">

<div class="col-md-6">
<label class="form-label">Select Degree</label>
<select class="form-select">
<option>Select Degree</option>
<option>B.Tech</option>
<option>BBA</option>
<option>BCA</option>
<option>M.Tech</option>
<option>MBA</option>
<option>MCA</option>
</select>
</div>

<div class="col-md-6">
<label class="form-label">Select Department</label>
<select class="form-select">
<option>Select Department</option>
<option>Computer Science and Engineering</option>
<option>Information Technology</option>
<option>Artificial Intelligence and Machine Learning</option>
<option>Electronics Engineering</option>
<option>Electrical Engineering</option>
<option>Mechanical Engineering</option>
<option>Civil Engineering</option>
<option>Management Studies</option>
</select>
</div>

<div class="col-md-6">
<label class="form-label">Admission Type</label>
<select class="form-select">
<option>Select Admission Type</option>
<option>Regular</option>
<option>Management Quota</option>
<option>Other</option>
</select>
</div>

<div class="col-md-6">
<label class="form-label">Preferred Academic Year</label>
<select class="form-select">
<option>2026-2027</option>
<option>2027-2028</option>
</select>
</div>

<div class="col-md-12">
<label class="form-label">Second Course Preference</label>
<select class="form-select">
<option>Select Second Preference</option>
<option>Computer Science and Engineering</option>
<option>Information Technology</option>
<option>Electronics Engineering</option>
<option>Mechanical Engineering</option>
<option>Artificial Intelligence and Machine Learning</option>
</select>
</div>

</div>

<!-- 7 CATEGORY -->
<h4 class="section-heading">7. Category and Reservation Details</h4>

<div class="row">

<div class="col-md-6">
<label class="form-label">Category</label>
<select class="form-select">
<option>Select Category</option>
<option>OPEN</option>
<option>OBC</option>
<option>SC</option>
<option>ST</option>
<option>VJ/DT</option>
<option>NT</option>
<option>EWS</option>
<option>Other</option>
</select>
</div>

<div class="col-md-6">
<label class="form-label">Caste Certificate Number</label>
<input type="text" class="form-control">
</div>

<div class="col-md-6">
<label class="form-label">Domicile State</label>
<input type="text" class="form-control">
</div>

<div class="col-md-6">
<label class="form-label">Domicile Certificate Number</label>
<input type="text" class="form-control">
</div>

<div class="col-md-6">
<label class="form-label">Are you eligible for EWS?</label>
<select class="form-select">
<option>Select</option>
<option>Yes</option>
<option>No</option>
</select>
</div>

<div class="col-md-6">
<label class="form-label">Scholarship Required?</label>
<select class="form-select">
<option>Select</option>
<option>Yes</option>
<option>No</option>
</select>
</div>

</div>

<!-- 8 HOSTEL -->
<h4 class="section-heading">8. Hostel and Transport Details</h4>

<div class="row">

<div class="col-md-6">
<label class="form-label">Hostel Accommodation</label>
<select class="form-select">
<option>Select Option</option>
<option>Required</option>
<option>Not Required</option>
</select>
</div>

<div class="col-md-6">
<label class="form-label">Hostel Preference</label>
<select class="form-select">
<option>Select Room Type</option>
<option>Single Sharing</option>
<option>Double Sharing</option>
<option>Triple Sharing</option>
</select>
</div>

<div class="col-md-6">
<label class="form-label">College Bus Facility</label>
<select class="form-select">
<option>Select Option</option>
<option>Required</option>
<option>Not Required</option>
</select>
</div>

<div class="col-md-6">
<label class="form-label">Preferred Transport</label>
<select class="form-select">
<option>Select Transport</option>
<option>College Bus</option>
<option>Private Vehicle</option>
<option>Public Transport</option>
<option>Walking</option>
</select>
</div>

</div>

<!-- 9 DOCUMENTS -->
<h4 class="section-heading">9. Document Upload</h4>

<div class="alert alert-warning">
Upload clear copies of the required documents wherever applicable.
</div>

<div class="row">

<div class="col-md-6">
<label class="form-label">Passport Size Photograph</label>
<input type="file" class="form-control" accept="image/*">
</div>

<div class="col-md-6">
<label class="form-label">Student Signature</label>
<input type="file" class="form-control" accept="image/*">
</div>

<div class="col-md-6">
<label class="form-label">10th Marksheet</label>
<input type="file" class="form-control" accept=".pdf,image/*">
</div>

<div class="col-md-6">
<label class="form-label">12th Marksheet</label>
<input type="file" class="form-control" accept=".pdf,image/*">
</div>

<div class="col-md-6">
<label class="form-label">Entrance Exam Scorecard</label>
<input type="file" class="form-control" accept=".pdf,image/*">
</div>

<div class="col-md-6">
<label class="form-label">Aadhaar Card</label>
<input type="file" class="form-control" accept=".pdf,image/*">
</div>

<div class="col-md-6">
<label class="form-label">Caste Certificate (if applicable)</label>
<input type="file" class="form-control" accept=".pdf,image/*">
</div>

<div class="col-md-6">
<label class="form-label">Domicile Certificate (if applicable)</label>
<input type="file" class="form-control" accept=".pdf,image/*">
</div>

</div>

<!-- 10 EXTRA -->
<h4 class="section-heading">10. Additional Information</h4>

<div class="row">

<div class="col-md-6">
<label class="form-label">Hobbies and Interests</label>
<input type="text" class="form-control" placeholder="Reading, Sports, Music etc.">
</div>

<div class="col-md-6">
<label class="form-label">Extracurricular Activities</label>
<input type="text" class="form-control">
</div>

<div class="col-md-12">
<label class="form-label">Why do you want to join Ramdeobaba University?</label>
<textarea class="form-control" rows="4" placeholder="Write your answer here..."></textarea>
</div>

<div class="col-md-12">
<label class="form-label">Any Other Information</label>
<textarea class="form-control" rows="3" placeholder="Enter additional information"></textarea>
</div>

</div>

<!-- DECLARATION -->
<h4 class="section-heading">11. Student Declaration</h4>

<div class="card bg-light p-3 mb-4">

<p>
I hereby declare that all the information provided in this
admission application is true and correct to the best of my
knowledge. I understand that the university may verify the
information and documents submitted by me.
</p>

<div class="form-check">
<input type="checkbox" class="form-check-input" id="agree" required>
<label class="form-check-label" for="agree">
I agree to the declaration and terms and conditions.
</label>
</div>

</div>

<!-- BUTTONS -->
<div class="text-center">

<button type="reset" class="btn btn-secondary btn-lg me-2">
Reset Form
</button>

<button type="submit" class="btn btn-primary btn-lg">
Submit Application
</button>

</div>

</form>
</div>
</div>

<!-- CONTACT -->
<section class="footer" id="contact">
<div class="container">

<h3>RAMDEOBABA UNIVERSITY</h3>

<p>Nagpur, Maharashtra, India</p>

<p>Admissions Office | Student Support</p>

<p>Email: admissions@university.edu.in</p>

<p>© 2026 Ramdeobaba University Admission Portal</p>

</div>
</section>


</body>
</html>
