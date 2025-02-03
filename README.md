# React Router DOM v6 Unexpected Route Behavior

This repository demonstrates an uncommon bug in React Router DOM v6 related to programmatic navigation after a click event that changes the component's internal state.  The issue occurs when using `useNavigate` or similar functions to navigate after a state change triggered by a click.

The bug is demonstrated in `bug.js`. The solution, showcasing how to avoid this issue, can be found in `bugSolution.js`.