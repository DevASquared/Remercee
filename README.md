# Remercee

Remercee is an innovative web application that allows consumers to leave quick and direct feedback on server performance by scanning a QR code. In addition to this feedback feature, the application also provides advanced tools for recruitment, facilitating the connection between restaurateurs and qualified servers through an optimized matching system.

## Objectives

- Provide consumers with a simple and instant method to evaluate servers.
- Facilitate the connection between restaurateurs and servers through effective matching between job offers and server profiles.

## Key Features

### Frontend (Webapp)

- **User Interface:**
  - Responsive design for smooth use on both mobile and desktop.
  - Intuitive interface for scanning QR codes, allowing consumers to access a dedicated server page with their name, photo, seniority, number of ratings, average rating, and number of employer reviews.
  - Dedicated dashboard for Admins and Restaurateurs (for recruitment and tracking).
  - Multilingual support for global use.

- **QR Code Evaluation:**
  - Scanning QR codes to access a specific evaluation page for each server.
  - Rating system from 1 to 5, without text, for quick feedback.

- **Statistics and Reports:**
  - Visualization of server performance through graphs and tables.
  - Generation of detailed reports for Admins and Restaurateurs.

### Backend (Node.js + Firebase)

- **User Management:**
  - Secure authentication system (Firebase Authentication).
  - Management of roles and permissions for different types of users (Admin, Server, Consumer, Restaurateur).

- **Evaluation Processing:**
  - Secure storage of consumer and restaurateur ratings.
  - Feedback analysis algorithm to provide real-time statistics based on a 1 to 5 scale.

- **Recruitment Module:**
  - Creation and management of job offers for servers.
  - Detailed server profiles with evaluation history and recommendations from restaurateurs.
  - Matching system between servers and job offers based on experience and evaluations.

## User Types

1. **Admin:**
   - Global view of server, consumer, and restaurateur statistics.
   - Moderation of reviews and management of comments.
   - Manual addition of servers and management of access and roles.

2. **Consumer:**
   - Leave quick reviews on servers via QR code scanning.
   - Access server page with details on seniority, ratings, average score, and employer reviews.
   - History of reviews left.

3. **Server:**
   - Access reviews received from consumers and restaurateurs.
   - View personal performance statistics.
   - Ability to respond to restaurateur reviews.

4. **Restaurateur:**
   - Leave reviews on servers with greater weight as an employer.
   - History of reviews left.
   - Access to global statistics of servers under their management.
   - Verification and attestation that the review is provided by a restaurant manager.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/DevASquared/remercee.git
   ```

2. Navigate to the project directory:
   ```bash
   cd remercee
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Configure Firebase and environment variables as indicated in the `.env` file.

5. Start the server:
   ```bash
   npm start
   ```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
