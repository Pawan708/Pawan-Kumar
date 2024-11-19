1.Form Fields
<label>Full Name</label>
<input type="text" id="name" placeholder="Enter your full name" required />
2.Email Address
<label>Email Address</label>
<input type="email" id="email" placeholder="you@example.com" pattern="^[^\s@]+@[^\s@]+\.[^\s@]+$" required />
<small>Please enter a valid email address</small>
3.Company Size
<label>Company Size</label>
<select id="companySize" required>
  <option value="1-50">1-50 employees</option>
  <option value="51-200">51-200 employees</option>
  <option value="201-1000">201-1000 employees</option>
  <option value="1000+">1000+ employees</option>
</select>
4.Industry
<label>Industry</label>
<div>
  <input type="radio" id="industry-tech" name="industry" value="tech" required />
  <label for="industry-tech">Technology</label>
  
  <input type="radio" id="industry-healthcare" name="industry" value="healthcare" required />
  <label for="industry-healthcare">Healthcare</label>
  
  <input type="radio" id="industry-finance" name="industry" value="finance" required />
  <label for="industry-finance">Finance</label>
  
  <input type="radio" id="industry-retail" name="industry" value="retail" required />
  <label for="industry-retail">Retail</label>
  
  <input type="radio" id="industry-other" name="industry" value="other" required />
  <label for="industry-other">Other</label>
</div>
5.Project Timeline
<label>Project Timeline</label>
<select id="timeline" required>
  <option value="immediate">Immediate (within 1 month)</option>
  <option value="short">Short-term (1-3 months)</option>
  <option value="medium">Medium-term (3-6 months)</option>
  <option value="long">Long-term (6+ months)</option>
</select>
6.Additional Comments
<label>Additional Comments</label>
<textarea id="comments" placeholder="Any other details you'd like to share..."></textarea>
