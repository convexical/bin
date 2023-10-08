### 1. **User Features:**
* Register
* Submit projects/proposals
* Vote on projects/proposals
* Connect social media accounts for validation
* View and generate a PDF of their donation for tax purposes
* View Ethereum wallet balance after a certain amount

### 2. **Non-Profit/Grantee Features:**
* Submit projects/proposals
* Withdraw funds (if they are not on the platform)
* Upload updates on the usage of the funding
* Connect with users

### 3. **Admin Features:**
* Oversee all projects/proposals
* Manage fund disbursements
* Validate non-profits/grantees
* Handle user queries and concerns

---

### Proposed Pages/Routes:

1. **Homepage** (`/`):
   - Overview of the platform
   - Highlighted projects/proposals
   - Call to action for registration and project submission

2. **Registration and Login**:
   - User Registration (`/register/user`)
   - Non-Profit Registration (`/register/non-profit`)
   - Login (`/login`)

3. **User Dashboard** (`/user/dashboard`):
   - List of submitted projects/proposals
   - Voting history
   - Donation history with PDF generation feature
   - Ethereum wallet balance view (once a certain amount is reached)
   - Connect to social media for validation

4. **Non-Profit Dashboard** (`/non-profit/dashboard`):
   - List of submitted projects/proposals
   - Fund withdrawal options
   - Update upload feature about the usage of funds

5. **Project/Proposal Submission**:
   - User Project Submission (`/user/submit-project`)
   - Non-Profit Project Submission (`/non-profit/submit-project`)

6. **Project/Proposal Viewing and Voting**:
   - View All Projects (`/projects`)
   - Individual Project View (`/projects/:id`)
   - Voting interface integrated within the individual project view

7. **Social Media Validation**:
   - Integration page for social media accounts (`/validate-social-media`)

8. **Admin Dashboard** (`/admin/dashboard`):
   - Overview of all projects/proposals
   - Manage fund disbursements
   - Handle validation of non-profits

9. **Funding and Ethereum Wallet**:
   - Deposit Funds (`/funding/deposit`)
   - View Ethereum Wallet Balance (`/funding/ethereum-wallet`)

10. **Contact and Support**:
   - Contact Form (`/contact`)
   - FAQ (`/faq`)