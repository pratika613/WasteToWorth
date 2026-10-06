# WasteToWorth

**Turning Waste into Opportunities**

WasteToWorth is an AI/ML-powered B2B circular-economy marketplace designed to connect waste generators with industries that can reuse, recycle, or repurpose their waste materials.

**Live project:** https://wastetoworth.vercel.app/

## Project Objectives

- Connect waste generators and potential industrial buyers through one digital marketplace.
- Help sellers list waste materials and buyers discover suitable materials.
- Support transparent offers and a bidding workflow.
- Use machine learning and similarity-based recommendations to improve material discovery.
- Encourage resource reuse, recycling, and circular-economy practices.

## Key Features

- **Role-based access:** Separate experiences for buyers, sellers, and administrators.
- **Material listings:** Sellers can list waste materials with details such as category, quantity, location, and images.
- **Search and discovery:** Buyers can browse and filter available materials.
- **Bidding system:** Buyers can place bids; sellers can review and compare offers on their listings.
- **AI/ML recommendations:** Machine-learning and similarity methods support material classification and recommendations.
- **Notifications and transaction tracking:** Designed to help users follow inquiries, offers, and transactions.
- **Sustainability insights:** The platform concept includes tracking recycling and environmental contributions.

## Machine Learning Approach

The project uses the following methods:

- **TF-IDF Vectorizer:** Converts text descriptions into numerical features.
- **Calibrated Logistic Regression:** Provides classification predictions with calibrated probability estimates.
- **Random Forest Regressor:** Predicts a relevance or value score, according to the project design.
- **Cosine Similarity Recommender:** Finds items with similar feature representations to support recommendations.

A typical ML workflow includes data collection, text/data cleaning, preprocessing, feature extraction, model training, evaluation, and integration with the application.

## Technology Stack

The project presentation describes the following technologies:

- **Frontend:** React 19, Vite, Tailwind CSS v4, React Router v7
- **Backend:** Node.js, Express.js, and Python for ML-related work
- **Database, cloud, and storage:** Supabase and PostgreSQL
- **Machine learning:** TF-IDF, Calibrated Logistic Regression, Random Forest Regressor, Cosine Similarity
- **Tools:** Git, GitHub, Postman, VS Code, Figma
- **Deployment:** Vercel for the frontend; the presentation also references Render for backend deployment

The exact services enabled in a deployment may differ from this project overview. Check the current code and deployment configuration before setting up a local or production environment.

## How the Platform Works

1. A user signs up and accesses the relevant buyer or seller experience.
2. A seller creates a listing for a waste material.
3. Buyers browse or search for materials they can use.
4. Interested buyers submit bids or offers.
5. Sellers review and compare the bids and select a suitable offer.
6. The parties coordinate the transaction and material handover.

## Future Scope

Potential improvements include:

- Image-based waste classification.
- Demand and price prediction using market trends.
- Automated buyer–seller matching.
- Android and iOS applications.
- Sustainability dashboards for waste diverted and emissions avoided.
- Partnerships with recycling industries, manufacturers, NGOs, and local authorities.
- IoT integrations and improved transaction traceability.

## Getting Started

This README summarizes the project concept and the technology stack described in the presentation. It does **not** assume that every listed service or feature is fully configured in the current deployment.

To run the project locally:

1. Clone or download the project repository.
2. Inspect the repository structure and its `package.json` / Python dependency files.
3. Install the dependencies specified by the project.
4. Configure the required environment variables and Supabase credentials.
5. Start the frontend and backend using the commands documented in their respective folders.
6. Verify the application and ML endpoints locally before testing end-to-end workflows.

The exact commands depend on the current repository files; add them here once the final code structure is confirmed.

## Deployment

The project URL listed in the presentation is:

https://wastetoworth.vercel.app/

Before deployment, verify environment variables, Supabase policies, authentication settings, API URLs, and any backend hosting configuration.

## Disclaimer

WasteToWorth is an academic/project prototype intended to demonstrate a digital circular-economy marketplace and ML-assisted recommendations. Environmental impact figures, business projections, and recommendation quality should be validated with reliable data before being presented as measured real-world outcomes.
