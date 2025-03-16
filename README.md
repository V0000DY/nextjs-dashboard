# Financial Dashboard

## Project Overview

This project is a financial dashboard developed as part of a Next.js tutorial. I have successfully completed the course and built a small application that includes:

- A public home page.
- A login page.
- Dashboard pages protected by authentication.
- Functionality for users to add, edit, and delete invoices.
- An accompanying database that was set up during the course.

## Live service
To try the result, click the link: [Dashboard](https://nextjs-dashboard-jet-three.vercel.app/).

## Accessing the Application

To log in to the application, use the following credentials:

- **Email:** user@nextmail.com
- **Password:** 123456

## Installation

I recommend using pnpm as your package manager, as it's faster and more efficient than npm or yarn. If you don't have pnpm installed, you can install it globally by running:

```bash
npm install -g pnpm
```

1. Clone the repository:
   ```bash
   git clone https://github.com/V0000DY/nextjs-dashboard.git
   ```

2. Navigate to the project directory:
   ```bash
   cd your-repository
   ```

3. Install the dependencies:
   ```bash
   pnpm install
   ```

4. Run the application:
   ```bash
   pnpm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Project Structure

- `dashboard/` - folder containing main routes, includes page.tsx and layout.tsx, with folder names corresponding to the routing.
- `lib/` - contains helper functions and database configurations.
- `login/` - login page for user authentication.
- `query/` - contains database queries.
- `seed/` - contains data for populating the database.
- `ui/` - user interface components.

## License

This project is licensed under the MIT License. See the LICENSE file for details.