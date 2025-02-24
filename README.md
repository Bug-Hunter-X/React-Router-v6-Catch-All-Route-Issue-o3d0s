This repository demonstrates a common issue in React Router DOM v6 where a catch-all route (`/*`) unexpectedly matches all routes, preventing other routes from working correctly.  The issue is resolved by ensuring that the catch-all route is placed last in the route definition, after all specific routes.