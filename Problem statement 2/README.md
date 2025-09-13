Ragworks.AI — Next.js E‑commerce Dashboard

Overview

This project is an advanced e‑commerce dashboard built with Next.js, TypeScript, Tailwind CSS, and Chart.js. It demonstrates a full-featured UI with product catalog, cart, checkout flow, analytics, order tracking, and responsive design.

Features
	•	Product catalog with search and category filtering
	•	Shopping cart with add/remove functionality
	•	Checkout flow simulation
	•	Order history with tracking statuses
	•	Analytics (sales trend & category distribution) using Chart.js
	•	Responsive design for desktop, tablet, and mobile
	•	Image grid showing 8 images in parallel (side-by-side)

Tech Stack
	•	Next.js (App Router)
	•	TypeScript
	•	Tailwind CSS
	•	Chart.js with react-chartjs-2

Getting Started
	1.	Clone the repository and install dependencies:

npm install


	2.	Run the development server:

npm run dev


	3.	Open http://localhost:3000 in your browser.
	4.	Navigate to /dashboard (or the page where you integrate the dashboard).

Folder Structure

/app
  /dashboard
    page.tsx       # Main dashboard page
/public
  /images          # Place 8 images here (img1.jpg ... img8.jpg)

Image Grid

The dashboard displays 8 images in parallel. Add your images under public/images/ and update names accordingly.

Example markdown image insertion:

<p>
  <img src="/images/img1.jpg" width="80" height="80" />
  <img src="/images/img2.jpg" width="80" height="80" />
  <img src="/images/img3.jpg" width="80" height="80" />
  <img src="/images/img4.jpg" width="80" height="80" />
  <img src="/images/img5.jpg" width="80" height="80" />
  <img src="/images/img6.jpg" width="80" height="80" />
  <img src="/images/img7.jpg" width="80" height="80" />
  <img src="/images/img8.jpg" width="80" height="80" />
</p>


Documentation

Components
	•	ProductCard: Displays individual product details
	•	Cart: Shows items in the cart and checkout button
	•	Analytics: Line chart and doughnut chart with mock data
	•	OrderHistory: List of past orders with status labels
	•	ImageGrid: Renders 8 static images in a responsive grid

State Management
	•	Uses React useState for local state.
	•	Replace with Redux/Zustand/Context for production scale.

Deployment

Deploy easily on Vercel (official Next.js platform):
	1.	Push your repo to GitHub.
	2.	Import into Vercel.
	3.	Configure environment (if needed).
	4.	Get a live deployed dashboard in minutes.

Evaluation Criteria (if assignment)
	•	Application architecture & state management
	•	User experience & interface design
	•	Performance optimization (loading states, lazy loading)
	•	Data visualization & interactivity
	•	Mobile responsiveness & touch support
	•	Error handling & user feedback

⸻

Built with ❤️ using Next.js, Tailwind CSS, and Chart.js
