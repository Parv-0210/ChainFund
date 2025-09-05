# ChainFund - Decentralized Crowdfunding Platform MVP

## Core Features to Implement:
1. **Project Creation & Management**
   - Create new crowdfunding projects with details, funding goals, and milestones
   - Display project cards with progress indicators
   - Project detail pages with milestone tracking

2. **Milestone System**
   - Define project milestones with descriptions and funding percentages
   - Milestone approval/voting mechanism (simulated for MVP)
   - Progress tracking and fund release triggers

3. **Fund Management**
   - Contribution interface for backers
   - Fund escrow simulation (smart contract simulation)
   - Automatic fund release when milestones are achieved

4. **Dashboard & Analytics**
   - Project creator dashboard
   - Backer portfolio view
   - Platform statistics

## Files to Create:
1. `src/pages/Index.tsx` - Main landing page with project listings
2. `src/pages/CreateProject.tsx` - Project creation form
3. `src/pages/ProjectDetail.tsx` - Individual project view with milestones
4. `src/pages/Dashboard.tsx` - User dashboard
5. `src/components/ProjectCard.tsx` - Project display component
6. `src/components/MilestoneTracker.tsx` - Milestone progress component
7. `src/components/FundingProgress.tsx` - Funding progress visualization
8. `src/lib/web3-simulation.ts` - Simulated Web3 smart contract interactions

## Tech Stack:
- React + TypeScript + Vite
- Shadcn/UI components
- Tailwind CSS for styling
- Local storage for data persistence (simulating blockchain state)
- React Router for navigation

## Implementation Notes:
- MVP will simulate smart contract interactions using local storage
- Focus on UI/UX that demonstrates the trustless, milestone-based funding concept
- Include visual indicators for blockchain transactions and milestone achievements
- Implement responsive design for mobile and desktop