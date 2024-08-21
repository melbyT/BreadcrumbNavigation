# Breadcrumb Navigation Component

This is a simple and customizable Breadcrumb Navigation component for React Native. It helps users navigate through a hierarchy of screens.

## Installation

No additional installation is required. Just copy the `Breadcrumb.js` file into your project.

## Usage

Import the `Breadcrumb` component and use it in your screens:

```javascript
import Breadcrumb from './src/components/Breadcrumb/Breadcrumb';

const routes = [
  { name: 'Home', label: 'Home' },
  { name: 'Details', label: 'Details' },
  { name: 'Profile', label: 'Profile' },
];

<Breadcrumb routes={routes} onNavigate={handleNavigate} />;
