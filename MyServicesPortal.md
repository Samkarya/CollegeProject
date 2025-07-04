# React Project Documentation

Generated on: 28/5/2025, 2:54:23 pm

## Project Structure

```
├── 📄 App.tsx
├── 📁 **components/**
│   ├── 📁 **analytics/**
│   │   └── 📄 AnalyticsTracker.tsx
│   ├── 📁 **auth/**
│   │   ├── 📁 **AuthFormContainer/**
│   │   │   ├── 📄 AuthFormContainer.module.scss
│   │   │   └── 📄 AuthFormContainer.tsx
│   │   ├── 📁 **ForgotPassword/**
│   │   │   ├── 📄 ForgotPassword.module.scss
│   │   │   └── 📄 ForgotPassword.tsx
│   │   ├── 📁 **Login/**
│   │   │   ├── 📄 Login.module.scss
│   │   │   └── 📄 Login.tsx
│   │   └── 📁 **Register/**
│   │       ├── 📄 Register.module.scss
│   │       └── 📄 Register.tsx
│   ├── 📁 **common/**
│   │   ├── 📁 **Button/**
│   │   │   ├── 📄 Button.module.scss
│   │   │   └── 📄 Button.tsx
│   │   ├── 📁 **Footer/**
│   │   │   ├── 📄 Footer.module.scss
│   │   │   └── 📄 Footer.tsx
│   │   ├── 📁 **Header/**
│   │   │   ├── 📄 Header.module.scss
│   │   │   └── 📄 Header.tsx
│   │   ├── 📁 **Input/**
│   │   │   ├── 📄 Input.module.scss
│   │   │   └── 📄 Input.tsx
│   │   ├── 📁 **LoadingSpinner/**
│   │   │   ├── 📄 LoadingSpinner.module.scss
│   │   │   └── 📄 LoadingSpinner.tsx
│   │   ├── 📁 **PaymentModal/**
│   │   │   ├── 📄 PaymentModal.module.scss
│   │   │   └── 📄 PaymentModal.tsx
│   │   ├── 📁 **Textarea/**
│   │   │   ├── 📄 Textarea.module.scss
│   │   │   └── 📄 Textarea.tsx
│   │   └── 📁 **Toast/**
│   │       ├── 📄 index.ts
│   │       ├── 📄 Toast.module.scss
│   │       ├── 📄 ToastMessage.tsx
│   │       ├── 📄 ToastProvider.tsx
│   │       ├── 📄 types.ts
│   │       └── 📄 useToast.ts
│   ├── 📁 **contact/**
│   │   └── 📁 **ContactForm/**
│   │       ├── 📄 ContactForm.module.scss
│   │       └── 📄 ContactForm.tsx
│   ├── 📁 **dashboard/**
│   │   ├── 📁 **Dashboard/**
│   │   │   ├── 📄 Dashboard.module.scss
│   │   │   └── 📄 Dashboard.tsx
│   │   └── 📁 **ServiceCard/**
│   │       ├── 📄 ServiceCard.module.scss
│   │       └── 📄 ServiceCard.tsx
│   └── 📁 **profile/**
│       └── 📁 **Profile/**
│           ├── 📄 Profile.module.scss
│           └── 📄 Profile.tsx
├── 📁 **config/**
│   └── 📄 appDefaults.ts
├── 📁 **contexts/**
│   └── 📄 AuthContext.tsx
├── 📁 **hooks/**
│   ├── 📄 useAuth.tsx
│   └── 📄 useNetworkStatus.ts
├── 📄 index.scss
├── 📄 index.tsx
├── 📁 **layouts/**
│   ├── 📄 AdminLayout.module.scss
│   ├── 📄 AdminLayout.tsx
│   ├── 📄 MainLayout.module.scss
│   └── 📄 MainLayout.tsx
├── 📁 **pages/**
│   ├── 📁 **AboutPage/**
│   │   └── 📄 AboutPage.tsx
│   ├── 📁 **Admin/**
│   │   ├── 📄 AdminConfigurationsPage.module.scss
│   │   ├── 📄 AdminConfigurationsPage.tsx
│   │   ├── 📄 AdminContactsPage.module.scss
│   │   ├── 📄 AdminContactsPage.tsx
│   │   ├── 📄 AdminDashboardPage.module.scss
│   │   ├── 📄 AdminDashboardPage.tsx
│   │   ├── 📄 AdminPaymentsPage.module.scss
│   │   ├── 📄 AdminPaymentsPage.tsx
│   │   ├── 📄 AdminUsersPage.module.scss
│   │   ├── 📄 AdminUsersPage.tsx
│   │   ├── 📄 DeletedUsersPage.module.scss
│   │   └── 📄 DeletedUsersPage.tsx
│   ├── 📁 **ContactPage/**
│   │   └── 📄 ContactPage.tsx
│   ├── 📁 **DashboardPage/**
│   │   └── 📄 DashBoardPage.tsx
│   ├── 📁 **ForgotPasswordPage/**
│   │   └── 📄 ForgotPasswordPage.tsx
│   ├── 📁 **LandingPage/**
│   │   ├── 📄 LandingPage.module.scss
│   │   └── 📄 LandingPage.tsx
│   ├── 📁 **LoginPage/**
│   │   └── 📄 LoginPage.tsx
│   ├── 📁 **NotFoundPage/**
│   │   └── 📄 NotFoundPage.tsx
│   ├── 📄 NotFoundPage.module.scss
│   ├── 📄 PageStyles.module.scss
│   ├── 📁 **PerksPage/**
│   │   ├── 📄 PerksPage.module.scss
│   │   └── 📄 PerksPage.tsx
│   ├── 📁 **PrivacyPage/**
│   │   └── 📄 PrivacyPage.tsx
│   ├── 📁 **ProfilePage/**
│   │   └── 📄 ProfilePage.tsx
│   ├── 📁 **RegisterPage/**
│   │   └── 📄 RegisterPage.tsx
│   ├── 📄 StaticPage.module.scss
│   └── 📁 **TermsPage/**
│       └── 📄 TermsPage.tsx
├── 📄 reportWebVitals.ts
├── 📁 **routes/**
│   ├── 📄 AdminRoute.tsx
│   └── 📄 AppRoutes.tsx
├── 📁 **services/**
│   ├── 📄 adminService.ts
│   ├── 📄 configService.ts
│   ├── 📄 firebase.ts
│   └── 📄 paymentService.ts
├── 📄 setupTests.ts
├── 📁 **styles/**
│   ├── 📄 index.scss
│   ├── 📄 _base.scss
│   └── 📄 _variables.scss
├── 📁 **types/**
│   └── 📄 index.ts
└── 📁 **utils/**
    ├── 📄 adminCheck.ts
    └── 📄 validators.ts
```

## File Contents

The following sections contain the content of each file in the project.


### App.tsx

```typescript
// src/App.tsx
import React, { useState, useEffect } from 'react'; // Added useState, useEffect
import { BrowserRouter as Router } from 'react-router-dom';
import { AuthProvider } from './contexts/AuthContext';
import AppRoutes from './routes/AppRoutes';
import { ToastProvider } from './components/common/Toast';
import AnalyticsTracker from './components/analytics/AnalyticsTracker';

const App: React.FC = () => {
  // --- Theme State ---
  // Initialize theme based on user preference or system setting
  const [theme] = useState(() => {
    const savedTheme = localStorage.getItem('app-theme');
    const prefersDark = window.matchMedia && window.matchMedia('(prefers-color-scheme: dark)').matches;
    return savedTheme || (prefersDark ? 'dark' : 'light');
  });

  // Effect to apply theme class to body and save preference
  useEffect(() => {
    document.body.className = ''; // Clear existing theme classes
    document.body.classList.add(`${theme}-theme`); // Apply 'light-theme' or 'dark-theme'
    localStorage.setItem('app-theme', theme); // Save preference
    //console.log(`App theme set to: ${theme}`); // Debug log
  }, [theme]);

  // TODO: Provide a way for the user to toggle the theme (e.g., in Header or Profile)
  // const toggleTheme = () => {
  //   setTheme(prevTheme => (prevTheme === 'light' ? 'dark' : 'light'));
  // };
  // --- End Theme State ---


  return (
    <Router> {/* BrowserRouter setup */}
      {/* ToastProvider should ideally be inside AuthProvider if toasts need auth context,
          or wrap AuthProvider if auth actions trigger toasts */}
      <ToastProvider><AuthProvider> {/* Provides auth context to the entire app */}
          {/* Toast context */}
            {/* Layout component could wrap AppRoutes here if needed */}

            <AnalyticsTracker/>
            <AppRoutes /> {/* Defines all application routes */}

         
      </AuthProvider></ToastProvider>
    </Router>
  );
};

export default App;
```

---

## components


## components\analytics


### components\analytics\AnalyticsTracker.tsx

```typescript
// src/components/analytics/AnalyticsTracker.tsx
import { useEffect } from 'react';
import { useLocation } from 'react-router-dom';
import { analytics, logAnalyticsEvent } from '../../services/firebase'; // Use the helper

const AnalyticsTracker: React.FC = () => {
  const location = useLocation();

  useEffect(() => {
    // Check if analytics is actually initialized (measurementId might be missing)
    if (!analytics) {
      return;
    }

    const page_path = location.pathname + location.search; // Get current path with query params

    // Log the page_view event using the helper function
    logAnalyticsEvent('page_view', {
      page_path: page_path,
      page_location: window.location.href, // Full URL
      page_title: document.title, // Send the current page title
    });

    // Optional: Log to console for debugging
    //console.log(`Analytics page_view logged for: ${page_path}`);

  }, [location]); // Re-run the effect when the location changes

  // This component doesn't render anything visible
  return null;
};

export default AnalyticsTracker;
```

---

## components\auth


## components\auth\AuthFormContainer


### components\auth\AuthFormContainer\AuthFormContainer.module.scss

```scss
// src/components/auth/AuthFormContainer/AuthFormContainer.module.scss
@import '../../../styles/variables'; // SCSS variables for structure

.authContainer {
  // --- Card Styling ---
  background-color: var(--color-bg-secondary); // Use secondary background
  padding: $spacing-xl $spacing-lg;        // Adjust padding if needed
  border-radius: $border-radius-lg;       // Larger radius for auth forms
  border: $border-width-base solid var(--color-border-primary);
  box-shadow: var(--shadow-md);             // Use themed shadow
  max-width: 450px;
  margin: $spacing-xl auto;               // Center container with vertical margin
  transition: background-color 0.2s ease, border-color 0.2s ease; // Smooth theme change
}

// --- Title & Subtitle ---
.title {
  text-align: center;
  margin-bottom: $spacing-sm;
  font-size: $font-size-h3; // Use heading size variable
  font-weight: 600;
  color: var(--color-primary); // Use primary color for title
}

.subtitle {
  text-align: center;
  color: var(--color-text-secondary);
  margin-bottom: $spacing-xl; // More space after subtitle
  font-size: $font-size-base;
  line-height: $line-height-base;
}

// --- Form Content Styling ---
.formContent {
  // Use flexbox for form layout if needed, otherwise let inputs stack
  > form {
    display: flex;
    flex-direction: column;
    gap: $spacing-md; // Consistent gap between direct children (inputs, buttons, links)

    // Remove default margin from Input/Textarea containers if gap is used
    > :global(.inputContainer), // Target global class from Input if needed
    > :global(.textareaContainer) { // Target global class from Textarea if needed
      margin-bottom: 0;
    }

     // Adjust spacing specifically for elements like the password help text or links
    .inputHelp, .forgotPasswordLink, .signupLink, .loginLink, .termsConsent {
       margin-top: -$spacing-sm; // Pull closer to the preceding element if needed
       margin-bottom: $spacing-xs; // Add small space below
    }
     // Ensure button has adequate top margin if gap isn't sufficient
     > button[type="submit"] {
       margin-top: $spacing-md; // Add extra space before submit button
     }
  }
}

// --- Link Styling (Common across auth forms) ---
// Specific link styles might be in individual component SCSS files,
// but common positioning/sizing can go here or be handled by form gap.
.authLink {
  text-align: center;
  font-size: $font-size-sm;
  color: var(--color-text-secondary);
  margin-top: $spacing-lg; // Space above the bottom link

  a {
    font-weight: 500;
    color: var(--color-text-link);
    margin-left: $spacing-xs;
    &:hover {
      color: var(--color-text-link-hover);
    }
  }
}
```

---

### components\auth\AuthFormContainer\AuthFormContainer.tsx

```typescript
// src/components/auth/AuthFormContainer/AuthFormContainer.tsx
import React from 'react';
import { AuthFormContainerProps } from '../../../types'; // Adjust path
import styles from './AuthFormContainer.module.scss'; // Adjust path

const AuthFormContainer: React.FC<AuthFormContainerProps> = ({
    children,
    title,
    subtitle,
    className = '', // Allow external classes to be passed
}) => {
    // Combine base class with any passed classes
    const containerClasses = [
        styles.authContainer,
        className // Append external classes
    ].filter(Boolean).join(' ');

    return (
        <div className={containerClasses}>
            {/* Title */}
            <h1 className={styles.title}>{title}</h1>
            {/* Subtitle (Optional) */}
            {subtitle && <p className={styles.subtitle}>{subtitle}</p>}
            {/* Form Content */}
            <div className={styles.formContent}>
                {children} {/* Render the form elements passed as children */}
            </div>
        </div>
    );
};

export default AuthFormContainer;
```

---

## components\auth\ForgotPassword


### components\auth\ForgotPassword\ForgotPassword.module.scss

```scss
// src/components/auth/ForgotPassword/ForgotPassword.module.scss
@import '../../../styles/variables'; // SCSS variables for structure

.backLinks {
  // Uses .authLink styles from AuthFormContainer by default if structure matches
  text-align: center;
  margin-top: $spacing-lg; // Space above link
  font-size: $font-size-sm;
  color: var(--color-text-secondary);

  a {
    font-weight: 500;
    color: var(--color-text-link);
    &:hover {
      color: var(--color-text-link-hover);
    }
  }
   // Style the separator if needed
   span {
     color: var(--color-text-tertiary); // Muted separator
     margin: 0 $spacing-xs;
   }
}
```

---

### components\auth\ForgotPassword\ForgotPassword.tsx

```typescript
// src/components/auth/ForgotPassword/ForgotPassword.tsx
import React, { useState, FormEvent } from 'react';
import { Link } from 'react-router-dom';
import { useAuth } from '../../../hooks/useAuth'; // Adjust path
import { validateForgotPasswordForm, ForgotPasswordErrors } from '../../../utils/validators'; // Adjust path
import AuthFormContainer from '../AuthFormContainer/AuthFormContainer'; // Adjust path
import Input from '../../common/Input/Input'; // Use redesigned Input
import Button from '../../common/Button/Button'; // Use redesigned Button
import { FiMail, FiSend } from 'react-icons/fi'; // Keep Feather icons
import styles from './ForgotPassword.module.scss'; // Adjust path
import { useToast } from '../../common/Toast'; // Import useToast

const ForgotPassword: React.FC = () => {
    const [email, setEmail] = useState('');
    const [errors, setErrors] = useState<ForgotPasswordErrors>({});
    const [loading, setLoading] = useState(false);
    // Use toast for success/error messages primarily
    // const [successMessage, setSuccessMessage] = useState<string | null>(null);
    const { resetPassword } = useAuth();
    const { addToast } = useToast(); // Get toast function

    const handleSubmit = async (e: FormEvent) => {
        e.preventDefault();
        setErrors({});
        // setSuccessMessage(null); // Clear local success message

        const validationErrors = validateForgotPasswordForm(email);
        if (Object.keys(validationErrors).length > 0) {
            setErrors(validationErrors);
            return;
        }

        setLoading(true);
        try {
            // resetPassword from useAuth now handles the success toast internally for security
            await resetPassword(email);
            // Optional: Maybe clear the email field or disable form after successful send
            // setEmail(''); // Clear email field
            // Keep form enabled unless explicitly needed otherwise
        } catch (error: any) {
           //console.error('Password reset request failed:', error);
            // Display user-friendly error (comes from useAuth hook)
            addToast(error.message || 'Failed to send reset email. Please try again.', 'error');
            // Set general error for inline display if needed
            // setErrors({ general: error.message || 'Failed to send reset email.' });
        } finally {
            setLoading(false);
        }
    };

    return (
        // Reuse AuthFormContainer for structure and styling
        <AuthFormContainer
            title="Reset Your Password"
            subtitle="Enter your email to receive instructions"
        >
             <form onSubmit={handleSubmit} noValidate>
                {/* Rely on Toast for success/general errors */}
                {/* {errors.general && <p className="alert alert-error">{errors.general}</p>} */}
                {/* {successMessage && !errors.general && <p className="alert alert-success">{successMessage}</p>} */}

                <Input
                    label="Email Address"
                    type="email"
                    id="email"
                    name="email"
                    value={email}
                    onChange={(e) => setEmail(e.target.value)}
                    error={errors.email}
                    disabled={loading} // Keep enabled after success maybe? Or disable? User choice.
                    icon={<FiMail />}
                    required
                    autoComplete="email"
                    aria-describedby={errors.email ? "email-error" : undefined}
                />

                 <Button
                    type="submit"
                    variant="primary"
                    size="large" // Match other auth buttons
                    fullWidth
                    loading={loading}
                    disabled={loading}
                    style={{ marginTop: '1rem' }} // Ensure spacing if only one input
                >
                    <FiSend style={{ marginRight: '8px' }} /> Send Reset Instructions
                </Button>

                 {/* Back Links */}
                 <div className={styles.backLinks}>
                    <Link to="/login">Back to Login</Link>
                    <span>|</span>
                    <Link to="/register">Create Account</Link>
                </div>
            </form>
        </AuthFormContainer>
    );
};

export default ForgotPassword;
```

---

## components\auth\Login


### components\auth\Login\Login.module.scss

```scss
// src/components/auth/Login/Login.module.scss
@import '../../../styles/variables'; // SCSS variables for structure
// Import base link styles if defined separately or rely on AuthFormContainer styles
// @import '../AuthFormContainer/AuthFormContainer.module.scss';

// Login-specific styles mostly deal with links and spacing

.forgotPasswordLink {
  text-align: right; // Align to the right, below password input
  font-size: $font-size-sm;
  margin-top: -$spacing-sm; // Pull up closer to password input
  margin-bottom: $spacing-lg; // Space before submit button

  a {
    color: var(--color-text-link);
    &:hover {
      color: var(--color-text-link-hover);
    }
  }
}

.signupLink {
  // Uses .authLink styles from AuthFormContainer by default if structure matches
  text-align: center;
  margin-top: $spacing-lg; // Ensure enough space after button
  font-size: $font-size-sm;
  color: var(--color-text-secondary);

  a {
    font-weight: 500;
    margin-left: $spacing-xs;
    color: var(--color-text-link);
    &:hover {
      color: var(--color-text-link-hover);
    }
  }
}

// Any other specific overrides for Login form structure within the container
```

---

### components\auth\Login\Login.tsx

```typescript
// src/components/auth/Login/Login.tsx
import React, { useState, FormEvent } from 'react';
import { Link, useNavigate, useLocation } from 'react-router-dom';
import { useAuth } from '../../../hooks/useAuth'; // Adjust path
import { validateLoginForm, LoginErrors } from '../../../utils/validators'; // Adjust path
import AuthFormContainer from '../AuthFormContainer/AuthFormContainer'; // Adjust path
import Input from '../../common/Input/Input'; // Use redesigned Input
import Button from '../../common/Button/Button'; // Use redesigned Button
import { FiMail, FiLock } from 'react-icons/fi'; // Keep Feather icons
import styles from './Login.module.scss'; // Adjust path
import { logAnalyticsEvent } from '../../../services/firebase'; // Adjust path
import { useToast } from '../../common/Toast'; // Import useToast

const Login: React.FC = () => {
    const [email, setEmail] = useState('');
    const [password, setPassword] = useState('');
    const [errors, setErrors] = useState<LoginErrors>({});
    const [loading, setLoading] = useState(false);
    const { login } = useAuth();
    const navigate = useNavigate();
    const location = useLocation();
    const { addToast } = useToast(); // Get toast function

    const from = location.state?.from?.pathname || '/dashboard'; // Redirect logic remains

    const handleSubmit = async (e: FormEvent) => {
        e.preventDefault();
        setErrors({}); // Clear previous errors on new submission

        const validationErrors = validateLoginForm(email, password);
        if (Object.keys(validationErrors).length > 0) {
            setErrors(validationErrors);
            // Optional: focus the first invalid field
            // const firstErrorField = document.getElementById(Object.keys(validationErrors)[0]);
            // firstErrorField?.focus();
            return;
        }

        setLoading(true);
        try {
            await login(email, password);
            logAnalyticsEvent('login', { method: 'Email/Password' });
            // No toast on success, navigate immediately
            navigate(from, { replace: true });
        } catch (error: any) {
           //console.error('Login failed:', error);
            // Display user-friendly error messages (coming from useAuth hook)
            // Use toast for general errors, or inline if AuthFormContainer supports it
            addToast(error.message || 'Login failed. Please try again.', 'error');
            setErrors({ general: error.message || 'Login failed.' }); // Still set general error if needed
        } finally {
            setLoading(false);
        }
    };

    return (
        // Reuse AuthFormContainer for structure and styling
        <AuthFormContainer
            title="Welcome Back!"
            subtitle="Log in to access your MyServices dashboard."
        >
            <form onSubmit={handleSubmit} noValidate>
                {/* Display general errors using Alert component (optional) or rely on Toast */}
                {/* {errors.general && <div className="alert alert-error">{errors.general}</div>} */}

                <Input
                    label="Email Address"
                    type="email"
                    id="email" // Use id for label association
                    name="email" // Ensure name attribute is present
                    value={email}
                    onChange={(e) => setEmail(e.target.value)}
                    error={errors.email} // Pass error message
                    disabled={loading}
                    icon={<FiMail />}
                    required
                    autoComplete="email"
                    aria-describedby={errors.email ? "email-error" : undefined}
                />

                <Input
                    label="Password"
                    type="password"
                    id="password" // Use id for label association
                    name="password" // Ensure name attribute is present
                    value={password}
                    onChange={(e) => setPassword(e.target.value)}
                    error={errors.password} // Pass error message
                    disabled={loading}
                    icon={<FiLock />}
                    required
                    autoComplete="current-password"
                    canToggleVisibility={true} // Enable visibility toggle
                    aria-describedby={errors.password ? "password-error" : undefined}
                />

                 {/* Forgot Password Link */}
                 <div className={styles.forgotPasswordLink}>
                    <Link to="/forgot-password">Forgot password?</Link>
                </div>

                {/* Submit Button */}
                <Button
                    type="submit"
                    variant="primary"
                    size="large" // Make submit button larger
                    fullWidth
                    loading={loading}
                    disabled={loading}
                >
                    {/* Optional Icon */}
                    {/* <FiLogIn style={{ marginRight: '8px' }}/> */}
                    Log In
                </Button>

                {/* Sign Up Link */}
                <div className={styles.signupLink}>
                    Don't have an account? <Link to="/register">Sign up</Link>
                </div>
            </form>
        </AuthFormContainer>
    );
};

export default Login;
```

---

## components\auth\Register


### components\auth\Register\Register.module.scss

```scss
// src/components/auth/Register/Register.module.scss
@import '../../../styles/variables'; // SCSS variables for structure

.loginLink {
  // Uses .authLink styles from AuthFormContainer by default if structure matches
  text-align: center;
  margin-top: $spacing-lg; // Space above link
  font-size: $font-size-sm;
  color: var(--color-text-secondary);

  a {
    font-weight: 500;
    margin-left: $spacing-xs;
    color: var(--color-text-link);
    &:hover {
      color: var(--color-text-link-hover);
    }
  }
}

.inputHelp {
  display: block;
  // Pulled closer to input by form gap setting in AuthFormContainer
  font-size: 0.75rem; // Smaller help text
  color: var(--color-text-tertiary); // Muted color
  padding: 0 $spacing-xs; // Slight indent if needed
}

// --- Password Strength Indicator ---
.passwordStrengthContainer {
  display: flex;
  align-items: center;
  gap: $spacing-sm; // Space between bars and label
  margin-top: $spacing-xs; // Space above indicator
  margin-bottom: $spacing-xs; // Space below before help text
}

.strengthBars {
  display: flex;
  gap: $spacing-xs; // Gap between individual bars
  flex: 1; // Take available space
  height: 6px; // Thicker bars
}

.strengthBar {
  flex: 1;
  height: 100%;
  border-radius: $border-radius-pill; // Rounded bars
  background-color: var(--color-bg-tertiary); // Default inactive bar color
  transition: background-color 0.3s ease;
}

.strengthLabel {
  font-size: 0.75rem;
  font-weight: 500;
  min-width: 70px; // Adjust as needed
  text-align: right;
  transition: color 0.3s ease;
  // Color set dynamically via inline style
}

// --- Terms & Privacy Consent ---
.termsConsent {
  display: flex;
  align-items: flex-start; // Align checkbox with first line of text
  // Spacing handled by form gap
  gap: $spacing-sm;
  padding: $spacing-sm 0; // Vertical padding

  input[type="checkbox"] {
    margin-top: 3px; // Align checkbox slightly better
    flex-shrink: 0; // Prevent checkbox shrinking
    width: 16px;    // Explicit size
    height: 16px;   // Explicit size
    cursor: pointer;

    &:disabled {
      cursor: not-allowed;
      opacity: 0.6;
    }
     &:focus-visible { // Custom focus for checkbox
       outline: none;
       box-shadow: 0 0 0 2px var(--color-bg-primary), 0 0 0 4px var(--color-primary); // Ring effect
       border-radius: $border-radius-sm;
     }
     // Consider custom checkbox styling if needed across the app
  }

  label {
    font-size: $font-size-sm;
    color: var(--color-text-secondary);
    line-height: 1.5; // Improve readability
    cursor: pointer;

    //a {
      // Inherit link styles from base/AuthFormContainer
    //}
  }
}

.termsError {
  // Pulled closer by form gap
  display: block;
  color: var(--color-error);
  font-size: 0.75rem;
  // Add padding matching checkbox indent + gap if needed
  padding-left: $spacing-sm + 16px; // Example: gap + checkbox width
}
```

---

### components\auth\Register\Register.tsx

```typescript
// src/components/auth/Register/Register.tsx
import React, { useState, FormEvent, useCallback, ChangeEvent } from 'react';
import { Link, useNavigate } from 'react-router-dom';
import { useAuth } from '../../../hooks/useAuth';
import {
    validateRegisterForm,
    RegisterErrors, // Import updated type
    passwordRequirementString,
    usernameRequirementString,
    checkPasswordStrength,
    PasswordStrength
} from '../../../utils/validators';
import AuthFormContainer from '../AuthFormContainer/AuthFormContainer';
import Input from '../../common/Input/Input';
import Button from '../../common/Button/Button';
import { FiMail, FiLock, FiUser, FiSmile } from 'react-icons/fi';
import styles from './Register.module.scss';
import { logAnalyticsEvent } from '../../../services/firebase';
import { useToast } from '../../common/Toast';

const initialFormData = {
    email: '',
    username: '',
    displayName: '',
    password: '',
    confirmPassword: '',
};

const initialPasswordStrength: PasswordStrength = { score: 0, label: '', color: 'transparent' };

const Register: React.FC = () => {
    const [formData, setFormData] = useState(initialFormData);
    // Initialize errors state as an empty object conforming to RegisterErrors
    const [errors, setErrors] = useState<RegisterErrors>({});
    const [loading, setLoading] = useState(false);
    const [passwordStrength, setPasswordStrength] = useState<PasswordStrength>(initialPasswordStrength);
    const [agreedToTerms, setAgreedToTerms] = useState(false);
    const { register } = useAuth();
    const navigate = useNavigate();
    const { addToast } = useToast();

    const handleChange = useCallback((e: ChangeEvent<HTMLInputElement>) => {
        const { name, value } = e.target;
        setFormData(prev => ({ ...prev, [name]: value }));

        // Use keyof RegisterErrors to ensure 'name' is a valid key
        const errorKey = name as keyof RegisterErrors;
        if (errors[errorKey]) {
            // Correctly clear the specific error using functional update
            setErrors(prev => ({ ...prev, [errorKey]: undefined }));
        }
        // Clear general error on any change
        if (errors.general) {
            setErrors(prev => ({ ...prev, general: undefined }));
        }

        // Update password strength
        if (name === 'password') {
            setPasswordStrength(checkPasswordStrength(value));
        }
        // Remove 'terms' error when related field changes? Not necessary here.
        // Clearing the 'terms' error is handled specifically in the checkbox onChange.

    }, [errors]); // Keep dependency on errors state

    const renderStrengthBars = useCallback(() => {
        // ... (renderStrengthBars function remains the same)
        const bars = [];
        const totalBars = 4;

        for (let i = 0; i < totalBars; i++) {
            bars.push(
                <div
                    key={i}
                    className={styles.strengthBar}
                    style={{
                        backgroundColor: i < passwordStrength.score ? passwordStrength.color : 'var(--color-bg-tertiary)'
                    }}
                />
            );
        }
        return bars;
    }, [passwordStrength]);

    const handleSubmit = async (e: FormEvent) => {
        e.preventDefault();
        // Clear all errors, conforming to RegisterErrors type
        setErrors({});

        if (!agreedToTerms) {
             // Set the specific 'terms' error correctly
             setErrors(prev => ({
                 ...prev,
                 terms: 'You must agree to the Terms and Privacy Policy.'
             }));
            addToast('Please agree to the terms to continue.', 'warning');
            return;
        }

        const { email, username, displayName, password, confirmPassword } = formData;
        // validateRegisterForm now returns a potentially empty RegisterErrors object
        const validationErrors = validateRegisterForm(email, username, displayName, password, confirmPassword);

        if (Object.keys(validationErrors).length > 0) {
            // Set the validation errors state correctly
            setErrors(validationErrors);
            return;
        }

        setLoading(true);
        try {
            await register(email, password, username, displayName);
            logAnalyticsEvent('Sign-up', { method: 'Email/Password' });
            addToast('Registration successful! Welcome!', 'success');
            navigate('/dashboard');
        } catch (error: any) {
           //console.error('Registration failed:', error);
            let generalErrorMessage = error.message || 'Registration failed. Please try again.';
            let specificErrors: RegisterErrors = {}; // Correctly typed empty object

            if (error.message.includes('username')) {
                specificErrors.username = error.message;
                generalErrorMessage = '';
            } else if (error.message.includes('email')) {
                 specificErrors.email = error.message;
                 generalErrorMessage = '';
            } else if (error.message.includes('password')) {
                 specificErrors.password = error.message;
                 generalErrorMessage = '';
            }

            addToast(generalErrorMessage || Object.values(specificErrors).find(msg => msg) || 'Registration failed.', 'error');
            // Set state correctly with potentially specific and general errors
            setErrors({ ...specificErrors, general: generalErrorMessage || undefined });

        } finally {
            setLoading(false);
        }
    };

    return (
        <AuthFormContainer
            title="Create Your Account"
            subtitle="Join MyServices to access all features"
        >
            <form onSubmit={handleSubmit} noValidate>
                {/* Input Fields ... */}
                 <Input
                    label="Email Address" type="email" id="email" name="email"
                    value={formData.email} onChange={handleChange} error={errors.email}
                    disabled={loading} icon={<FiMail />} required autoComplete="email"
                />

                <Input
                    label="Username" type="text" id="username" name="username"
                    value={formData.username} onChange={handleChange} error={errors.username}
                    disabled={loading} icon={<FiUser />} required autoComplete="username"
                    aria-describedby="username-help"
                />
                <small id="username-help" className={styles.inputHelp}>{usernameRequirementString}</small>

                <Input
                    label="Display Name" type="text" id="displayName" name="displayName"
                    value={formData.displayName} onChange={handleChange} error={errors.displayName}
                    disabled={loading} icon={<FiSmile />} required autoComplete="name"
                />

                <Input
                    label="Password" type="password" id="password" name="password"
                    value={formData.password} onChange={handleChange} error={errors.password}
                    disabled={loading} icon={<FiLock />} required autoComplete="new-password"
                    aria-describedby="password-help password-strength" canToggleVisibility={true}
                />

                {formData.password && (
                  <div className={styles.passwordStrengthContainer} id="password-strength" aria-live="polite">
                      <div className={styles.strengthBars}>
                          {renderStrengthBars()}
                      </div>
                      {passwordStrength.label && (
                          <span
                              className={styles.strengthLabel}
                              style={{ color: passwordStrength.color }}
                          >
                              {passwordStrength.label}
                          </span>
                      )}
                  </div>
                )}
                <small id="password-help" className={styles.inputHelp}>{passwordRequirementString}</small>

                <Input
                    label="Confirm Password" type="password" id="confirmPassword" name="confirmPassword"
                    value={formData.confirmPassword} onChange={handleChange} error={errors.confirmPassword}
                    disabled={loading} icon={<FiLock />} required autoComplete="new-password"
                    canToggleVisibility={true}
                />
                {/* --- Terms and Privacy Policy Consent --- */}
                <div className={styles.termsConsent}>
                    <input
                        type="checkbox"
                        id="termsConsent"
                        checked={agreedToTerms}
                        onChange={(e) => {
                            const isChecked = e.target.checked;
                            setAgreedToTerms(isChecked);
                            // Clear terms error ONLY if checkbox is checked
                            if (isChecked && errors.terms) {
                                // Correctly clear only the terms error
                                setErrors(prev => ({ ...prev, terms: undefined }));
                            }
                        }}
                        disabled={loading}
                        aria-describedby="terms-help"
                        required
                    />
                    <label htmlFor="termsConsent">
                        I agree to the <Link to="/terms-of-service" target="_blank" rel="noopener noreferrer">Terms of Service</Link> and <Link to="/privacy-policy" target="_blank" rel="noopener noreferrer">Privacy Policy</Link>.
                    </label>
                </div>
                {/* Display terms error using the correct key */}
                {errors.terms && (
                    <small id="terms-help" className={styles.termsError} role="alert">
                        {errors.terms}
                    </small>
                )}

                {/* Submit Button */}
                <Button
                    type="submit"
                    variant="primary"
                    size="large"
                    fullWidth
                    loading={loading}
                    disabled={loading}
                >
                    Sign Up
                </Button>

                {/* Login Link */}
                <div className={styles.loginLink}>
                    Already have an account? <Link to="/login">Log in</Link>
                </div>
            </form>
        </AuthFormContainer>
    );
};

export default Register;
```

---

## components\common


## components\common\Button


### components\common\Button\Button.module.scss

```scss
// src/components/common/Button/Button.module.scss
@use 'sass:color'; // Use sass color module for adjustments
@import '../../../styles/variables'; // Import SCSS variables (spacing, fonts, etc.)

.button {
  // --- Base Styles ---
  display: inline-flex;
  align-items: center;
  justify-content: center;
  border-radius: $border-radius-md; // Use SCSS var for structure
  font-family: $font-family-base;
  font-weight: 500; // Medium weight for buttons
  text-align: center;
  text-transform: none;
  border: $border-width-base solid transparent; // Start with transparent border
  cursor: pointer;
  transition: background-color 0.2s ease, border-color 0.2s ease, color 0.2s ease, box-shadow 0.15s ease, transform 0.1s ease;
  white-space: nowrap;
  user-select: none;
  line-height: 1.2; // Prevent tall buttons from extra spacing
  position: relative; // For potential pseudo-elements or absolute positioning inside
  overflow: hidden; // Helps with ripple or other effects

  // --- Base States ---
  &:focus-visible {
    outline: none; // Already handled globally, but ensure it's off here
    box-shadow: var(--shadow-focus-ring); // Use CSS Var for focus
  }

  &:active:not(:disabled):not(.button--loading) {
    transform: scale(0.98); // Subtle press effect
  }

  &:disabled,
  &.button--loading { // Apply disabled styles when loading too
    cursor: not-allowed;
    opacity: 0.65;
    // Optionally remove transform on disabled active state
    &:active {
        transform: none;
    }
  }

  // --- Variants (Using CSS Variables) ---

  // Primary (Solid background, primary color)
  &--primary {
    background-color: var(--color-primary);
    color: var(--color-text-inverse); // Text on dark/colored background
    border-color: var(--color-primary);

    &:hover:not(:disabled):not(.button--loading) {
      // Slightly darken background on hover - using Sass for adjustability if needed
      background-color: var(--color-primary-dark);
      border-color: var(--color-primary-dark);
    }
  }

  // Secondary (Solid background, secondary color)
  &--secondary {
    background-color: var(--color-secondary);
    color: var(--color-text-inverse);
    border-color: var(--color-secondary);

     &:hover:not(:disabled):not(.button--loading) {
        background-color: var(--color-secondary-dark);
        border-color: var(--color-secondary-dark);
    }
  }

  // Outline (Transparent background, colored border/text)
  &--outline {
    background-color: transparent;
    color: var(--color-primary); // Text matches border
    border-color: var(--color-primary);

     &:hover:not(:disabled):not(.button--loading) {
        // Subtle background fill on hover
        background-color: var(--color-primary-light);
        color: var(--color-primary-dark); // Optionally darken text too
        border-color: var(--color-primary-dark); // Optionally darken border
    }
  }

  // Danger (Similar to primary/secondary but with error colors)
  &--danger {
      background-color: var(--color-error);
      color: var(--color-text-inverse);
      border-color: var(--color-error);

      &:hover:not(:disabled):not(.button--loading) {
          background-color: var(--color-error-dark);
          border-color: var(--color-error-dark);
      }

      // Specific focus ring for danger if needed
      &:focus-visible {
        box-shadow: 0 0 0 3px rgba(var(--color-error-raw), 0.3); // Danger focus ring
      }

      // Outline-Danger Sub-variant (Example) - could be a separate prop or class combo
      // &.button--outline-danger { ... }
      // OR just style based on context using regular outline + a context class
  }

  // Text (No background or border, just colored text)
  &--text {
      background-color: transparent;
      color: var(--color-primary); // Typically primary color
      border-color: transparent;
      padding-left: $spacing-xs; // Less padding for text buttons
      padding-right: $spacing-xs;

      &:hover:not(:disabled):not(.button--loading) {
          background-color: var(--color-primary-light); // Subtle bg on hover
          color: var(--color-primary-dark);
      }

      // Allow danger text button too
      &.button--danger { // Check how specific SCSS gets - may need higher specificity
          color: var(--color-error);
          &:hover:not(:disabled):not(.button--loading) {
              background-color: var(--color-error-light);
              color: var(--color-error-dark);
          }
      }
  }


  // --- Sizes ---
  &--small {
    padding: $spacing-xs $spacing-sm; // 4px 8px
    font-size: $font-size-sm;      // 14px
    // Adjust spinner size if needed within button via CSS
  }

  &--medium {
    // Default padding
    padding: $spacing-sm $spacing-lg; // 8px 24px (Example: more horizontal padding)
    font-size: $font-size-base;     // 16px
  }

  &--large {
    padding: $spacing-md $spacing-xl; // 16px 32px
    font-size: $font-size-lg;      // 18px
  }

  // --- Full Width ---
  &--fullWidth {
    width: 100%;
    display: flex; // Ensure spinner centers correctly
  }

  // --- Loading State ---
  // Spinner component should handle its own colors, but we ensure it's centered
  // and potentially hide the text content visually while loading
  &.button--loading {
      color: transparent; // Hide text visually (spinner shows instead)
      .buttonContent { // Assuming children are wrapped or handle hiding directly
          visibility: hidden;
      }
      // Ensure spinner is absolutely centered if text is hidden
      // The spinner component itself should handle centering, this is fallback
      :global(.loading-spinner-class) { // Use a global class name for spinner if needed
         position: absolute;
         left: 50%;
         top: 50%;
         transform: translate(-50%, -50%);
      }
  }
}

// Optional: Add styles for icons inside buttons if needed globally
// .button > svg {
//    margin-right: $spacing-sm;
//    width: 1em; // Scale with font size
//    height: 1em;
// }
```

---

### components\common\Button\Button.tsx

```typescript
// src/components/common/Button/Button.tsx
import React from 'react';
import styles from './Button.module.scss';
import { ButtonProps } from '../../../types'; // Ensure path is correct
import LoadingSpinner from '../LoadingSpinner/LoadingSpinner'; // Ensure path is correct

const Button: React.FC<ButtonProps> = ({
    children,
    variant = 'primary',
    size = 'medium',
    loading = false,
    disabled = false,
    fullWidth = false,
    className = '',
    type = 'button', // Default type to button
    ...props
}) => {
    const buttonClasses = [
        styles.button,
        styles[`button--${variant}`],
        styles[`button--${size}`],
        fullWidth ? styles['button--fullWidth'] : '',
        loading ? styles['button--loading'] : '',
        // Allow combining variants for specific cases like text danger button
        // Example: If using variant="text" and className="button--danger"
        // This depends on how you handle combined styles in SCSS
        // If variant="danger" handles text itself, this is less needed.
        className, // Allow external classes
    ].filter(Boolean).join(' '); // Filter out empty strings and join

    return (
        <button
            className={buttonClasses}
            type={type}
            disabled={disabled || loading} // Disable if loading
            {...props} // Spread remaining props like onClick, id, etc.
        >
            {/* Conditionally render spinner OR children */}
            {loading ? (
                // Ensure LoadingSpinner uses appropriate colors or inherits via CSS
                 // Pass color="inherit" or similar if spinner accepts color prop
                <LoadingSpinner size="small" />
            ) : (
                // Wrap children to allow hiding via CSS during loading state
                <span className={styles.buttonContent}>{children}</span>
            )}
        </button>
    );
};

export default Button;
```

---

## components\common\Footer


### components\common\Footer\Footer.module.scss

```scss
// src/components/common/Footer/Footer.module.scss
@import '../../../styles/variables'; // SCSS variables for layout/breakpoints

.footer {
  background-color: var(--color-bg-primary); // Use primary bg
  color: var(--color-text-secondary); // Muted text
  padding: $spacing-lg 0; // Standard vertical padding
  margin-top: auto; // Pushes footer to bottom in flex layout
  font-size: $font-size-sm; // Smaller text in footer
  border-top: $border-width-base solid var(--color-border-primary); // Separator line
  transition: background-color 0.2s ease-in-out, border-color 0.2s ease-in-out, color 0.2s ease-in-out;
}

.footerContainer {
  // Use global .container
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap; // Allow wrapping on small screens
  gap: $spacing-md; // Space between items when wrapped
}

.copyright {
   margin: 0;
   text-align: center; // Center on small screens
   flex-basis: 100%; // Take full width initially

   @media (min-width: $breakpoint-md) {
     text-align: left;
     flex-basis: auto; // Allow natural width
     order: 1; // Copyright first
   }
}

.secureConnection {
   margin-left: $spacing-sm; // Space from copyright text
   opacity: 0.8;
   display: inline-flex; // Align icon and text
   align-items: center;
   gap: $spacing-xs; // Space icon and text
   white-space: nowrap;

   svg { width: 14px; height: 14px; } // Smaller icon
}

.footerNav {
    display: flex;
    gap: $spacing-sm; // Space between links
    justify-content: center; // Center on small screens
    flex-wrap: wrap;
    list-style: none; // Remove list bullets if using ul
    padding: 0;
    margin: 0;
    flex-basis: 100%; // Take full width initially

     @media (min-width: $breakpoint-md) {
         flex-basis: auto; // Allow natural width
         order: 2; // Nav second
         gap: $spacing-lg; // More space on larger screens
         justify-content: flex-end;
     }
}

.footerLink {
    color: var(--color-text-secondary); // Use theme variable
    text-decoration: none;
    transition: color 0.2s ease;

    &:hover, &:focus {
        color: var(--color-text-link); // Use primary link color on hover
        text-decoration: underline; // Add underline on hover
    }
    &:focus-visible {
        outline: none; // Focus handled globally or customize
        // Optional: Add a subtle background or ring
        // background-color: var(--color-bg-tertiary);
        // border-radius: $border-radius-sm;
        // box-shadow: var(--shadow-focus-ring);
    }
}
```

---

### components\common\Footer\Footer.tsx

```typescript
// src/components/common/Footer/Footer.tsx
import React from 'react';
import { Link } from 'react-router-dom';
import styles from './Footer.module.scss'; // Adjust path
import { FiLock } from 'react-icons/fi'; // Keep using Feather

const Footer: React.FC = () => {
  const currentYear = new Date().getFullYear();
  // Check protocol for secure connection indicator
  const isSecure = typeof window !== 'undefined' && window.location.protocol === 'https:';

  return (
    <footer className={styles.footer}>
      {/* Use global container class */}
      <div className={`container ${styles.footerContainer}`}>
        <div className={styles.copyright}>
          © {currentYear} Samkarya | MyServices Portal. All rights reserved.
          {isSecure && (
              <span className={styles.secureConnection} title="Secure HTTPS Connection">
                  <FiLock /> Secure Connection
              </span>
          )}
        </div>
        {/* Use an unordered list for navigation links */}
        <ul className={styles.footerNav}>
          <li><Link to="/about" className={styles.footerLink}>About Us</Link></li>
          <li><Link to="/privacy-policy" className={styles.footerLink}>Privacy Policy</Link></li>
          <li><Link to="/terms-of-service" className={styles.footerLink}>Terms of Service</Link></li>
          <li><Link to="/contact" className={styles.footerLink}>Contact Us</Link></li>
        </ul>
      </div>
    </footer>
  );
};

export default Footer;
```

---

## components\common\Header


### components\common\Header\Header.module.scss

```scss
// src/components/common/Header/Header.module.scss
@import '../../../styles/variables'; // SCSS variables for layout/breakpoints

.header {
  // --- Base Styles ---
  background-color: var(--color-bg-secondary); 
  border-bottom: $border-width-base solid var(--color-border-primary);
  padding: 0 $spacing-md; // Add horizontal padding on mobile
  position: sticky;
  top: 0;
  z-index: $z-index-header;
  width: 100%;
  transition: background-color 0.2s ease-in-out, border-color 0.2s ease-in-out;
  height: 60px; // Consistent height on mobile

  @media (min-width: $breakpoint-lg) {
    padding: 0; // Remove horizontal padding on desktop (container handles it)
    height: 64px; // Slightly taller header on desktop
  }
}

.headerContainer {
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 100%; // Fill the header height
  width: 100%;
}

// --- Logo / Branding ---
.logo {
  font-size: $font-size-lg; // Slightly smaller logo on mobile
  font-weight: 700;
  color: var(--color-primary);
  text-decoration: none;
  white-space: nowrap;
  flex-shrink: 0; // Prevent logo from shrinking

  @media (min-width: $breakpoint-lg) {
    font-size: $font-size-xl; // Larger logo on desktop
  }

  &:hover, &:focus {
    text-decoration: none;
    color: var(--color-primary-dark);
  }
}

// --- Mobile Menu Button ---
.mobileMenuButton {
  background: none;
  border: none;
  color: var(--color-text-primary);
  padding: $spacing-sm;
  cursor: pointer;
  display: inline-flex;
  align-items: center;
  justify-content: center;

  @media (min-width: $breakpoint-md) {
    display: none; // Hide on medium screens and up
  }

  svg {
    width: 24px;
    height: 24px;
  }
}

// --- Navigation ---
.nav {
  display: none; // Hide full nav by default on mobile
  align-items: center;
  gap: $spacing-sm;

  @media (min-width: $breakpoint-md) {
    display: flex; // Show nav on medium screens and up
    gap: $spacing-md; // Increase gap on desktop
  }
}

// --- Mobile Navigation Panel ---
.mobileNav {
  position: fixed;
  top: 60px; // Below header
  left: 0;
  right: 0;
  bottom: 0;
  background-color: var(--color-bg-primary);
  z-index: calc($z-index-header - 10); // Below header but above content
  padding: $spacing-lg;
  display: flex;
  flex-direction: column;
  gap: $spacing-md;
  transform: translateX(-100%); // Hidden off-screen by default
  transition: transform 0.3s ease-in-out;

  &.isOpen {
    transform: translateX(0); // Slide in when open
  }

  // Style links within the mobile nav
  .navLink {
    display: block; // Stack links
    font-size: $font-size-lg; // Larger text for touch targets
    padding: $spacing-md 0;
    border-bottom: 1px solid var(--color-border-primary);
    color: var(--color-text-primary);
    
    &:hover {
      background-color: var(--color-bg-secondary);
    }
    
    svg {
      margin-right: $spacing-sm;
      vertical-align: middle;
    }
  }
}

// Shared nav link styles (adjust as needed)
.navLink {
  color: var(--color-text-secondary);
  text-decoration: none;
  font-size: $font-size-sm;
  font-weight: 500;
  transition: color 0.2s ease, background-color 0.2s ease;
  padding: $spacing-xs $spacing-sm;
  border-radius: $border-radius-sm;

  &:hover, &:focus {
    color: var(--color-text-link-hover);
    background-color: var(--color-bg-tertiary);
    text-decoration: none;
  }
}

.welcomeMessage {
  display: none; // Hide completely on small screens
  color: var(--color-text-secondary);
  font-size: $font-size-sm;
  margin-right: $spacing-xs;

  @media (min-width: $breakpoint-lg) {
    display: inline; // Show only on large screens
  }
}

.themeToggle {
  background: none;
  border: none;
  color: var(--color-text-secondary);
  padding: $spacing-xs;
  cursor: pointer;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  transition: color 0.2s ease, background-color 0.2s ease;
  margin-left: $spacing-sm;

  &:hover, &:focus {
    color: var(--color-text-primary);
    background-color: var(--color-bg-tertiary);
  }

  svg {
    width: 18px;
    height: 18px;
  }
}

// Mobile theme toggle (inside mobile nav)
.mobileThemeToggle {
  width: 100%;
  padding: $spacing-md;
  justify-content: center;
  background: var(--color-bg-secondary);
  border: none;
  border-radius: $border-radius-sm;
  color: var(--color-text-secondary);
  margin-top: auto; // Push to bottom
  display: flex;
  align-items: center;
  cursor: pointer;

  svg {
    margin-left: $spacing-sm;
  }
}

// Backdrop for mobile menu
.backdrop {
  position: fixed;
  inset: 0;
  background-color: rgba(0, 0, 0, 0.4);
  z-index: calc($z-index-header - 15);
}
```

---

### components\common\Header\Header.tsx

```typescript
// src/components/common/Header/Header.tsx
import React, { useState } from 'react';
import { Link, useNavigate } from 'react-router-dom';
import { useAuth } from '../../../hooks/useAuth';
import Button from '../Button/Button';
import { useToast } from '../../common/Toast';
import styles from './Header.module.scss';
import { 
  FiAward, 
  FiLogOut, 
  FiLogIn, 
  FiUserPlus, 
  FiUser, 
  FiMoon, 
  FiSun, 
  FiMenu, 
  FiX,
  FiGrid
} from 'react-icons/fi';

interface HeaderProps {
  theme?: 'light' | 'dark';
  toggleTheme?: () => void;
}

const Header: React.FC<HeaderProps> = ({ theme = 'light', toggleTheme }) => {
  const { addToast } = useToast();
  const { currentUser, userData, logout } = useAuth();
  const navigate = useNavigate();
  const [isMobileMenuOpen, setIsMobileMenuOpen] = useState(false);

  const handleLogout = async () => {
    try {
      await logout();
      addToast('Logged out successfully.', 'info');
      navigate('/login');
    } catch (error: any) {
     //console.error("Logout failed:", error);
      addToast(error.message || 'Failed to log out. Please try again.', 'error');
    }
  };

  const toggleMobileMenu = () => {
    setIsMobileMenuOpen(!isMobileMenuOpen);
  };

  const handleNavClick = () => {
    if (isMobileMenuOpen) {
      setIsMobileMenuOpen(false);
    }
  };

  const displayName = userData?.displayName || userData?.username;

  return (
    <>
      <header className={styles.header}>
        <div className={styles.headerContainer}>
          <Link to={currentUser ? "/dashboard" : "/"} className={styles.logo} onClick={handleNavClick}>
            MyServices Portal
          </Link>

          {/* Desktop Navigation */}
          <nav className={styles.nav}>
            {currentUser && userData?.status !== 'deleted' ? (
              <>
                {displayName && (
                  <span className={styles.welcomeMessage} title={`Logged in as ${displayName}`}>
                    Hi, {displayName.split(' ')[0]}!
                  </span>
                )}
                <Link to="/perks" className={styles.navLink}>
                  <FiAward style={{ verticalAlign: 'middle', marginRight: '4px' }} /> Perks
                </Link>
                <Link to="/profile" className={styles.navLink} title="View Profile">
                  <FiUser style={{ verticalAlign: 'middle', marginRight: '4px' }} /> Profile
                </Link>
                <Button
                  onClick={handleLogout}
                  variant="outline"
                  size="small"
                  className={styles.actionButton}
                  title="Log Out"
                >
                  <FiLogOut style={{ marginRight: '4px' }} /> Logout
                </Button>
              </>
            ) : (
              <>
                <Link to="/login" className={styles.navLink}>
                  <FiLogIn style={{ verticalAlign: 'middle', marginRight: '4px' }} /> Login
                </Link>
                <Link to="/register">
                  <Button variant="primary" size="small" className={styles.actionButton}>
                    <FiUserPlus style={{ marginRight: '4px' }} /> Register
                  </Button>
                </Link>
              </>
            )}

            {/* Theme Toggle Button (Desktop) */}
            {toggleTheme && (
              <button
                onClick={toggleTheme}
                className={styles.themeToggle}
                title={`Switch to ${theme === 'light' ? 'dark' : 'light'} mode`}
                aria-label={`Switch to ${theme === 'light' ? 'dark' : 'light'} mode`}
              >
                {theme === 'light' ? <FiMoon /> : <FiSun />}
              </button>
            )}
          </nav>

          {/* Mobile Menu Button */}
          <button 
            className={styles.mobileMenuButton} 
            onClick={toggleMobileMenu}
            aria-label={isMobileMenuOpen ? "Close menu" : "Open menu"}
            aria-expanded={isMobileMenuOpen}
          >
            {isMobileMenuOpen ? <FiX /> : <FiMenu />}
          </button>
        </div>
      </header>

      {/* Mobile Navigation Panel */}
      <div className={`${styles.mobileNav} ${isMobileMenuOpen ? styles.isOpen : ''}`}>
        {currentUser && userData?.status !== 'deleted' ? (
          <>
            <Link to="/dashboard" className={styles.navLink} onClick={handleNavClick}>
              <FiGrid /> Dashboard
            </Link>
            <Link to="/perks" className={styles.navLink} onClick={handleNavClick}>
              <FiAward /> Perks
            </Link>
            <Link to="/profile" className={styles.navLink} onClick={handleNavClick}>
              <FiUser /> Profile
            </Link>
            <hr style={{ borderColor: 'var(--color-border-primary)', margin: '16px 0' }} />
            <Button 
              onClick={handleLogout} 
              variant="secondary" 
              size="medium" 
              fullWidth 
              className={styles.actionButton}
            >
              <FiLogOut style={{ marginRight: '8px' }} /> Logout
            </Button>
          </>
        ) : (
          <>
            <Link to="/login" className={styles.navLink} onClick={handleNavClick}>
              <FiLogIn /> Login
            </Link>
            <Link to="/register" className={styles.navLink} onClick={handleNavClick}>
              <FiUserPlus /> Register
            </Link>
          </>
        )}
        
        {/* Theme Toggle Button (Mobile) */}
        {toggleTheme && (
          <button onClick={toggleTheme} className={styles.mobileThemeToggle}>
            Switch to {theme === 'light' ? 'Dark' : 'Light'} Mode 
            {theme === 'light' ? <FiMoon /> : <FiSun />}
          </button>
        )}
      </div>

      {/* Backdrop for Mobile Menu */}
      {isMobileMenuOpen && (
        <div className={styles.backdrop} onClick={toggleMobileMenu} />
      )}
    </>
  );
};

export default Header;
```

---

## components\common\Input


### components\common\Input\Input.module.scss

```scss
// src/components/common/Input/Input.module.scss
@import '../../../styles/variables'; // SCSS variables for structure/layout

.inputContainer {
  margin-bottom: $spacing-lg; // Increase default spacing below input group
  width: 100%;
  position: relative; // For positioning error messages
}

.label {
  display: block;
  margin-bottom: $spacing-sm; // More space between label and input
  font-weight: 500;
  font-size: $font-size-sm;
  color: var(--color-text-secondary);
  cursor: default; // It's not clickable itself
}

.inputWrapper {
  position: relative;
  display: flex;
  align-items: center;
}

.input {
  // --- Base Styles ---
  width: 100%;
  padding: $spacing-sm $spacing-md; // Adjust padding as needed
  border: $border-width-base solid var(--color-border-input); // Use CSS Var
  border-radius: $border-radius-md;
  font-size: $font-size-base;
  line-height: $line-height-base;
  background-color: var(--color-bg-primary); // Use background var
  color: var(--color-text-primary); // Use text var
  transition: border-color 0.2s ease-in-out, box-shadow 0.15s ease-in-out;
  appearance: none; // Reset default browser styles

  &:focus {
    outline: none; // Remove default outline
    border-color: var(--color-border-input-focus); // Use focus border color var
    // Use the global focus ring variable defined in _base.scss
    // Box-shadow will be applied by the global *:focus-visible rule
  }

  &::placeholder {
    color: var(--color-text-placeholder);
    opacity: 1; // Ensure placeholder is visible
  }

  &:disabled {
    // Use a slightly different background for disabled state
    background-color: var(--color-bg-tertiary);
    color: var(--color-text-tertiary); // Use less prominent text color
    cursor: not-allowed;
    opacity: 0.7; // Make it slightly faded
    border-color: var(--color-border-secondary); // Use less prominent border
  }

  // --- Variants based on icon/toggle ---
  &--withIcon {
    padding-left: $spacing-xl + $spacing-xs; // More space for icon: 32px + 4px = 36px
  }

  &--withToggle {
    padding-right: $spacing-xl + $spacing-xs; // Make space for toggle button
  }
}

// --- Icon Styling ---
.iconWrapper {
  position: absolute;
  left: $spacing-md;
  top: 0; // Align top
  bottom: 0; // Align bottom
  display: flex;
  align-items: center;
  color: var(--color-text-tertiary); // Use muted color for icon
  pointer-events: none;

  svg {
    width: 18px;
    height: 18px;
  }
}

// --- Password Visibility Toggle ---
.toggleVisibility {
  position: absolute;
  right: $spacing-sm; // Closer to the edge
  top: 0;
  bottom: 0;
  display: flex;
  align-items: center;
  justify-content: center;
  background: none;
  border: none;
  padding: 0 $spacing-sm; // Add some clickable padding
  cursor: pointer;
  color: var(--color-text-secondary);
  transition: color 0.2s ease;

  &:hover, &:focus {
    color: var(--color-primary); // Highlight on hover/focus
  }

  // Focus handled globally, no extra outline needed here

  svg {
    width: 18px;
    height: 18px;
  }
}

// --- Error State ---
.inputContainer--error {
  // Change label color
  .label {
    color: var(--color-error);
  }

  // Change input border
  .input {
    border-color: var(--color-error);

    // Override focus style for error state
    &:focus {
      border-color: var(--color-error-dark); // Keep border red on focus
      // Adjust focus ring color for error state
      box-shadow: 0 0 0 3px rgba(var(--color-error-raw), 0.3);
    }
  }

  // Change icon/toggle color
  .iconWrapper, .toggleVisibility {
    color: var(--color-error);
  }
}

// --- Error Message Styling ---
.errorMessage {
  // Position absolutely below the input or use margin
  margin-top: $spacing-xs;
  // position: absolute;
  // top: 100%;
  // left: 0;
  // padding-top: $spacing-xs;

  color: var(--color-error);
  font-size: $font-size-sm;
  // Optional: Add animation for appearance
}
```

---

### components\common\Input\Input.tsx

```typescript
// src/components/common/Input/Input.tsx
import React, { useState } from 'react';
import styles from './Input.module.scss';
import { InputProps } from '../../../types'; // Ensure path is correct
import { FiEye, FiEyeOff } from 'react-icons/fi'; // Assuming still using Feather Icons

const Input: React.FC<InputProps> = ({
    label,
    id,
    type = 'text',
    error,
    icon,
    canToggleVisibility = false,
    containerClassName = '',
    inputClassName = '', // Changed from className to inputClassName for clarity
    ...props
}) => {
    const [isPasswordVisible, setIsPasswordVisible] = useState(false);
    // Generate ID if not provided, using a simple approach
    const inputId = id || (label ? label.toLowerCase().replace(/\s+/g, '-') : undefined);

    const containerClasses = [
        styles.inputContainer,
        error ? styles['inputContainer--error'] : '',
        containerClassName,
    ].filter(Boolean).join(' ');

    const inputClasses = [
        styles.input,
        icon ? styles['input--withIcon'] : '',
        (type === 'password' && canToggleVisibility) ? styles['input--withToggle'] : '',
        inputClassName, // Use inputClassName for the input element
    ].filter(Boolean).join(' ');

    // Determine actual input type based on visibility state
    const actualType = type === 'password' && isPasswordVisible ? 'text' : type;

    // Toggle password visibility handler
    const togglePasswordVisibility = () => {
        setIsPasswordVisible(prevState => !prevState);
    };

    return (
        <div className={containerClasses}>
            {label && (
                <label htmlFor={inputId} className={styles.label}>
                    {label}
                </label>
            )}
            <div className={styles.inputWrapper}>
                {icon && <span className={styles.iconWrapper}>{icon}</span>}
                <input
                    id={inputId}
                    type={actualType}
                    className={inputClasses}
                    aria-invalid={!!error} // Accessibility: Mark input as invalid if error exists
                    aria-describedby={error ? `${inputId}-error` : undefined} // Link error message
                    {...props} // Spread remaining props like value, onChange, placeholder, disabled etc.
                />
                {/* Render visibility toggle only if type is password and canToggleVisibility is true */}
                {type === 'password' && canToggleVisibility && (
                    <button
                        type="button"
                        className={styles.toggleVisibility}
                        onClick={togglePasswordVisibility}
                        aria-label={isPasswordVisible ? "Hide password" : "Show password"}
                        tabIndex={-1} // Optional: prevents tab focus on the button, keeping focus flow on input
                    >
                        {isPasswordVisible ? <FiEyeOff /> : <FiEye />}
                    </button>
                )}
            </div>
            {error && (
                <p id={`${inputId}-error`} className={styles.errorMessage} role="alert">
                    {error}
                </p>
            )}
        </div>
    );
};

export default Input;
```

---

## components\common\LoadingSpinner


### components\common\LoadingSpinner\LoadingSpinner.module.scss

```scss
// src/components/common/LoadingSpinner/LoadingSpinner.module.scss
@import '../../../styles/variables'; // SCSS variables for sizes

.spinnerContainer {
  // Optional container if you need to position the spinner specifically
  // within another element, e.g., centering in a button
  display: inline-flex; // Or 'flex' if it's a block-level spinner overlay
  align-items: center;
  justify-content: center;
}

.spinner {
  display: inline-block; // Keep it inline by default
  border-style: solid;
  border-radius: 50%;
  animation: spinner-spin 0.75s linear infinite;

  // Use CSS variable for the main spinner color
  // Use !important only if absolutely necessary to override specific styles,
  // usually better to manage specificity. Using it here as per original for the clear segment.
  border-color: var(--color-primary); // Main color from theme
  border-right-color: transparent !important; // Spinner effect segment

  // Theme-specific adjustments if needed (e.g., darker spinner on light theme?)
  // .light-theme & { border-color: var(--color-primary-dark); border-right-color: transparent !important; }
  // .dark-theme & { border-color: var(--color-primary); border-right-color: transparent !important; }
}

// --- Sizes ---
.spinner--small {
  width: 16px;
  height: 16px;
  border-width: 2px;
}

.spinner--medium {
  // Default size
  width: 28px;
  height: 28px;
  border-width: 3px;
}

.spinner--large {
  width: 40px;
  height: 40px;
  border-width: 4px;
}

// --- Animation ---
@keyframes spinner-spin {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}

// --- Accessibility ---
.visuallyHidden {
  border: 0;
  clip: rect(0 0 0 0);
  height: 1px;
  margin: -1px;
  overflow: hidden;
  padding: 0;
  position: absolute;
  width: 1px;
  white-space: nowrap;
}
```

---

### components\common\LoadingSpinner\LoadingSpinner.tsx

```typescript
// src/components/common/LoadingSpinner/LoadingSpinner.tsx
import React from 'react';
import styles from './LoadingSpinner.module.scss';

interface LoadingSpinnerProps {
  size?: 'small' | 'medium' | 'large';
  className?: string; // Class for the spinner element itself
  containerClassName?: string; // Class for the optional outer container
  'aria-label'?: string; // Allow custom accessible label
}

const LoadingSpinner: React.FC<LoadingSpinnerProps> = ({
  size = 'medium',
  className = '',
  containerClassName = '',
  'aria-label': ariaLabel = 'Loading...', // Default accessible label
}) => {
  const spinnerClasses = [
    styles.spinner,
    styles[`spinner--${size}`],
    className,
  ].filter(Boolean).join(' ');

  const containerClasses = [
    styles.spinnerContainer,
    containerClassName
  ].filter(Boolean).join(' ');

  return (
    // Using a simple span container here, adjust if block is needed
    <span className={containerClasses}>
      <span
        className={spinnerClasses}
        role="status" // Indicates dynamic content change
        aria-live="polite" // Announce changes when idle
        aria-label={ariaLabel} // Use the passed or default label
      >
        {/* Visually hidden text fallback - some screen readers might prefer */}
        <span className={styles.visuallyHidden}>{ariaLabel}</span>
      </span>
    </span>
  );
};

export default LoadingSpinner;
```

---

## components\common\PaymentModal


### components\common\PaymentModal\PaymentModal.module.scss

```scss
// src/components/common/PaymentModal/PaymentModal.module.scss
@import '../../../styles/variables'; // Use SCSS variables for structure

// --- Backdrop ---
.modalBackdrop {
    position: fixed;
    inset: 0;
    background-color: rgba(0, 0, 0, 0.65); // Consistent backdrop opacity
    display: flex;
    align-items: center; // Center vertically
    justify-content: center; // Center horizontally
    z-index: $z-index-modal-backdrop; // Use variable
    padding: $spacing-md;
    overflow-y: auto; // Allow backdrop scroll if modal is tall
    backdrop-filter: blur(3px); // Consistent blur effect
    // Animation handled by Framer Motion in the component now
}

// --- Modal Content ---
.modalContent {
    background-color: var(--color-bg-primary); // Use primary bg
    border-radius: $border-radius-lg; // Consistent large radius
    box-shadow: var(--shadow-lg); // Use theme shadow
    border: $border-width-base solid var(--color-border-primary);
    width: 100%;
    max-width: 600px; // Adjust max width if needed
    display: flex;
    flex-direction: column;
    max-height: 90vh; // Limit height
    overflow: hidden; // Prevents content breaking radius
     // Animation handled by Framer Motion in the component now
}

// --- Modal Header ---
.modalHeader {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: $spacing-md $spacing-lg;
    border-bottom: $border-width-base solid var(--color-border-primary);
    flex-shrink: 0;

    h3 {
        margin: 0;
        font-size: $font-size-h4; // Header size
        font-weight: 600;
        color: var(--color-primary); // Use primary color for title
    }
    .closeButton { // Consistent close button style
        background: none; border: none; font-size: 1.8rem; line-height: 1;
        color: var(--color-text-tertiary); cursor: pointer; padding: $spacing-xs;
        border-radius: 50%; transition: color 0.2s ease, background-color 0.2s ease;
        &:hover { color: var(--color-text-secondary); background-color: var(--color-bg-tertiary); }
    }
}

// --- Modal Body ---
.modalBody {
    padding: $spacing-lg;
    overflow-y: auto; // Allow body scroll
    text-align: center; // Center align content
    color: var(--color-text-primary); // Default text color

    p { // Standard paragraph styling
        margin-bottom: $spacing-md;
        line-height: $line-height-base;
        font-size: $font-size-base;
    }
}

.paymentAmount {
    font-size: 1.3rem; // Slightly larger
    margin-bottom: $spacing-sm; // Less space below amount

    strong { 
        font-size: 1.8rem; 
        font-weight: 700;
        color: var(--color-primary); // Highlight amount color
    }
}

.scanInstructions {
    font-size: $font-size-sm;
    color: var(--color-text-secondary);
    margin-bottom: $spacing-lg;
}

.qrContainer {
    margin-bottom: $spacing-lg;
    display: inline-block; // Keep inline-block for centering
}

.qrCode {
    padding: $spacing-lg; // More padding around QR
    background-color: #ffffff; // Ensure white background for QR contrast
    border: 1px solid var(--color-border-secondary); // Subtle border
    border-radius: $border-radius-md;
    display: inline-flex; // To correctly size around canvas
    box-shadow: var(--shadow-md); // Make it pop a bit
    // QR code canvas styling handled by the component props mostly
}

// --- Important Instructions Refinements ---
.importantInstructions {
  margin-top: $spacing-xl;
  background-color: var(--color-bg-secondary); // Use secondary bg for contrast
  border: 1px solid var(--color-border-primary); // Subtle border
  padding: $spacing-lg;
  border-radius: $border-radius-md;
  text-align: left;

  h4 {
    display: flex;
    align-items: center;
    gap: $spacing-sm;
    font-size: $font-size-base;
    font-weight: 600;
    color: var(--color-warning-dark); // Warning color for heading
    margin: 0 0 $spacing-sm 0;
    svg { color: var(--color-warning); } // Icon color
  }
  
  ol {
    padding-left: $spacing-md; // Standard list indent
    margin-left: 0;
    margin-bottom: 0;
    list-style: none; // Remove default numbering, use custom
    counter-reset: instruction-counter;
  }
  
  li {
    font-size: $font-size-sm;
    color: var(--color-text-primary); // Use primary text for better readability
    margin-bottom: $spacing-md; // More space between steps
    line-height: 1.6;
    position: relative;
    padding-left: $spacing-lg + $spacing-xs; // Space for custom counter

    &::before { // Custom step counter
        counter-increment: instruction-counter;
        content: counter(instruction-counter);
        position: absolute;
        left: 0;
        top: 1px; // Align with text
        background-color: var(--color-warning); // Counter bg
        color: var(--color-text-inverse); // Counter text
        font-weight: 700;
        width: 24px;
        height: 24px;
        border-radius: 50%;
        display: inline-flex;
        align-items: center;
        justify-content: center;
        font-size: 0.8em;
    }

    strong { // Label for the step
      font-weight: 600;
      color: var(--color-text-primary);
      margin-right: $spacing-xs;
    }
  }

  // Specific styling for the NOTE box
  .noteBox {
      background-color: var(--color-bg-primary); // Contrast box for the note
      border: 1px dashed var(--color-error); // Error dash to highlight importance
      padding: $spacing-sm $spacing-md;
      margin: $spacing-xs 0 $spacing-sm 0;
      border-radius: $border-radius-sm;
      font-size: $font-size-sm;
      color: var(--color-text-secondary);
  }
  
  .expectedNoteValue { // The actual note code
      display: block; // Make it take full width
      font-family: monospace;
      font-weight: 700;
      font-size: $font-size-base; // Larger for visibility
      color: var(--color-error-dark); // Error color for extreme importance
      background-color: var(--color-error-light);
      padding: $spacing-xs $spacing-sm;
      border-radius: $border-radius-sm;
      margin-top: $spacing-xs;
      text-align: center;
      word-break: break-all; // Break long notes
  }
  
  .noteWarning { // Text below the note box
      display: block;
      font-size: 0.8rem;
      color: var(--color-error-dark);
      font-weight: 500;
  }
  
  .verificationInfo { // Text about verification time
      margin-top: $spacing-md;
      padding-top: $spacing-sm;
      border-top: 1px dashed var(--color-border-secondary);
      font-size: $font-size-sm;
      color: var(--color-text-secondary);
  }
}

// --- Modal Footer ---
.modalFooter {
    padding: $spacing-md $spacing-lg;
    border-top: $border-width-base solid var(--color-border-primary);
    display: flex;
    justify-content: flex-end;
    gap: $spacing-md;
    background-color: var(--color-bg-secondary);
    flex-shrink: 0;
    // Button styling handled by variants
}

// Confirm button specific style if needed
.confirmButton {
    svg { margin-right: $spacing-sm; }
}
```

---

### components\common\PaymentModal\PaymentModal.tsx

```typescript
// src/components/common/PaymentModal/PaymentModal.tsx
import React, { useEffect, useRef } from 'react';
import { QRCodeCanvas } from 'qrcode.react';
import Button from '../Button/Button'; // Adjust path
import styles from './PaymentModal.module.scss'; // Create this SCSS file
import { FiCheck, FiX, FiAlertTriangle, FiDollarSign } from 'react-icons/fi';

interface PaymentModalProps {
    isOpen: boolean;
    onClose: () => void; // Called on Cancel or backdrop click
    onConfirm: () => void; // Called when "I've Paid" is clicked
    tierName: string;
    amount: number;
    upiUrl: string;
    expectedNote: string;
}

const PaymentModal: React.FC<PaymentModalProps> = ({
    isOpen,
    onClose,
    onConfirm,
    tierName,
    amount,
    upiUrl,
    expectedNote,
}) => {
    const modalContentRef = useRef<HTMLDivElement>(null);

    // Close modal on Escape key
    useEffect(() => {
        const handleKeyDown = (event: KeyboardEvent) => {
            if (event.key === 'Escape') {
                onClose();
            }
        };
        if (isOpen) {
            document.addEventListener('keydown', handleKeyDown);
        }
        return () => {
            document.removeEventListener('keydown', handleKeyDown);
        };
    }, [isOpen, onClose]);

    if (!isOpen) return null;

    return (
        <div className={styles.modalBackdrop} onClick={onClose}>
            <div className={styles.modalContent} ref={modalContentRef} onClick={(e) => e.stopPropagation()}>
                <div className={styles.modalHeader}>
                    <h3><FiDollarSign style={{marginRight: '8px'}}/> Unlock {tierName}</h3>
                    <button onClick={onClose} className={styles.closeButton}>×</button>
                </div>

                <div className={styles.modalBody}>
                    <p className={styles.paymentAmount}>Please Pay <strong>₹{amount}</strong></p>
                    <p className={styles.scanInstructions}>
                        Use any UPI app (GPay, PhonePe, Paytm, etc.) to scan the QR code below.
                    </p>

                    <div className={styles.qrContainer}>
                        <div className={styles.qrCode}>
                            <QRCodeCanvas
                                value={upiUrl}
                                size={260} // Increased size for better scannability
                                level={"H"} // Higher error correction level
                                includeMargin={true}
                                bgColor={"#ffffff"}
                                fgColor={"#000000"}
                             />
                        </div>
                    </div>

                    <div className={styles.importantInstructions}>
                        <h4><FiAlertTriangle /> Important Payment Steps:</h4>
                        <ol>
                             <li>
                                <strong>1. Scan:</strong> Open your UPI app and scan the QR code above.
                             </li>
                             <li>
                                <strong>2. Verify Amount:</strong> Ensure the amount shown is <strong>₹{amount}</strong>.
                             </li>
                            <li>
                                <strong>3. CRITICAL - Check Note/Remark:</strong>
                                <div className={styles.noteBox}>
                                    The transaction note/remarks in your UPI app MUST be exactly:
                                    <code className={styles.expectedNoteValue}>{expectedNote}</code>
                                </div>
                                <span className={styles.noteWarning}>Do NOT change this note, or your payment cannot be verified automatically.</span>
                            </li>
                            <li>
                                <strong>4. Pay:</strong> Complete the payment in your UPI app.
                            </li>
                            <li>
                                <strong>5. Confirm Here:</strong> After successful payment, return to this page and click "I've Made the Payment" below.
                            </li>
                        </ol>
                        <p className={styles.verificationInfo}>
                            Perk activation is subject to payment verification (usually a few minutes to a couple of hours).
                        </p>
                    </div>
                </div>

                <div className={styles.modalFooter}>
                     <Button variant="secondary" onClick={onClose}><FiX /> Cancel Payment</Button>
                     <Button variant="primary" onClick={onConfirm} className={styles.confirmButton}>
                       <FiCheck /> I've Made the Payment
                     </Button>
                </div>
            </div>
        </div>
    );
};

export default PaymentModal;
```

---

## components\common\Textarea


### components\common\Textarea\Textarea.module.scss

```scss
// src/components/common/Textarea/Textarea.module.scss
@use 'sass:color'; // Use sass color module for adjustments
@import '../../../styles/variables';

.textareaContainer {
  margin-bottom: $spacing-lg;
  width: 100%;
  position: relative;
}

.label {
  // Identical to Input label style
  display: block;
  margin-bottom: $spacing-sm;
  font-weight: 500;
  font-size: $font-size-sm;
  color: var(--color-text-secondary);
  cursor: default;
}

.textareaWrapper {
  // Simpler wrapper, no icons typically
  position: relative;
}

.textarea {
  // --- Base Styles (Similar to Input) ---
  width: 100%;
  padding: $spacing-sm $spacing-md;
  border: $border-width-base solid var(--color-border-input);
  border-radius: $border-radius-md;
  font-size: $font-size-base;
  line-height: $line-height-base; // Textarea often benefits from slightly more line height
  background-color: var(--color-bg-primary);
  color: var(--color-text-primary);
  transition: border-color 0.2s ease-in-out, box-shadow 0.15s ease-in-out;
  resize: vertical; // Allow only vertical resizing
  min-height: 100px; // Set a reasonable min height
  appearance: none;

  &:focus {
    outline: none;
    border-color: var(--color-border-input-focus);
    // Focus ring applied globally
  }

  &::placeholder {
    color: var(--color-text-placeholder);
    opacity: 1;
  }

  &:disabled {
    background-color: var(--color-bg-tertiary);
    color: var(--color-text-tertiary);
    cursor: not-allowed;
    opacity: 0.7;
    border-color: var(--color-border-secondary);
    resize: none; // Disable resize when disabled
  }
}

// --- Error State ---
.textareaContainer--error {
  // Change label color
  .label {
    color: var(--color-error);
  }

  // Change textarea border
  .textarea {
    border-color: var(--color-error);

    &:focus {
      border-color: var(--color-error-dark);
      box-shadow: 0 0 0 3px rgba(var(--color-error-raw), 0.3);
    }
  }
}

// --- Error Message Styling ---
.errorMessage {
  // Identical to Input error message style
  margin-top: $spacing-xs;
  color: var(--color-error);
  font-size: $font-size-sm;
}
```

---

### components\common\Textarea\Textarea.tsx

```typescript
// src/components/common/Textarea/Textarea.tsx
import React from 'react';
import styles from './Textarea.module.scss'; // Ensure path is correct
import { TextareaProps } from '../../../types'; // Ensure path is correct

const Textarea: React.FC<TextareaProps> = ({
    label,
    id,
    error,
    containerClassName = '',
    textareaClassName = '', // Changed from className to textareaClassName for clarity
    rows = 4, // Default number of rows
    ...props
}) => {
    // Generate ID if not provided
    const textareaId = id || (label ? label.toLowerCase().replace(/\s+/g, '-') : undefined);

    const containerClasses = [
        styles.textareaContainer,
        error ? styles['textareaContainer--error'] : '',
        containerClassName,
    ].filter(Boolean).join(' ');

    const textareaClasses = [
        styles.textarea,
        textareaClassName, // Use textareaClassName for the textarea element
    ].filter(Boolean).join(' ');

    return (
        <div className={containerClasses}>
            {label && (
                <label htmlFor={textareaId} className={styles.label}>
                    {label}
                </label>
            )}
            <div className={styles.textareaWrapper}>
                <textarea
                    id={textareaId}
                    rows={rows}
                    className={textareaClasses}
                    aria-invalid={!!error} // Accessibility
                    aria-describedby={error ? `${textareaId}-error` : undefined}
                    {...props} // Spread remaining props like value, onChange, placeholder, disabled etc.
                />
            </div>
            {error && (
                <p id={`${textareaId}-error`} className={styles.errorMessage} role="alert">
                    {error}
                </p>
            )}
        </div>
    );
};

export default Textarea;
```

---

## components\common\Toast


### components\common\Toast\index.ts

```typescript
// src/components/common/Toast/index.ts
export { ToastProvider } from './ToastProvider';
export { useToast } from './useToast';
```

---

### components\common\Toast\Toast.module.scss

```scss
// src/components/common/Toast/Toast.module.scss
@import '../../../styles/variables'; // SCSS variables for structure/layout

.toastContainer {
  position: fixed;
  // Position top-right is common, adjust as needed
  top: $spacing-lg;
  right: $spacing-lg;
  // Add bottom/left positioning options if required later
  z-index: $z-index-toast;
  display: flex;
  flex-direction: column;
  align-items: flex-end; // Align toasts to the right
  gap: $spacing-md;    // Space between toasts
  max-width: calc(100vw - #{$spacing-lg * 2}); // Prevent overflow on small screens
}

.toast {
  display: flex;
  align-items: flex-start; // Align icon top-left with text block
  padding: $spacing-md;
  border-radius: $border-radius-md; // Use consistent radius
  box-shadow: var(--shadow-lg); // Use theme shadow
  color: var(--color-text-primary); // Use theme text color
  background-color: var(--color-bg-secondary); // Use theme background
  border-left: 4px solid transparent; // Thick border for status indication
  min-width: 300px;
  max-width: 450px;
  font-size: $font-size-sm;
  line-height: 1.5;
  position: relative; // For positioning close button inside if needed

  // Animation (Example fade-in, add fade-out if managing exits)
  animation: toast-fade-in 0.3s ease-out forwards;

  .icon {
    flex-shrink: 0;
    margin-right: $spacing-md;
    // Vertical alignment might need slight adjustment depending on icon size/line height
    // margin-top: 2px;
    width: 20px;
    height: 20px;
  }

  .message {
    flex-grow: 1; // Take remaining space
    word-wrap: break-word; // Prevent long words overflowing
  }

  .closeButton {
    background: none;
    border: none;
    color: var(--color-text-tertiary);
    opacity: 0.7;
    margin-left: $spacing-lg; // Space between message and button
    padding: $spacing-xs; // Click target padding
    font-size: 1.3rem; // Adjust size
    line-height: 1;
    cursor: pointer;
    transition: color 0.2s ease, opacity 0.2s ease;
    flex-shrink: 0;

    &:hover {
      opacity: 1;
      color: var(--color-text-secondary);
    }
    &:focus-visible {
        // Use a subtle focus ring for the close button
        outline: none;
        box-shadow: 0 0 0 2px var(--color-primary-light);
        border-radius: $border-radius-sm;
    }
  }

  // --- Type Variations (Using CSS Variables) ---
  &--success {
    border-left-color: var(--color-success);
    .icon { color: var(--color-success); }
    // Optional: Different background/text for emphasis
    // background-color: var(--color-success-light);
    // color: var(--color-success-dark);
  }

  &--error {
    border-left-color: var(--color-error);
    .icon { color: var(--color-error); }
    // background-color: var(--color-error-light);
    // color: var(--color-error-dark);
    // .closeButton { color: var(--color-error-dark); } // Match text color
  }

  &--info {
    border-left-color: var(--color-info);
    .icon { color: var(--color-info); }
    // background-color: var(--color-info-light);
    // color: var(--color-info-dark);
  }

  &--warning {
    border-left-color: var(--color-warning);
    .icon { color: var(--color-warning); }
    // background-color: var(--color-warning-light);
    // color: var(--color-warning-dark);
  }
}


// --- Animations ---
@keyframes toast-fade-in {
  from {
    opacity: 0;
    transform: translateX(100%); // Slide in from right
  }
  to {
    opacity: 1;
    transform: translateX(0);
  }
}

// Add fade-out animation class if needed, applied before removal
// .toast--exiting {
//   animation: toast-fade-out 0.3s ease-in forwards;
// }
// @keyframes toast-fade-out {
//   from { opacity: 1; transform: translateX(0); }
//   to { opacity: 0; transform: translateX(100%); }
// }
```

---

### components\common\Toast\ToastMessage.tsx

```typescript
// src/components/common/Toast/ToastMessage.tsx
import React, { useMemo } from 'react';
import { ToastMessageProps, ToastType } from './types'; // Ensure paths are correct
import styles from './Toast.module.scss'; // Ensure path is correct

// Assuming still using Feather Icons
import { FiCheckCircle, FiXCircle, FiInfo, FiAlertTriangle } from 'react-icons/fi';

const ICONS: Record<ToastType, React.ElementType> = {
  success: FiCheckCircle,
  error: FiXCircle,
  info: FiInfo,
  warning: FiAlertTriangle,
};

const ToastMessage: React.FC<ToastMessageProps> = ({ toast, onDismiss }) => {
  const { id, message, type } = toast;
  const Icon = useMemo(() => ICONS[type], [type]); // Memoize icon selection

  // --- Optional: Auto-dismissal and Pause on Hover ---
  // The ToastProvider already handles auto-dismissal via setTimeout.
  // For pause on hover, you'd need to clear/reset the timer in the Provider.
  // We'll keep it simple for now and rely on the Provider's timer.
  // const toastRef = useRef<HTMLDivElement>(null);
  // const timerRef = useRef<NodeJS.Timeout | null>(null);
  //
  // useEffect(() => {
  //   // Clear timer logic would interact with ToastProvider state/refs
  //   // This example assumes timer logic is solely in Provider
  //   return () => {
  //     // if (timerRef.current) clearTimeout(timerRef.current); // Cleanup local timer if used
  //   };
  // }, [id, duration, onDismiss]);
  //
  // const handleMouseEnter = () => { /* Signal Provider to pause timer for 'id' */ };
  // const handleMouseLeave = () => { /* Signal Provider to resume timer for 'id' */ };
  // --- End Optional Pause Logic ---

  const handleDismiss = () => {
    // Optional: Add exit animation class before calling onDismiss
    // const element = toastRef.current;
    // if (element) {
    //   element.classList.add(styles['toast--exiting']);
    //   element.addEventListener('animationend', () => onDismiss(id), { once: true });
    // } else {
    //   onDismiss(id); // Fallback if ref fails
    // }
    onDismiss(id); // Simple dismissal for now
  };


  const toastClasses = `${styles.toast} ${styles[`toast--${type}`]}`;
  const iconClasses = styles.icon;

  return (
    <div
      // ref={toastRef} // Uncomment if managing exit animations here
      className={toastClasses}
      role="alert" // Use alert for errors, status for others? Polite is usually fine.
      aria-live={type === 'error' ? 'assertive' : 'polite'}
      // onMouseEnter={handleMouseEnter} // Uncomment for pause on hover
      // onMouseLeave={handleMouseLeave} // Uncomment for pause on hover
    >
      {/* Icon */}
      <Icon className={iconClasses} aria-hidden="true" />

      {/* Message Content */}
      <span className={styles.message}>{message}</span>

      {/* Close Button */}
      <button
        className={styles.closeButton}
        onClick={handleDismiss}
        aria-label="Dismiss notification" // More descriptive label
      >
        × {/* Use HTML entity for 'x' */}
      </button>
    </div>
  );
};

export default ToastMessage;
```

---

### components\common\Toast\ToastProvider.tsx

```typescript
// src/components/common/Toast/ToastProvider.tsx
import React, { createContext, useState, useCallback, ReactNode, useRef, useEffect } from 'react';
import ReactDOM from 'react-dom';
import { Toast, ToastContextType, ToastType } from './types';
import ToastMessage from './ToastMessage';
import styles from './Toast.module.scss';

const DEFAULT_DURATION = 6000; // Slightly longer default duration

const ToastContext = createContext<ToastContextType | undefined>(undefined);

// Ensure the portal root exists
const portalRootId = 'toast-portal';
let portalRoot = document.getElementById(portalRootId);
if (!portalRoot) {
    portalRoot = document.createElement('div');
    portalRoot.id = portalRootId;
    document.body.appendChild(portalRoot);
}


export const ToastProvider: React.FC<{ children: ReactNode }> = ({ children }) => {
  const [toasts, setToasts] = useState<Toast[]>([]);
  const timersRef = useRef<Record<string, NodeJS.Timeout>>({});

  const removeToast = useCallback((id: string) => {
    // Clear the timer associated with this toast ID
    if (timersRef.current[id]) {
      clearTimeout(timersRef.current[id]);
      delete timersRef.current[id];
    }
    // Remove the toast from state (Consider exit animation state management here if added)
    setToasts((prevToasts) => prevToasts.filter((toast) => toast.id !== id));
  }, []);

  const addToast = useCallback(
    (message: string | React.ReactNode, type: ToastType, duration: number = DEFAULT_DURATION) => {
      const id = crypto.randomUUID ? crypto.randomUUID() : String(Date.now() + Math.random()); // Fallback ID

      // Avoid adding duplicate messages very close together (optional)
      // const isDuplicate = toasts.some(t => t.message === message && t.type === type);
      // if(isDuplicate) return;

      const newToast: Toast = { id, message, type, duration };
      setToasts((prevToasts) => [...prevToasts, newToast]);

      // Set a timer to automatically remove the toast
      const timerId = setTimeout(() => {
        removeToast(id);
      }, duration);

      timersRef.current[id] = timerId;
    },
    [removeToast] // Added toasts to dependency array for duplicate check (if implemented)
  );

  // Effect to clean up all timers on unmount
  useEffect(() => {
    const timers = timersRef.current;
    return () => {
      Object.values(timers).forEach(clearTimeout);
    };
  }, []);

  return (
    <ToastContext.Provider value={{ addToast }}>
      {children}
      {/* Render the Toast Container via a Portal */}
       {portalRoot && ReactDOM.createPortal( // Check if portalRoot exists
           <div
             className={styles.toastContainer}
             aria-live="polite" // Announce additions politely
             aria-relevant="additions" // Announce only additions
             aria-atomic="false" // Announce whole container changes? Usually false is ok.
           >
              {toasts.map((toast) => (
                  <ToastMessage key={toast.id} toast={toast} onDismiss={removeToast} />
              ))}
           </div>,
           portalRoot // Target the portal element
       )}
    </ToastContext.Provider>
  );
};

export { ToastContext }; // Export context for useToast hook
```

---

### components\common\Toast\types.ts

```typescript
// src/components/common/Toast/types.ts

export type ToastType = 'success' | 'error' | 'info' | 'warning';

export interface Toast {
  id: string;
  message: string | React.ReactNode; // Allow ReactNode for richer content
  type: ToastType;
  duration?: number; // Optional duration in milliseconds
  // Add optional action buttons later if needed
  // actions?: Array<{ label: string; onClick: () => void }>;
}

export interface ToastContextType {
  addToast: (message: string | React.ReactNode, type: ToastType, duration?: number) => void;
}

export interface ToastMessageProps {
    toast: Toast;
    onDismiss: (id: string) => void;
}
```

---

### components\common\Toast\useToast.ts

```typescript
// src/components/common/Toast/useToast.ts
import { useContext } from 'react';
import { ToastContext } from './ToastProvider'; // Import context itself
import { ToastContextType } from './types';

export const useToast = (): ToastContextType => {
  const context = useContext(ToastContext);
  if (context === undefined) {
    // This error is crucial for ensuring the hook is used correctly
    throw new Error('useToast must be used within a ToastProvider');
  }
  return context;
};
```

---

## components\contact


## components\contact\ContactForm


### components\contact\ContactForm\ContactForm.module.scss

```scss

```

---

### components\contact\ContactForm\ContactForm.tsx

```typescript
// src/components/contact/ContactForm/ContactForm.tsx
import React, { useState, useEffect, FormEvent } from 'react';
import { useSearchParams } from 'react-router-dom';
import { useAuth } from '../../../hooks/useAuth';
import { useToast } from '../../common/Toast';
import { submitContactForm } from '../../../services/firebase'; // We'll create this
import Input from '../../common/Input/Input';
import Textarea from '../../common/Textarea/Textarea'; // Use the new Textarea
import Button from '../../common/Button/Button';
import AuthFormContainer from '../../auth/AuthFormContainer/AuthFormContainer'; // Reuse container style
import { validateContactForm, ContactFormErrors } from '../../../utils/validators'; // We'll add validation
import { ContactFormData } from '../../../types';
import { FiUser, FiMail, FiInfo } from 'react-icons/fi';

const initialFormData: ContactFormData = {
    name: '',
    email: '',
    subject: '',
    message: '',
};

const ContactForm: React.FC = () => {
    const [formData, setFormData] = useState<ContactFormData>(initialFormData);
    const [errors, setErrors] = useState<ContactFormErrors>({});
    const [loading, setLoading] = useState(false);
    const [successMessage, setSuccessMessage] = useState<string | null>(null);

    const { currentUser, userData } = useAuth();
    const { addToast } = useToast();
    const [searchParams] = useSearchParams();

    // Effect to pre-fill from URL parameters ONCE on mount
    useEffect(() => {
        const subjectParam = searchParams.get('subject');
        const messageParam = searchParams.get('message');

        setFormData(prev => ({
            ...prev,
            subject: subjectParam || prev.subject,
            message: messageParam || prev.message,
        }));
        // We only want to run this logic once based on initial URL params
        // eslint-disable-next-line react-hooks/exhaustive-deps
    }, []); // Empty dependency array means run once

    // Effect to pre-fill user details from Auth context
    useEffect(() => {
        if (userData) {
            // Only pre-fill if the fields are currently empty (don't override typed values)
            setFormData(prev => ({
                ...prev,
                name: prev.name || userData.displayName || userData.username || '',
                email: prev.email || userData.email || '',
            }));
        }
    }, [userData]); // Run when userData loads/changes


    const handleChange = (e: React.ChangeEvent<HTMLInputElement | HTMLTextAreaElement>) => {
        const { name, value } = e.target;
        setFormData(prev => ({ ...prev, [name]: value }));

        // Clear specific error on change
        if (errors[name as keyof ContactFormErrors]) {
            setErrors(prev => ({ ...prev, [name]: undefined }));
        }
        // Clear general/success messages on any change
        if (errors.general) setErrors(prev => ({ ...prev, general: undefined }));
        if (successMessage) setSuccessMessage(null);
    };

    const handleSubmit = async (e: FormEvent) => {
        e.preventDefault();
        setErrors({});
        setSuccessMessage(null);

        if (!currentUser) {
             addToast("You must be logged in to submit the form.", "error");
             setErrors({ general: "Authentication required." });
            return;
        }

        const validationErrors = validateContactForm(
            formData.name,
            formData.email,
            formData.subject,
            formData.message
        );

        if (Object.keys(validationErrors).length > 0) {
            setErrors(validationErrors);
            return;
        }

        setLoading(true);
        try {
            // Prepare data structure for Firestore (match isValidContactSubmission rules)
            const submissionData = {
                userId: currentUser.uid, // CRITICAL: Use auth UID
                userName: formData.name.trim(),
                userEmail: formData.email.trim(),
                subject: formData.subject.trim(),
                message: formData.message.trim(),
                // submittedAt is handled by serverTimestamp in the service function
            };

            await submitContactForm(submissionData);

            setSuccessMessage('Your message has been sent successfully! We will get back to you soon.');
            addToast('Message Sent!', 'success');
            setFormData(initialFormData); // Reset form
            // Optionally pre-fill user details again after reset
             if (userData) {
                 setFormData(prev => ({
                    ...prev,
                    name: userData.displayName || userData.username || '',
                    email: userData.email || '',
                 }));
             }


        } catch (error: any) {
           //console.error("Contact form submission failed:", error);
            addToast(`Failed to send message: ${error.message}`, 'error');
            setErrors({ general: error.message || 'An unexpected error occurred. Please try again.' });
        } finally {
            setLoading(false);
        }
    };

    return (
        // Reusing AuthFormContainer styling/structure, adjust title/subtitle
         <AuthFormContainer
            title="Contact Us"
            subtitle="Have questions or feedback? Send us a message."
         >
             <form onSubmit={handleSubmit} noValidate>
                {errors.general && <p className="alert alert-error">{errors.general}</p>}
                {successMessage && <p className="alert alert-success">{successMessage}</p>}

                <Input
                    label="Your Name"
                    type="text"
                    id="name"
                    name="name"
                    value={formData.name}
                    onChange={handleChange} // Keep onChange in case you revert
                    error={errors.name}
                    // Disable if loading OR if the form has been successfully pre-filled from userData
                    disabled={loading || (!!userData && !!formData.name)}
                    icon={<FiUser />}
                    required
                    autoComplete="name"
                    readOnly={!!userData && !!formData.name} // Makes it clear it's not meant to be edited
                    style={ (!!userData && !!formData.name) ? { backgroundColor: '#eee' } : {} } // Visual cue
                />

                <Input
                    label="Your Email"
                    type="email"
                    id="email"
                    name="email"
                    value={formData.email}
                    onChange={handleChange}
                    error={errors.email}
                    // Disable if loading OR if the form has been successfully pre-filled from userData
                    disabled={loading || (!!userData && !!formData.email)}
                    icon={<FiMail />}
                    required
                    autoComplete="email"
                    readOnly={!!userData && !!formData.email} // Add readOnly
                    style={ (!!userData && !!formData.email) ? { backgroundColor: '#eee' } : {} } // Visual cue
                />

                <Input
                    label="Subject"
                    type="text"
                    id="subject"
                    name="subject"
                    value={formData.subject}
                    onChange={handleChange}
                    error={errors.subject}
                    disabled={loading}
                    icon={<FiInfo />}
                    required
                    maxLength={150} // Match rule limit
                />

                <Textarea
                    label="Message"
                    id="message"
                    name="message"
                    value={formData.message}
                    onChange={handleChange}
                    error={errors.message}
                    disabled={loading}
                    rows={6}
                    required
                    maxLength={2000} // Match rule limit
                />

                <Button
                    type="submit"
                    variant="primary"
                    size="large"
                    fullWidth
                    loading={loading}
                    disabled={loading}
                    style={{ marginTop: '1rem' }}
                >
                    Send Message
                </Button>

             </form>
        </AuthFormContainer>
    );
};

export default ContactForm;
```

---

## components\dashboard


## components\dashboard\Dashboard


### components\dashboard\Dashboard\Dashboard.module.scss

```scss
// src/components/dashboard/Dashboard/Dashboard.module.scss
@import '../../../styles/variables'; // SCSS variables

//.dashboard {
  // No specific container styles needed if page applies .container
//}

// --- Header / Titles ---
.title {
  // Use h1 styles from _base.scss
  font-size: $font-size-h2; // Maybe slightly smaller than page title h1
  color: var(--color-text-primary);
  margin-bottom: $spacing-sm;
}

.subtitle {
  font-size: $font-size-lg;
  color: var(--color-text-secondary);
  margin-bottom: $spacing-xl;
  max-width: 600px; // Limit subtitle width for readability
}

// --- Service Grid ---
.serviceGrid {
  display: grid;
  // Use auto-fill with minmax for responsive columns
  grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
  gap: $spacing-lg; // Gap between cards
}

// --- States (Loading, Error, Empty) ---
.loadingContainer,
.errorContainer,
.noServicesContainer {
  display: flex;
  flex-direction: column; // Stack icon/spinner and text
  justify-content: center;
  align-items: center;
  min-height: 400px; // Ensure sufficient height for visual centering
  width: 100%;
  padding: $spacing-xl;
  text-align: center;
  border-radius: $border-radius-lg; // Rounded container for states
  background-color: var(--color-bg-secondary); // Use secondary background
  border: $border-width-base dashed var(--color-border-secondary); // Dashed border indicator
}

.loadingContainer {
  // Spinner already styled, just add text
  p {
      margin-top: $spacing-md;
      font-size: $font-size-base;
      color: var(--color-text-secondary);
  }
}

.errorContainer {
    border-color: var(--color-error); // Error border color
    background-color: var(--color-error-light); // Subtle error bg
    color: var(--color-error-dark); // Error text color

    // Add an icon potentially
    // svg { font-size: 3rem; margin-bottom: $spacing-md; }
}

.noServicesContainer {
    // Similar to error/loading, but use info colors perhaps
    border-color: var(--color-info); // Info border color
    background-color: var(--color-info-light); // Subtle info bg
    color: var(--color-info-dark); // Info text color

     // Add icon for empty state
     svg {
        font-size: 3rem; // Large icon
        margin-bottom: $spacing-md;
        color: var(--color-info);
     }

     // Style optional action button
     button {
        margin-top: $spacing-lg;
     }
}


// Removed AddServiceCard styles, as it's not currently used
// Reintroduce if the "Add Service" feature is implemented
```

---

### components\dashboard\Dashboard\Dashboard.tsx

```typescript
// src/components/dashboard/Dashboard/Dashboard.tsx
import React, { useState, useEffect, useMemo } from 'react'; // Import useMemo
import { useAuth } from '../../../hooks/useAuth'; // Adjust path
import ServiceCard from '../ServiceCard/ServiceCard'; // Use redesigned card
import LoadingSpinner from '../../common/LoadingSpinner/LoadingSpinner'; // Adjust path
import { UserService } from '../../../types'; // Adjust path
// Removed useToast as it wasn't used here previously for errors
import styles from './Dashboard.module.scss'; // Adjust path
import { FiGrid, FiAlertCircle} from 'react-icons/fi'; // Icons for states
import { getDefaultServices } from '../../../services/configService';
import Button from '../../common/Button/Button';

const Dashboard: React.FC = () => {
    const { userData } = useAuth();
    // Initialize loading to true only if userData isn't immediately available maybe?
    // Or always show loading briefly for fetching services.
    const [loading, setLoading] = useState(true);
    const [services, setServices] = useState<UserService[]>([]);
    const [error, setError] = useState<string | null>(null);

    // Memoize user name for display
    const displayName = useMemo(() => {
        return userData?.displayName || userData?.username || 'User';
    }, [userData]);

    useEffect(() => {
        let isMounted = true;
        setLoading(true);
        setError(null);

        getDefaultServices() // <<< Use function from configService
            .then(fetchedServices => {
                if (isMounted) {
                    setServices(fetchedServices);
                }
            })
            .catch(fetchError => {
               //console.error("Error fetching default services:", fetchError);
                 if (isMounted) setError("Could not load services. Please try refreshing.");
            })
            .finally(() => {
                if (isMounted) setLoading(false);
            });

        return () => { isMounted = false };
    }, []); // Depends only on user ID change for refetching


    // --- Render Loading State ---
    if (loading) {
        return (
            <div className={styles.loadingContainer}>
                <LoadingSpinner size="large" />
                <p>Loading your dashboard...</p>
            </div>
        );
    }

    // --- Render Error State ---
    if (error) {
        return (
            <div className={styles.errorContainer}>
                 <FiAlertCircle size="3rem" style={{ marginBottom: styles['spacing-md'] }}/>
                 <h4>Oops! Something went wrong.</h4>
                 <p>{error}</p>
                 {/* Optional: Add a retry button */}
                  <Button variant="outline" onClick={() => window.location.reload()}>Retry</Button>
            </div>
        );
    }

    // --- Render Main Dashboard Content ---
    return (
        <div className={styles.dashboard}>
            <h1 className={styles.title}>Dashboard</h1>
            <p className={styles.subtitle}>
                Welcome back, {displayName}! Access your services below.
            </p>

            {services.length === 0 ? (
                // --- Render Empty State ---
                <div className={styles.noServicesContainer}>
                    <FiGrid /> {/* Use a relevant icon */}
                    <h4>No Services Linked Yet</h4>
                    <p>Explore available services or contact support if you expect to see services here.</p>
                    {/* Optional: Button to explore services or docs */}
                    {/* <Button variant="outline">Explore Services</Button> */}
                </div>
            ) : (
                // --- Render Service Grid ---
                <div className={styles.serviceGrid}>
                    {services.map((service) => (
                        <ServiceCard key={service.id} service={service} />
                    ))}
                    {/* Optional: Add a placeholder card for adding more services */}
                </div>
            )}
        </div>
    );
};

export default Dashboard;
```

---

## components\dashboard\ServiceCard


### components\dashboard\ServiceCard\ServiceCard.module.scss

```scss
// src/components/dashboard/ServiceCard/ServiceCard.module.scss
@import '../../../styles/variables'; // SCSS variables for structure

.card {
  // --- Base Card Styles ---
  background-color: var(--color-bg-secondary); // Use secondary background for cards
  border-radius: $border-radius-lg; // Consistent larger radius
  border: $border-width-base solid var(--color-border-primary);
  padding: $spacing-lg;
  display: flex;
  flex-direction: column; // Stack icon -> content -> actions
  text-align: center; // Center content by default
  height: 100%; // Ensure cards in a grid have same height if needed (handled by grid usually)
  transition: transform 0.25s ease-in-out, box-shadow 0.25s ease-in-out, border-color 0.2s ease-in-out;
  cursor: pointer;
  overflow: hidden; // In case of hover effects extending bounds

  &:hover, &:focus-within { // Apply hover styles on focus too for keyboard nav
    transform: translateY(-5px); // Lift effect
    box-shadow: var(--shadow-md); // Use themed shadow
    border-color: var(--color-primary); // Highlight border on hover/focus
  }

  // Ensure focus outline is handled correctly if default is removed elsewhere
  &:focus {
      outline: none; // Use focus-within or ensure focus-visible handles it
  }
   &:focus-visible {
       outline: none;
       // You might want a ring *inside* the card or rely on the border color change
       box-shadow: var(--shadow-md), 0 0 0 2px var(--color-primary-light); // Combine shadow and ring
       border-color: var(--color-primary);
   }
}

// --- Icon ---
.iconWrapper {
  margin-bottom: $spacing-md;
  // Optional: Style a background shape for the icon
  // background-color: var(--color-primary-light);
  // width: 64px;
  // height: 64px;
  // border-radius: 50%;
  // display: inline-flex;
  // align-items: center;
  // justify-content: center;
  // margin-left: auto;
  // margin-right: auto;
}

.icon {
  width: 48px; // Adjust size
  height: 48px;
  object-fit: contain; // Prevent distortion if images are used
  // Optional: If using icon fonts/svg directly
  // font-size: 48px;
  // color: var(--color-primary);
  display: block; // Prevents potential bottom space
  margin-left: auto; // Center the icon img/svg
  margin-right: auto;
}

// --- Content Area ---
.content {
  flex-grow: 1; // Allow content to push actions down
  display: flex; // Use flex to manage internal spacing
  flex-direction: column;
  justify-content: center; // Center content vertically if space allows
}

.title {
  font-size: $font-size-lg; // Card title size
  font-weight: 600; // Bolder title
  margin-bottom: $spacing-xs; // Less space below title
  color: var(--color-text-primary); // Use theme text color
  display: flex; // For aligning icon within title if needed
  align-items: center;
  justify-content: center;
  gap: $spacing-xs;
}

.description {
  font-size: $font-size-sm;
  color: var(--color-text-secondary); // Muted color for description
  line-height: 1.5;
  margin-bottom: $spacing-md; // Space below description
}

// --- External Link Icon ---
.externalIcon {
  font-size: 0.8em; // Smaller than title text
  color: var(--color-text-tertiary); // Even more muted
  opacity: 0.8;
  margin-left: $spacing-xs;
  vertical-align: middle; // Align with text nicely
  flex-shrink: 0; // Prevent shrinking
}

// --- Optional Actions Area ---
// If you add explicit buttons later instead of making the whole card clickable
// .actions {
//    margin-top: auto; // Pushes to bottom
//    padding-top: $spacing-md; // Space above actions
//    border-top: $border-width-base solid var(--color-border-primary); // Separator
//    display: flex;
//    justify-content: center; // Or flex-end
// }
```

---

### components\dashboard\ServiceCard\ServiceCard.tsx

```typescript
// src/components/dashboard/ServiceCard/ServiceCard.tsx
import React, { useCallback } from 'react'; // Import useCallback
import { UserService } from '../../../types'; // Adjust path
import styles from './ServiceCard.module.scss'; // Adjust path
import { FiExternalLink } from 'react-icons/fi'; // Keep Feather
import { logAnalyticsEvent } from '../../../services/firebase'; // Adjust path
import DefaultServiceIcon from './default-icon.svg'; // Create a default SVG icon

interface ServiceCardProps {
  service: UserService;
  className?: string; // Allow passing extra classes
}

const ServiceCard: React.FC<ServiceCardProps> = ({ service, className = '' }) => {

    const getIconPath = useCallback((iconId: string): string => {
        // If iconId is a URL, use it directly
        if (iconId.startsWith('http') || iconId.startsWith('//')) {
            return iconId;
        }
        
        // Keep existing logic for predefined icons
        switch (iconId) {
            case 'blog': return 'https://bcaexamprep.blogspot.com/favicon.ico';
            case 'exam': return 'https://examify.web.app/favicon.ico';
            default: return DefaultServiceIcon; // Use imported default SVG
        }
    }, []); // Empty dependency array - this logic doesn't change

    // Determine if it's an external link
    const isExternal = service.url.startsWith('http') || service.url.startsWith('//');

    const handleClick = useCallback(() => {
         logAnalyticsEvent('select_content', {
            content_type: 'service_card',
            item_id: service.id,
            item_name: service.name,
            is_external: isExternal, // Add context
         });

         if (isExternal) {
             window.open(service.url, '_blank', 'noopener noreferrer');
         } else {
             // Handle internal navigation (assuming React Router context)
             // If navigation needs to be passed down, adjust props
             // For now, log or perhaps do nothing if internal links aren't set up
            //console.warn(`Internal navigation attempt to: ${service.url}. Ensure routing is handled.`);
             // navigate(service.url); // If navigate function is available
         }
    }, [service.id, service.name, service.url, isExternal]); // Dependencies for the click handler

    // Fallback icon handler
    const handleIconError = useCallback((e: React.SyntheticEvent<HTMLImageElement, Event>) => {
        (e.target as HTMLImageElement).src = DefaultServiceIcon; // Set to default SVG on error
    }, []);


    const cardClasses = `${styles.card} ${className}`;

    return (
        // Make the div behave like a link for accessibility and interaction
        <div
            className={cardClasses}
            onClick={handleClick}
            onKeyPress={(e) => (e.key === 'Enter' || e.key === ' ') && handleClick()} // Keyboard activation
            role="link" // Semantically treat as a link
            tabIndex={0} // Make it focusable
            aria-label={`Access ${service.name}`} // Accessible label
        >
            <div className={styles.iconWrapper}>
               <img
                    src={getIconPath(service.icon)}
                    alt="" // Alt text is redundant given the aria-label on the parent
                    aria-hidden="true" // Hide decorative icon from screen readers
                    className={styles.icon}
                    onError={handleIconError} // Handle loading errors
                    loading="lazy" // Lazy load icons if many cards exist
                />
            </div>
            <div className={styles.content}>
                <h3 className={styles.title}>
                    {service.name}
                    {isExternal && (
                        <FiExternalLink
                          className={styles.externalIcon}
                          aria-label="(opens in new tab)" // Accessible label for external link icon
                        />
                    )}
                </h3>
                <p className={styles.description}>{service.description}</p>
            </div>
            {/* Removed explicit action button - entire card is clickable */}
        </div>
    );
};

export default ServiceCard;
```

---

## components\profile


## components\profile\Profile


### components\profile\Profile\Profile.module.scss

```scss
// src/components/profile/Profile/Profile.module.scss
@import '../../../styles/variables'; // SCSS variables for structure/layout

.profileContainer {
  background-color: var(--color-bg-secondary); // Card-like background
  padding: $spacing-xl $spacing-lg;
  border-radius: $border-radius-lg; // Consistent large radius
  border: $border-width-base solid var(--color-border-primary);
  box-shadow: var(--shadow-md);
  max-width: 800px; // Allow slightly wider for profile info
  margin: $spacing-xl auto; // Center container
  transition: background-color 0.2s ease, border-color 0.2s ease;
}

.title {
  text-align: center;
  font-size: $font-size-h2; // Use heading size
  font-weight: 600;
  color: var(--color-primary);
  margin-bottom: $spacing-xl; // More space after title
  padding-bottom: $spacing-sm;
  // Optional: Subtle border under title
  // border-bottom: $border-width-base solid var(--color-border-secondary);
}

// --- Message Area (Top for General Feedback) ---
.message {
  // Reuse alert styles or create specific ones
  padding: $spacing-sm $spacing-md;
  margin-bottom: $spacing-lg;
  border-radius: $border-radius-md;
  font-size: $font-size-sm;
  text-align: left; // Keep text aligned left
  border-width: $border-width-base;
  border-style: solid;

  &.message--success { // Example using modifier class
      color: var(--color-success-dark);
      background-color: var(--color-success-light);
      border-color: var(--color-success);
  }
  &.message--error { // Example using modifier class
      color: var(--color-error-dark);
      background-color: var(--color-error-light);
      border-color: var(--color-error);
  }
}

// --- Profile Sections ---
.profileSection {
  margin-bottom: $spacing-xl; // Consistent spacing between sections
  padding-bottom: $spacing-lg; // Space below content before border
  border-bottom: $border-width-base solid var(--color-border-secondary); // Subtle separator

  &:last-of-type {
    border-bottom: none; // No border on the last section
    margin-bottom: 0;
    padding-bottom: 0;
  }

  // Section Title (h3)
  h3 {
    font-size: $font-size-h4; // Use heading size
    font-weight: 600;
    color: var(--color-text-primary);
    margin-bottom: $spacing-lg; // Space below section title
    display: flex; // Align icon and text
    align-items: center;
    gap: $spacing-sm; // Space icon and text
    padding-bottom: $spacing-sm;
    border-bottom: $border-width-base dashed var(--color-border-secondary); // Dashed line under title

    // Style icons within h3
    svg {
        color: var(--color-primary); // Use primary color for section icons
        width: 20px;
        height: 20px;
    }
  }
}

// --- Info Item Styling (e.g., Email, Username) ---
.infoItem {
  display: flex;
  flex-wrap: wrap; // Allow items to wrap on small screens
  align-items: center; // Vertically align items
  gap: $spacing-sm $spacing-md; // Row gap, Column gap
  margin-bottom: $spacing-md; // Space below each info item row
  font-size: $font-size-base;
  color: var(--color-text-primary);

  .infoLabel { // Use a specific class for the label part
    font-weight: 500;
    color: var(--color-text-secondary);
    margin-right: $spacing-xs; // Small space after label
    flex-shrink: 0; // Prevent label shrinking
    // Optional: Min-width for alignment, but flex gap often works better
    // min-width: 100px;
  }

  .infoValue { // Class for the actual value
    flex-grow: 1; // Allow value to take space
    word-break: break-word; // Break long emails/usernames
  }

  // Common style for icons within info items (like mail, user icons)
  .infoIcon {
    flex-shrink: 0;
    color: var(--color-text-tertiary);
    width: 18px;
    height: 18px;
    margin-right: $spacing-sm; // Icon on the left of label
  }
}

// --- Status Badges (Verified, Not Verified) ---
.statusBadge {
  display: inline-flex;
  align-items: center;
  gap: $spacing-xs;
  font-size: $font-size-sm * 0.9; // Slightly smaller badge text
  font-weight: 500;
  padding: $spacing-xs * 0.75 $spacing-sm;
  border-radius: $border-radius-pill; // Pill shape
  line-height: 1; // Ensure tight fit

  svg { width: 12px; height: 12px; } // Smaller icon in badge

  &.verified {
    color: var(--color-success-dark);
    background-color: var(--color-success-light);
  }

  &.notVerified {
    color: var(--color-warning-dark); // Use warning color for 'not verified'
    background-color: var(--color-warning-light);
  }
}

// Inline button (e.g., Send Verification) positioned next to info
.inlineButton {
  margin-left: auto; // Push to the right within the flex container
  // Use small size button variant
}

// --- Update Form Section ---
.submitButtonContainer {
  margin-top: $spacing-md;
  text-align: right; // Align save button right
}

// --- Account Management Actions (e.g., Password Reset) ---
.managementAction {
  display: flex;
  flex-direction: column; // Stack elements vertically on small screens
  gap: $spacing-sm;
  margin-bottom: $spacing-lg;
  background-color: var(--color-bg-primary); // Slight contrast background
  padding: $spacing-md;
  border-radius: $border-radius-md;
  border: $border-width-base solid var(--color-border-primary);

  @media (min-width: $breakpoint-md) {
      flex-direction: row; // Side-by-side on larger screens
      align-items: center; // Align items vertically center
  }

  .actionIcon {
    flex-shrink: 0;
    color: var(--color-text-secondary);
    width: 20px;
    height: 20px;
     @media (min-width: $breakpoint-md) {
         margin-right: $spacing-sm;
     }
  }

  .actionDescription {
    flex-grow: 1; // Allow text to take available space
    margin: 0; // Remove default paragraph margin
    color: var(--color-text-secondary);
    font-size: $font-size-sm;
    line-height: 1.5;
  }

  .actionButton {
     flex-shrink: 0;
     @media (max-width: ($breakpoint-md - 1px)) {
          margin-top: $spacing-sm; // Add space above button on mobile
          align-self: flex-end; // Align button right on mobile
     }
      // Use secondary button variant by default
  }
}

// --- Plan & Perks Section Specifics ---
.planInfo {
  font-weight: 600;
  color: var(--color-primary-dark); // Highlight plan name
}
.expiryInfo {
   font-size: $font-size-sm;
   color: var(--color-text-secondary);
}
.expiredMessage {
    // Use warning status colors
    color: var(--color-warning-dark);
    background-color: var(--color-warning-light);
    border: $border-width-base solid var(--color-warning);
    font-size: $font-size-sm;
    font-weight: 500;
    padding: $spacing-sm $spacing-md;
    border-radius: $border-radius-md;
    margin-top: $spacing-sm;
    display: inline-flex;
    align-items: center;
    gap: $spacing-sm;
    svg { flex-shrink: 0; }
}
.limitsInfo {
    font-size: $font-size-sm;
    color: var(--color-text-secondary);
    margin-top: $spacing-sm;
    padding-left: $spacing-md; // Indent limit info
    border-left: 2px solid var(--color-border-secondary);

    span > strong { // Make limit value stand out
        color: var(--color-text-primary);
        font-weight: 600;
    }
     // Stack limits on mobile
     display: flex;
     flex-direction: column;
     gap: $spacing-xs;
      @media (min-width: $breakpoint-sm) {
         // Side-by-side on larger screens
         flex-direction: row;
         gap: $spacing-lg; // More space between items
      }
}
.managePerksButton {
    margin-top: $spacing-md;
    // Style using Button component variants
}


// --- Payment History Table ---
.historyTable {
  width: 100%;
  border-collapse: collapse;
  margin-top: $spacing-md;
  font-size: $font-size-sm;
  background-color: var(--color-bg-primary); // Use primary background for table
  border: $border-width-base solid var(--color-border-primary);
  border-radius: $border-radius-md;
  overflow: hidden; // Clip content to border radius

  th, td {
    padding: $spacing-sm $spacing-md;
    text-align: left;
    border-bottom: $border-width-base solid var(--color-border-primary);
    vertical-align: middle;
  }

  th {
    background-color: var(--color-bg-secondary); // Header background
    font-weight: 600; // Bolder headers
    color: var(--color-text-secondary);
    text-transform: none; // No uppercase needed
  }

  tbody tr:last-child td {
    border-bottom: none;
  }

  tbody tr {
     transition: background-color 0.15s ease;
     &:hover {
         background-color: var(--color-bg-tertiary); // Hover effect
     }
  }

  // Status badge styling from AdminPaymentsPage might need adjustments
 // .statusBadgeCell {
      // Ensure badge fits well
  //}
  .rejectionReasonInfoIcon { // For tooltip icon
    display: inline-block;
    margin-left: $spacing-xs;
    color: var(--color-text-tertiary);
    cursor: help;
    vertical-align: middle;
    line-height: 1;
    &:hover { color: var(--color-text-secondary); }
    svg { display: block; width: 14px; height: 14px; }
  }
   // Style for details/ID cell
   .detailsCell {
       code { // Small ID snippet
          font-family: monospace;
          font-size: 0.85em;
          color: var(--color-text-tertiary);
          background-color: var(--color-bg-secondary);
          padding: 2px 4px;
          border-radius: $border-radius-sm;
          display: inline-block;
       }
   }
}


// --- Danger Zone ---
.dangerZone {
  border-top: $border-width-lg solid var(--color-error); // Thicker top border
  padding-top: $spacing-lg;
  margin-top: $spacing-xl;
  background-color: var(--color-error-light); // Subtle danger background
  padding: $spacing-lg;
  border-radius: $border-radius-md;
  border-bottom: none; // Override section border

  h3 {
     color: var(--color-error-dark); // Use darker error color for title
     border-bottom-color: var(--color-error); // Match top border
     svg { color: var(--color-error); } // Make icon red
  }

  // Use managementAction styling but adjust colors
  .managementAction {
      background-color: transparent; // Remove inner background
      border: none;
      padding: 0;

     .actionDescription {
         color: var(--color-error-dark); // Danger text color
     }
     .actionIcon {
         color: var(--color-error); // Make icon red
     }
      // Button uses 'danger' variant from Button component
     // .actionButton {
          // Default handled by Button variant="danger"
      //}
  }
}

// --- Modal Styles (Use common modal styles if available, or define here) ---
// Assuming a common Modal component exists or reusing styles from DeletedUsersPage
.modalActions {
    margin-top: $spacing-lg;
    display: flex;
    justify-content: flex-end;
    gap: $spacing-md;
}

// Placeholder for modal content styling if specific overrides needed
// .deleteModalContent { ... }
```

---

### components\profile\Profile\Profile.tsx

```typescript
// src/components/profile/Profile/Profile.tsx
import React, { useState, useEffect, FormEvent, useMemo, useCallback } from 'react'; // Add useCallback
import { useAuth } from '../../../hooks/useAuth'; // Adjust path
import {
    deleteUserAccount, // Keep soft delete
    resetPassword,
    sendUserEmailVerification,
    updateUserProfileData
} from '../../../services/firebase'; // Adjust path
import { getUserPaymentHistory } from '../../../services/paymentService'; // Adjust path
import { PaymentAttempt } from '../../../types'; // Adjust path
import { getTierConfigs } from '../../../services/configService';
import { TierConfig, UserData } from '../../../types'; // Adjust path
import Input from '../../common/Input/Input'; // Use redesigned Input
import Button from '../../common/Button/Button'; // Use redesigned Button
import LoadingSpinner from '../../common/LoadingSpinner/LoadingSpinner'; // Use redesigned Spinner
import { ProfileErrors } from '../../../types'; // Adjust path
import styles from './Profile.module.scss'; // Adjust path
import { useToast } from '../../common/Toast'; // Use redesigned Toast
import { useNavigate } from 'react-router-dom';
import { Timestamp } from 'firebase/firestore';
// Import Feather icons for sections and statuses
import {
    FiUser, FiMail, FiLock, FiSmile, FiCalendar, FiAward, FiCreditCard,
    FiAlertTriangle, FiCheckCircle, FiInfo, FiLoader, FiTrash2, FiAlertCircle as FiWarning, // Alias for warning
    FiAlertCircle
} from 'react-icons/fi';

// --- Reusable Helper Functions (Keep or move to utils) ---
const getEffectiveTier = (
    userData: UserData | null, // Accept null UserData
    tierConfigs: TierConfig[]
): TierConfig | undefined => {
     if (!tierConfigs || tierConfigs.length === 0) {
        return undefined; // Return undefined if configs not loaded
    }
    const freeTier = tierConfigs.find(t => t.id === 'free');
    if (!userData) {
        return freeTier; // Default to free if no user data
    }
    const currentLevelId = userData.perkLevel || 'free';
    const expiryDate = userData.perkExpiry instanceof Timestamp ? userData.perkExpiry.toDate() : userData.perkExpiry; // Handle Timestamp or Date
    const isExpired = !!expiryDate && expiryDate < new Date();
    const effectiveLevelId = isExpired ? 'free' : currentLevelId;
    return tierConfigs.find(t => t.id === effectiveLevelId) || freeTier; // Fallback to free if ID not found
};

const formatDate = (dateInput: Date | Timestamp | undefined | null): string => {
    if (!dateInput) return 'N/A';
    const date = dateInput instanceof Timestamp ? dateInput.toDate() : dateInput;
    // Use more user-friendly format
    return date ? date.toLocaleDateString(undefined, { year: 'numeric', month: 'short', day: 'numeric' }) : 'N/A';
};
// --- End Helpers ---

// --- Reusable Status Badge Component (for Payments) ---
const StatusBadge: React.FC<{ status: PaymentAttempt['status'], reason?: string | null }> = ({ status, reason }) => {
     // Base styles (could be moved to SCSS module and use classes)
    const baseStyle: React.CSSProperties = {
        padding: '4px 10px',
        borderRadius: styles['border-radius-pill'] || '99px', // Use variable or fallback
        fontSize: '0.75rem',
        fontWeight: 500,
        textTransform: 'capitalize',
        display: 'inline-flex', // Use inline-flex
        alignItems: 'center',
        gap: styles['spacing-xs'] || '4px', // Use variable or fallback
        lineHeight: 1.2,
        border: '1px solid transparent',
        whiteSpace: 'nowrap',
    };
    let specificStyle: React.CSSProperties = {};
    let Icon = FiInfo; // Default icon

     // Determine style and icon based on status
     switch(status) {
        case 'completed':
            specificStyle = { backgroundColor: 'var(--color-success-light)', color: 'var(--color-success-dark)', borderColor: 'var(--color-success)' };
            Icon = FiCheckCircle;
            break;
        case 'pending_verification':
            specificStyle = { backgroundColor: 'var(--color-warning-light)', color: 'var(--color-warning-dark)', borderColor: 'var(--color-warning)' };
            Icon = FiLoader; // Use loader icon for pending
            break;
        case 'rejected':
            specificStyle = { backgroundColor: 'var(--color-error-light)', color: 'var(--color-error-dark)', borderColor: 'var(--color-error)' };
            Icon = FiAlertCircle; // Error icon for rejected
            break;
         default:
             specificStyle = { backgroundColor: 'var(--color-bg-tertiary)', color: 'var(--color-text-secondary)'};
     }

     const statusText = status.replace(/_/g, ' ');

     return (
        <span style={{ ...baseStyle, ...specificStyle }}>
            <Icon size="1em" style={{ marginRight: '4px' }} />
            {statusText}
            {status === 'rejected' && reason && (
                <span title={reason} className={styles.rejectionReasonInfoIcon} style={{marginLeft: '4px'}}>
                   <FiInfo size="0.9em" />
                </span>
            )}
        </span>
    );
}
// --- End Status Badge ---


// --- Basic Placeholder Modal --- (Use a proper Modal component if available)
const Modal: React.FC<{ isOpen: boolean; onClose: () => void; title: string; children: React.ReactNode }> = ({ isOpen, onClose, title, children }) => {
    // Existing simple modal implementation - keep as is or replace
     if (!isOpen) return null;
    return (
        <div style={{ position: 'fixed', top: 0, left: 0, right: 0, bottom: 0, backgroundColor: 'rgba(0,0,0,0.6)', display: 'flex', justifyContent: 'center', alignItems: 'center', zIndex: 1050, padding: '16px' }}>
            <div style={{ background: 'var(--color-bg-secondary)', padding: '24px', borderRadius: '16px', minWidth: '300px', maxWidth: '500px', border: '1px solid var(--color-border-primary)', boxShadow: 'var(--shadow-lg)' }}>
                <div style={{ display: 'flex', justifyContent: 'space-between', alignItems: 'center', marginBottom: '15px', borderBottom: '1px solid var(--color-border-secondary)', paddingBottom: '10px' }}>
                    <h3 style={{ margin: 0, color: 'var(--color-primary)', fontSize: '1.25rem' }}>{title}</h3>
                    <button onClick={onClose} style={{ background: 'none', border: 'none', fontSize: '1.75rem', cursor: 'pointer', color: 'var(--color-text-tertiary)', padding: '0 5px' }}>×</button>
                </div>
                <div>{children}</div>
            </div>
        </div>
    );
};
// --- End Placeholder Modal ---


const Profile: React.FC = () => {
    const { addToast } = useToast();
    const { currentUser, userData, isLoading: authLoading } = useAuth();
    const navigate = useNavigate();

    // Profile Update State
    const [displayName, setDisplayName] = useState('');
    const [updateLoading, setUpdateLoading] = useState(false);
    const [profileErrors, setProfileErrors] = useState<ProfileErrors>({});
    const [profileSuccess, setProfileSuccess] = useState<string | null>(null); // For inline success msg

    // Action States
    const [isVerifying, setIsVerifying] = useState(false);
    const [isSendingReset, setIsSendingReset] = useState(false);

    // Deletion State
    const [isDeleteModalOpen, setIsDeleteModalOpen] = useState(false);
    const [confirmDeleteInput, setConfirmDeleteInput] = useState('');
    const [isDeletingAccount, setIsDeletingAccount] = useState(false);
    const [deleteError, setDeleteError] = useState<string | null>(null); // Error specific to delete modal

    // Payment History State
    const [paymentHistory, setPaymentHistory] = useState<PaymentAttempt[]>([]);
    const [isFetchingHistory, setIsFetchingHistory] = useState<boolean>(false);
    const [historyError, setHistoryError] = useState<string | null>(null);

    // Tier Config State
    const [tierConfigs, setTierConfigs] = useState<TierConfig[]>([]);
    const [isLoadingTiers, setIsLoadingTiers] = useState<boolean>(true);

    const isEmailVerified = currentUser?.emailVerified ?? false;

    // --- Effects ---
    // Populate display name from userData
    useEffect(() => {
        if (userData) {
            setDisplayName(userData.displayName || '');
        }
        // Clear messages when user data changes/loads
        setProfileSuccess(null);
        setProfileErrors({});
        setDeleteError(null);
    }, [userData]);

    // Fetch Tier Configs
    useEffect(() => {
        let isMounted = true; // Prevent state update on unmounted component
        setIsLoadingTiers(true);
        getTierConfigs() // <<< Use function from configService
            .then((configs) => {
                if (isMounted) setTierConfigs(configs);
            })
            .catch((err) => { // configService returns [], handle toast here maybe
                 if (isMounted) addToast("Could not load perk plans.", "error");
                //console.error(err); // Log the actual error
            })
            .finally(() => {
                if (isMounted) setIsLoadingTiers(false);
            });
        return () => { isMounted = false }; // Cleanup
    }, [addToast]); 

    // Fetch Payment History
    useEffect(() => {
        if (currentUser?.uid) {
            setIsFetchingHistory(true);
            setHistoryError(null);
            getUserPaymentHistory(currentUser.uid)
                .then(history => setPaymentHistory(history))
                .catch(error => {
                   //console.error("Failed to fetch payment history:", error);
                    setHistoryError("Could not load payment history.");
                })
                .finally(() => setIsFetchingHistory(false));
        } else {
            setPaymentHistory([]); // Clear on logout
        }
    }, [currentUser?.uid]);

    // --- Derived State ---
    const effectiveCurrentTier = useMemo(() => {
        return getEffectiveTier(userData, tierConfigs);
    }, [userData, tierConfigs]);

    const isCurrentPlanExpired = useMemo(() => {
        if (!userData?.perkExpiry || userData.perkLevel === 'free') return false;
        const expiryDate = userData.perkExpiry instanceof Timestamp ? userData.perkExpiry.toDate() : userData.perkExpiry;
        return expiryDate < new Date();
    }, [userData?.perkExpiry, userData?.perkLevel]);

    // --- Handlers ---
    // Basic Profile Validation (extracted)
    const validateProfileForm = (currentDisplayName: string): ProfileErrors => {
        const errors: ProfileErrors = {};
        const trimmedName = displayName.trim(); // Validate the state variable 'displayName'
        if (!trimmedName) {
            errors.displayName = 'Display Name cannot be empty.';
        } else if (trimmedName.length < 2 || trimmedName.length > 50) {
            errors.displayName = 'Display Name must be between 2 and 50 characters.';
        } else if (trimmedName === currentDisplayName) {
            errors.displayName = 'No changes detected.'; // Prevent submitting same name
        }
        return errors;
    }

    // Profile Update
    const handleProfileUpdate = async (e: FormEvent) => {
        e.preventDefault();
        setProfileErrors({});
        setProfileSuccess(null);

        if (!currentUser || !userData) return;

        const validationErrors = validateProfileForm(userData.displayName); // Pass current name for comparison
        if (Object.keys(validationErrors).length > 0) {
            setProfileErrors(validationErrors);
            return;
        }

        setUpdateLoading(true);
        try {
            await updateUserProfileData(currentUser.uid, { displayName: displayName.trim() });
            setProfileSuccess('Display Name updated successfully!');
            addToast('Profile Updated!', 'success');
            // userData updates via AuthContext listener
        } catch (error: any) {
           //console.error("Profile update error:", error);
            addToast(`Profile update failed: ${error.message}`, 'error');
            setProfileErrors({ general: error.message || 'Failed to update profile.' });
        } finally {
            setUpdateLoading(false);
        }
    };

    // Send Verification Email
    const handleSendVerificationEmail = useCallback(async () => {
        if (!currentUser || isVerifying) return;
        setIsVerifying(true);
        setProfileErrors({}); // Clear errors
        setProfileSuccess(null);
        try {
            await sendUserEmailVerification();
            addToast('Verification email sent! Check your inbox (and spam folder).', 'success');
            setProfileSuccess('Verification email sent!'); // Also show inline message
        } catch (error: any) {
           //console.error("Send verification error:", error);
            addToast(`Failed to send verification email: ${error.message}`, 'error');
            setProfileErrors({ general: error.message || 'Failed to send verification email.' });
        } finally {
            setIsVerifying(false);
        }
    }, [currentUser, addToast, isVerifying]);

    // Send Password Reset
    const handleSendPasswordReset = useCallback(async () => {
        if (!currentUser?.email || isSendingReset) return;
        setIsSendingReset(true);
        setProfileErrors({}); // Clear errors
        setProfileSuccess(null);
        try {
            // The function in firebase.ts already shows a success toast for security
            await resetPassword(currentUser.email);
            // Optionally show an inline message too
            setProfileSuccess('Password reset instructions sent (if account exists).');
        } catch (error: any) {
           //console.error("Send password reset error:", error);
            addToast(`Failed to send password reset email: ${error.message}`, 'error');
            setProfileErrors({ general: error.message || 'Failed to send password reset.' });
        } finally {
            setIsSendingReset(false);
        }
    }, [currentUser?.email, addToast, isSendingReset]);


    // Delete Account Handlers
    const handleOpenDeleteModal = () => {
        setConfirmDeleteInput('');
        setDeleteError(null); // Clear modal-specific errors
        setProfileErrors({}); // Clear main page errors
        setProfileSuccess(null);
        setIsDeleteModalOpen(true);
    };
    const handleCloseDeleteModal = () => setIsDeleteModalOpen(false);

    const handleConfirmDelete = async () => {
        if (!currentUser || !userData || confirmDeleteInput.toLowerCase() !== userData.username.toLowerCase()) {
             setDeleteError('Username does not match.'); // Set error within the modal
            return;
        }
        setIsDeletingAccount(true);
        setDeleteError(null);
        try {
            await deleteUserAccount(currentUser.uid, userData.username); // Uses soft delete
            
            // No need to manually navigate - logout will trigger AuthContext update
            handleCloseDeleteModal(); // Close modal on successful request
            // Auth listener handles the rest (state change, logout UI)
            addToast('Account marked for deletion. You will be logged out.', 'info', 8000);
        } catch (error: any) {
           //console.error("Delete account error:", error);
            addToast(`Account deletion request failed: ${error.message}`, 'error', 10000);
            setDeleteError(error.message || 'Failed to request account deletion.'); // Show error in modal
            // Don't close modal automatically on error, let user see message
            setIsDeletingAccount(false); // Stop loading but keep modal open
        }
        // No finally needed here as loading state is handled in catch/success path
    };

    // --- Render Loading State ---
    // Combined loading check
    if (authLoading || isLoadingTiers || !userData || !currentUser) {
        return (
            <div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', padding: '50px 0' }}>
                <LoadingSpinner size="large" />
                <p style={{marginTop: '16px', color: 'var(--color-text-secondary)'}}>Loading Profile...</p>
            </div>
        );
    }

    // Should not happen if ProtectedRoute works, but safeguard
    if (!userData || !currentUser) {
        return <p>User data not available.</p>;
    }

    const joinedDate = formatDate(userData.createdAt);


    // --- Render Profile ---
    return (
        <div className={styles.profileContainer}>
            <h1 className={styles.title}>My Profile</h1>

            {/* General Messages Area (top) */}
            {profileErrors.general && <p className={`${styles.message} ${styles['message--error']}`}>{profileErrors.general}</p>}
            {profileSuccess && <p className={`${styles.message} ${styles['message--success']}`}>{profileSuccess}</p>}

            {/* === Basic Info Section === */}
            <section className={styles.profileSection}>
                <h3><FiUser /> Basic Information</h3>
                 <div className={styles.infoItem}>
                     <FiMail className={styles.infoIcon} />
                    <span className={styles.infoLabel}>Email:</span>
                    <span className={styles.infoValue}>{userData.email}</span>
                    {isEmailVerified ? (
                        <span className={`${styles.statusBadge} ${styles.verified}`}><FiCheckCircle /> Verified</span>
                    ) : (
                        <span className={`${styles.statusBadge} ${styles.notVerified}`}><FiWarning /> Not Verified</span>
                    )}
                    {!isEmailVerified && (
                         <Button
                             variant="outline" size="small"
                             onClick={handleSendVerificationEmail}
                             loading={isVerifying}
                             disabled={isVerifying}
                             className={styles.inlineButton}
                             title="Resend verification email"
                         >
                             Send Verification
                         </Button>
                    )}
                 </div>
                 <div className={styles.infoItem}>
                     <FiUser className={styles.infoIcon}/>
                    <span className={styles.infoLabel}>Username:</span>
                     <span className={styles.infoValue}>{userData.username}</span>
                 </div>
                 <div className={styles.infoItem}>
                     <FiCalendar className={styles.infoIcon}/>
                    <span className={styles.infoLabel}>Joined:</span>
                     <span className={styles.infoValue}>{joinedDate}</span>
                 </div>
            </section>

             {/* === Current Plan & Perks Section === */}
            <section className={styles.profileSection}>
                <h3><FiAward /> Current Plan & Perks</h3>
                <div className={styles.infoItem}>
                   <span className={styles.infoLabel}>Plan:</span>
                   <span className={`${styles.infoValue} ${styles.planInfo}`}>
                       {effectiveCurrentTier?.name ?? 'N/A'}
                   </span>
                    {/* Show expiry only for non-free, non-expired plans */}
                   {effectiveCurrentTier?.id !== 'free' && userData.perkExpiry && !isCurrentPlanExpired && (
                       <span className={styles.expiryInfo}>(Expires: {formatDate(userData.perkExpiry)})</span>
                   )}
                </div>

                 {/* Show message if plan expired */}
                 {isCurrentPlanExpired && (
                    <div className={styles.expiredMessage}>
                       <FiWarning/> Your '{userData?.perkLevel}' plan expired on {formatDate(userData.perkExpiry)}. You are now on the Free plan.
                    </div>
                 )}

                 {/* Display limits from effective tier */}
                 <div className={styles.limitsInfo}>
                    <span>Current Limits:</span>
                    <span>
  Exam History: <strong>{effectiveCurrentTier?.limits?.examAttempts === null ? 'Unlimited' : effectiveCurrentTier?.limits?.examAttempts}</strong>
</span>
<span>
  Hosted Sessions: <strong>{effectiveCurrentTier?.limits?.hostedSessions === null ? 'Unlimited' : effectiveCurrentTier?.limits?.hostedSessions}</strong>
</span>

                </div>

                 {/* Link to manage/upgrade */}
                <Button
                     variant={effectiveCurrentTier?.id === 'free' ? "primary" : "secondary"}
                     size="small"
                     onClick={() => navigate('/perks')}
                     className={styles.managePerksButton}
                >
                     {effectiveCurrentTier?.id === 'free' ? 'View Perks / Upgrade Plan' : 'Manage Perks'}
                 </Button>
             </section>

             {/* === Payment History Section === */}
             <section className={styles.profileSection}>
                 <h3><FiCreditCard /> Payment History</h3>
                 {isFetchingHistory ? (
                     <LoadingSpinner />
                 ) : historyError ? (
                     <p className={`${styles.message} ${styles['message--error']}`}>{historyError}</p>
                 ) : paymentHistory.length === 0 ? (
                     <p>No payment history found.</p>
                 ) : (
                     <table className={styles.historyTable}>
                         <thead>
                             <tr>
                                 <th>Date</th>
                                 <th>Tier</th>
                                 <th>Amount</th>
                                 <th className={styles.statusBadgeCell}>Status</th>
                                 <th className={styles.detailsCell}>Details/ID</th>
                             </tr>
                         </thead>
                         <tbody>
                             {paymentHistory.map(payment => (
                                 <tr key={payment.id}>
                                     <td>{formatDate(payment.createdAt)}</td>
                                     <td>{payment.tierName}</td>
                                     <td>₹{payment.amount}</td>
                                     <td className={styles.statusBadgeCell}>
                                        <StatusBadge status={payment.status} reason={payment.rejectionReason} />
                                     </td>
                                     <td className={styles.detailsCell}>
                                         <code title={payment.id}>{payment.id.substring(0, 8)}...</code>
                                     </td>
                                 </tr>
                             ))}
                         </tbody>
                     </table>
                 )}
             </section>

            {/* === Update Profile Section === */}
            <section className={styles.profileSection}>
                <h3><FiSmile /> Update Profile</h3>
                 <form onSubmit={handleProfileUpdate} noValidate>
                    <Input
                        label="Display Name" type="text" id="displayName" name="displayName"
                        value={displayName}
                        onChange={(e) => setDisplayName(e.target.value)}
                        error={profileErrors.displayName}
                        disabled={updateLoading}
                        icon={<FiUser />} // Keep user icon consistent
                        required autoComplete="name"
                    />
                    <div className={styles.submitButtonContainer}>
                        <Button
                            type="submit" variant="primary"
                            loading={updateLoading}
                            disabled={updateLoading || (userData && displayName.trim() === userData.displayName)}
                        >
                            Save Display Name
                        </Button>
                    </div>
                </form>
            </section>

            {/* === Account Management Section === */}
            <section className={styles.profileSection}>
                 <h3><FiLock /> Account Management</h3>
                 <div className={styles.managementAction}>
                    <FiLock className={styles.actionIcon}/>
                    <p className={styles.actionDescription}>
                        For security, request a password reset link to be sent to your verified email: <strong>{currentUser.email}</strong>.
                    </p>
                     <Button
                         variant="secondary" // Secondary action
                         onClick={handleSendPasswordReset}
                         loading={isSendingReset}
                         disabled={isSendingReset}
                         className={styles.actionButton}
                     >
                         Send Password Reset
                     </Button>
                 </div>
             </section>


            {/* === Danger Zone Section === */}
            <section className={`${styles.profileSection} ${styles.dangerZone}`}>
                <h3><FiAlertTriangle /> Danger Zone</h3>
                 <div className={styles.managementAction}>
                     <FiAlertTriangle className={styles.actionIcon} />
                     <p className={styles.actionDescription}>
                         Deleting your account will mark it for permanent removal and cannot be undone. All associated data will eventually be purged by an administrator.
                     </p>
                     <Button
                         variant="danger" // Use the danger variant
                         onClick={handleOpenDeleteModal}
                         disabled={isDeletingAccount}
                         className={styles.actionButton}
                     >
                         <FiTrash2 style={{ marginRight: '4px' }} /> Delete My Account
                     </Button>
                 </div>
             </section>

            {/* --- Delete Confirmation Modal --- */}
            <Modal isOpen={isDeleteModalOpen} onClose={handleCloseDeleteModal} title="Confirm Account Deletion">
                 <p>This action marks your account for deletion and is irreversible. To confirm, type your username (<b>{userData.username}</b>) below:</p>
                 <Input
                     label={`Username (${userData.username})`}
                     type="text" id="confirmDelete" value={confirmDeleteInput}
                     onChange={(e) => {
                         setConfirmDeleteInput(e.target.value);
                         if (deleteError) setDeleteError(null); // Clear error on input change
                     }}
                     error={deleteError || profileErrors.deleteConfirm} // Show modal-specific error first
                     disabled={isDeletingAccount}
                     autoComplete="off" placeholder="Type username here"
                     // Add autoFocus to the input when modal opens?
                     // autoFocus
                 />
                 {/* General deletion error */}
                 {/* {profileErrors.general && <p className={styles.message + ' ' + styles['message--error']}>{profileErrors.general}</p>} */}
                 <div className={styles.modalActions}>
                     <Button variant="secondary" onClick={handleCloseDeleteModal} disabled={isDeletingAccount}>
                         Cancel
                     </Button>
                     <Button
                         variant="danger" // Use danger variant for confirmation
                         onClick={handleConfirmDelete}
                         loading={isDeletingAccount}
                         disabled={isDeletingAccount || confirmDeleteInput.toLowerCase() !== userData.username.toLowerCase()}
                     >
                         Confirm Deletion Request
                     </Button>
                 </div>
             </Modal>
        </div>
    );
};
export default Profile;
```

---

## config


### config\appDefaults.ts

```typescript
// src/config/appDefaults.ts

import { TierConfig, UserService /* Add other specific config types */ } from '../types'; // Adjust path

// --- Default Tier Configurations ---
export const DEFAULT_TIERS: TierConfig[] = [
    {
        id: 'free',
        name: 'Free',
        pricingOptions: [{billingCycle: 'monthly', priceINR: 0, durationMonths: 1, displaySuffix: ''}],
        description: 'Get started with essential practice tools.',
        features: [
            "Practice with official & custom JSON exams",
            "Basic performance summary",
            "Host 1 small group session (up to 5 participants)",
            "Limited attempt history (5 attempts)",
            "Community support"
        ],
        limits: { examAttempts: 5, hostedSessions: 1 }
    },
    {
        id: 'basic',
        name: 'Basic',
        pricingOptions: [
            { billingCycle: 'monthly', priceINR: 18, durationMonths: 1, displaySuffix: '/mo' },
            { billingCycle: 'yearly', priceINR: 149, durationMonths: 12, displaySuffix: '/yr', savingsText: 'Save ~27%' }
        ],
        description: 'Unlock more history, larger groups, and review your custom tests.',
        features: [
            "All Free features, plus:",
            "Expanded attempt history (20 attempts)",
            "Host up to 3 group sessions",
            "Increased participants per session (up to 15)",
            "Review your custom uploaded exams",
            "Basic email support"
        ],
        limits: { examAttempts: 20, hostedSessions: 3 }
    },
    {
        id: 'pro',
        name: 'Pro',
        pricingOptions: [
            { billingCycle: 'monthly', priceINR: 28, durationMonths: 1, displaySuffix: '/mo' },
            { billingCycle: 'yearly', priceINR: 249, durationMonths: 12, displaySuffix: '/yr', savingsText: 'Save ~25%' }
        ],
        description: 'For serious aspirants: advanced group tools and monitoring.',
        isPopular: true, // Marking Pro as popular based on previous 'Supporter'
        recommendedCycle: 'yearly',
        features: [
            "All Basic features, plus:",
            "Generous attempt history (50 attempts)",
            "Host up to 10 group sessions",
            "Enable Basic Anti-Cheating Monitoring for group sessions",
            "Download group session participant results (CSV)",
            "Ad-free experience on Examify", // Feature string for Examify
            "Standard email support"
        ],
        limits: { examAttempts: 50, hostedSessions: 10 }
    },
    {
        id: 'elite',
        name: 'Elite',
        pricingOptions: [
            { billingCycle: 'monthly', priceINR: 85, durationMonths: 1, displaySuffix: '/mo' },
            { billingCycle: 'yearly', priceINR: 799, durationMonths: 12, displaySuffix: '/yr', savingsText: 'Save ~21%' }
        ],
        description: 'The ultimate toolkit for individuals and educators: unlimited access and priority support.',
        features: [
            "All Pro features, plus:",
            "Unlimited attempt history",
            "Host unlimited group sessions",
            "Advanced Anti-Cheating Monitoring options (GeoLocationLocking)",
            "Priority support"
            // If "Ad-free on BCA Prep Blog" is a distinct Elite feature, add it here too.
        ],
        limits: { examAttempts: null, hostedSessions: null }
    },
];

// --- Default Services Configuration ---
export const DEFAULT_SERVICES: UserService[] = [
    {
      id: 'website', name: 'Bca Exam Preparation', description: 'Blogs, MCQs, PYQs, Syllabus and more.',
      url: 'https://bcaexamprep.blogspot.com/', icon: 'blog'
    },
    {
      id: 'examify-app', name: 'Examify - Exam Simulator', description: 'Practice exams and test your knowledge.',
      url: 'https://examify.web.app', icon: 'exam'
    },
    // Add future default services here
];

export const DEFAULT_AVAILABLE_SERVICES_IDS: string[] = ['website', 'examify-app'];

// --- Default Service-Specific Settings ---
export const DEFAULT_EXAMIFY_SETTINGS = {
    maxAttemptsHistoryFree: 5, // Updated based on Free tier
    maxAttemptsHistorySupporter: 20, // Mapping old 'supporter' limit to new 'basic' for this old var name
    maxAttemptsHistoryPro: 50, // Mapping old 'pro' limit to new 'pro' for this old var name
                                  // (Note: These specific maxAttemptsHistory... vars might be redundant if app only uses TierConfig.limits)
    defaultExamDurationMinutes: 120,
    resultsDisplayMode: 'detailed',
    allowCustomUploads: ['basic', 'pro', 'elite'], // MODIFIED: Tiers that can review custom uploads
};

export const DEFAULT_BCAPREPBLOG_SETTINGS = {
    // Assuming "Ad-free experience on Examify" (from Pro/Elite) should also grant ad-free on the blog.
    // If blog ad-free is a separate, lower-tier perk, the "features" array in DEFAULT_TIERS
    // for 'basic' would need a specific string like "Ad-free BCA Prep Blog".
    // Based on the current plan where Pro gets "Ad-free experience on Examify",
    // mapping this to blog ad-free for Pro and Elite.
    adFreeTiers: ['pro', 'elite'], // MODIFIED: Tiers that get ad-free for BCA Prep Blog
    featuredPostCount: 5,
};

// --- Default Payment Settings ---
// IMPORTANT: Sensitive details like actual UPI ID should ideally come from secure environment variables,
// not be hardcoded here, even in defaults. Placeholder used.
export const DEFAULT_PAYMENT_SETTINGS = {
    upiDetails: {
        upiId: "1904sumitkumar@oksbi", // USE PLACEHOLDER or load from ENV
        payeeName: "Samkarya",
        notePrefix: "P",
      },
     supportedCurrencies: ['INR'],
     verificationTimeoutHours: 24,
};

// --- Default Global Settings ---
export const DEFAULT_GLOBAL_SETTINGS = {
     settings: {
         maintenanceMode: false,
         maintenanceMessage: "Portal is undergoing maintenance. Please check back soon.",
         supportEmail: "support@example.com", // Use your actual support email
     },
     features: {
         perksEnabled: true,
         contactFormEnabled: true,
         groupExamsEnabled: false, // Example feature flag
     }
};


// --- Structure for Initialization Function ---
// This object maps the intended Firestore document ID to its default data structure.
export const DEFAULT_CONFIG_DOCS = {
    tiers: { tiers: DEFAULT_TIERS }, // Uses the updated DEFAULT_TIERS
    services: {
        defaultServices: DEFAULT_SERVICES,
        availableServices: DEFAULT_AVAILABLE_SERVICES_IDS
    },
    payments: DEFAULT_PAYMENT_SETTINGS,
    global: DEFAULT_GLOBAL_SETTINGS,
    // Add service-specific defaults
    examify: { settings: DEFAULT_EXAMIFY_SETTINGS }, // Uses updated DEFAULT_EXAMIFY_SETTINGS
    bcaPrepBlog: { settings: DEFAULT_BCAPREPBLOG_SETTINGS }, // Uses updated DEFAULT_BCAPREPBLOG_SETTINGS
    // Add 'newCoolService': { settings: DEFAULT_NEWCOOLSERVICE_SETTINGS }, etc.
};
```

---

## contexts


### contexts\AuthContext.tsx

```typescript
// src/contexts/AuthContext.tsx
import React, { createContext, useEffect, useState, useMemo, ReactNode, useRef } from 'react';
import { User as FirebaseUser } from 'firebase/auth';
import { doc, onSnapshot, Timestamp} from 'firebase/firestore';
import { FirebaseError } from 'firebase/app'; // Import specific error type
import {
    loginUser,
    registerUser,
    resetPassword as resetPasswordFirebase,
    onAuthUserStateChanged,
    auth,
    logoutUser as firebaseLogout,
    db
} from '../services/firebase';
import { AuthContextType, UserData } from '../types';
import LoadingSpinner from '../components/common/LoadingSpinner/LoadingSpinner';
import { useToast } from '../components/common/Toast';
import { useNetworkStatus } from '../hooks/useNetworkStatus';

export const AuthContext = createContext<AuthContextType | undefined>(undefined);

interface AuthProviderProps {
    children: ReactNode;
}

// Helper constant for consistent password requirement messaging
const passwordRequirementString = 'Please use a stronger password.';

// Define deletion grace period in milliseconds (5 seconds)
const DELETION_GRACE_PERIOD_MS = 5000;

export const AuthProvider: React.FC<AuthProviderProps> = ({ children }) => {
    const [currentUser, setCurrentUser] = useState<FirebaseUser | null>(null);
    const [userData, setUserData] = useState<UserData | null>(null);
    const [isLoading, setIsLoading] = useState<boolean>(true);
    const { addToast } = useToast();
    
    // Ref to store the Firestore listener unsubscribe function
    const userDocListenerUnsubscribe = useRef<(() => void) | null>(null);
    
    // Timer for grace period forced logout
    const gracePeriodTimerRef = useRef<NodeJS.Timeout | null>(null);

    // Track previous perk level for change detection
    const prevPerkLevelRef = useRef<string | null>(null);

    useNetworkStatus();

    useEffect(() => {
        //console.log("[AuthContext] Setting up auth state listener.");
        
        // Clear any existing grace period timer when auth state changes significantly
        if (gracePeriodTimerRef.current) {
            clearTimeout(gracePeriodTimerRef.current);
            gracePeriodTimerRef.current = null;
        }
        
        const unsubscribeAuth = onAuthUserStateChanged(async (user) => {
            //console.log("[AuthContext] Auth listener triggered. Firebase User:", user ? user.uid : 'null');

            // Clean up previous Firestore listener if it exists
            if (userDocListenerUnsubscribe.current) {
                //console.log("[AuthContext] Unsubscribing previous user document listener.");
                userDocListenerUnsubscribe.current();
                userDocListenerUnsubscribe.current = null;
            }

            // Clear grace period timer if user logs out or changes
            if (gracePeriodTimerRef.current) {
                clearTimeout(gracePeriodTimerRef.current);
                gracePeriodTimerRef.current = null;
            }

            if (user) {
                // User is logged in - Set up Firestore listener for their document
                //console.log(`[AuthContext] User ${user.uid} logged in. Setting up Firestore listener.`);
                const userDocRef = doc(db, 'users', user.uid);

                userDocListenerUnsubscribe.current = onSnapshot(userDocRef, (docSnap) => {
                    //console.log(`[AuthContext] Firestore snapshot received for user ${user.uid}. Exists: ${docSnap.exists()}`);
                    if (docSnap.exists()) {
                        const data = docSnap.data();
                        // Convert Firestore data to UserData type
                        const fetchedData: UserData = {
                            uid: user.uid,
                            email: data.email ?? '',
                            username: data.username ?? '',
                            displayName: data.displayName ?? '',
                            services: data.services ?? [],
                            status: data.status ?? 'active',
                            createdAt: data.createdAt instanceof Timestamp ? data.createdAt.toDate() : null,
                            updatedAt: data.updatedAt instanceof Timestamp ? data.updatedAt.toDate() : null,
                            deletedAt: data.deletedAt instanceof Timestamp ? data.deletedAt.toDate() : null,
                            perkLevel: data.perkLevel ?? 'free',
                            perkExpiry: data.perkExpiry instanceof Timestamp ? data.perkExpiry.toDate() : null,
                            currentBillingCycle: data.currentBillingCycle ?? null, 
                        };

                        //console.log(`[AuthContext] User data fetched/updated for ${user.uid}:`, fetchedData);

                        // --- Status Handling Logic ---
                        let accessDeniedReason: string | null = null;

                        // Check for suspended account
                        if (fetchedData.status === 'suspended') {
                            accessDeniedReason = "This account has been suspended by an administrator.";
                        } 
                        // Check for deleted account
                        else if (fetchedData.status === 'deleted') {
                            const now = new Date().getTime();
                            const deletedAtTime = fetchedData.deletedAt ? (fetchedData.deletedAt as Date).getTime() : 0;

                            if (deletedAtTime > 0 && (now - deletedAtTime < DELETION_GRACE_PERIOD_MS)) {
                                // --- WITHIN DELETION GRACE PERIOD ---
                                //console.log(`[AuthContext] User ${user.uid} 'deleted' but WITHIN grace period.`);
                                setCurrentUser(user);      // Keep Firebase user authenticated in context
                                setUserData(fetchedData);  // userData now has status: 'deleted'
                                // UI should react to userData.status === 'deleted' (e.g., show "Pending deletion..." banner)
                                
                                // Schedule a re-check/forced logout after grace period
                                if (gracePeriodTimerRef.current) clearTimeout(gracePeriodTimerRef.current);
                                gracePeriodTimerRef.current = setTimeout(() => {
                                    //console.log(`[AuthContext] Grace period ended for ${user.uid}. Forcing logout.`);
                                    const reason = "Account deletion grace period expired. Access revoked.";
                                    addToast(reason, "error", 10000);
                                    setCurrentUser(null); 
                                    setUserData(null);
                                    if (auth.currentUser?.uid === user.uid) {
                                         firebaseLogout().catch(err =>console.error("Error during grace period forced logout:", err));
                                    }
                                }, DELETION_GRACE_PERIOD_MS - (now - deletedAtTime) + 100); // Remaining time + small buffer
                            } else {
                                // --- DELETION GRACE PERIOD EXPIRED or deletedAt missing/invalid ---
                                accessDeniedReason = "This account has been marked for deletion. Access revoked.";
                            }
                        }

                        // If access is denied for any reason (suspended, or deleted outside grace)
                        if (accessDeniedReason) {
                            //console.log(`[AuthContext] Access DENIED for ${user.uid}: ${accessDeniedReason}`);
                            addToast(accessDeniedReason, "error", 10000);
                            setCurrentUser(null);
                            setUserData(null);
                            /*if (auth.currentUser?.uid === user.uid) {
                                //console.log(`[AuthContext] Forcing logout for ${user.uid} due to: ${fetchedData.status}`);
                                firebaseLogout().catch(err =>//console.error("[AuthContext] Error during forced logout (status denied):", err));
                            }*/
                        } else if (fetchedData.status === 'active' || (fetchedData.status === 'deleted' /* and within grace*/)) {
                            // If active, OR if deleted but still within grace period (handled above by not setting accessDeniedReason)
                            //console.log(`[AuthContext] Setting state for user ${user.uid} (status: ${fetchedData.status})`);
                            
                            // Check for perk level changes and notify user
                            const currentPerkLevel = fetchedData.perkLevel;
                            const previousPerkLevel = prevPerkLevelRef.current;
                            
                            // Only show toast if:
                            // 1. User was already logged in (not first login)
                            // 2. There's a previous perk level stored
                            // 3. The perk level has actually changed
                            if (previousPerkLevel && currentPerkLevel !== previousPerkLevel) {
                                //console.log(`[AuthContext] Perk level changed: ${previousPerkLevel} -> ${currentPerkLevel}`);
                                
                                // Determine message based on change type
                                let toastMessage = "";
                                let toastType: "success" | "info" | "warning" | "error" = "info";
                                
                                if (currentPerkLevel === 'free' && previousPerkLevel !== 'free') {
                                    // Downgrade to free
                                    toastMessage = "Your premium subscription has ended. You're now on the free plan.";
                                    toastType = "info";
                                } else if (currentPerkLevel !== 'free' && previousPerkLevel === 'free') {
                                    // Upgrade from free
                                    toastMessage = `Thank you for subscribing! You now have ${currentPerkLevel} access.`;
                                    toastType = "success";
                                } else {
                                    // Any other change (e.g., pro to premium)
                                    toastMessage = `Your subscription has changed to ${currentPerkLevel}.`;
                                    toastType = "info";
                                }
                                
                                // Show toast notification
                                addToast(toastMessage, toastType, 8000);
                            }
                            
                            // Update the state and the ref
                            setCurrentUser(user);
                            setUserData(fetchedData);
                            prevPerkLevelRef.current = currentPerkLevel;
                        }
                        // else: an unhandled status or combination, which shouldn't happen
                    } else {
                        // User exists in Auth but NOT in Firestore (Error Case)
                       //console.warn(`[AuthContext] User ${user.uid} found in Auth, but NO data in Firestore! Logging out.`);
                        addToast("User data not found. Please contact support if this persists.", "error", 10000);
                        setCurrentUser(null);
                        setUserData(null);
                        // Reset perk level ref
                        prevPerkLevelRef.current = null;
                        // Force logout
                        if (auth.currentUser?.uid === user.uid) {
                            firebaseLogout().catch(err =>console.error("[AuthContext] Error during forced logout (no Firestore doc):", err));
                        }
                    }
                    // Set loading to false after first snapshot
                    setIsLoading(prev => (prev ? false : prev)); // Only transition from true to false

                }, (error) => {
                    // Handle Firestore listener errors
                   //console.error(`[AuthContext] Error listening to user document (${user.uid}):`, error);
                    addToast("Error fetching user details. Please try refreshing.", "error");
                    setCurrentUser(null); // Log out on listener error
                    setUserData(null);
                    prevPerkLevelRef.current = null; // Reset perk level ref
                    if (auth.currentUser?.uid === user.uid) {
                        firebaseLogout().catch(err =>console.error("[AuthContext] Error during forced logout (listener error):", err));
                    }
                    setIsLoading(false); // Stop loading on error too
                });
            } else {
                // User is logged out
                //console.log("[AuthContext] No Firebase user detected. Setting state to null.");
                setCurrentUser(null);
                setUserData(null);
                prevPerkLevelRef.current = null; // Reset perk level ref when logged out
                setIsLoading(false); // Stop loading
            }
        });

        // Cleanup function for the main useEffect
        return () => {
            //console.log("[AuthContext] Cleaning up auth state listener.");
            unsubscribeAuth();
            if (userDocListenerUnsubscribe.current) {
                //console.log("[AuthContext] Cleaning up active user document listener.");
                userDocListenerUnsubscribe.current(); // Unsubscribe Firestore listener
            }
            if (gracePeriodTimerRef.current) {
                clearTimeout(gracePeriodTimerRef.current); // Clear grace period timer
            }
            prevPerkLevelRef.current = null; // Reset perk level ref on unmount
        };
    }, [addToast]); // addToast dependency is needed for error reporting

    // --- Login Function ---
    const login = useMemo(() => async (email: string, password: string) => {
        //console.log("[AuthContext][Login] Attempting login for:", email);
        try {
            // 1. Attempt Firebase Auth sign-in
            await loginUser(email, password);
            //console.log("[AuthContext][Login] Firebase sign-in successful for:", email);

            // 2. Immediate check for status (safeguard before listener runs)
            await new Promise(resolve => setTimeout(resolve, 100)); // Small delay to allow auth state to update
            const user = auth.currentUser;

            if (!user) {
               //console.warn("[AuthContext][Login] auth.currentUser was null shortly after login resolved. Relying on listener.");
                throw new Error("Login failed. Please check your credentials and try again.");
            }

            //console.log("[AuthContext][Login] Login request processed. Listener will finalize auth state.");
            // Successful login outcome is primarily handled by the onAuthStateChanged listener

        } catch (error: any) {
           //console.error("[AuthContext][Login] Raw Error:", error); // Log original error
            let userFriendlyMessage = 'Login failed. Please check connection or try again later.'; // Better default

            // Check if it's a FirebaseError with a code property
            if (error instanceof FirebaseError || (error && error.code)) {
                switch (error.code) {
                    case 'auth/user-not-found':
                    case 'auth/wrong-password':
                    case 'auth/invalid-credential':
                        userFriendlyMessage = 'Incorrect email or password. Please check details.';
                        break;
                    case 'auth/too-many-requests':
                        userFriendlyMessage = 'Too many failed attempts. Access blocked temporarily. Try again later or reset password.';
                        break;
                    case 'auth/network-request-failed':
                        userFriendlyMessage = 'Network connection error. Please check your internet.';
                        break;
                    case 'auth/user-disabled':
                        userFriendlyMessage = 'This account has been disabled.';
                        break;
                    case 'auth/invalid-email':
                        userFriendlyMessage = 'The email address format is invalid.';
                        break;
                    default:
                        userFriendlyMessage = `Login error. Please try again. [Code: ${error.code}]`; // Include code for support if needed
                }
            } else if (error instanceof Error) {
                // Handle generic JS errors or custom errors thrown previously
                // Check for specific custom messages
                if (error.message.includes("deletion") || error.message.includes("suspended")) {
                    userFriendlyMessage = error.message; // e.g., "Account marked for deletion..." or "Account suspended..."
                } else {
                    userFriendlyMessage = error.message; // Use the generic error message
                }
            }
            // Rethrow the user-friendly message for the UI component to catch
            throw new Error(userFriendlyMessage);
        }
    }, []); // No dependencies needed here

    // --- Register Function ---
    const register = useMemo(() => async (email: string, password: string, username: string, displayName: string) => {
        try {
            await registerUser(email, password, username, displayName);
        } catch (error: any) {
           //console.error("[AuthContext][Register] Raw Error:", error);
            let userFriendlyMessage = 'Registration failed. Please try again.';
            
            if (error instanceof FirebaseError) {
                // Handle Firebase-specific errors with code property
                if (error.code === 'auth/email-already-in-use') {
                    userFriendlyMessage = 'This email address is already registered. Try logging in.';
                } else if (error.code === 'auth/weak-password') {
                    userFriendlyMessage = 'Password is too weak. ' + passwordRequirementString;
                } else if (error.code === 'auth/invalid-email') {
                    userFriendlyMessage = 'The email address format is invalid.';
                }
            } else if (error instanceof Error) {
                // Handle custom application errors or other Error instances
                if (error.message === 'Username already taken') {
                    userFriendlyMessage = 'That username is already in use. Please choose another.';
                } else if (error.message.includes('email-already-in-use')) {
                    userFriendlyMessage = 'This email address is already registered. Try logging in.';
                } else if (error.message.includes('weak-password')) {
                    userFriendlyMessage = 'Password is too weak. ' + passwordRequirementString;
                } else {
                    // Use original message if it wasn't one of the specific cases above
                    userFriendlyMessage = error.message || userFriendlyMessage;
                }
            }
            throw new Error(userFriendlyMessage);
        }
    }, []);

    // --- Logout Function ---
    const logout = useMemo(() => async () => {
        //console.log("[AuthContext] Attempting logout...");
        try {
            // Clear any grace period timer immediately on explicit logout
            if (gracePeriodTimerRef.current) {
                clearTimeout(gracePeriodTimerRef.current);
                gracePeriodTimerRef.current = null;
            }
            
            await firebaseLogout(); // Use Firebase SDK signOut
            //console.log("[AuthContext] Logout successful.");
            // The onAuthStateChanged listener will handle setting currentUser/userData to null
        } catch (error: any) {
           //console.error("[AuthContext] Logout failed:", error);
            addToast(`Logout failed: ${error.message}`, 'error'); // Inform user via toast
            throw error; // Rethrow if needed elsewhere
        }
    }, [addToast]);

    // --- Reset Password Function ---
    const resetPassword = useMemo(() => async (email: string) => {
        //console.log("[AuthContext] Sending password reset for:", email);
        try {
            await resetPasswordFirebase(email);
            // DO NOT confirm/deny account existence here for security
            addToast(`If an account exists for ${email}, a password reset link has been sent.`, 'success', 8000);
        } catch (error: any) {
           //console.error("[AuthContext][ResetPassword] Raw Error:", error);
            // Provide a generic failure message regardless of the actual Firebase error
            throw new Error("Failed to send reset instructions. Please ensure the email address is correct and try again.");
        }
    }, [addToast]);

    // --- Context Value ---
    const value = useMemo(() => ({
        currentUser,
        userData,
        isLoading,
        login,
        register,
        logout,
        resetPassword
    }), [currentUser, userData, isLoading, login, register, logout, resetPassword]);

    // --- Loading Spinner ---
    if (isLoading) {
        return (
            <div style={{ display: 'flex', justifyContent: 'center', alignItems: 'center', height: '100vh' }}>
                <LoadingSpinner size="large" />
            </div>
        );
    }

    return (
        <AuthContext.Provider value={value}>
            {children}
        </AuthContext.Provider>
    );
};
```

---

## hooks


### hooks\useAuth.tsx

```typescript
// src/hooks/useAuth.tsx
import { useContext } from 'react';
import { AuthContext } from '../contexts/AuthContext';
import { AuthContextType } from '../types';

export const useAuth = (): AuthContextType => {
  const context = useContext(AuthContext);

  // Ensure the hook is used within an AuthProvider
  if (context === undefined) {
    throw new Error('useAuth must be used within an AuthProvider');
  }

  return context;
};
```

---

### hooks\useNetworkStatus.ts

```typescript
// src/hooks/useNetworkStatus.ts
import { useState, useEffect, useCallback } from 'react';
import { useToast } from '../components/common/Toast'; // Adjust path

export const useNetworkStatus = () => {
    // Initialize state based on the current navigator status
    const [isOnline, setIsOnline] = useState(() =>
        typeof navigator !== 'undefined' ? navigator.onLine : true
    );
    const { addToast } = useToast();

    const goOnline = useCallback(() => {
        // Check if status actually changed from offline before showing toast
        if (!isOnline) {
            //console.log("Network status changed: Online");
            setIsOnline(true);
            addToast("You are back online! 🎉", 'success', 4000);
        }
    }, [addToast, isOnline]); // Depend on current isOnline state

    const goOffline = useCallback(() => {
         // Check if status actually changed from online before showing toast
        if (isOnline) {
            //console.log("Network status changed: Offline");
            setIsOnline(false);
            // Use a warning toast that persists longer or indefinitely?
            // For now, use a long duration warning.
            addToast("You are currently offline. Some features may be unavailable.", 'warning', 10000);
        }
    }, [addToast, isOnline]); // Depend on current isOnline state

    useEffect(() => {
        // Add event listeners
        window.addEventListener('online', goOnline);
        window.addEventListener('offline', goOffline);

        // Check status immediately on mount in case it changed before listener attached
        if (typeof navigator !== 'undefined' && navigator.onLine !== isOnline) {
            setIsOnline(navigator.onLine);
        }

        // Cleanup listeners on unmount
        return () => {
            window.removeEventListener('online', goOnline);
            window.removeEventListener('offline', goOffline);
        };
        // Dependencies ensure listeners use the latest stateful callbacks
    }, [goOnline, goOffline, isOnline]);

    return isOnline; // Return the current status
};
```

---

### index.scss

```scss
// src/index.scss
@import './styles/variables';
@import './styles/base';

```

---

### index.tsx

```typescript
// src/index.tsx
import React from 'react';
import ReactDOM from 'react-dom/client';
import App from './App';
import './index.scss';

const root = ReactDOM.createRoot(
  document.getElementById('root') as HTMLElement
);

root.render(
  <React.StrictMode>
    <App />
  </React.StrictMode>
);


```

---

## layouts


### layouts\AdminLayout.module.scss

```scss
// src/layouts/AdminLayout.module.scss
@import '../styles/variables';

.adminLayout {
  display: flex;
  min-height: 100vh;
  background-color: var(--color-bg-primary); // Main background
}

// --- Sidebar ---
.sidebar {
  width: 240px; // Standard sidebar width
  flex-shrink: 0;
  background-color: var(--color-bg-secondary); // Sidebar background
  color: var(--color-text-primary); // Text color for sidebar content
  display: flex;
  flex-direction: column;
  border-right: $border-width-base solid var(--color-border-primary); // Separator line
  transition: background-color 0.2s ease-in-out, border-color 0.2s ease-in-out;
}

.sidebarHeader {
  padding: $spacing-md;
  height: 56px + ($spacing-sm * 2); // Match header height + padding
  display: flex;
  align-items: center;
  justify-content: center; // Or left-align
  border-bottom: $border-width-base solid var(--color-border-primary);
}

.sidebarBrand {
  color: var(--color-primary);
  font-size: $font-size-lg;
  font-weight: 700; // Bold brand
  text-decoration: none;
  &:hover, &:focus {
    text-decoration: none;
    color: var(--color-primary-dark);
  }
  &:focus-visible {
      outline: none;
      // Optional: custom ring
  }
}

.sidebarNav {
  flex-grow: 1; // Take remaining vertical space
  padding: $spacing-md 0; // Padding top/bottom
  display: flex;
  flex-direction: column;
  gap: $spacing-xs; // Small gap between nav items
}

.sidebarLink {
  display: flex; // Use flex for icon alignment
  align-items: center;
  gap: $spacing-sm; // Space between icon and text
  padding: $spacing-sm $spacing-lg; // Adjust padding
  margin: 0 $spacing-sm; // Horizontal margin to allow background effects
  color: var(--color-text-secondary);
  text-decoration: none;
  border-radius: $border-radius-md; // Rounded links
  transition: background-color 0.2s ease, color 0.2s ease, box-shadow 0.15s ease;
  font-weight: 500;

  &:hover {
    background-color: var(--color-bg-tertiary); // Hover background
    color: var(--color-text-primary); // Hover text color
    text-decoration: none;
  }

  &.active { // Style for active NavLink (from React Router)
    background-color: var(--color-primary-light); // Active background
    color: var(--color-primary-dark); // Active text color
    font-weight: 600; // Bolder active link
    // Optional: Add a subtle left border or different indicator
    // border-left: 3px solid var(--color-primary);
  }

  &:focus-visible {
      outline: none;
      background-color: var(--color-bg-tertiary); // Ensure hover bg on focus
      box-shadow: inset 0 0 0 2px var(--color-primary-light); // Inset focus ring
  }
}

.navIcon {
  flex-shrink: 0; // Prevent icon shrinking
  width: 18px;
  height: 18px;
  // Color is inherited from .sidebarLink text color by default
}


.sidebarFooter {
  padding: $spacing-md;
  border-top: $border-width-base solid var(--color-border-primary);
  display: flex;
  flex-direction: column;
  gap: $spacing-md;

  .backLink {
    // Reuse sidebarLink styles or create specific ones
    display: flex;
    align-items: center;
    justify-content: center; // Center link text/icon
    gap: $spacing-sm;
    font-size: $font-size-sm;
    color: var(--color-text-secondary);
    padding: $spacing-xs;
    border-radius: $border-radius-md;

    &:hover, &:focus {
        background-color: var(--color-bg-tertiary);
        color: var(--color-text-primary);
        text-decoration: none;
    }
     &:focus-visible {
      outline: none;
      box-shadow: inset 0 0 0 2px var(--color-primary-light); // Inset focus ring
    }
  }
  // Logout button styling handled by Button component styles
 // button {
      // Apply 'text' or 'outline' variant as appropriate
      // Maybe force small size?
  //}
}


// --- Main Content Area ---
.mainContent {
  flex-grow: 1;
  display: flex;
  flex-direction: column;
  overflow-x: hidden;
  background-color: var(--color-bg-primary); // Ensure main area bg matches theme
}

// Header within the main content area (Optional, could be simpler)
.mainHeader {
  background-color: var(--color-bg-secondary); // Match sidebar or header bg
  padding: 0 $spacing-lg; // Horizontal padding
  height: 56px + ($spacing-sm * 2); // Match sidebar header height
  border-bottom: $border-width-base solid var(--color-border-primary);
  display: flex;
  align-items: center;
  color: var(--color-text-primary);
  font-size: $font-size-lg;
  font-weight: 600;
  flex-shrink: 0; // Prevent shrinking
}

.pageContent {
  flex-grow: 1; // Takes remaining space
  padding: $spacing-xl; // Generous padding around admin page content
  overflow-y: auto; // Allow content scrolling if needed
}
```

---

### layouts\AdminLayout.tsx

```typescript
// src/layouts/AdminLayout.tsx
import React from 'react';
import { Link, NavLink, Outlet, useNavigate } from 'react-router-dom'; // Import useNavigate
import { useAuth } from '../hooks/useAuth'; // Adjust path
import Button from '../components/common/Button/Button'; // Adjust path
import styles from './AdminLayout.module.scss'; // Adjust path
import { useToast } from '../components/common/Toast'; // Adjust path
// Import Feather icons
import { FiUsers, FiMessageSquare, FiSlash, FiCreditCard, FiHome, FiLogOut, FiGrid, FiSliders } from 'react-icons/fi';

interface AdminLayoutProps {}

const AdminLayout: React.FC<AdminLayoutProps> = () => {
    const { logout } = useAuth();
    const navigate = useNavigate();
    const { addToast } = useToast();

    const handleLogout = async () => {
        try {
            await logout();
            addToast('Admin logged out.', 'info');
            navigate('/login'); // Redirect to login after admin logout
        } catch (error: any) {
           //console.error("Admin logout failed:", error);
            addToast(error.message || "Admin logout failed.", 'error');
        }
    };

    // Function to determine active class for NavLink
    const getNavLinkClass = ({ isActive }: { isActive: boolean }): string =>
        isActive ? `${styles.sidebarLink} ${styles.active}` : styles.sidebarLink;

    return (
        <div className={styles.adminLayout}>
            {/* Sidebar */}
            <aside className={styles.sidebar}>
                <div className={styles.sidebarHeader}>
                    <Link to="/admin" className={styles.sidebarBrand} title="Admin Dashboard">
                        {/* Optionally add an icon */}
                        {/* <FiSettings style={{ marginRight: '8px' }} /> */}
                        Admin Portal
                    </Link>
                </div>
                <nav className={styles.sidebarNav}>
                    <NavLink to="/admin" end className={getNavLinkClass}>
                        <FiGrid className={styles.navIcon} aria-hidden="true"/> Dashboard
                    </NavLink>
                    <NavLink to="/admin/users" className={getNavLinkClass}>
                        <FiUsers className={styles.navIcon} aria-hidden="true"/> Users
                    </NavLink>
                    <NavLink to="/admin/contacts" className={getNavLinkClass}>
                        <FiMessageSquare className={styles.navIcon} aria-hidden="true"/> Contacts
                    </NavLink>
                    <NavLink to="/admin/payments" className={getNavLinkClass}>
                        <FiCreditCard className={styles.navIcon} aria-hidden="true"/> Payments
                    </NavLink>
                    <NavLink to="/admin/deleted-users" className={getNavLinkClass}>
                        <FiSlash className={styles.navIcon} aria-hidden="true"/> Deleted Users
                    </NavLink>
                    <NavLink to="/admin/configurations" className={getNavLinkClass}><FiSliders /> Configurations</NavLink>
                    {/* Add links to other admin sections here */}
                </nav>
                <div className={styles.sidebarFooter}>
                   <Link to="/dashboard" className={styles.backLink} title="Go back to user dashboard">
                       <FiHome className={styles.navIcon} aria-hidden="true"/> Back to Site
                   </Link>
                   <Button
                       onClick={handleLogout}
                       variant="text" // Use text variant for less emphasis
                       size="small"
                       fullWidth
                       title="Log out of admin session"
                   >
                       <FiLogOut className={styles.navIcon} aria-hidden="true"/> Logout
                   </Button>
                </div>
            </aside>

            {/* Main Content Area */}
            <div className={styles.mainContent}>
                <header className={styles.mainHeader}>
                    {/* Could display current section title here later */}
                    Admin Panel
                </header>
                <main className={styles.pageContent}>
                    {/* Nested routes defined in AppRoutes will render here */}
                    <Outlet />
                </main>
            </div>
        </div>
    );
};

export default AdminLayout;
```

---

### layouts\MainLayout.module.scss

```scss
// src/layouts/MainLayout.module.scss
@import '../styles/variables';

.layout {
  display: flex;
  flex-direction: column;
  min-height: 100vh; // Ensure layout takes full viewport height
  background-color: var(--color-bg-primary); // Main background color
}

.mainContent {
  flex-grow: 1; // Allow main content to fill available vertical space
  padding-top: $spacing-xl; // Generous space below header
  padding-bottom: $spacing-xl; // Generous space above footer
  width: 100%; // Takes full width horizontally

  // Container class applied *within* pages will handle content max-width
}
```

---

### layouts\MainLayout.tsx

```typescript
// src/layouts/MainLayout.tsx
import React, { ReactNode } from 'react';
import Header from '../components/common/Header/Header'; // Adjust path
import Footer from '../components/common/Footer/Footer'; // Adjust path
import styles from './MainLayout.module.scss'; // Adjust path

// --- Receive theme props from App.tsx ---
interface MainLayoutProps {
    children: ReactNode;
    theme?: 'light' | 'dark';
    toggleTheme?: () => void;
}

const MainLayout: React.FC<MainLayoutProps> = ({ children, theme, toggleTheme }) => {
    return (
        <div className={styles.layout}>
            {/* Pass theme props to Header */}
            <Header theme={theme} toggleTheme={toggleTheme} />
            <main className={styles.mainContent}>
                {/* Children (Pages) are rendered here */}
                {children}
            </main>
            <Footer />
        </div>
    );
};

export default MainLayout;
```

---

## pages


## pages\AboutPage


### pages\AboutPage\AboutPage.tsx

```typescript
// src/pages/AboutPage/AboutPage.tsx
import React from 'react';
import MainLayout from '../../layouts/MainLayout'; // Adjust path
import pageStyles from '../PageStyles.module.scss'; // Shared styles (mostly for wrapper)
import staticStyles from '../StaticPage.module.scss'; // Styles for static content container
import { Link } from 'react-router-dom';

const AboutPage: React.FC = () => {
  // --- Get theme props if needed by MainLayout ---
  // const { theme, toggleTheme } = useTheme(); // Assuming a theme context or props passed down

  return (
    // Pass theme props if MainLayout expects them
    <MainLayout /* theme={theme} toggleTheme={toggleTheme} */ >
      {/* Apply base page wrapper and container centering */}
      <div className={`container ${pageStyles.pageWrapper} ${staticStyles.pageWrapperOverride}`}>
        {/* Apply the specific styling for the static content box */}
        <div className={staticStyles.staticPageContainer}>

          {/* --- Page Content (Keep existing valid HTML structure) --- */}
          <h1>About MyServices Portal</h1>
          <p>
            Tired of juggling multiple logins and searching endlessly for the right study tools and resources? The MyServices Portal by Samkarya is your central gateway, designed to streamline your access to essential educational services.
          </p>

          <h2>Our Mission: Simplify Your Journey</h2>
          <p>
            Our mission is to provide a seamless, secure, and unified experience for students. We believe that by centralizing access and simplifying account management, you can spend less time navigating and more time learning and preparing effectively.
          </p>

          <h2>Why Use the Portal?</h2>
          <ul>
            <li>
              <strong>Single Sign-On (SSO):</strong> Log in once here and gain access to connected services like Examify without needing separate credentials.
            </li>
            <li>
              <strong>Centralized Dashboard:</strong> Discover, launch, and manage all available Samkarya educational services from one convenient hub.
            </li>
            <li>
              <strong>Secure Profile Management:</strong> Easily update your display name, manage your password securely, verify your email, and control your account settings all in one place.
            </li>
            <li>
              <strong>Unified Experience:</strong> Enjoy a consistent look and feel as you navigate between different tools within our ecosystem.
            </li>
          </ul>

          <h2>Explore Our Services</h2>
          <p>From your dashboard, you can currently access:</p>
          <ul>
            <li>
              <strong><a href="https://examify.web.app" target="_blank" rel="noopener noreferrer">Examify Exam Simulator</a>:</strong> Practice realistically for competitive entrance exams (like NIMCET, CUET MCA) with features like timed tests, question palettes, custom uploads, and detailed performance analysis.
            </li>
            <li>
              <strong><a href="https://bcaexamprep.blogspot.com/" target="_blank" rel="noopener noreferrer">BCA Exam Prep Blog</a>:</strong> A rich resource site featuring MCQs, Previous Year Questions (PYQs), syllabus details, career guidance, and informative articles for BCA and related fields.
            </li>
          </ul>
          <p>
            <em>We're always working on expanding our offerings! Stay tuned for future additions.</em>
          </p>

          <h2>Get Started</h2>
          <p>
            If you haven't already, <Link to="/register">create your free account</Link> or <Link to="/login">log in</Link> to access your personalized dashboard and start using our services today.
          </p>

          <hr />

          <p style={{ textAlign: 'center', marginTop: "2rem", color: "var(--color-text-tertiary)" }}> {/* Muted text */}
            Built by Samkarya. We're passionate about leveraging technology to support student success. Have feedback? <Link to="/contact">Let us know!</Link>
          </p>
          {/* --- End Page Content --- */}

        </div>
      </div>
    </MainLayout>
  );
};

export default AboutPage;
```

---

## pages\Admin


### pages\Admin\AdminConfigurationsPage.module.scss

```scss
// src/pages/Admin/AdminConfigurationsPage.module.scss
@import '../../styles/variables';

.configurationsPage {
  h1 { /* ... same as other admin page H1 ... */
    font-size: $font-size-h2; color: var(--color-primary); margin-bottom: $spacing-lg;
  }
  p { color: var(--color-text-secondary); margin-bottom: $spacing-lg; }
}

.configSelector {
  display: flex;
  flex-wrap: wrap;
  gap: $spacing-sm;
  margin-bottom: $spacing-xl;
  padding-bottom: $spacing-md;
  border-bottom: 1px solid var(--color-border-primary);
}

.editorContainer {
  padding: $spacing-lg;
  background-color: var(--color-bg-secondary);
  border-radius: $border-radius-md;
  border: 1px solid var(--color-border-primary);
  min-height: 300px; // Ensure space for editor
}

.configEditor { // Base for any specific editor component
  h4 {
    font-size: $font-size-lg;
    color: var(--color-text-primary);
    margin-bottom: $spacing-md;
    padding-bottom: $spacing-xs;
    border-bottom: 1px dashed var(--color-border-secondary);
    display: flex; justify-content: space-between; align-items: center;
  }
  label {
    display: block;
    font-weight: 500;
    font-size: $font-size-sm;
    color: var(--color-text-secondary);
    margin-bottom: $spacing-xs;
    margin-top: $spacing-sm;
  }
  input[type="text"], input[type="number"], textarea, select {
    width: 100%;
    padding: $spacing-sm;
    border: 1px solid var(--color-border-input);
    border-radius: $border-radius-sm;
    background-color: var(--color-bg-primary);
    color: var(--color-text-primary);
    font-size: $font-size-sm;
    margin-bottom: $spacing-sm;
    &:focus {
      outline: none;
      border-color: var(--color-primary);
      box-shadow: var(--shadow-focus-ring);
    }
  }
  textarea {
    min-height: 80px;
    resize: vertical;
  }
}

.tierEditItem {
  border: 1px solid var(--color-border-secondary);
  border-radius: $border-radius-sm;
  padding: $spacing-md;
  margin-bottom: $spacing-lg;
  background-color: var(--color-bg-primary);
}
.pricingOptionEdit, .featureEditItem {
    display: flex;
    gap: $spacing-sm;
    align-items: center;
    margin-bottom: $spacing-xs;
    padding-left: $spacing-md; // Indent nested items
    input[type="text"], input[type="number"], select { margin-bottom: 0; } // Remove bottom margin on inline inputs
}
.featureEditItem input { flex-grow: 1; }


.jsonEditor { // For displaying/editing raw JSON
  width: 100%;
  min-height: 300px;
  font-family: monospace;
  font-size: $font-size-sm;
  border: 1px solid var(--color-border-input);
  border-radius: $border-radius-md;
  padding: $spacing-md;
  background-color: var(--color-bg-primary);
  color: var(--color-text-primary);
  white-space: pre;
  overflow: auto;
}

.resetAllSection {
  margin-top: $spacing-xl * 2;
  padding: $spacing-lg;
  border: 1px solid var(--color-error);
  background-color: var(--color-error-light);
  border-radius: $border-radius-md;
  text-align: center;
  h3 {
    color: var(--color-error-dark);
    margin-top: 0;
    svg { color: var(--color-error); }
  }
  p { color: var(--color-error-dark); font-weight: 500; }
  // Button styled via variant="danger"
}
```

---

### pages\Admin\AdminConfigurationsPage.tsx

```typescript
// src/pages/Admin/AdminConfigurationsPage.tsx
import React, { useState, useEffect, useCallback } from 'react';
import { useToast } from '../../components/common/Toast';
import Button from '../../components/common/Button/Button';
import LoadingSpinner from '../../components/common/LoadingSpinner/LoadingSpinner';
import {
    // Import admin functions for fetching and updating configs (to be created)
    getSpecificConfigAdmin, // e.g., getConfigAdmin('tiers')
    updateSpecificConfigAdmin, // e.g., updateConfigAdmin('tiers', newTiersData)
} from '../../services/adminService';
import { TierConfig } from '../../types';
import styles from './AdminConfigurationsPage.module.scss'; // Create this SCSS file
import { FiSave, FiRefreshCw, FiAlertTriangle, FiPlusCircle, FiTrash2 } from 'react-icons/fi';

// Define which configurations are editable
type EditableConfigKey = 'tiers' | 'services' | 'payments' | 'global' | 'examify' | 'bcaPrepBlog'; // Add as needed

/*interface ConfigSection<T> {
    title: string;
    docId: EditableConfigKey;
    data: T | null;
    isLoading: boolean;
    editorComponent?: React.FC<{ data: T; onSave: (updatedData: T) => Promise<void>; }>;
}*/

// --- Simple Tier Editor Component (Example) ---
// For complex configs like arrays of objects, you'll need more robust editors
// src/pages/Admin/AdminConfigurationsPage.tsx
// ... (imports and other parts of AdminConfigurationsPage)

// --- Simple Tier Editor Component (Example) ---
// For complex configs like arrays of objects, you'll need more robust editors
const TierEditor: React.FC<{
    tiers: TierConfig[]; // TierConfig type should now reflect new structure (including PaidTierId = 'basic' | 'pro' | 'elite')
    onSave: (updatedTiers: TierConfig[]) => Promise<void>;
}> = ({ tiers: initialTiers, onSave }) => {
    const [localTiers, setLocalTiers] = useState<TierConfig[]>(initialTiers ? JSON.parse(JSON.stringify(initialTiers)) : []);
    const [isSaving, setIsSaving] = useState(false);

    useEffect(() => {
        setLocalTiers(initialTiers ? JSON.parse(JSON.stringify(initialTiers)) : []);
    }, [initialTiers]);

    // handleTierChange needs to correctly update nested 'limits'
    const handleTierChange = (index: number, field: keyof TierConfig | keyof TierConfig["limits"], value: any, isLimitField: boolean = false) => {
        const updatedTiers = [...localTiers];
        const tierToUpdate = { ...updatedTiers[index] };

        if (isLimitField && field in tierToUpdate.limits) {
            // Ensure value is number or null for limits
            const numericValue = value === '' ? null : parseInt(value, 10);
            tierToUpdate.limits = { ...tierToUpdate.limits, [field]: isNaN(numericValue as any) ? null : numericValue };
        } else if (!isLimitField && field in tierToUpdate) {
            (tierToUpdate as any)[field] = value;
        }
        updatedTiers[index] = tierToUpdate;
        setLocalTiers(updatedTiers);
    };

    const handleAddFeature = (tierIndex: number) => { /* ... no change needed ... */ };
    const handleRemoveFeature = (tierIndex: number, featureIndex: number) => { /* ... no change needed ... */ };
    const handleFeatureChange = (tierIndex: number, featureIndex: number, value: string) => { /* ... no change needed ... */ };

    // Add a new tier
    const handleAddTier = () => {
        const newTier: TierConfig = {
            // Ensure this default matches the new structure expectations
            id: `new-tier-${Date.now()}` as any, // Admin should change this to 'basic', 'pro', or 'elite' if it's a standard paid tier. Or a custom ID for a new non-standard one.
            name: 'New Tier Name (e.g., Basic)',
            pricingOptions: [{billingCycle: 'monthly', priceINR: 0, durationMonths: 1, displaySuffix: '/mo', savingsText: ''}],
            description: 'Description for the new tier.',
            features: ["Feature 1", "Feature 2"],
            limits: { examAttempts: 10, hostedSessions: 1 }, // Default limits for a new tier
        };
        setLocalTiers([...localTiers, newTier]);
    };
    const handleRemoveTier = (index: number) => { /* ... no change needed ... */ };


    const handleSaveTiers = async () => {
        setIsSaving(true);
        try {
            // Validation before saving:
            // 1. Ensure tier IDs ('free', 'basic', 'pro', 'elite') are unique if they are standard.
            // 2. Validate numeric fields (price, duration, limits).
            // 3. Ensure required fields are not empty.
            const tierIds = localTiers.map(t => t.id);
            const standardTierIds = ['free', 'basic', 'pro', 'elite'];
            const duplicateStandardIds = tierIds.filter((id, idx) => standardTierIds.includes(id as any) && tierIds.indexOf(id) !== idx);

            if (duplicateStandardIds.length > 0) {
                alert(`Error: Duplicate standard tier IDs found: ${duplicateStandardIds.join(', ')}. IDs 'free', 'basic', 'pro', 'elite' must be unique.`);
                setIsSaving(false);
                return;
            }

            // Basic validation for prices and limits
            for (const tier of localTiers) {
                if (tier.pricingOptions.some(opt => isNaN(opt.priceINR) || opt.priceINR < 0)) {
                    alert(`Error: Tier '${tier.name}' has invalid price. Price must be a non-negative number.`);
                    setIsSaving(false); return;
                }
                if (tier.limits.examAttempts !== null && (isNaN(tier.limits.examAttempts) || tier.limits.examAttempts < 0)) {
                    alert(`Error: Tier '${tier.name}' has invalid exam attempts limit. Must be non-negative number or empty for unlimited.`);
                    setIsSaving(false); return;
                }
                if (tier.limits.hostedSessions !== null && (isNaN(tier.limits.hostedSessions) || tier.limits.hostedSessions < 0)) {
                    alert(`Error: Tier '${tier.name}' has invalid hosted sessions limit. Must be non-negative or empty for unlimited.`);
                    setIsSaving(false); return;
                }
                if (!tier.id.trim() || !tier.name.trim()) {
                     alert(`Error: Tier ID and Name cannot be empty for tier index ${localTiers.indexOf(tier) +1 }.`);
                     setIsSaving(false); return;
                }
            }

            await onSave(localTiers);
        } catch (e){
            // Error already handled by onSave in parent if it throws, but alert here is also fine.
            alert(`Save failed: ${(e as Error).message}`);
        }
        finally {
            setIsSaving(false);
        }
    };

    return (
        <div className={styles.configEditor}>
            {localTiers.map((tier, index) => (
                <div key={tier.id || index} className={styles.tierEditItem}>
                    <h4>Editing: {tier.name || `Tier ${index + 1}`} ({tier.id}) <Button size="small" variant="danger" onClick={()=> handleRemoveTier(index)} style={{marginLeft: 'auto'}}><FiTrash2/></Button></h4>
                    <div><label>ID (must be 'free', 'basic', 'pro', 'elite', or unique custom ID):</label>
                        <input type="text" value={tier.id} onChange={e => handleTierChange(index, 'id', e.target.value)} placeholder="e.g., basic, pro (no spaces, lowercase)" />
                    </div>
                    <div><label>Name:</label><input type="text" value={tier.name} onChange={e => handleTierChange(index, 'name', e.target.value)} /></div>
                    <div><label>Description:</label><textarea value={tier.description} onChange={e => handleTierChange(index, 'description', e.target.value)} /></div>

                    <h5>Pricing Options:</h5>
                    {tier.pricingOptions.map((opt, optIndex) => (
                        <div key={optIndex} className={styles.pricingOptionEdit}>
                            <select value={opt.billingCycle} onChange={e => {
                                const updatedTiers = [...localTiers];
                                updatedTiers[index].pricingOptions[optIndex].billingCycle = e.target.value as 'monthly' | 'yearly';
                                setLocalTiers(updatedTiers);
                            }}>
                                <option value="monthly">Monthly</option>
                                <option value="yearly">Yearly</option>
                            </select>
                            <input type="number" value={opt.priceINR} placeholder="Price (INR)" onChange={e => {
                                const updatedTiers = [...localTiers];
                                updatedTiers[index].pricingOptions[optIndex].priceINR = parseFloat(e.target.value) || 0;
                                setLocalTiers(updatedTiers);
                            }} />
                            <input type="number" value={opt.durationMonths} placeholder="Duration (Months)" onChange={e => {
                                const updatedTiers = [...localTiers];
                                updatedTiers[index].pricingOptions[optIndex].durationMonths = parseInt(e.target.value) || 1;
                                setLocalTiers(updatedTiers);
                            }} />
                             <input type="text" value={opt.displaySuffix || ''} placeholder="Suffix (e.g. /mo)" onChange={e => {
                                const updatedTiers = [...localTiers];
                                updatedTiers[index].pricingOptions[optIndex].displaySuffix = e.target.value;
                                setLocalTiers(updatedTiers);
                            }} />
                            <input type="text" value={opt.savingsText || ''} placeholder="Savings (e.g. Save 20%)" onChange={e => {
                                const updatedTiers = [...localTiers];
                                updatedTiers[index].pricingOptions[optIndex].savingsText = e.target.value;
                                setLocalTiers(updatedTiers);
                            }} />
                            {/* TODO: Button to remove pricing option */}
                        </div>
                    ))}
                     {/* TODO: Button to add pricing option */}


                    <h5>Features (Enter one feature string per line/input):</h5>
                    {tier.features.map((feature, fIndex) => (
                        <div key={fIndex} className={styles.featureEditItem}>
                            <input type="text" value={feature} onChange={(e) => handleFeatureChange(index, fIndex, e.target.value)} />
                            <Button size="small" variant="text" onClick={() => handleRemoveFeature(index, fIndex)}><FiTrash2/></Button>
                        </div>
                    ))}
                    <Button size="small" variant="outline" onClick={() => handleAddFeature(index)} style={{marginTop: '8px'}}><FiPlusCircle/> Add Feature</Button>

                    <h5>Limits:</h5>
                     <div><label>Exam Attempts (empty for unlimited):</label>
                        <input type="number" value={tier.limits.examAttempts ?? ''} placeholder="Number or empty for unlimited" onChange={e => handleTierChange(index, 'examAttempts', e.target.value, true)} />
                     </div>
                     <div><label>Hosted Sessions (empty for unlimited):</label>
                        <input type="number" value={tier.limits.hostedSessions ?? ''} placeholder="Number or empty for unlimited" onChange={e => handleTierChange(index, 'hostedSessions', e.target.value, true)} />
                     </div>
                </div>
            ))}
            <Button variant="secondary" onClick={handleAddTier} style={{ margin: '20px 0' }}><FiPlusCircle/> Add New Tier</Button>
            <Button onClick={handleSaveTiers} loading={isSaving} variant="primary" size="large"><FiSave/> Save Tiers Configuration</Button>
        </div>
    );
};
// --- End Tier Editor ---

// ... (rest of AdminConfigurationsPage.tsx)
// Ensure JsonEditor and renderConfigEditor correctly pass data for other configs
const AdminConfigurationsPage: React.FC = () => {
    const { addToast } = useToast();
    const [activeConfigKey, setActiveConfigKey] = useState<EditableConfigKey>('tiers');
    const [configData, setConfigData] = useState<Record<EditableConfigKey, any | null>>({
        tiers: null, services: null, payments: null, global: null, examify: null, bcaPrepBlog: null
    });
    const [isLoading, setIsLoading] = useState<Record<EditableConfigKey, boolean>>({
        tiers: true, services: true, payments: true, global: true, examify: true, bcaPrepBlog: true
    });
    const [isSaving, setIsSaving] = useState<Partial<Record<EditableConfigKey, boolean>>>({});


    const fetchConfig = useCallback(async (key: EditableConfigKey) => {
        setIsLoading(prev => ({ ...prev, [key]: true }));
        try {
            const data = await getSpecificConfigAdmin(key); 
            setConfigData(prev => ({ ...prev, [key]: data }));
        } catch (error: any) {
            addToast(`Error fetching ${key} config: ${error.message}`, "error");
            setConfigData(prev => ({ ...prev, [key]: { error: error.message } })); 
        } finally {
            setIsLoading(prev => ({ ...prev, [key]: false }));
        }
    }, [addToast]);

    useEffect(() => {
        fetchConfig(activeConfigKey);
    }, [fetchConfig, activeConfigKey]);

    const handleSaveConfig = async (key: EditableConfigKey, updatedData: any) => {
        setIsSaving(prev => ({...prev, [key]: true }));
        try {
            let dataToSave = updatedData; 

            if (key === 'tiers' && Array.isArray(updatedData)) { 
                dataToSave = { tiers: updatedData };
            } else if (key === 'services' && (updatedData.defaultServices || updatedData.availableServices)) {
                dataToSave = {
                    defaultServices: updatedData.defaultServices || [],
                    availableServices: updatedData.availableServices || []
                };
            } else if ((key === 'examify' || key === 'bcaPrepBlog') && typeof updatedData === 'object' && !Array.isArray(updatedData)) {
                dataToSave = { settings: updatedData };
            }
            
            await updateSpecificConfigAdmin(key, dataToSave);
            addToast(`${key.charAt(0).toUpperCase() + key.slice(1)} configuration saved!`, "success");
            // If saving "tiers", the data passed (updatedData) is array, but stored as {tiers: array}
            // So, when updating local state, ensure it matches Firestore structure
            setConfigData(prev => ({ ...prev, [key]: dataToSave }));
        } catch (error: any) {
            addToast(`Error saving ${key} config: ${error.message}`, "error");
        } finally {
            setIsSaving(prev => ({...prev, [key]: false }));
        }
    };
    
    const handleResetAllConfigs = async () => { /* ... no change needed ... */ };

    const renderConfigEditor = () => {
        const currentData = configData[activeConfigKey];
        const currentIsLoading = isLoading[activeConfigKey];

        if (currentIsLoading) return <LoadingSpinner size="large" />;
        if (!currentData || currentData.error) return <div className="alert alert-error">Error loading {activeConfigKey}: {currentData?.error || "Data not found or invalid."}</div>;

        switch (activeConfigKey) {
            case 'tiers':
                // The TierEditor expects an array of tiers.
                // The data fetched by getSpecificConfigAdmin('tiers') returns { tiers: TierConfig[] }
                // So, we pass currentData.tiers to the TierEditor.
                return currentData.tiers ?
                    <TierEditor
                        tiers={currentData.tiers as TierConfig[]} // Pass the array
                        onSave={(updatedTiersArray) => handleSaveConfig('tiers', updatedTiersArray)} // handleSaveConfig expects the array for 'tiers' key specifically
                    /> : <p>Tiers data is missing or in incorrect format.</p>;
            // ... (other cases remain the same as previous version, ensuring they pass correct part of currentData if nested)
            case 'services':
                 return <JsonEditor
                            jsonData={currentData} 
                            onSave={(updatedJson) => handleSaveConfig('services', updatedJson)}
                            configKey="services"
                            isSaving={!!isSaving['services']}
                        />;
            case 'examify':
            case 'bcaPrepBlog':
                return currentData.settings ?
                        <JsonEditor
                            jsonData={currentData.settings} 
                            onSave={(updatedSettings) => handleSaveConfig(activeConfigKey, updatedSettings)}
                            configKey={activeConfigKey}
                            isSaving={!!isSaving[activeConfigKey]}
                        /> : <p>{activeConfigKey} settings data is missing or in incorrect format.</p>;

            case 'payments':
            case 'global':
                return <JsonEditor
                            jsonData={currentData}
                            onSave={(updatedJson) => handleSaveConfig(activeConfigKey, updatedJson)}
                            configKey={activeConfigKey}
                            isSaving={!!isSaving[activeConfigKey]}
                        />;
            default:
                return <p>No specific editor for '{activeConfigKey}'. Raw: <pre>{JSON.stringify(currentData, null, 2)}</pre></p>;
        }
    };
    // ... (rest of the component including JSX structure, configSelector, editorContainer, resetAllSection)
    return (
        <div className={styles.configurationsPage}>
            <h1>Application Configurations</h1>
            <p>Manage various settings for the portal and its services. Changes here are live and will affect the application behavior.</p>

            <div className={styles.configSelector}>
                {(Object.keys(configData) as EditableConfigKey[]).map(key => (
                    <Button
                        key={key}
                        variant={activeConfigKey === key ? "primary" : "outline"}
                        onClick={() => {
                            setActiveConfigKey(key);
                            if(configData[key] === null && !isLoading[key]) {
                                fetchConfig(key);
                            }
                        }}
                    >
                        {key.charAt(0).toUpperCase() + key.slice(1)}
                    </Button>
                ))}
            </div>

            <div className={styles.editorContainer}>
                {renderConfigEditor()}
            </div>
            {/* ResetAllSection placeholder - no changes needed from original */}
            <div className={styles.resetAllSection}>
                <h3><FiAlertTriangle/> Reset All Configurations</h3>
                <p>This will overwrite ALL configurations with the application defaults. Use with caution.</p>
                <Button onClick={handleResetAllConfigs} variant="danger" loading={isLoading.global /* Example */}>
                    <FiRefreshCw/> Reset ALL to Defaults
                </Button>
            </div>
        </div>
    );
};

// --- Placeholder JsonEditor if not already defined ---
interface JsonEditorProps { jsonData: any; onSave: (updatedJsonData: any) => Promise<void>; configKey: EditableConfigKey; isSaving: boolean; }
const JsonEditor: React.FC<JsonEditorProps> = ({ jsonData, onSave, configKey, isSaving }) => {
    const { addToast } = useToast();
    const textareaId = `json-editor-${configKey}`;
    const handleSave = async () => {
        const textareaElement = document.getElementById(textareaId) as HTMLTextAreaElement;
        if (textareaElement) {
            try {
                const newJson = JSON.parse(textareaElement.value);
                await onSave(newJson);
            } catch (e: any) { addToast(`Invalid JSON for ${configKey}: ${e.message}`, "error"); }
        }
    };
    return (
        <div>
            <textarea id={textareaId} className={styles.jsonEditor} defaultValue={JSON.stringify(jsonData, null, 2)} rows={20} />
            <Button onClick={handleSave} loading={isSaving} variant="primary" style={{ marginTop: '10px', display: 'block' }} >
                <FiSave style={{ marginRight: '8px' }}/> Save {configKey.charAt(0).toUpperCase() + configKey.slice(1)} Config
            </Button>
        </div>
    );
};


export default AdminConfigurationsPage;
```

---

### pages\Admin\AdminContactsPage.module.scss

```scss
// src/pages/Admin/AdminContactsPage.module.scss
@import '../../styles/variables';

.contactsPage {
  h1 {
    font-size: $font-size-h2;
    color: var(--color-primary);
    margin-bottom: $spacing-lg;
  }
}

// --- Notification Controls --- (Similar to AdminPaymentsPage)
.notificationControl {
    margin-bottom: $spacing-lg;
    display: flex;
    flex-wrap: wrap; // Allow wrapping
    align-items: center;
    gap: $spacing-md;
    padding: $spacing-sm $spacing-md;
    background-color: var(--color-bg-secondary);
    border-radius: $border-radius-md;
    border: 1px solid var(--color-border-primary);
    font-size: $font-size-sm;
}
.notificationStatusDenied {
    color: var(--color-error-dark); // Use theme error color
    display: flex;
    align-items: center;
    gap: $spacing-xs;
    svg { color: var(--color-error); } // Make icon match
}

// --- Filter Controls ---
.controls {
  display: flex;
  margin-bottom: $spacing-lg;
  padding: $spacing-md;
  background-color: var(--color-bg-secondary);
  border-radius: $border-radius-md;
  border: $border-width-base solid var(--color-border-primary);
}

.filterGroup {
  display: flex;
  align-items: center;
  gap: $spacing-sm;

  label {
    font-weight: 500;
    font-size: $font-size-sm;
    color: var(--color-text-secondary);
  }

  select {
    padding: $spacing-xs $spacing-sm;
    border-radius: $border-radius-md;
    border: $border-width-base solid var(--color-border-input);
    background-color: var(--color-bg-primary);
    color: var(--color-text-primary);
    min-width: 150px;
    font-size: $font-size-sm;
    transition: border-color 0.2s ease, box-shadow 0.15s ease;

    &:focus {
      outline: none;
      border-color: var(--color-border-input-focus);
      // Focus ring handled globally
    }
    &:disabled {
       background-color: var(--color-bg-tertiary);
       cursor: not-allowed;
       opacity: 0.7;
    }
  }
}

// --- Submissions Table ---
.submissionsTable {
  width: 100%;
  border-collapse: collapse;
  margin-bottom: $spacing-lg;
  background-color: var(--color-bg-primary);
  box-shadow: var(--shadow-md);
  border-radius: $border-radius-md;
  border: $border-width-base solid var(--color-border-primary);
  overflow: hidden;

  th, td {
    padding: $spacing-sm $spacing-md;
    text-align: left;
    border-bottom: $border-width-base solid var(--color-border-primary);
    vertical-align: middle;
  }

  th {
    background-color: var(--color-bg-secondary);
    font-weight: 600;
    color: var(--color-text-secondary);
    font-size: $font-size-sm * 0.9;
    text-transform: uppercase;
    letter-spacing: 0.5px;
  }

  tbody tr {
    cursor: pointer;
    transition: background-color 0.15s ease;
    &:hover {
      background-color: var(--color-bg-tertiary);
    }
    &:last-child td {
       border-bottom: none;
    }
    // Highlight new submissions subtly
    &.newSubmission td {
      // Example: Slightly bolder text or different background hint
      // font-weight: 500;
      background-color: var(--color-primary-light);
      opacity: 0.8;
    }
  }

  td {
    font-size: $font-size-sm;
    color: var(--color-text-primary);
  }
  // User column specific style
  .userColumn {
      line-height: 1.4;
      .userName { font-weight: 500; }
      small {
          display: block;
          font-size: 0.9em;
          color: var(--color-text-tertiary);
          margin-top: 2px;
      }
  }
  // Subject column maybe needs width limit?
  .subjectColumn {
      max-width: 300px;
      white-space: nowrap;
      overflow: hidden;
      text-overflow: ellipsis;
  }
}

// --- Status Badge ---
.statusBadge {
    padding: $spacing-xs * 0.75 $spacing-sm;
    border-radius: $border-radius-pill; // Pill shape
    font-size: 0.75rem;
    font-weight: 500;
    text-transform: capitalize;
    display: inline-flex; // Align icon if added later
    align-items: center;
    line-height: 1;
    border: 1px solid transparent;

    &.status-new {
        background-color: var(--color-primary-light);
        color: var(--color-primary-dark);
        border-color: var(--color-primary);
    }
    &.status-read {
         background-color: var(--color-bg-tertiary);
         color: var(--color-text-secondary);
         border-color: var(--color-border-secondary);
    }
    &.status-archived {
      background-color: var(--color-bg-tertiary); // Slightly darker gray
        color: var(--color-text-tertiary);
        border-color: var(--color-border-secondary);
        // text-decoration: line-through; // Optional: strikethrough archived
    }
}

// --- Actions Cell ---
.actionsCell {
  display: flex;
  gap: $spacing-sm;
  align-items: center;
  justify-content: flex-end; // Align actions right

  button {
    white-space: nowrap;
    // Styling handled by Button component variants
  }
}

// --- Modal Styles --- (Adopt common modal styling or redefine)
.modalBackdrop {
    position: fixed;
    inset: 0; // top, left, right, bottom = 0
    background-color: rgba(0, 0, 0, 0.65); // Darker backdrop
    display: flex;
    justify-content: center;
    align-items: center;
    z-index: $z-index-modal-backdrop; // Use z-index variable
    padding: $spacing-md;
    backdrop-filter: blur(3px); // Optional blur effect
    animation: modal-fade-in 0.3s ease-out forwards;
}

.modalContent {
    background-color: var(--color-bg-primary); // Use primary bg for modal content
    border-radius: $border-radius-lg; // Larger radius
    box-shadow: var(--shadow-lg); // Use themed shadow
    border: $border-width-base solid var(--color-border-primary);
    width: 100%;
    max-width: 750px; // Allow wider modal for content
    max-height: 90vh;
    display: flex;
    flex-direction: column;
    overflow: hidden; // Prevent content overflow breaking radius
}

.modalHeader {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: $spacing-md $spacing-lg;
    border-bottom: $border-width-base solid var(--color-border-primary);
    flex-shrink: 0; // Prevent header shrinking

    h2 {
        margin: 0;
        font-size: $font-size-h4; // Use heading size
        font-weight: 600;
        color: var(--color-text-primary);
    }
}

.closeButton {
    // Use redesigned text button style potentially
    background: none;
    border: none;
    font-size: 1.8rem;
    line-height: 1;
    color: var(--color-text-tertiary);
    cursor: pointer;
    padding: $spacing-xs;
    border-radius: 50%;
    transition: color 0.2s ease, background-color 0.2s ease;
     &:hover {
         color: var(--color-text-secondary);
         background-color: var(--color-bg-tertiary);
     }
}

.modalBody {
    padding: $spacing-lg;
    overflow-y: auto;
    flex-grow: 1;

    .infoGrid { // Use grid for structured info display
        display: grid;
        grid-template-columns: auto 1fr; // Label and Value columns
        gap: $spacing-xs $spacing-md; // Row and Column gaps
        margin-bottom: $spacing-lg;
        align-items: center;

        strong { // Label style
            font-weight: 500;
            color: var(--color-text-secondary);
            text-align: right;
        }
        span { // Value style
            color: var(--color-text-primary);
            word-break: break-word;
        }
    }

     .separator { // Subtle separator before message
         margin: $spacing-md 0;
         border: 0;
         border-top: $border-width-base dashed var(--color-border-secondary);
     }

     .messageLabel { // Label for the message content
        font-weight: 600;
        color: var(--color-text-primary);
        margin-bottom: $spacing-sm;
        display: block;
     }

     .messageContent {
         line-height: 1.6;
         white-space: pre-wrap; // Preserve line breaks
         background-color: var(--color-bg-secondary); // Contrast background for message
         padding: $spacing-md;
         border-radius: $border-radius-md;
         border: $border-width-base solid var(--color-border-primary);
         color: var(--color-text-primary);
         max-height: 40vh; // Limit message height if very long
         overflow-y: auto; // Scroll long messages
         font-family: $font-family-base; // Ensure consistent font
         font-size: $font-size-base; // Base size for message readability
     }
}

.modalFooter {
    padding: $spacing-md $spacing-lg;
    border-top: $border-width-base solid var(--color-border-primary);
    display: flex;
    justify-content: flex-end; // Align buttons right
    gap: $spacing-md;
    background-color: var(--color-bg-secondary); // Footer background
    flex-shrink: 0; // Prevent footer shrinking
    // Buttons styled via Button component variants
}

// --- Modal Animation ---
@keyframes modal-fade-in {
  from { opacity: 0; }
  to { opacity: 1; }
}

// Optional: Add exit animation if needed
```

---

### pages\Admin\AdminContactsPage.tsx

```typescript
// src/pages/Admin/AdminContactsPage.tsx
import React, { useState, useEffect, useCallback, useRef, useMemo } from 'react';
import { Timestamp } from 'firebase/firestore';
import { listenToSubmissions, updateSubmissionStatus } from '../../services/adminService';
import LoadingSpinner from '../../components/common/LoadingSpinner/LoadingSpinner';
import Button from '../../components/common/Button/Button';
import { useToast } from '../../components/common/Toast';
import { ContactSubmission } from '../../types';
import styles from './AdminContactsPage.module.scss';
import { FiBell, FiAlertCircle, FiEye, FiArchive, FiMail } from 'react-icons/fi';

// Helper function to format dates
const formatDate = (timestamp: Timestamp | undefined | null): string => {
    return timestamp ? timestamp.toDate().toLocaleString() : 'N/A';
}

const AdminContactsPage: React.FC = () => {
    const [submissions, setSubmissions] = useState<ContactSubmission[]>([]);
    const [isLoading, setIsLoading] = useState<boolean>(true); // Start as true for initial load
    const [filterStatus, setFilterStatus] = useState<'new' | 'read' | 'archived' | 'all'>('new');
    const [selectedSubmission, setSelectedSubmission] = useState<ContactSubmission | null>(null);
    const [isModalOpen, setIsModalOpen] = useState<boolean>(false);
    const [actionLoading, setActionLoading] = useState<Record<string, boolean>>({});
    const [notificationPermission, setNotificationPermission] = useState(Notification.permission);
    const notifiedSubmissionIdsRef = useRef<Set<string>>(new Set());
    // Use a ref to track if it's the very first mount, distinct from isLoading
    const isMountedRef = useRef(false);
    const { addToast } = useToast();

    // --- Notifications ---
    const requestNotificationPermission = useCallback(() => {
        if (!("Notification" in window)) {
            addToast("This browser does not support desktop notifications.", "warning");
            return;
        }
        if (notificationPermission !== 'granted' && notificationPermission !== 'denied') {
            Notification.requestPermission().then((permission) => {
                setNotificationPermission(permission);
                if (permission === 'granted') {
                    addToast("Notifications Enabled!", "success");
                } else if (permission === 'denied') {
                    addToast("Notifications Denied. You can enable them in browser settings.", "warning");
                }
            });
        } else {
            addToast(`Notifications are already ${notificationPermission}.`, "info");
        }
    }, [addToast, notificationPermission]);

    const sendNotification = useCallback((sub: ContactSubmission) => {
        if (notificationPermission !== 'granted' || notifiedSubmissionIdsRef.current.has(sub.id)) {
            return; // Don't notify if permission not granted or already notified
        }
        try {
            const shortSubject = sub.subject.length > 40 ? sub.subject.substring(0, 37) + '...' : sub.subject;
            new Notification('New Contact Submission', {
                body: `From: ${sub.userName}\nSubject: ${shortSubject}`,
                // icon: '/path/to/icon.png' // Optional
                tag: `contact-${sub.id}` // Optional: Use a tag to replace previous notifications
            });
            notifiedSubmissionIdsRef.current.add(sub.id);
        } catch (err) {
           //console.warn("Error showing notification:", err);
            notifiedSubmissionIdsRef.current.add(sub.id); // Mark as attempted
        }
    }, [notificationPermission]);

    // --- Data Fetching Effect (Refined Loading Logic) ---
    useEffect(() => {
        // --- Handle Loading State ---
        // On subsequent runs (filter change), always set loading to true.
        // Skip setting loading true on the very first mount because
        // isLoading state already defaults to true.
        if (isMountedRef.current) {
            //console.log(`Filter changed to ${filterStatus}, setting isLoading=true`); // Debug
            setIsLoading(true);
            setSubmissions([]); // Clear previous results immediately on filter change
        } else {
            // Mark as mounted after the first run completes its setup phase
            isMountedRef.current = true;
        }

        //console.log(`Setting up listener for filter: ${filterStatus}`); // Debug

        const unsubscribe = listenToSubmissions(filterStatus, (fetchedSubmissions) => {
            //console.log(`Listener received ${fetchedSubmissions.length} submissions for ${filterStatus}`); // Debug
            setSubmissions(fetchedSubmissions);

            // *** Always set isLoading to false when data arrives from the listener ***
            // This ensures that whether it's the initial load or a load after a filter change,
            // the loading state is cleared once data is present.
            //console.log("Data received, setting isLoading=false"); // Debug
            setIsLoading(false);

            // Notification Logic
            if (notificationPermission === 'granted' && (filterStatus === 'new' || filterStatus === 'all')) {
                fetchedSubmissions.forEach(sub => {
                    if (sub.status === 'new') {
                        sendNotification(sub);
                    }
                });
            }
        }, (error) => {
            addToast(error.message, "error");
            setIsLoading(false); // Ensure loading stops on error
        });

        // Cleanup function
        return () => {
            //console.log(`Cleaning up listener for filter: ${filterStatus}`); // Debug
            unsubscribe();
        };
    // Dependencies that SHOULD trigger re-subscription
    // Only filterStatus and potentially stable functions affect the *query* itself.
    }, [filterStatus, addToast, sendNotification, notificationPermission]);
    const closeModal = useCallback(() => {
        setIsModalOpen(false);
        // Delay clearing selected submission slightly for fade-out animation if added
        // setTimeout(() => setSelectedSubmission(null), 300);
        setSelectedSubmission(null);
    }, []);
    // --- Actions ---
    const handleStatusUpdate = useCallback(async (submissionId: string, newStatus: 'read' | 'archived') => {
        // No visual loading feedback needed for marking as read usually
        // Only show loading for archiving
        const showLoading = newStatus === 'archived';
        if (showLoading) {
            setActionLoading(prev => ({ ...prev, [submissionId]: true }));
        }
        try {
            await updateSubmissionStatus(submissionId, newStatus);
            if (newStatus === 'archived') {
                addToast("Submission archived", "success");
                if(selectedSubmission?.id === submissionId) {
                    closeModal(); // Close modal if archiving the viewed one
                }
            }
            // UI updates via the Firestore listener
        } catch (error: any) {
            addToast(`Error updating status: ${error.message}`, "error");
        } finally {
            if (showLoading) {
                setActionLoading(prev => ({ ...prev, [submissionId]: false }));
            }
        }
    }, [addToast, selectedSubmission?.id, closeModal]);

    const handleViewSubmission = useCallback((submission: ContactSubmission) => {
        setSelectedSubmission(submission);
        setIsModalOpen(true);
        // Mark as read implicitly when opened if it's new
        if (submission.status === 'new') {
            handleStatusUpdate(submission.id, 'read'); // Call status update silently
        }
    }, [handleStatusUpdate]);



    // --- Render Helpers ---
    const renderStatusBadge = useMemo(() => (status: ContactSubmission['status']) => {
        // Added explicit icons for each status
        let Icon = FiMail;
        if (status === 'read') Icon = FiEye;
        else if (status === 'archived') Icon = FiArchive;

        return (
            <span className={`${styles.statusBadge} ${styles[`status-${status}`]}`}>
                <Icon size="1em" style={{ marginRight: '4px' }} />
                {status}
            </span>
        );
    }, []);

    const renderTableRow = useCallback((sub: ContactSubmission) => {
        const isActionLoading = actionLoading[sub.id];
        return (
            <tr key={sub.id} onClick={() => handleViewSubmission(sub)} className={sub.status === 'new' ? styles.newSubmission : ''} title="Click to view details">
                <td className={styles.userColumn}>
                    <span className={styles.userName}>{sub.userName}</span>
                    <small>{sub.userEmail}</small>
                </td>
                <td className={styles.subjectColumn} title={sub.subject}>{sub.subject}</td>
                <td>{formatDate(sub.submittedAt)}</td>
                <td>{renderStatusBadge(sub.status)}</td>
                <td>
                    <div className={styles.actionsCell}>
                        <Button size="small" variant='outline' onClick={(e) => { e.stopPropagation(); handleViewSubmission(sub); }}>
                            <FiEye size="1em" /> View
                        </Button>
                        {sub.status !== 'archived' && (
                            <Button
                                size="small" variant="secondary"
                                onClick={(e) => { e.stopPropagation(); handleStatusUpdate(sub.id, 'archived'); }}
                                loading={isActionLoading}
                                disabled={isActionLoading}
                                title="Archive this submission" >
                                <FiArchive size="1em" /> Archive
                            </Button>
                        )}
                    </div>
                </td>
            </tr>
        );
    }, [handleViewSubmission, renderStatusBadge, actionLoading, handleStatusUpdate]);

    return (
        <div className={styles.contactsPage}>
            <h1>Contact Submissions</h1>

            {/* Notification Controls */}
            <div className={styles.notificationControl}>
                <span>Notifications for new submissions:</span>
                {notificationPermission === 'default' && (
                    <Button onClick={requestNotificationPermission} variant="secondary" size="small">
                        <FiBell style={{ marginRight: '4px' }}/> Enable Notifications
                    </Button>
                )}
                {notificationPermission === 'granted' && (
                    <span style={{ color: 'var(--color-success-dark)', fontWeight: 500 }}>Enabled</span>
                )}
                {notificationPermission === 'denied' && (
                    <span className={styles.notificationStatusDenied}>
                        <FiAlertCircle /> Blocked by browser
                    </span>
                )}
            </div>

            {/* Filter Controls */}
            <div className={styles.controls}>
                <div className={styles.filterGroup}>
                    <label htmlFor="statusFilter">Filter Status:</label>
                    <select
                        id="statusFilter" value={filterStatus}
                        onChange={(e) => setFilterStatus(e.target.value as any)}
                        disabled={isLoading} >
                        <option value="new">New</option>
                        <option value="read">Read</option>
                        <option value="archived">Archived</option>
                        <option value="all">All</option>
                    </select>
                </div>
            </div>

            {/* Loading or Table */}
            {isLoading ? (
                <LoadingSpinner size="large" />
            ) : (
                <div style={{ overflowX: 'auto' }}> {/* Table responsiveness */}
                    <table className={styles.submissionsTable}>
                        <thead>
                            <tr>
                                <th>From</th>
                                <th>Subject</th>
                                <th>Date</th>
                                <th>Status</th>
                                <th style={{textAlign: 'right'}}>Actions</th>
                            </tr>
                        </thead>
                        <tbody>
                            {submissions.length === 0 ? (
                                <tr><td colSpan={5} style={{textAlign: 'center'}}>No submissions found for "{filterStatus}" status.</td></tr>
                            ) : (
                                submissions.map(renderTableRow)
                            )}
                        </tbody>
                    </table>
                </div>
            )}

            {/* Submission Detail Modal */}
            {isModalOpen && selectedSubmission && (
                <div className={styles.modalBackdrop} /* onClick={closeModal} */ > {/* Don't close on backdrop click maybe? */}
                    <div className={styles.modalContent} onClick={(e) => e.stopPropagation()}>
                        <div className={styles.modalHeader}>
                            <h2>Message Details</h2>
                            <button onClick={closeModal} className={styles.closeButton} aria-label="Close modal">×</button>
                        </div>
                        <div className={styles.modalBody}>
                            {/* Structured Info Area */}
                            <div className={styles.infoGrid}>
                                <strong>Subject:</strong>   <span>{selectedSubmission.subject}</span>
                                <strong>From:</strong>      <span>{selectedSubmission.userName}</span>
                                <strong>Email:</strong>     <span><a href={`mailto:${selectedSubmission.userEmail}`}>{selectedSubmission.userEmail}</a></span>
                                <strong>Date:</strong>      <span>{formatDate(selectedSubmission.submittedAt)}</span>
                                <strong>Status:</strong>    <span>{renderStatusBadge(selectedSubmission.status)}</span>
                            </div>

                            <hr className={styles.separator}/>

                            {/* Message Content Area */}
                            <label className={styles.messageLabel}>Message:</label>
                            <div className={styles.messageContent}>{selectedSubmission.message}</div>

                            {/* TODO: Add Admin Notes section here later if needed */}
                        </div>
                        <div className={styles.modalFooter}>
                            <Button variant="secondary" onClick={closeModal}>Close</Button>
                            {selectedSubmission.status !== 'archived' && (
                                <Button
                                    variant="secondary" // Archive is secondary action here maybe?
                                    onClick={() => handleStatusUpdate(selectedSubmission.id, 'archived')}
                                    loading={actionLoading[selectedSubmission.id]}
                                    disabled={actionLoading[selectedSubmission.id]} >
                                    <FiArchive size="1em"/> Archive
                                </Button>
                            )}
                            <a href={`mailto:${selectedSubmission.userEmail}?subject=Re: ${encodeURIComponent(selectedSubmission.subject)}`} target="_blank" rel="noopener noreferrer">
                                <Button variant='primary'> <FiMail size="1em"/> Reply via Email</Button>
                            </a>
                        </div>
                    </div>
                </div>
            )}
        </div>
    );
};

export default AdminContactsPage;
```

---

### pages\Admin\AdminDashboardPage.module.scss

```scss
// src/pages/Admin/AdminDashboardPage.module.scss
@import '../../styles/variables'; // Use SCSS variables

.dashboardPage {
  // Padding is handled by AdminLayout's .pageContent
  h1 {
    // Uses base h1 styles, maybe adjust size/margin if needed
    font-size: $font-size-h2; // Example: Use H2 size for admin page titles
    color: var(--color-primary); // Use theme primary color
    margin-bottom: $spacing-lg;
  }
  p {
    color: var(--color-text-secondary);
    margin-bottom: $spacing-xl;
  }
}

// Styling for the config initialization section
.configSection {
  margin-top: $spacing-xl;
  padding: $spacing-lg;
  border: $border-width-base solid var(--color-border-primary);
  border-radius: $border-radius-md;
  background-color: var(--color-bg-secondary); // Use secondary background

  h2 {
    margin-top: 0;
    margin-bottom: $spacing-sm;
    font-size: $font-size-lg; // Smaller heading for section
    font-weight: 600;
    color: var(--color-text-primary);
  }
  p {
    font-size: $font-size-sm;
    color: var(--color-text-secondary);
    margin-bottom: $spacing-md;
  }
  // Button styling is handled by the Button component
}
```

---

### pages\Admin\AdminDashboardPage.tsx

```typescript
// src/pages/Admin/AdminDashboardPage.tsx
import React, { useState } from 'react';
import Button from '../../components/common/Button/Button'; // Use redesigned Button
import { initializeAllConfigurations } from '../../services/adminService';
import { useToast } from '../../components/common/Toast'; // Adjust path
import styles from './AdminDashboardPage.module.scss'; // Adjust path
import { FiAlertTriangle } from 'react-icons/fi';

const AdminDashboardPage: React.FC = () => {
    const [isInitializing, setIsInitializing] = useState(false);
    const { addToast } = useToast();

    const handleInitAllConfigs = async () => {
        // Stronger Confirmation
        const confirm1 = window.prompt("DANGER: This will overwrite ALL application configurations (Tiers, Services, Payments, Global Settings) with default values. This cannot be undone easily. Type 'RESET ALL CONFIGS' to confirm.");
        if (confirm1 !== "RESET ALL CONFIGS") {
            addToast("Configuration reset cancelled.", "info");
            return;
        }

        setIsInitializing(true);
        try {
            const result = await initializeAllConfigurations();
            if (result.success) {
                addToast(result.message, "success", 8000);
            } else {
                 // Show specific errors if available
                 const errorMsg = result.errors.length > 0 ? result.errors.join('; ') : result.message;
                 addToast(`Configuration Error: ${errorMsg}`, "error", 15000);
                //console.error("Config Init Errors:", result.errors);
            }
        } catch (error: any) { // Catch any unexpected errors from the service function itself
             addToast(`Unexpected Error: ${error.message}`, "error", 10000);
            //console.error("Unexpected config init error:", error);
        } finally {
            setIsInitializing(false);
        }
    };

    return (
        <div className={styles.dashboardPage}>
            <h1>Admin Dashboard</h1>
            <p>Welcome, Admin! Manage application settings and user data.</p>

            {/* Initialization Section */}
            <div className={styles.configSection}>
                <h2><FiAlertTriangle style={{ color: 'var(--color-error)' }}/> Application Configuration Reset</h2>
                <p style={{ color: 'var(--color-error-dark)'}}>
                    Use this button ONLY to reset ALL configurations (Tiers, Services, Payment settings, Global flags, etc.)
                    to their default values from the code. This is useful for initial setup or fixing corrupted data,
                    but **use with extreme caution as it overwrites current settings.**
                </p>
                <Button
                    onClick={handleInitAllConfigs} // Call the new function
                    loading={isInitializing}
                    disabled={isInitializing}
                    variant="danger" // Keep as danger
                    size="small"
                >
                    Reset ALL Configurations to Default
                </Button>
            </div>

            {/* Add more dashboard widgets or stats here later */}
        </div>
    );
};

export default AdminDashboardPage;
```

---

### pages\Admin\AdminPaymentsPage.module.scss

```scss
// src/pages/Admin/AdminPaymentsPage.module.scss
@import '../../styles/variables';

.paymentsPage {
  h1 {
    font-size: $font-size-h2;
    color: var(--color-primary);
    margin-bottom: $spacing-lg;
  }
  .infoText {
    font-size: $font-size-sm;
    color: var(--color-text-secondary);
    margin-bottom: $spacing-lg;
    background-color: var(--color-info-light); // Use info color scheme
    border-left: 4px solid var(--color-info);
    padding: $spacing-sm $spacing-md;
    border-radius: $border-radius-sm;
  }
}

// --- Notification Controls --- (Same as AdminContactsPage)
.notificationControl {
    margin-bottom: $spacing-lg;
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    gap: $spacing-md;
    padding: $spacing-sm $spacing-md;
    background-color: var(--color-bg-secondary);
    border-radius: $border-radius-md;
    border: 1px solid var(--color-border-primary);
    font-size: $font-size-sm;
}
.notificationStatusDenied {
    color: var(--color-error-dark);
    display: flex;
    align-items: center;
    gap: $spacing-xs;
    svg { color: var(--color-error); }
}

// --- Filter Controls --- (Same as AdminContactsPage)
.controls {
    display: flex;
    margin-bottom: $spacing-lg;
    padding: $spacing-md;
    background-color: var(--color-bg-secondary);
    border-radius: $border-radius-md;
    border: $border-width-base solid var(--color-border-primary);
}
.filterGroup {
  display: flex;
  align-items: center;
  gap: $spacing-sm;
  label {
    font-weight: 500;
    font-size: $font-size-sm;
    color: var(--color-text-secondary);
  }
  select {
    padding: $spacing-xs $spacing-sm;
    border-radius: $border-radius-md;
    border: $border-width-base solid var(--color-border-input);
    background-color: var(--color-bg-primary);
    color: var(--color-text-primary);
    min-width: 200px; // Wider select for longer status names
    font-size: $font-size-sm;
    transition: border-color 0.2s ease, box-shadow 0.15s ease;
    &:focus {
      outline: none;
      border-color: var(--color-border-input-focus);
    }
    &:disabled {
       background-color: var(--color-bg-tertiary);
       cursor: not-allowed;
       opacity: 0.7;
    }
  }
}

// --- Payments Table --- (Similar to AdminUsersTable)
.paymentsTable {
    width: 100%;
    border-collapse: collapse;
    margin-bottom: $spacing-lg;
    background-color: var(--color-bg-primary);
    box-shadow: var(--shadow-md);
    border-radius: $border-radius-md;
    border: $border-width-base solid var(--color-border-primary);
    overflow: hidden;

    th, td {
        padding: $spacing-sm $spacing-md;
        text-align: left;
        border-bottom: $border-width-base solid var(--color-border-primary);
        vertical-align: middle;
    }

    th {
        background-color: var(--color-bg-secondary);
        font-weight: 600;
        color: var(--color-text-secondary);
        font-size: $font-size-sm * 0.9;
        text-transform: uppercase;
        letter-spacing: 0.5px;
    }

    tbody tr {
        transition: background-color 0.15s ease;
        &:hover { background-color: var(--color-bg-tertiary); }
        &:last-child td { border-bottom: none; }
    }

    td {
        font-size: $font-size-sm;
        color: var(--color-text-primary);
    }

    // Specific column styling
    .userColumn {
        line-height: 1.4;
        .userName { font-weight: 500; }
        small {
            display: block;
            font-size: 0.9em;
            color: var(--color-text-tertiary);
            margin-top: 2px;
        }
    }
    .amountColumn {
        font-weight: 500;
        white-space: nowrap;
    }
    .noteColumn {
        font-family: monospace;
        font-size: 0.9em;
        color: var(--color-text-secondary);
        max-width: 180px; // Adjust width
        overflow: hidden;
        text-overflow: ellipsis;
        white-space: nowrap;
    }
    .dateColumn {
        white-space: nowrap; // Prevent date wrapping
    }
}

// --- Actions Cell ---
.actionsCell {
    display: flex;
    gap: $spacing-sm;
    align-items: center;
    justify-content: flex-end; // Align right

    button {
        white-space: nowrap;
        // Styling handled by Button component variants
        // Ensure small size is used maybe
        // Use 'primary' for Approve, 'danger' for Reject?
    }
}
// Specific styles for approve/reject if variants aren't enough
//.approveButton {
    // Use variant="primary" or variant="success" if added
//}
//.rejectButton {
    // Use variant="danger"
//}

// --- Status Badges --- (Consolidated from Profile Page logic)
.statusBadge {
    display: inline-flex;
    align-items: center;
    gap: $spacing-xs * 0.75; // Small gap for icon
    padding: $spacing-xs $spacing-sm;
    border-radius: $border-radius-pill;
    font-size: 0.75rem;
    font-weight: 500;
    text-transform: capitalize;
    line-height: 1.2;
    border: 1px solid transparent; // Base border
    white-space: nowrap;

    svg { width: 12px; height: 12px; } // Icon size in badge

    &.status-completed {
        background-color: var(--color-success-light);
        color: var(--color-success-dark);
        border-color: var(--color-success);
    }
    &.status-pending_verification {
        background-color: var(--color-warning-light);
        color: var(--color-warning-dark);
        border-color: var(--color-warning);
    }
    &.status-rejected {
        background-color: var(--color-error-light);
        color: var(--color-error-dark);
        border-color: var(--color-error);
    }
    &.status-expired {
        background-color: var(--color-bg-tertiary);
        color: var(--color-text-tertiary);
        border-color: var(--color-border-secondary);
    }
    &.status-pending_user_action {
        background-color: var(--color-info-light);
        color: var(--color-info-dark);
        border-color: var(--color-info);
    }
}

// Rejection reason icon (same as profile)
.rejectionReasonIcon {
    display: inline-flex; // Use inline-flex to allow title attribute
    align-items: center;
    margin-left: $spacing-xs;
    color: var(--color-text-tertiary);
    cursor: help;
    vertical-align: middle;
    &:hover { color: var(--color-text-secondary); }
    svg { display: block; width: 14px; height: 14px; }
}
```

---

### pages\Admin\AdminPaymentsPage.tsx

```typescript
// src/pages/Admin/AdminPaymentsPage.tsx
import React, { useState, useEffect, useRef, useCallback } from 'react';
import { Timestamp } from 'firebase/firestore';
import {
    listenToPaymentsByStatus,
    approvePaymentAdmin,
    rejectPaymentAdmin
} from '../../services/adminService';
import { PaymentAttempt } from '../../types';
import LoadingSpinner from '../../components/common/LoadingSpinner/LoadingSpinner';
import Button from '../../components/common/Button/Button';
import { useToast } from '../../components/common/Toast';
import { useAuth } from '../../hooks/useAuth';
import styles from './AdminPaymentsPage.module.scss';
import { FiBell, FiAlertCircle, FiCheckCircle, FiXCircle, FiLoader, FiInfo } from 'react-icons/fi';

// Helper function for formatting dates
const formatDate = (timestamp: Timestamp | Date | undefined | null): string => {
    if (!timestamp) return 'N/A';
    const date = timestamp instanceof Timestamp ? timestamp.toDate() : timestamp;
    return date 
        ? date.toLocaleString(undefined, { 
            year: 'numeric', 
            month: 'short', 
            day: 'numeric', 
            hour: '2-digit', 
            minute: '2-digit' 
          }) 
        : 'N/A';
};

// Status badge component
const StatusBadge: React.FC<{ status: PaymentAttempt['status'], reason?: string | null }> = ({ status, reason }) => {
    let Icon = FiInfo;
    let styleClass = styles[`status-${status}`] || styles['status-unknown'];

    switch(status) {
        case 'completed': Icon = FiCheckCircle; break;
        case 'pending_verification': Icon = FiLoader; styleClass += ` ${styles.spinIcon}`; break;
        case 'rejected': Icon = FiXCircle; break;
    }

    const statusText = status.replace(/_/g, ' ');

    return (
        <span className={`${styles.statusBadge} ${styleClass}`}>
            <Icon size="1em" style={{ marginRight: '4px' }} />
            {statusText}
            {status === 'rejected' && reason && (
                <span title={reason} className={styles.rejectionReasonIcon}>
                   <FiInfo size="0.9em" />
                </span>
            )}
        </span>
    );
};

const AdminPaymentsPage: React.FC = () => {
    // --- State ---
    const [payments, setPayments] = useState<PaymentAttempt[]>([]);
    const [isLoading, setIsLoading] = useState<boolean>(true);
    const [actionLoading, setActionLoading] = useState<Record<string, boolean>>({});
    const [filterStatus, setFilterStatus] = useState<PaymentAttempt['status'] | 'all'>('pending_verification');
    const [notificationPermission, setNotificationPermission] = useState(Notification.permission);
    const notifiedPaymentIdsRef = useRef<Set<string>>(new Set());

    // --- Hooks ---
    const { addToast } = useToast();
    const { currentUser } = useAuth();

    // --- Notifications ---
    const requestNotificationPermission = useCallback(() => {
       if (!("Notification" in window)) { 
           addToast("Browser doesn't support notifications.", "warning"); 
           return; 
       }
       
       if (notificationPermission !== 'granted' && notificationPermission !== 'denied') {
           Notification.requestPermission().then((permission) => {
               setNotificationPermission(permission);
               if (permission === 'granted') 
                   addToast("Payment notifications enabled!", "success");
               else 
                   addToast("Payment notifications denied.", "warning");
           });
       } else { 
           addToast(`Notifications are already ${notificationPermission}.`, "info"); 
       }
    }, [addToast, notificationPermission]);

    const sendPaymentNotification = useCallback((payment: PaymentAttempt) => {
       if (notificationPermission !== 'granted' || notifiedPaymentIdsRef.current.has(payment.id)) 
           return;
       
       try {
           const title = `Payment Verification Needed`;
           const body = `User: ${payment.userName || payment.userEmail}\nTier: ${payment.tierName} (₹${payment.amount})\nNote: ${payment.expectedNote}`;
           new Notification(title, { body, tag: `payment-${payment.id}` });
           notifiedPaymentIdsRef.current.add(payment.id);
       } catch (err) {
          //console.warn("Error showing payment notification:", err);
           notifiedPaymentIdsRef.current.add(payment.id);
       }
    }, [notificationPermission]);

    // --- Data Fetching Effect ---
    useEffect(() => {
        // Track if changing filters (vs initial load)
        const isFilterChange = !isLoading;
        
        if (isFilterChange) {
            // Reset data and show loading when filter changes
            setIsLoading(true);
            setPayments([]);
        }
        
        //console.log(`Setting up payment listener for filter: ${filterStatus}`);

        const unsubscribe = listenToPaymentsByStatus(
            filterStatus,
            (fetchedPayments) => {
                //console.log(`Received ${fetchedPayments.length} payments for ${filterStatus}`);
                setPayments(fetchedPayments);
                
                // Always set loading to false after receiving data
                setIsLoading(false);
                
                // Trigger notifications if appropriate
                if (notificationPermission === 'granted' && 
                    (filterStatus === 'pending_verification' || filterStatus === 'all')) {
                    fetchedPayments
                        .filter(p => p.status === 'pending_verification')
                        .forEach(sendPaymentNotification);
                }
            },
            (error) => {
                addToast(error.message, "error");
                setIsLoading(false);
            }
        );

        return () => {
            //console.log(`Cleaning up payment listener for filter: ${filterStatus}`);
            unsubscribe();
        };
    // IMPORTANT: isLoading removed from dependency array to prevent infinite loop
    // eslint-disable-next-line
    }, [filterStatus, addToast, notificationPermission, sendPaymentNotification]);

    // --- Action Handlers ---
    const handleApprove = useCallback(async (payment: PaymentAttempt) => {
        if (!currentUser?.uid || actionLoading[payment.id]) return;
        
        if (!window.confirm(`Approve payment: ₹${payment.amount} for ${payment.tierName} by ${payment.userName || payment.userEmail}?\nNote: ${payment.expectedNote}`)) {
            return;
        }
        
        setActionLoading(prev => ({ ...prev, [payment.id]: true }));
        
        try {
            await approvePaymentAdmin(payment.id, currentUser.uid);
            addToast(`Payment approved & perks applied for ${payment.userName || 'user'}.`, "success");
        } catch (error: any) {
           //console.error("Approve error:", error);
            addToast(`Approval failed: ${error.message}`, "error");
        } finally {
            setActionLoading(prev => ({ ...prev, [payment.id]: false }));
        }
    }, [currentUser?.uid, actionLoading, addToast]);

    const handleReject = useCallback(async (payment: PaymentAttempt) => {
        if (!currentUser?.uid || actionLoading[payment.id]) return;
        
        const reason = prompt(`Enter reason for rejecting payment for ${payment.userName || 'user'} (optional):`);
        if (reason === null) return; // User cancelled

        setActionLoading(prev => ({ ...prev, [payment.id]: true }));
        
        try {
            await rejectPaymentAdmin(payment.id, currentUser.uid, reason || undefined);
            addToast(`Payment rejected for ${payment.userName || 'user'}.`, "info");
        } catch (error: any) {
           //console.error("Reject error:", error);
            addToast(`Rejection failed: ${error.message}`, "error");
        } finally {
            setActionLoading(prev => ({ ...prev, [payment.id]: false }));
        }
    }, [currentUser?.uid, actionLoading, addToast]);

    // --- Table Row Rendering ---
    const renderPaymentRow = useCallback((payment: PaymentAttempt) => {
        const isLoadingAction = actionLoading[payment.id];
        const displayDate = payment.processedAt || payment.userConfirmedAt || payment.createdAt;

        return (
            <tr key={payment.id}>
                <td className={styles.userColumn}>
                    <span className={styles.userName}>{payment.userName || 'N/A'}</span>
                    <small>{payment.userEmail || payment.userId}</small>
                </td>
                <td>{payment.tierName}</td>
                <td className={styles.amountColumn}>₹{payment.amount}</td>
                <td className={styles.noteColumn} title={payment.expectedNote}>
                    <code>{payment.expectedNote}</code>
                </td>
                <td><StatusBadge status={payment.status} reason={payment.rejectionReason}/></td>
                <td className={styles.dateColumn}>{formatDate(displayDate)}</td>
                <td>
                    {payment.status === 'pending_verification' && (
                        <div className={styles.actionsCell}>
                            <Button
                                size="small"
                                variant="primary"
                                onClick={() => handleApprove(payment)}
                                loading={isLoadingAction}
                                disabled={isLoadingAction}
                                title="Approve Payment">
                                <FiCheckCircle size="1em"/> Approve
                            </Button>
                            <Button
                                size="small"
                                variant="danger"
                                onClick={() => handleReject(payment)}
                                loading={isLoadingAction}
                                disabled={isLoadingAction}
                                title="Reject Payment">
                                <FiXCircle size="1em"/> Reject
                            </Button>
                        </div>
                    )}
                    {payment.status !== 'pending_verification' && (
                        <div className={styles.actionsCell} style={{ justifyContent: 'flex-start' }}>
                            {payment.adminProcessorUid && (
                                <span title={`Processed by Admin: ${payment.adminProcessorUid.substring(0,6)}...`} 
                                      style={{ fontSize: '0.75rem', color: 'var(--color-text-tertiary)'}}>
                                    Processed
                                </span>
                            )}
                        </div>
                    )}
                </td>
            </tr>
        );
    }, [actionLoading, handleApprove, handleReject]);

    return (
        <div className={styles.paymentsPage}>
            <h1>Payment Verifications & History</h1>
            <p className={styles.infoText}>
                Review payments marked as "Pending Verification". Approve to grant perks, Reject to mark as failed.
            </p>

            {/* Notification Controls */}
            <div className={styles.notificationControl}>
                <span>Payment Notifications:</span>
                {notificationPermission === 'default' && (
                    <Button onClick={requestNotificationPermission} variant="secondary" size="small">
                        <FiBell /> Enable
                    </Button>
                )}
                {notificationPermission === 'granted' && (
                    <span style={{ color: 'var(--color-success-dark)', fontWeight: 500 }}>Enabled</span>
                )}
                {notificationPermission === 'denied' && (
                    <span className={styles.notificationStatusDenied}>
                        <FiAlertCircle /> Blocked
                    </span>
                )}
            </div>

            {/* Filters */}
            <div className={styles.controls}>
                <div className={styles.filterGroup}>
                    <label htmlFor="statusFilter">Filter Status:</label>
                    <select
                        id="statusFilter" 
                        value={filterStatus}
                        onChange={(e) => setFilterStatus(e.target.value as any)}
                        disabled={isLoading}>
                        <option value="pending_verification">Pending Verification</option>
                        <option value="completed">Completed</option>
                        <option value="rejected">Rejected</option>
                        <option value="expired">Expired</option>
                        <option value="pending_user_action">Pending User Action</option>
                        <option value="all">All</option>
                    </select>
                </div>
            </div>

            {/* Table / Loading */}
            {isLoading ? (
                <LoadingSpinner size="large" />
            ) : (
                <div style={{ overflowX: 'auto' }}>
                    <table className={styles.paymentsTable}>
                        <thead>
                            <tr>
                                <th>User</th>
                                <th>Tier</th>
                                <th>Amount</th>
                                <th>Expected Note</th>
                                <th>Status</th>
                                <th className={styles.dateColumn}>Date</th>
                                <th style={{ textAlign: 'right' }}>Actions</th>
                            </tr>
                        </thead>
                        <tbody>
                            {payments.length === 0 ? (
                                <tr><td colSpan={7} style={{ textAlign: 'center' }}>No payments found for "{filterStatus}" status.</td></tr>
                            ) : (
                                payments.map(renderPaymentRow)
                            )}
                        </tbody>
                    </table>
                </div>
            )}
        </div>
    );
};

export default AdminPaymentsPage;
```

---

### pages\Admin\AdminUsersPage.module.scss

```scss
// src/pages/Admin/AdminUsersPage.module.scss
@import '../../styles/variables';

.usersPage {
  h1 {
    font-size: $font-size-h2;
    color: var(--color-primary);
    margin-bottom: $spacing-lg;
  }
  .infoText { // Subtle info box
    font-size: $font-size-sm;
    color: var(--color-text-secondary);
    margin-bottom: $spacing-lg;
    background-color: var(--color-info-light);
    border-left: 4px solid var(--color-info);
    padding: $spacing-sm $spacing-md;
    border-radius: $border-radius-sm;
  }
}

// --- Controls (Filters, Search) ---
.controls {
  display: flex;
  flex-wrap: wrap;
  gap: $spacing-lg;
  margin-bottom: $spacing-lg;
  padding: $spacing-md;
  background-color: var(--color-bg-secondary); // Use secondary bg
  border-radius: $border-radius-md;
  border: $border-width-base solid var(--color-border-primary);
}

.filterGroup, .searchGroup { // Common styling for control groups
  display: flex;
  align-items: center;
  gap: $spacing-sm;

  label {
    font-weight: 500;
    font-size: $font-size-sm;
    color: var(--color-text-secondary);
    white-space: nowrap;
  }

  select, input[type="search"] {
    padding: $spacing-xs $spacing-sm;
    border-radius: $border-radius-md;
    border: $border-width-base solid var(--color-border-input);
    background-color: var(--color-bg-primary);
    color: var(--color-text-primary);
    min-width: 180px;
    font-size: $font-size-sm;
    transition: border-color 0.2s ease, box-shadow 0.15s ease;

    &:focus {
      outline: none;
      border-color: var(--color-border-input-focus);
    }
    &:disabled {
       background-color: var(--color-bg-tertiary);
       cursor: not-allowed;
       opacity: 0.7;
    }
  }
  input[type="search"] { min-width: 220px; }
}

// --- Users Table ---
.usersTable {
  width: 100%;
  border-collapse: collapse;
  margin-bottom: $spacing-lg;
  background-color: var(--color-bg-primary);
  box-shadow: var(--shadow-md);
  border-radius: $border-radius-md;
  border: $border-width-base solid var(--color-border-primary);
  overflow: hidden;

  th, td {
    padding: $spacing-sm $spacing-md;
    text-align: left;
    border-bottom: $border-width-base solid var(--color-border-primary);
    vertical-align: middle;
  }

  th {
    background-color: var(--color-bg-secondary);
    font-weight: 600;
    color: var(--color-text-secondary);
    font-size: $font-size-sm * 0.9;
    text-transform: uppercase;
    letter-spacing: 0.5px;
  }

  tbody tr {
    transition: background-color 0.15s ease;
    &:hover {
      background-color: var(--color-bg-tertiary);
    }
    &:last-child td {
       border-bottom: none;
    }
  }

  td {
    font-size: $font-size-sm;
    color: var(--color-text-primary);
  }
}

// Column specific styling
.userColumn {
  line-height: 1.4;
  .displayName { font-weight: 500; }
  small {
    display: block;
    font-size: 0.9em;
    color: var(--color-text-tertiary);
    margin-top: 2px;
    &.emailText { font-style: normal; }
  }
}

// Perk Cell Styling (Same as Profile Page)
.perkCell {
    display: flex;
    flex-direction: column;
    gap: $spacing-xs * 0.5;
    align-items: flex-start;
}
.perkBadge {
    padding: $spacing-xs * 0.75 $spacing-sm * 0.75;
    border-radius: $border-radius-pill;
    font-size: 0.75rem;
    font-weight: 500;
    text-transform: capitalize;
    display: inline-block;
    line-height: 1;
    border: 1px solid transparent;

    // --- UPDATED Perk Badge Styles (Task 4.4) ---
    &.perk-free {
        background-color: var(--color-bg-tertiary);
        color: var(--color-text-secondary);
        border-color: var(--color-border-secondary);
    }
    // Basic Tier (Example: using Info colors)
    &.perk-basic {
        background-color: var(--color-info-light);
        color: var(--color-info-dark);
        border-color: var(--color-info);
    }
    // Pro Tier (Example: using Primary colors)
    &.perk-pro {
        background-color: var(--color-primary-light);
        color: var(--color-primary-dark);
        border-color: var(--color-primary);
    }
    // Elite Tier (Example: using a distinct color like a darker/richer secondary, or keep as Supporter example)
    // Let's use a different scheme for Elite, maybe a darker gray or a specific accent if defined.
    // For now, let's use a more prominent success-like color.
    &.perk-elite {
        background-color: var(--color-success-light); // Example: light green
        color: var(--color-success-dark);        // Dark green text
        border-color: var(--color-success);         // Green border
        // Alternative: Darker/richer theme
        // background-color: var(--color-secondary-dark); // Example
        // color: var(--color-text-inverse);
        // border-color: var(--color-secondary-dark);
    }
    // --- End UPDATED Perk Badge Styles ---
}
.expiredIndicator {
    color: var(--color-error-dark);
    font-size: 0.75rem;
    font-weight: 500;
    display: inline-flex;
    align-items: center;
    gap: $spacing-xs * 0.5;
    svg { width: 12px; height: 12px; }
}

// Status Badge
.statusBadge {
    padding: $spacing-xs $spacing-sm;
    border-radius: $border-radius-pill;
    font-size: 0.75rem;
    font-weight: 500;
    text-transform: capitalize;
    display: inline-block;
    line-height: 1;
    border: 1px solid transparent;

    &.status-active {
        background-color: var(--color-success-light);
        color: var(--color-success-dark);
        border-color: var(--color-success);
    }
    &.status-suspended {
        background-color: var(--color-warning-light);
        color: var(--color-warning-dark);
        border-color: var(--color-warning);
    }
    &.status-deleted {
        background-color: var(--color-bg-tertiary);
        color: var(--color-text-tertiary);
        border-color: var(--color-border-secondary);
    }
}

// Actions Cell
.actionsCell {
  display: flex;
  gap: $spacing-sm;
  align-items: center;
  flex-wrap: nowrap;
  justify-content: flex-end;

  button {
     white-space: nowrap;
  }
}

// Load More Container
.loadMoreContainer {
    text-align: center;
    padding: $spacing-md 0;
    margin-top: -$spacing-sm;
}
```

---

### pages\Admin\AdminUsersPage.tsx

```typescript
// src/pages/Admin/AdminUsersPage.tsx
import React, { useState, useEffect, useCallback, useMemo } from 'react';
import {
    QueryDocumentSnapshot,
    DocumentData,
    Timestamp
} from 'firebase/firestore';
import {
    getUsersAdmin, updateUserStatusAdmin, downgradeUserPerksAdmin, USERS_PER_PAGE
} from '../../services/adminService';
import { resetPassword } from '../../services/firebase';
import { UserData } from '../../types';
import LoadingSpinner from '../../components/common/LoadingSpinner/LoadingSpinner';
import Button from '../../components/common/Button/Button';
import { useToast } from '../../components/common/Toast';
import styles from './AdminUsersPage.module.scss';
import { FiUserCheck, FiUserX, FiArrowDownCircle, FiAlertTriangle, FiRotateCw } from 'react-icons/fi';

const formatDate = (dateInput: Date | Timestamp | undefined | null): string => {
    if (!dateInput) return 'N/A';
    const date = dateInput instanceof Timestamp ? dateInput.toDate() : dateInput;
    return date ? date.toLocaleDateString(undefined, { year: 'numeric', month: 'short', day: 'numeric' }) : 'N/A';
};


const AdminUsersPage: React.FC = () => {
    const [users, setUsers] = useState<UserData[]>([]);
    const [isLoading, setIsLoading] = useState<boolean>(true);
    const [isFetchingMore, setIsFetchingMore] = useState<boolean>(false);
    const [lastVisible, setLastVisible] = useState<QueryDocumentSnapshot<DocumentData> | null>(null);
    const [hasMore, setHasMore] = useState<boolean>(true);
    const [filterStatus, setFilterStatus] = useState<'active' | 'suspended'>('active');
    const [actionLoading, setActionLoading] = useState<Record<string, string | boolean>>({});

    const { addToast } = useToast();

    const fetchUsers = useCallback(async (loadMore = false) => {
        const currentAction = loadMore ? 'fetchingMore' : 'loading';
        setActionLoading(prev => ({ ...prev, general: currentAction }));
        if (!loadMore) {
            setLastVisible(null); setUsers([]); setHasMore(true); setIsLoading(true);
        } else {
            if (!hasMore) { setActionLoading(prev => ({ ...prev, general: false })); return; }
            setIsFetchingMore(true);
        }
        try {
            const result = await getUsersAdmin({
                statusFilter: filterStatus,
                startAfterDoc: loadMore ? lastVisible : null,
                limitPerPage: USERS_PER_PAGE,
            });
            setUsers(prev => loadMore ? [...prev, ...result.users] : result.users);
            setLastVisible(result.lastVisible);
            setHasMore(result.hasMore);
        } catch (error: any) {
            addToast(error.message || "Failed to fetch users", "error");
            setHasMore(false);
        } finally {
            setActionLoading(prev => ({ ...prev, general: false }));
            setIsLoading(false); setIsFetchingMore(false);
        }
    }, [filterStatus, lastVisible, hasMore, addToast]);

    useEffect(() => {
        fetchUsers(false);
        // eslint-disable-next-line react-hooks/exhaustive-deps
    }, [filterStatus]);

    const handleAction = useCallback(async (
        actionType: 'activate' | 'suspend' | 'resetPassword' | 'downgrade',
        userId: string,
        currentStatus?: UserData['status'],
        email?: string,
        username?: string,
        currentPerk?: UserData['perkLevel'],
        perkExpiry?: UserData['perkExpiry']
    ) => {
        const actionKey = `${userId}_${actionType}`;
        if (actionLoading[actionKey]) return;
        setActionLoading(prev => ({ ...prev, [actionKey]: true }));
        let toastMessage = '';
        let toastType: 'success' | 'error' | 'info' = 'info';
        try {
            switch (actionType) {
                case 'activate':
                    if (currentStatus !== 'suspended') throw new Error("User is not suspended.");
                    await updateUserStatusAdmin(userId, 'active');
                    toastMessage = `User activated successfully.`; toastType = 'success';
                    setUsers(prev => prev.map(u => u.uid === userId ? { ...u, status: 'active' } : u));
                    break;
                case 'suspend':
                    if (currentStatus !== 'active') throw new Error("User is not active.");
                    await updateUserStatusAdmin(userId, 'suspended');
                    toastMessage = `User suspended successfully.`; toastType = 'success';
                    setUsers(prev => prev.map(u => u.uid === userId ? { ...u, status: 'suspended' } : u));
                    break;
                case 'resetPassword':
                    if (!email) throw new Error("Email address is missing.");
                    await resetPassword(email);
                    toastMessage = `Password reset sent to ${email}.`; toastType = 'info';
                    break;
                case 'downgrade':
                     if (currentPerk === 'free') throw new Error("User already has Free plan.");
                     const isExpired = !!perkExpiry && (perkExpiry instanceof Timestamp ? perkExpiry.toDate() : perkExpiry) < new Date();
                     if (!isExpired) {
                        if (!window.confirm(`User "${username}" plan is NOT expired. Still downgrade to Free?`)) {
                           throw new Error("Downgrade cancelled by admin.");
                        }
                     } else {
                        if (!window.confirm(`Downgrade user "${username}" perks to 'Free'?`)) {
                           throw new Error("Downgrade cancelled by admin.");
                        }
                     }
                    await downgradeUserPerksAdmin(userId);
                    toastMessage = `User "${username}" perks downgraded to 'Free'.`; toastType = 'success';
                    setUsers(prev => prev.map(u => u.uid === userId ? { ...u, perkLevel: 'free', perkExpiry: null } : u));
                    break;
                default: throw new Error("Invalid action type");
            }
             if(toastMessage && actionType !== 'resetPassword') { addToast(toastMessage, toastType); }
        } catch (error: any) {
            addToast(error.message || `Failed to perform action: ${actionType}`, 'error');
        } finally {
            setActionLoading(prev => ({ ...prev, [actionKey]: false }));
        }
    }, [addToast, actionLoading]);

    const renderStatusBadge = useMemo(() => (status: string | undefined) => {
        const effectiveStatus = status || 'active';
        return (
            <span className={`${styles.statusBadge} ${styles[`status-${effectiveStatus}`]}`}>
                {effectiveStatus}
            </span>
        );
    }, []);

    // --- MODIFIED renderPerkLevel for Task 4.3 ---
    const renderPerkLevel = useMemo(() => (level: UserData['perkLevel'] | undefined, expiry: Date | Timestamp | null | undefined) => {
        const currentLevel = level || 'free';
        const jsExpiryDate = expiry instanceof Timestamp ? expiry.toDate() : expiry;
        const isExpired = !!jsExpiryDate && jsExpiryDate < new Date();

        // Determine the tier name based on the ID for display
        let tierDisplayName = 'Free';
        if (currentLevel === 'basic') tierDisplayName = 'Basic';
        else if (currentLevel === 'pro') tierDisplayName = 'Pro';
        else if (currentLevel === 'elite') tierDisplayName = 'Elite';

        return (
            <div className={styles.perkCell}>
                {/* Use currentLevel (the ID) for CSS class, and tierDisplayName for text */}
                <span className={`${styles.perkBadge} ${styles[`perk-${currentLevel}`]}`}>
                    {tierDisplayName}
                </span>
                {currentLevel !== 'free' && isExpired && (
                    <span className={styles.expiredIndicator} title={`Expired on ${formatDate(jsExpiryDate)}`}>
                        <FiAlertTriangle /> Expired
                    </span>
                )}
            </div>
        );
    }, []); // No direct dependencies needed as it's a pure formatting function based on props

    const renderTableRow = useCallback((user: UserData) => {
        const status = user.status || 'active';
        const perkLevel = user.perkLevel || 'free';
        const perkExpiryDate = user.perkExpiry instanceof Timestamp ? user.perkExpiry.toDate() : user.perkExpiry;
        const isExpired = !!perkExpiryDate && perkExpiryDate < new Date();
        const canDowngrade = perkLevel !== 'free';

        return (
            <tr key={user.uid}>
                <td className={styles.userColumn}>
                    <span className={styles.displayName}>{user.displayName}</span>
                    <small>({user.username})</small>
                    <small className={styles.emailText}>{user.email}</small>
                </td>
                <td>{renderStatusBadge(status)}</td>
                <td>{renderPerkLevel(perkLevel, user.perkExpiry)}</td>
                <td>{perkLevel !== 'free' ? formatDate(user.perkExpiry) : 'N/A'}</td>
                <td>{formatDate(user.createdAt)}</td>
                <td>
                    <div className={styles.actionsCell}>
                        {status === 'suspended' && (
                            <Button size="small" variant="outline"
                                onClick={() => handleAction('activate', user.uid, status)}
                                loading={actionLoading[`${user.uid}_activate`] === true}
                                disabled={!!actionLoading[`${user.uid}_activate`]}
                                title="Activate User">
                                <FiUserCheck size="1em"/>
                            </Button>
                        )}
                        {status === 'active' && (
                            <Button size="small" variant="outline"
                                onClick={() => handleAction('suspend', user.uid, status)}
                                loading={actionLoading[`${user.uid}_suspend`] === true}
                                disabled={!!actionLoading[`${user.uid}_suspend`]}
                                title="Suspend User">
                                <FiUserX size="1em"/>
                            </Button>
                        )}
                        <Button size="small" variant="secondary"
                            onClick={() => handleAction('resetPassword', user.uid, status, user.email)}
                            loading={actionLoading[`${user.uid}_resetPassword`] === true}
                            disabled={!!actionLoading[`${user.uid}_resetPassword`]}
                            title={`Send password reset to ${user.email}`}>
                            <FiRotateCw size="1em"/>
                        </Button>
                        {canDowngrade && status !== 'deleted' && (
                            <Button size="small" variant="outline"
                                onClick={() => handleAction('downgrade', user.uid, status, user.email, user.username, perkLevel, user.perkExpiry)}
                                loading={actionLoading[`${user.uid}_downgrade`] === true}
                                disabled={!!actionLoading[`${user.uid}_downgrade`]}
                                title={isExpired ? `Downgrade Expired Plan` : `Downgrade Active Plan (Requires Confirm)`}>
                                <FiArrowDownCircle size="1em"/>
                            </Button>
                        )}
                    </div>
                </td>
            </tr>
        );
    }, [actionLoading, renderStatusBadge, renderPerkLevel, handleAction]);

    return (
        <div className={styles.usersPage}>
            <h1>User Management</h1>
            <p className={styles.infoText}>View and manage active and suspended user accounts.</p>

            <div className={styles.controls}>
                <div className={styles.filterGroup}>
                    <label htmlFor="statusFilter">Filter Status:</label>
                    <select
                        id="statusFilter" value={filterStatus}
                        onChange={(e) => setFilterStatus(e.target.value as 'active' | 'suspended')}
                        disabled={isLoading || isFetchingMore} >
                        <option value="active">Active</option>
                        <option value="suspended">Suspended</option>
                    </select>
                </div>
            </div>

            {isLoading ? (
                <LoadingSpinner size="large" />
            ) : (
                <>
                    <div style={{ overflowX: 'auto' }}>
                        <table className={styles.usersTable}>
                            <thead>
                                <tr>
                                    <th>User</th>
                                    <th>Status</th>
                                    <th>Perk Level</th>
                                    <th>Perk Expiry</th>
                                    <th>Joined</th>
                                    <th style={{textAlign: 'right'}}>Actions</th>
                                </tr>
                            </thead>
                            <tbody>
                                {users.length === 0 && (
                                    <tr><td colSpan={6} style={{textAlign: 'center'}}>No users found for "{filterStatus}" status.</td></tr>
                                )}
                                {users.map(renderTableRow)}
                            </tbody>
                        </table>
                    </div>

                    {hasMore && (
                        <div className={styles.loadMoreContainer}>
                            <Button
                                onClick={() => fetchUsers(true)}
                                loading={isFetchingMore}
                                disabled={isLoading || isFetchingMore}
                                variant="secondary" >
                                Load More Users
                            </Button>
                        </div>
                    )}
                </>
            )}
        </div>
    );
};

export default AdminUsersPage;
```

---

### pages\Admin\DeletedUsersPage.module.scss

```scss
// src/pages/Admin/DeletedUsersPage.module.scss
@import '../../styles/variables';

.deletedUsersPage {
  // Padding handled by AdminLayout .pageContent
  h1 {
    font-size: $font-size-h2;
    color: var(--color-primary); // Or perhaps Error color? Primary is fine.
    margin-bottom: $spacing-sm; // Less space below title
  }

  .explanation, .warning {
    margin-bottom: $spacing-lg; // Consistent spacing
    font-size: $font-size-sm;
    line-height: 1.6; // Improve readability
    border-radius: $border-radius-md;
    padding: $spacing-sm $spacing-md;
  }

  .explanation {
      color: var(--color-text-secondary);
      background-color: var(--color-bg-secondary); // Subtle background
      border-left: 4px solid var(--color-border-secondary);
  }

  .warning { // Use Error theme colors for warning box
      color: var(--color-error-dark);
      background-color: var(--color-error-light);
      border-left: 4px solid var(--color-error);
      font-weight: 500; // Make warning text slightly bolder
      strong { color: inherit; font-weight: 700; } // Ensure strong text stands out
  }
}

// --- Users Table --- (Similar to other Admin tables)
.usersTable {
    width: 100%;
    border-collapse: collapse;
    margin-bottom: $spacing-lg;
    background-color: var(--color-bg-primary);
    box-shadow: var(--shadow-md);
    border-radius: $border-radius-md;
    border: $border-width-base solid var(--color-border-primary);
    overflow: hidden;

    th, td {
        padding: $spacing-sm $spacing-md;
        text-align: left;
        border-bottom: $border-width-base solid var(--color-border-primary);
        vertical-align: middle;
    }

    th {
        background-color: var(--color-bg-secondary);
        font-weight: 600;
        color: var(--color-text-secondary);
        font-size: $font-size-sm * 0.9;
        text-transform: uppercase;
        letter-spacing: 0.5px;
    }

    tbody tr {
        transition: background-color 0.15s ease;
        // No hover needed for deleted users? Optional.
        // &:hover { background-color: var(--color-bg-tertiary); }
        &:last-child td { border-bottom: none; }
    }

    td {
        font-size: $font-size-sm;
        color: var(--color-text-primary);
    }
    // Style for code/ID columns
    code {
        font-family: monospace;
        font-size: 0.9em;
        color: var(--color-text-tertiary); // Muted ID
        background-color: var(--color-bg-secondary);
        padding: 2px 5px;
        border-radius: $border-radius-sm;
        word-break: break-all;
    }
    .dateColumn {
        white-space: nowrap;
    }
}

// --- Actions Cell ---
.actionsCell {
    display: flex;
    gap: $spacing-sm;
    align-items: center;
    justify-content: flex-end; // Align actions right
    flex-wrap: nowrap;

    // Button styling handled by Button component variants
    //.reviewButton { // Example class if specific style needed
       // variant="secondary" might be suitable
    //}
    //.purgeButton {
        // Use variant="danger"
    //}
}

// --- Load More ---
.loadMoreContainer {
    text-align: center;
    padding: $spacing-md 0;
}

// --- Modal Styles --- (Standardize with other admin modals)
.modalBackdrop {
    position: fixed;
    inset: 0;
    background-color: rgba(0, 0, 0, 0.65);
    display: flex;
    justify-content: center;
    align-items: center;
    z-index: $z-index-modal-backdrop;
    padding: $spacing-md;
    backdrop-filter: blur(3px);
    animation: modal-fade-in 0.3s ease-out forwards;
}

.modalContent {
    background-color: var(--color-bg-primary);
    border-radius: $border-radius-lg;
    box-shadow: var(--shadow-lg);
    border: $border-width-base solid var(--color-border-primary);
    width: 100%;
    max-width: 650px; // Max width for modal
    max-height: 90vh;
    display: flex;
    flex-direction: column;
    overflow: hidden;
}

.modalHeader {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: $spacing-md $spacing-lg;
    border-bottom: $border-width-base solid var(--color-border-primary);
    flex-shrink: 0;

    h3 { // Modal title
        margin: 0;
        font-size: $font-size-h4;
        font-weight: 600;
        color: var(--color-primary); // Use primary for modal titles
    }
    .closeButton { // Close button 'X'
        background: none; border: none; font-size: 1.8rem; line-height: 1;
        color: var(--color-text-tertiary); cursor: pointer; padding: $spacing-xs;
        border-radius: 50%; transition: color 0.2s ease, background-color 0.2s ease;
         &:hover { color: var(--color-text-secondary); background-color: var(--color-bg-tertiary); }
    }
}

.modalBody {
    padding: $spacing-lg;
    overflow-y: auto;
    flex-grow: 1;
    line-height: 1.6;
    font-size: $font-size-sm;
    color: var(--color-text-primary); // Ensure text color is readable

    p { margin-bottom: $spacing-md; } // Standard paragraph spacing
    strong { font-weight: 600; color: var(--color-text-primary); } // Bolder strong tags
}

.modalActions {
    display: flex;
    justify-content: flex-end;
    gap: $spacing-md;
    padding: $spacing-md $spacing-lg;
    border-top: $border-width-base solid var(--color-border-primary);
    background-color: var(--color-bg-secondary); // Footer background
    flex-shrink: 0;
    // Buttons styled via variants
}

// --- Specific Modal Content Styling ---
.warningText { // For the red warning in Purge modal
    color: var(--color-error-dark);
    background-color: var(--color-error-light);
    border: 1px solid var(--color-error);
    padding: $spacing-sm $spacing-md;
    border-radius: $border-radius-md;
    margin: $spacing-md 0;
    font-weight: 500;
    font-size: $font-size-sm;
}

.loadingContainer { // For Review Data modal loading state
    text-align: center;
    padding: $spacing-xl 0;
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: $spacing-md;
    color: var(--color-text-secondary);
}

.noDataMessage { // Review Data modal - no associated data found
    padding: $spacing-md;
    background-color: var(--color-success-light); // Use success theme
    border: 1px solid var(--color-success);
    color: var(--color-success-dark);
    border-radius: $border-radius-md;
    margin-bottom: $spacing-md;
    font-size: $font-size-sm;
    p { margin-bottom: $spacing-xs; &:last-child { margin-bottom: 0; } }
}

.modalError { // Review Data modal - error fetching data
    // Similar to warningText but maybe different background?
    color: var(--color-error-dark);
    background-color: var(--color-error-light);
    border: 1px solid var(--color-error);
    padding: $spacing-sm $spacing-md;
    border-radius: $border-radius-md;
    margin-bottom: $spacing-md;
     font-size: $font-size-sm;
}

.dataListContainer {
    margin-bottom: $spacing-md;
    strong { display: block; margin-bottom: $spacing-xs; font-weight: 600; }
}

.dataList {
    max-height: 200px;
    overflow-y: auto;
    border: 1px solid var(--color-border-primary);
    border-radius: $border-radius-md;
    margin: $spacing-xs 0 $spacing-sm;
    background-color: var(--color-bg-secondary); // List background

    .dataListItem {
        padding: $spacing-xs $spacing-sm;
        border-bottom: 1px solid var(--color-border-primary);
        font-size: $font-size-sm * 0.9; // Smaller list item text
        color: var(--color-text-primary);
        display: flex;
        justify-content: space-between; // Space out content and ID
        gap: $spacing-md;

        &:last-child { border-bottom: none; }
        &:hover { background-color: var(--color-bg-tertiary); }

        .itemInfo { // Text content
            flex-grow: 1;
            word-break: break-word;
        }
        code { // Style for ID
             font-family: monospace;
             color: var(--color-text-tertiary);
             background-color: var(--color-bg-primary); // Contrast with list bg
             padding: 1px 4px;
             border-radius: $border-radius-sm;
             flex-shrink: 0; // Prevent ID shrinking
        }
    }
}

.reviewSummary { // Text after data lists in Review modal
    margin-top: $spacing-md;
    padding-top: $spacing-md;
    font-weight: 500;
    font-size: $font-size-sm;
    color: var(--color-text-secondary);
    border-top: $border-width-base dashed var(--color-border-secondary);
}

// Modal animation (same as contacts modal)
@keyframes modal-fade-in { from { opacity: 0; } to { opacity: 1; } }
```

---

### pages\Admin\DeletedUsersPage.tsx

```typescript
// src/pages/Admin/DeletedUsersPage.tsx
import React, { useState, useEffect, useCallback, useMemo } from 'react';
import { QueryDocumentSnapshot, DocumentData, Timestamp } from 'firebase/firestore';
import {
    getDeletedUsersAdmin,
    getUserAttemptsAdmin,
    getUserGroupParticipationsAdmin,
    purgeFirestoreDataClientSide,
    OrphanedAttempt, OrphanedParticipant, USERS_PER_PAGE
} from '../../services/adminService'; // Adjust paths
import { UserData } from '../../types'; // Adjust path
import LoadingSpinner from '../../components/common/LoadingSpinner/LoadingSpinner';
import Button from '../../components/common/Button/Button';
import { useToast } from '../../components/common/Toast';
import Input from '../../components/common/Input/Input';
import styles from './DeletedUsersPage.module.scss';
import { FiUsers, FiDatabase, FiAlertTriangle, FiTrash2, FiSearch } from 'react-icons/fi';

// --- Helper Functions ---
const formatDate = (dateInput: Date | Timestamp | undefined | null): string => {
    if (!dateInput) return 'N/A';
    const date = dateInput instanceof Timestamp ? dateInput.toDate() : dateInput;
    return date ? date.toLocaleString(undefined, { year: 'numeric', month: 'short', day: 'numeric', hour: '2-digit', minute: '2-digit' }) : 'N/A';
};

// --- Standardized Modal Component ---
const Modal: React.FC<{ isOpen: boolean; onClose: () => void; title: string; children: React.ReactNode }> = ({ isOpen, onClose, title, children }) => {
     if (!isOpen) return null;
     return (
         <div className={styles.modalBackdrop} onClick={onClose}>
             <div className={styles.modalContent} onClick={(e) => e.stopPropagation()}>
                 <div className={styles.modalHeader}>
                     <h3>{title}</h3>
                     <button onClick={onClose} className={styles.closeButton}>×</button>
                 </div>
                 {children}
             </div>
         </div>
     );
 };

// --- Review Data Modal Content Component ---
const ReviewDataModalContent: React.FC<{
    isLoading: boolean;
    error: string | null;
    associatedData: { attempts: OrphanedAttempt[], participants: OrphanedParticipant[] } | null;
    onClose: () => void;
}> = ({ isLoading, error, associatedData, onClose }) => {

    const renderContent = () => {
        if (isLoading) {
            return (
                <div className={styles.loadingContainer}>
                    <LoadingSpinner />
                    <p>Fetching associated data...</p>
                </div>
            );
        }

        if (error) {
            return <div className={styles.modalError}><p>{error}</p></div>;
        }

        if (!associatedData) {
            return <div className={styles.modalError}><p>Could not load data.</p></div>;
        }

        const { attempts, participants } = associatedData;
        const hasNoData = attempts.length === 0 && participants.length === 0;

        return (
            <>
                {hasNoData ? (
                    <div className={styles.noDataMessage}>
                        <p><FiDatabase style={{marginRight: '8px'}}/>No associated Examify attempts or Group Session participations found for this user.</p>
                        <p>Purging will remove the main user record and username lock.</p>
                    </div>
                ) : (
                    <div>
                        <div className={styles.dataListContainer}>
                            <strong><FiUsers style={{marginRight: '4px'}}/> Exam Attempts Found ({attempts.length}):</strong>
                            {attempts.length > 0 ? (
                                <ul className={styles.dataList}>
                                    {attempts.map(att => (
                                        <li key={att.id} className={styles.dataListItem}>
                                            <span className={styles.itemInfo}>{att.examTitle || 'Unknown Exam'} ({formatDate(att.attemptTimestamp)})</span>
                                            <code>{att.id.substring(0, 8)}...</code>
                                        </li>
                                    ))}
                                </ul>
                            ) : <p style={{marginLeft: '8px', fontSize: '0.9em', color: 'var(--color-text-tertiary)'}}>None</p>}
                        </div>
 
                         <div className={styles.dataListContainer}>
                             <strong><FiUsers style={{marginRight: '4px'}}/> Group Participations Found ({participants.length}):</strong>
                            {participants.length > 0 ? (
                                <ul className={styles.dataList}>
                                    {participants.map(part => (
                                        <li key={part.path} className={styles.dataListItem}>
                                             <span className={styles.itemInfo}>Session: {part.sessionId} ({part.status || 'N/A'})</span>
                                             <code>{part.id.substring(0, 8)}...</code>
                                        </li>
                                    ))}
                                </ul>
                             ) : <p style={{marginLeft: '8px', fontSize: '0.9em', color: 'var(--color-text-tertiary)'}}>None</p>}
                        </div>

                        <p className={styles.reviewSummary}>
                           Review complete. Purging will permanently delete these listed Firestore records along with the user profile and username lock. The Authentication record requires manual deletion in Firebase Console.
                        </p>
                    </div>
                )}
            </>
        );
    }

    return (
         <>
             <div className={styles.modalBody}>
                {renderContent()}
             </div>
              <div className={styles.modalActions}>
                <Button variant="secondary" onClick={onClose} disabled={isLoading}>Close</Button>
            </div>
         </>
    );
};

// --- Main DeletedUsersPage Component ---
const DeletedUsersPage: React.FC = () => {
    // --- State ---
    const [deletedUsers, setDeletedUsers] = useState<UserData[]>([]);
    const [isLoading, setIsLoading] = useState<boolean>(true);
    const [isFetchingMore, setIsFetchingMore] = useState<boolean>(false);
    const [lastVisible, setLastVisible] = useState<QueryDocumentSnapshot<DocumentData> | null>(null);
    const [hasMore, setHasMore] = useState<boolean>(true);
    const [actionLoading, setActionLoading] = useState<Record<string, string | boolean>>({});

    // Modal States
    const [selectedUser, setSelectedUser] = useState<UserData | null>(null);
    const [associatedData, setAssociatedData] = useState<{ attempts: OrphanedAttempt[], participants: OrphanedParticipant[] } | null>(null);
    const [isCheckingData, setIsCheckingData] = useState<boolean>(false);
    const [checkDataError, setCheckDataError] = useState<string | null>(null);
    const [isReviewModalOpen, setIsReviewModalOpen] = useState<boolean>(false);
    const [isPurgeModalOpen, setIsPurgeModalOpen] = useState<boolean>(false);
    const [confirmPurgeInput, setConfirmPurgeInput] = useState('');
    const [purgeModalError, setPurgeModalError] = useState<string | null>(null);

    // --- Hooks ---
    const { addToast } = useToast();

    // --- Data Fetching ---
    // Fix 1: Stable fetchDeletedUsers function - removed unstable dependencies 
    // that get updated by the function itself
    const fetchDeletedUsers = useCallback(async (loadMore = false) => {
        // Avoid running if already fetching
        if (loadMore && (isFetchingMore || !hasMore)) {
            return;
        }
        
        if (!loadMore) {
            setIsLoading(true);
            setLastVisible(null); 
            setDeletedUsers([]);
            setHasMore(true);
        } else {
            setIsFetchingMore(true);
        }
        
        try {
            const result = await getDeletedUsersAdmin({
                startAfterDoc: loadMore ? lastVisible : null,
                limitPerPage: USERS_PER_PAGE,
            });
            
            setDeletedUsers(prev => loadMore ? [...prev, ...result.users] : result.users);
            setLastVisible(result.lastVisible);
            setHasMore(result.hasMore);
        } catch (error: any) {
           //console.error('Failed to fetch deleted users:', error);
            addToast(error.message || "Failed to fetch deleted users", "error");
            setHasMore(false);
        } finally {
            if (loadMore) {
                setIsFetchingMore(false);
            } else {
                setIsLoading(false);
            }
        }
        // eslint-disable-next-line
    }, [addToast]); // Fix: Only depend on stable addToast

    // Fix 2: Initial fetch effect with empty dependency array
    useEffect(() => {
        fetchDeletedUsers(false);
        // eslint-disable-next-line
    }, []); // Empty array ensures this runs once on mount
    
    // We need to use the latest fetchDeletedUsers in the above effect
    // but don't want to re-run the effect when fetchDeletedUsers changes
    useEffect(() => {
        const initialFetch = async () => {
            await fetchDeletedUsers(false);
        };
        initialFetch();
    // eslint-disable-next-line react-hooks/exhaustive-deps
    }, []);

    // --- Modal Handling & Actions ---
    const handleReviewData = useCallback(async (user: UserData) => {
        if (!user?.uid) return;
        
        const actionKey = `${user.uid}_review`;
        setActionLoading(prev => ({ ...prev, [actionKey]: true }));
        setSelectedUser(user);
        setIsCheckingData(true);
        setCheckDataError(null);
        setAssociatedData(null);
        setIsReviewModalOpen(true);
        
        //console.log(`[Admin][ReviewData] Fetching for ${user.uid}...`);
        
        try {
            const [attempts, participants] = await Promise.all([
                getUserAttemptsAdmin(user.uid),
                getUserGroupParticipationsAdmin(user.uid)
            ]);
            
            //console.log(`[Admin][ReviewData] Fetched ${attempts.length} attempts, ${participants.length} participants.`);
            setAssociatedData({ attempts, participants });
        } catch (error: any) {
           //console.error(`[Admin][ReviewData] Error for ${user.uid}:`, error);
            addToast(`Failed to fetch associated data: ${error.message}`, "error");
            setCheckDataError(`Failed to fetch associated data: ${error.message}`);
            setAssociatedData(null);
        } finally {
            setIsCheckingData(false);
            setActionLoading(prev => ({ ...prev, [actionKey]: false }));
            //console.log(`[Admin][ReviewData] Finished check for ${user.uid}.`);
        }
    }, [addToast]);

    const closeReviewModal = useCallback(() => {
        setIsReviewModalOpen(false);
        setSelectedUser(null);
        setAssociatedData(null);
        setCheckDataError(null);
    }, []);

    const handleOpenPurgeModal = useCallback((user: UserData) => {
        setSelectedUser(user);
        setConfirmPurgeInput('');
        setPurgeModalError(null);
        setIsPurgeModalOpen(true);
    }, []);

    const closePurgeModal = useCallback(() => {
        setIsPurgeModalOpen(false);
        setSelectedUser(null);
    }, []);

    const handleConfirmPurge = useCallback(async () => {
        if (!selectedUser || !selectedUser.uid || !selectedUser.username) {
            setPurgeModalError("Selected user data is invalid.");
            return;
        }
        
        // Case-insensitive comparison for username confirmation
        if (confirmPurgeInput.toLowerCase() !== selectedUser.username.toLowerCase()) {
            setPurgeModalError(`Confirmation text does not match username "${selectedUser.username}".`);
            return;
        }

        const userIdToPurge = selectedUser.uid;
        const usernameToPurge = selectedUser.username;
        const actionKey = `${userIdToPurge}_purge`;

        setActionLoading(prev => ({ ...prev, [actionKey]: true }));
        setPurgeModalError(null);

        try {
            addToast(`Purging Firestore data for ${usernameToPurge}...`, "info");

            // Pass empty arrays if review wasn't done or failed
            const attemptsToPass = associatedData?.attempts || [];
            const participantsToPass = associatedData?.participants || [];

            const result = await purgeFirestoreDataClientSide(
                userIdToPurge, usernameToPurge, attemptsToPass, participantsToPass
            );

            if (result.success) {
                addToast(result.message, "success", 8000);
                // Remove from local list instead of refetching
                setDeletedUsers(prev => prev.filter(u => u.uid !== userIdToPurge));
                closePurgeModal();
            } else {
                throw new Error(result.message);
            }
        } catch (error: any) {
           //console.error(`Error purging user ${userIdToPurge}:`, error);
            addToast(`Purge failed: ${error.message}`, "error", 10000);
            setPurgeModalError(`Purge failed: ${error.message}`);
        } finally {
            setActionLoading(prev => ({ ...prev, [actionKey]: false }));
        }
    }, [selectedUser, confirmPurgeInput, associatedData, addToast, closePurgeModal]);

    // Fix 3: Memoized table row rendering
    const renderTableRow = useCallback((user: UserData) => {
        const isPurging = actionLoading[`${user.uid}_purge`] === true;
        const isReviewing = actionLoading[`${user.uid}_review`] === true;
        const deletedAt = (user as any).deletedAt;
        const deletedAtDate = deletedAt instanceof Timestamp ? deletedAt.toDate() : deletedAt;

        return (
            <tr key={user.uid}>
                <td><code>{user.uid}</code></td>
                <td>{user.email}</td>
                <td>{user.username}</td>
                <td>{user.displayName}</td>
                <td className={styles.dateColumn}>{formatDate(deletedAtDate)}</td>
                <td>
                    <div className={styles.actionsCell}>
                        <Button
                            size="small"
                            variant="secondary"
                            onClick={() => handleReviewData(user)}
                            loading={isReviewing}
                            disabled={isPurging || isReviewing}
                            title="Review associated data before purging"
                            className={styles.reviewButton}>
                            <FiSearch size="1em"/> Review Data
                        </Button>
                        <Button
                            size="small"
                            variant="danger"
                            onClick={() => handleOpenPurgeModal(user)}
                            loading={isPurging}
                            disabled={isPurging || isReviewing}
                            title="Permanently delete this user's Firestore data"
                            className={styles.purgeButton}>
                            <FiTrash2 size="1em"/> Purge Data
                        </Button>
                    </div>
                </td>
            </tr>
        );
    }, [actionLoading, handleReviewData, handleOpenPurgeModal]);

    // Fix 4: Memoize elements that don't need to re-render often
    const emptyTableMessage = useMemo(() => (
        <tr><td colSpan={6} style={{textAlign: 'center'}}>No users currently marked for deletion.</td></tr>
    ), []);

    const loadMoreButton = useMemo(() => (
        hasMore && (
            <div className={styles.loadMoreContainer}>
                <Button
                    onClick={() => fetchDeletedUsers(true)}
                    loading={isFetchingMore}
                    disabled={isLoading || isFetchingMore}
                    variant="secondary">
                    Load More
                </Button>
            </div>
        )
    ), [hasMore, fetchDeletedUsers, isFetchingMore, isLoading]);

    return (
        <div className={styles.deletedUsersPage}>
            <h1>Deleted User Management</h1>
            <p className={styles.explanation}>
                Users listed here have requested account deletion. Review their associated data and permanently purge their Firestore records.
                The Firebase Authentication record must be deleted manually via the Firebase Console after purging Firestore data.
            </p>
            <p className={styles.warning}>
                <strong>Warning:</strong> Purging Firestore data is irreversible. Ensure you have reviewed associated data if necessary.
            </p>

            {isLoading ? (
                <LoadingSpinner size="large" />
            ) : (
                <>
                    <div style={{ overflowX: 'auto' }}>
                        <table className={styles.usersTable}>
                            <thead>
                                <tr>
                                    <th>User ID</th>
                                    <th>Email</th>
                                    <th>Username</th>
                                    <th>Display Name</th>
                                    <th className={styles.dateColumn}>Marked Deleted</th>
                                    <th style={{textAlign: 'right'}}>Actions</th>
                                </tr>
                            </thead>
                            <tbody>
                                {deletedUsers.length === 0 ? emptyTableMessage : deletedUsers.map(renderTableRow)}
                            </tbody>
                        </table>
                    </div>

                    {loadMoreButton}
                </>
            )}

            <Modal
                isOpen={isReviewModalOpen}
                onClose={closeReviewModal}
                title={`Review Data for ${selectedUser?.username || ''}`}>
                <ReviewDataModalContent
                    isLoading={isCheckingData}
                    error={checkDataError}
                    associatedData={associatedData}
                    onClose={closeReviewModal} />
            </Modal>

            <Modal
                isOpen={isPurgeModalOpen}
                onClose={closePurgeModal}
                title="Confirm Firestore Data Purge">
                <div className={styles.modalBody}>
                    <p>Are you sure you want to permanently purge all associated Firestore data (User Profile, Username Lock, Exam Attempts, Group Participations) for user <strong>{selectedUser?.username}</strong> ({selectedUser?.email})?</p>
                    <p className={styles.warningText}>
                        <FiAlertTriangle style={{marginRight: '8px', verticalAlign: 'middle'}}/>
                        This action is IRREVERSIBLE. The Firebase Authentication record WILL REMAIN and must be deleted manually afterwards.
                    </p>
                    <Input
                        label={`Confirm by typing username: ${selectedUser?.username}`}
                        type="text"
                        id="confirmPurge"
                        value={confirmPurgeInput}
                        onChange={(e) => {
                            setConfirmPurgeInput(e.target.value);
                            if (purgeModalError) setPurgeModalError(null);
                        }}
                        error={purgeModalError || undefined}
                        disabled={actionLoading[`${selectedUser?.uid}_purge`] === true}
                        autoComplete="off"
                        placeholder="Type username to confirm"
                        inputClassName={purgeModalError ? styles.inputErrorHighlight : ''}
                    />
                </div>
                <div className={styles.modalActions}>
                    <Button 
                        variant="secondary" 
                        onClick={closePurgeModal} 
                        disabled={actionLoading[`${selectedUser?.uid}_purge`] === true}>
                        Cancel
                    </Button>
                    <Button
                        variant="danger"
                        onClick={handleConfirmPurge}
                        loading={actionLoading[`${selectedUser?.uid}_purge`] === true}
                        disabled={!selectedUser || 
                            actionLoading[`${selectedUser?.uid}_purge`] === true || 
                            confirmPurgeInput.toLowerCase() !== selectedUser?.username.toLowerCase()}>
                        <FiTrash2 style={{marginRight: '4px'}}/> Confirm Firestore Purge
                    </Button>
                </div>
            </Modal>
        </div>
    );
};

export default DeletedUsersPage;
```

---

## pages\ContactPage


### pages\ContactPage\ContactPage.tsx

```typescript
// src/pages/ContactPage/ContactPage.tsx
import React from 'react';
import MainLayout from '../../layouts/MainLayout'; // Adjust path
import ContactForm from '../../components/contact/ContactForm/ContactForm'; // Import the form
import pageStyles from '../PageStyles.module.scss'; // Adjust path
import staticStyles from '../StaticPage.module.scss'; // Adjust path
import { FaGithub } from 'react-icons/fa'; // Import GitHub icon
const ContactPage: React.FC = () => {
  const GITHUB_PROFILE_URL = "https://github.com/Samkarya/"; // Define your GitHub URL

  return (
    <MainLayout>
      <div className={`container ${pageStyles.pageWrapper} ${staticStyles.pageWrapperOverride}`}>
        {/* Apply the specific styling for the static content box */}
        <div className={staticStyles.staticPageContainer}>

          {/* --- Static Content Section --- */}
          <h1>Get In Touch</h1>
          <p>
            Need help? Have feedback, suggestions, or questions about MyServices Portal, Examify, the BCA Prep Blog, or any other related service? We're here to listen!
          </p>
          <p>
            Please use the form below to send us a message. If you're logged in, your name and email should be pre-filled for convenience.
          </p>
          {/* --- End Static Content Section --- */}

          <hr /> {/* Separator */}

          {/* --- Render the Contact Form --- */}
          {/* The ContactForm component will use the redesigned Input/Button/Textarea */}
          <ContactForm />
          {/* --- End Contact Form --- */}

          <hr /> {/* Separator */}

          {/* --- Additional Contact Info --- */}
          <h2>Other Ways to Connect</h2>
          <div style={{ display: 'flex', alignItems: 'center', gap: staticStyles['spacing-sm'] || '8px', marginBottom: staticStyles['spacing-md'] || '16px' }}>
             <FaGithub size="1.5em" aria-hidden="true" />
             <p style={{ margin: 0 }}>
                 Explore our projects or report issues on GitHub:
                 <a href={GITHUB_PROFILE_URL} target="_blank" rel="noopener noreferrer" style={{ marginLeft: '5px' }}>
                     {GITHUB_PROFILE_URL.replace('https://', '')}
                 </a>
             </p>
           </div>
          {/* --- End Additional Contact Info --- */}

        </div>
      </div>
    </MainLayout>
  );
};

export default ContactPage;
```

---

## pages\DashboardPage


### pages\DashboardPage\DashBoardPage.tsx

```typescript
// src/pages/DashboardPage/DashboardPage.tsx
import React from 'react';
import MainLayout from '../../layouts/MainLayout';
import Dashboard from '../../components/dashboard/Dashboard/Dashboard';
import styles from '../PageStyles.module.scss';

const DashboardPage: React.FC = () => {
  // Add sidebar state management here if implementing sidebar
  // const [isSidebarOpen, setIsSidebarOpen] = useState(false);

  return (
    <MainLayout>
      {/* Add Sidebar component here if implemented */}
      {/* <Sidebar open={isSidebarOpen} onClose={() => setIsSidebarOpen(false)} /> */}
      <div className={`${styles.pageWrapper} ${styles.dashboardLayout} container`}>
         {/* The main content area */}
         <Dashboard />
      </div>
    </MainLayout>
  );
};

export default DashboardPage;
```

---

## pages\ForgotPasswordPage


### pages\ForgotPasswordPage\ForgotPasswordPage.tsx

```typescript
// src/pages/ForgotPasswordPage/ForgotPasswordPage.tsx
import React from 'react';
import MainLayout from '../../layouts/MainLayout';
import ForgotPassword from '../../components/auth/ForgotPassword/ForgotPassword';
import styles from '../PageStyles.module.scss';

const ForgotPasswordPage: React.FC = () => {
  return (
    <MainLayout>
      <div className={`${styles.pageWrapper} container`}>
        <ForgotPassword />
      </div>
    </MainLayout>
  );
};

export default ForgotPasswordPage;
```

---

## pages\LandingPage


### pages\LandingPage\LandingPage.module.scss

```scss
// src/pages/LandingPage/LandingPage.module.scss
@import '../../styles/variables';

// --- Base & Section Styling ---
.container { // Using global container styles usually
  width: 100%;
  max-width: $breakpoint-xl; // Use wider breakpoint for landing page
  margin-left: auto;
  margin-right: auto;
  padding-left: $spacing-lg; // More padding on landing page
  padding-right: $spacing-lg;
}

.section {
  padding: $spacing-xxl 0; // Generous vertical spacing

  &:nth-child(even) { // Alternate background for visual separation
    background-color: var(--color-bg-secondary); // Use theme secondary bg
  }
   &:first-child { // Hero section
     padding-top: $spacing-xl; // Less top padding if header is present
     padding-bottom: $spacing-xxl; // More bottom padding
     background-color: var(--color-bg-primary); // Ensure hero starts with primary bg
   }
}

.sectionTitle {
  text-align: center;
  font-size: $font-size-h2; // Section title size
  font-weight: 600;
  color: var(--color-primary); // Use primary color
  margin-bottom: $spacing-xl;
}

// --- Hero Section ---
.hero {
  // Background handled by .section &:first-child
  min-height: 80vh; // Ensure hero takes significant viewport height
  display: flex;
  align-items: center;
}

.heroContainer {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: $spacing-xl * 1.5; // Larger gap in hero

  @media (min-width: $breakpoint-md) {
    flex-direction: row; // Side-by-side layout
    text-align: left;
    gap: $spacing-xl;
  }
}

.heroContent {
  flex: 1 1 55%; // Allow text slightly more space
  max-width: 600px;
  @media (max-width: ($breakpoint-md - 1px)) { // Center text on mobile below image
      order: 2; // Text below image on mobile
      text-align: center;
  }
}

.heroTitle {
  font-size: $font-size-h1 * 1.2; // Even larger hero title
  line-height: 1.2;
  font-weight: 700; // Bolder title
  color: var(--color-text-primary);
  margin-bottom: $spacing-md;
}

.heroSubtitle {
  font-size: $font-size-lg;
  color: var(--color-text-secondary);
  margin-bottom: $spacing-xl; // More space before actions
  line-height: 1.7;
}

.heroActions {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: $spacing-md;
  width: 100%; // Take full width for centering buttons

  @media (min-width: $breakpoint-sm) {
     flex-direction: row;
     justify-content: center; // Center buttons on small screens+
     width: auto;
  }
  @media (min-width: $breakpoint-md) {
     justify-content: flex-start; // Align left on medium+
  }

  // Buttons use component variants
  a { text-decoration: none; width: 100%; max-width: 200px; // Limit button width when stacked
      @media (min-width: $breakpoint-sm) { width: auto; max-width: none; }
  }
}

.heroImageContainer {
  flex: 1 1 45%;
  display: flex;
  justify-content: center;
  align-items: center;
  @media (max-width: ($breakpoint-md - 1px)) { // Image first on mobile
      order: 1;
      width: 100%; // Allow image container to take width
      max-width: 450px; // But constrain image size
      margin-bottom: $spacing-xl;
  }
}

.heroImage { // Style for a real image
  max-width: 100%;
  height: auto;
  border-radius: $border-radius-lg; // Larger radius for hero image
  box-shadow: var(--shadow-lg); // Use themed shadow
}

.heroPlaceholder { // Style for the placeholder div
  width: 100%;
  aspect-ratio: 4 / 3; // Adjust aspect ratio
  background-color: var(--color-bg-tertiary);
  border-radius: $border-radius-lg;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  color: var(--color-text-tertiary);
  border: $border-width-lg dashed var(--color-border-secondary);
  p { margin-top: $spacing-sm; margin-bottom: 0; font-size: $font-size-sm; font-weight: 500;}
  svg { width: 80px; height: 80px; opacity: 0.5; } // Larger placeholder icon
}

// --- Features Section ---
.featuresGrid {
  display: grid;
  grid-template-columns: 1fr; // Mobile first
  gap: $spacing-lg;
  margin-top: $spacing-xl; // Space after section title

  @media (min-width: $breakpoint-sm) {
    grid-template-columns: repeat(2, 1fr);
  }
  @media (min-width: $breakpoint-lg) {
    grid-template-columns: repeat(3, 1fr); // Three columns
    gap: $spacing-xl; // Wider gap on large screens
  }
}

.featureItem {
  background-color: var(--color-bg-primary); // Use primary background for feature cards
  padding: $spacing-lg;
  border-radius: $border-radius-md;
  text-align: center;
  border: 1px solid var(--color-border-primary);
  transition: transform 0.2s ease-in-out, box-shadow 0.2s ease-in-out;

  &:hover {
    transform: translateY(-5px);
    box-shadow: var(--shadow-md);
  }
}

.featureIcon {
  color: var(--color-primary); // Use primary color for icon
  margin-bottom: $spacing-md;
  background-color: var(--color-primary-light); // Icon background circle
  width: 56px;
  height: 56px;
  border-radius: 50%;
  display: inline-flex;
  align-items: center;
  justify-content: center;
  svg { width: 28px; height: 28px; } // Icon size within circle
}

.featureTitle {
  font-size: $font-size-lg; // Feature title size
  margin-bottom: $spacing-sm;
  font-weight: 600;
  color: var(--color-text-primary);
}
.featureItem p { // Feature description text
    font-size: $font-size-sm;
    color: var(--color-text-secondary);
    line-height: 1.6;
    margin-bottom: 0; // No bottom margin usually needed
}


// --- Services Section ---
.servicesGrid {
    // Same grid setup as features
    display: grid;
    grid-template-columns: 1fr;
    gap: $spacing-lg;
    margin-top: $spacing-xl;

    @media (min-width: $breakpoint-sm) { grid-template-columns: repeat(2, 1fr); }
    @media (min-width: $breakpoint-lg) { grid-template-columns: repeat(3, 1fr); gap: $spacing-xl; }
}

.serviceCard { // Style cards similar to features, maybe slightly different bg
    background-color: var(--color-bg-primary);
    border: 1px solid var(--color-border-primary);
    border-radius: $border-radius-md;
    padding: $spacing-lg;
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    transition: transform 0.2s ease, box-shadow 0.2s ease;
    &:hover { transform: translateY(-5px); box-shadow: var(--shadow-md); }

    &.serviceCardMore { // Style for the 'coming soon' card
      background-color: var(--color-bg-secondary);
      border-style: dashed;
      border-color: var(--color-border-secondary);
      color: var(--color-text-secondary);
      &:hover { transform: none; box-shadow: none; } // Disable hover effect
   }
}

.serviceIcon { // Icon in service card
  color: var(--color-secondary); // Use secondary color for service icons? Or primary?
  margin-bottom: $spacing-md;
  svg { width: 40px; height: 40px; } // Service icon size
   .serviceCardMore & { color: var(--color-text-tertiary); opacity: 0.7; } // Muted icon for 'more' card
}
.serviceTitle {
  font-size: $font-size-lg; // Match feature title size
  color: var(--color-text-primary);
  margin-bottom: $spacing-sm;
  font-weight: 600;
   .serviceCardMore & { color: inherit; } // Inherit muted color for 'more' card
}
.serviceCard p { // Service description
     font-size: $font-size-sm;
    color: var(--color-text-secondary);
    line-height: 1.6;
    margin-bottom: $spacing-md; // Space before link
    flex-grow: 1; // Push link down if needed
}
.serviceLink { // Learn More link
     font-size: $font-size-sm;
     font-weight: 500;
     color: var(--color-text-link);
     text-decoration: underline;
     margin-top: auto; // Ensure link is at bottom
}
.testimonialGrid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: $spacing-lg;
  margin-top: $spacing-xl;
}
.testimonialCard {
  background-color: var(--color-bg-secondary); // Card background
  padding: $spacing-lg;
  border-radius: $border-radius-md;
  border: 1px solid var(--color-border-primary);
  box-shadow: var(--shadow-sm);
  p {
      font-style: italic;
      color: var(--color-text-primary);
      margin-bottom: $spacing-md;
      position: relative;
      padding-left: $spacing-lg; // Indent for quote mark
      &::before { // Quote mark
          content: '“';
          position: absolute;
          left: 0;
          top: -$spacing-xs;
          font-size: 3rem;
          color: var(--color-primary);
          opacity: 0.3;
          line-height: 1;
      }
  }
  span { // Author name
      display: block;
      font-weight: 600;
      color: var(--color-text-secondary);
      text-align: right;
      margin-top: $spacing-sm;
  }
   // Style for stat card
   &:has(svg) { // If card contains an svg (the stat card)
      text-align: center;
      background-color: var(--color-primary-light);
      border-color: var(--color-primary);
      p { font-style: normal; padding-left: 0; &::before { content: none; }}
      svg { color: var(--color-primary); width: 40px; height: 40px; margin-bottom: $spacing-sm; }
   }
}


// --- Section 6: Perks Teaser Styles ---
.perksTeaser {
  // background handled by section:nth-child(even)
   .sectionTitle { margin-bottom: $spacing-xs; } // Less space after title
   // Button styling handled by variant
}

// --- Final CTA Section ---
.cta {
  background-color: var(--color-primary); // Primary background
  color: var(--color-text); // Inverse text color
  text-align: center;
  padding: $spacing-xxl $spacing-lg; // Match section padding
}

.ctaTitle {
  font-size: $font-size-h3; // CTA title size
  color: var(--color-text-primary); // Ensure white text
  font-weight: 700;
  margin-bottom: $spacing-sm;
}

.ctaSubtitle {
  font-size: $font-size-base;
  color: rgba(255, 255, 255, 0.85); // Slightly transparent white
  margin-bottom: $spacing-xl; // Space before button
  max-width: 550px;
  margin-left: auto;
  margin-right: auto;
  line-height: 1.6;
}

// CTA Button - uses component variant, override if needed
.cta {
   a button { // Target button specifically if needed
     // Use variant="secondary" maybe? Or a custom light variant?
     background-color: var(--color-bg-primary); // White button on primary bg
     color: var(--color-primary);
     &:hover {
       background-color: var(--color-bg-secondary); // Slightly off-white hover
     }
   }
}
```

---

### pages\LandingPage\LandingPage.tsx

```typescript
// src/pages/LandingPage/LandingPage.tsx
import React from 'react';
import { Link } from 'react-router-dom';
import MainLayout from '../../layouts/MainLayout';
import Button from '../../components/common/Button/Button';
import styles from './LandingPage.module.scss';
// Import more relevant icons
import {
    FiLock, FiUserPlus,FiGrid, FiBookOpen, FiSmartphone, FiCoffee,
    FiArrowRightCircle, FiZap, FiStar,
    FiUser
} from 'react-icons/fi';
// Placeholder for a potential Hero illustration/image
// import HeroIllustration from './hero-illustration.svg'; // Example

const LandingPage: React.FC = () => {
    return (
        // Assuming MainLayout passes theme props if needed
        <MainLayout>
            {/* === Section 1: Hero === */}
            <section className={`${styles.hero} ${styles.section}`}>
                <div className={`${styles.container} ${styles.heroContainer}`}>
                    <div className={styles.heroContent}>
                        {/* Engaging Headline */}
                        <h1 className={styles.heroTitle}>
                           Stop Juggling Logins, Start Aceing Exams.
                        </h1>
                        {/* Benefit-driven Subtitle */}
                        <p className={styles.heroSubtitle}>
                            Your free MyServices Portal unifies access to essential Samkarya study tools like Examify and the BCA Prep Blog. One login, one dashboard, zero hassle.
                        </p>
                        {/* Clear CTAs */}
                        <div className={styles.heroActions}>
                            <Link to="/register">
                                <Button variant="primary" size="large"> <FiUserPlus/> Create Your Free Hub </Button>
                            </Link>
                            <Link to="/login">
                                <Button variant="outline" size="large">Log In</Button>
                            </Link>
                        </div>
                    </div>
                    <div className={styles.heroImageContainer}>
                        {/* Replace Placeholder with a better visual */}
                        {/* <img src={HeroIllustration} alt="Diagram showing services connecting to a central dashboard" className={styles.heroImage} /> */}
                        <div className={styles.heroPlaceholder}>
                           <FiGrid size={100} /> {/* TEMP Placeholder */}
                           <p>Your Central Dashboard</p>
                        </div>
                    </div>
                </div>
            </section>

            {/* === Section 2: Problem/Solution (Optional but Recommended) === */}
            <section className={`${styles.problemSolution} ${styles.section}`}>
                 <div className={styles.container} style={{ textAlign: 'center', maxWidth: '800px' }}>
                      <h2 className={styles.sectionTitle}>Lost in a Maze of Study Tools?</h2>
                      <p style={{ color: 'var(--color-text-secondary)', fontSize: styles['font-size-lg'] }}>
                          Switching between bookmarks, remembering different passwords, digging for resources... Sound familiar? We built the MyServices Portal to bring order to your digital student life.
                      </p>
                      {/* Optional visual comparing scattered icons vs unified portal icon */}
                 </div>
            </section>

            {/* === Section 3: Key Features/Benefits === */}
            <section className={`${styles.features} ${styles.section}`}>
                <div className={styles.container}>
                    <h2 className={styles.sectionTitle}>Your Unified Advantage</h2>
                    <div className={styles.featuresGrid}>
                        {/* Benefit 1: Single Sign-On */}
                        <div className={styles.featureItem}>
                            <div className={styles.featureIcon}><FiLock /></div>
                            <h3 className={styles.featureTitle}>One Login, Zero Friction</h3>
                            <p>Securely access Examify, the Prep Blog, and future tools with a single email and password. No more password fatigue!</p>
                        </div>
                        {/* Benefit 2: Central Hub */}
                        <div className={styles.featureItem}>
                             <div className={styles.featureIcon}><FiGrid /></div>
                            <h3 className={styles.featureTitle}>Dashboard Command Center</h3>
                            <p>Launch your essential study services, check resources, and manage your profile instantly from one organized view.</p>
                        </div>
                        {/* Benefit 3: Easy Management */}
                        <div className={styles.featureItem}>
                             <div className={styles.featureIcon}><FiUser /></div>
                            <h3 className={styles.featureTitle}>Effortless Account Control</h3>
                            <p>Update your profile, manage security settings, and view your activity easily within your personal portal space.</p>
                        </div>
                    </div>
                </div>
            </section>

            {/* === Section 4: Showcase Services === */}
             <section className={`${styles.services} ${styles.section}`}>
                 <div className={styles.container}>
                     <h2 className={styles.sectionTitle}>Power Up with Connected Services</h2>
                     <div className={styles.servicesGrid}>
                         {/* Service 1: Examify */}
                         <div className={styles.serviceCard}>
                              <div className={styles.serviceIcon}><FiSmartphone/></div>
                              <h3 className={styles.serviceTitle}>Examify Simulator</h3>
                              <p>Sharpen your skills with realistic exam simulations for NIMCET, CUET & more. Track progress, analyze mistakes.</p>
                              <a href="https://examify.web.app" target="_blank" rel="noopener noreferrer" className={styles.serviceLink}>Launch Examify <FiArrowRightCircle size="1em" style={{marginLeft: '4px'}}/></a>
                         </div>
                         {/* Service 2: BCA Prep */}
                         <div className={styles.serviceCard}>
                             <div className={styles.serviceIcon}><FiBookOpen/></div>
                              <h3 className={styles.serviceTitle}>BCA Prep Resources</h3>
                              <p>Your go-to source for MCQs, PYQs, syllabus details, notes, and career guidance articles for BCA studies.</p>
                              <a href="https://bcaexamprep.blogspot.com/" target="_blank" rel="noopener noreferrer" className={styles.serviceLink}>Visit Prep Blog <FiArrowRightCircle size="1em" style={{marginLeft: '4px'}}/></a>
                         </div>
                         {/* Service 3: Coming Soon */}
                          <div className={`${styles.serviceCard} ${styles.serviceCardMore}`}>
                              <div className={styles.serviceIcon}><FiCoffee /></div> {/* Changed Icon */}
                              <h3 className={styles.serviceTitle}>More Tools Brewing...</h3>
                              <p>We're actively developing new resources and tools to integrate into your portal. Stay tuned!</p>
                              {/* No link needed */}
                         </div>
                     </div>
                 </div>
             </section>

             {/* === Section 5: Social Proof (Optional Example) === */}
             {/*
             <section className={`${styles.testimonials} ${styles.section}`}>
                  <div className={styles.container}>
                      <h2 className={styles.sectionTitle}>What Students Are Saying</h2>
                      <div className={styles.testimonialGrid}>
                           <div className={styles.testimonialCard}>
                                <p>"Examify via the portal saved me hours preparing for NIMCET. The analysis is spot on!"</p>
                                <span>- Priya S.</span>
                           </div>
                           </div>
                           <div className={styles.testimonialCard}>
                                <p>"Having the blog resources linked in the same place I access the simulator is super convenient."</p>
                                <span>- Rohan K.</span>
                           </div>
                           <div className={styles.testimonialCard}>
                               <FiUsers/>
                               <p>Join <strong>1000+</strong> students streamlining their prep!</p>
                           </div>
                      </div>
                  </div>
             </section>
             */}


             {/* === Section 6: Perks Teaser (Optional) === */}
             <section className={`${styles.perksTeaser} ${styles.section}`}>
                 <div className={styles.container} style={{ textAlign: 'center', maxWidth: '700px' }}>
                      <FiZap size={40} color="var(--color-warning)" style={{ marginBottom: styles['spacing-sm']}} />
                      <h2 className={styles.sectionTitle} style={{color: 'var(--color-text-primary)'}}>Ready to Elevate Your Experience?</h2>
                      <p style={{ color: 'var(--color-text-secondary)', fontSize: styles['font-size-base'], marginBottom: styles['spacing-lg'] }}>
                          Explore Premium Perks to unlock features like ad-free browsing on the Prep Blog, extended Examify history, priority support, and more.
                      </p>
                      <Link to="/perks">
                         <Button variant="secondary" size="medium"> <FiStar style={{marginRight: '8px'}}/> Explore Perks </Button>
                      </Link>
                 </div>
             </section>


            {/* === Section 7: Final Call-to-Action === */}
            <section className={`${styles.cta} ${styles.section}`}>
                <div className={styles.container}>
                    <h2 className={styles.ctaTitle}>Start Your Unified Journey Today!</h2>
                    <p className={styles.ctaSubtitle}>Get free, secure access to your essential Samkarya study tools. Simplify and succeed.</p>
                    <Link to="/register">
                        <Button variant="primary" size="large" className={styles.finalCtaButton}>
                             Sign Up Now - It's Free!
                        </Button>
                    </Link>
                    <p style={{ marginTop: styles['spacing-md'], fontSize: styles['font-size-sm']}}>
                        Already have an account? <Link to="/login" style={{color: 'var(--color-text-inverse)', fontWeight: 'bold'}}>Log In Here</Link>
                    </p>
                </div>
            </section>

        </MainLayout>
    );
};

export default LandingPage;
```

---

## pages\LoginPage


### pages\LoginPage\LoginPage.tsx

```typescript
// src/pages/LoginPage/LoginPage.tsx
import React from 'react';
import MainLayout from '../../layouts/MainLayout';
import Login from '../../components/auth/Login/Login';
import styles from '../PageStyles.module.scss'; // Shared page styles

const LoginPage: React.FC = () => {
  return (
    <MainLayout>
      <div className={`${styles.pageWrapper} container`}>
        <Login />
      </div>
    </MainLayout>
  );
};

export default LoginPage;
```

---

## pages\NotFoundPage


### pages\NotFoundPage\NotFoundPage.tsx

```typescript
// src/pages/NotFoundPage/NotFoundPage.tsx
import React from 'react';
import { Link } from 'react-router-dom';
import MainLayout from '../../layouts/MainLayout';
import Button from '../../components/common/Button/Button';
import styles from '../PageStyles.module.scss'; // Reuse common styles
import notFoundStyles from '../NotFoundPage.module.scss'; // Specific styles

const NotFoundPage: React.FC = () => {
  return (
    <MainLayout>
      <div className={`${styles.pageWrapper} ${notFoundStyles.notFoundWrapper} container`}>
         <h1 className={notFoundStyles.errorCode}>404</h1>
         <h2 className={notFoundStyles.errorMessage}>Page Not Found</h2>
         <p className={notFoundStyles.errorDescription}>
            Sorry, the page you are looking for does not exist or may have been moved.
         </p>
         <Button variant="primary" size="large" onClick={() => window.history.back()}>
            Go Back
         </Button>
         <Link to="/" className={notFoundStyles.homeLink}>
             Or go to Homepage
         </Link>
      </div>
    </MainLayout>
  );
};

export default NotFoundPage;
```

---

### pages\NotFoundPage.module.scss

```scss
// src/pages/NotFoundPage.module.scss
@import '../styles/variables';

.notFoundWrapper {
  // Use pageWrapper styles for padding/flex behavior
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-align: center;
  min-height: calc(80vh - #{$spacing-xl * 2}); // Adjust based on header/footer approx height + padding
  color: var(--color-text-primary); // Ensure text uses theme color
}

.errorCode {
  font-size: clamp(6rem, 20vw, 12rem); // Responsive font size
  font-weight: 800; // Very bold
  color: var(--color-primary); // Primary color for the code
  margin-bottom: 0; // Remove space below code
  line-height: 0.8; // Tighten line height
  opacity: 0.8; // Slightly faded maybe
}

.errorMessage {
  font-size: $font-size-h3; // Use heading size
  font-weight: 600;
  color: var(--color-text-primary);
  margin-top: $spacing-sm; // Space between code and message
  margin-bottom: $spacing-md;
}

.errorDescription {
  font-size: $font-size-lg;
  color: var(--color-text-secondary);
  max-width: 500px;
  margin-bottom: $spacing-xl; // Space before buttons
  line-height: 1.7;
}

// Action Buttons are styled by Button component variants

.homeLink {
  display: block;
  margin-top: $spacing-lg; // More space above home link
  font-size: $font-size-sm;
  color: var(--color-text-link);
  font-weight: 500;
  &:hover {
    color: var(--color-text-link-hover);
    text-decoration: underline;
  }
}
```

---

### pages\PageStyles.module.scss

```scss
// src/pages/PageStyles.module.scss
@import '../styles/variables';

.pageWrapper {
  padding-top: $spacing-lg; // Add space below header
  padding-bottom: $spacing-xl; // Add space above footer
  flex-grow: 1; // Ensure page content tries to fill space
}

// Styles for pages with sidebar potential (adjust as needed)
.dashboardLayout {
  // Example if sidebar is added
  // display: flex;
  // .mainContentArea { flex-grow: 1; padding-left: 260px; } // If sidebar has fixed width
}
```

---

## pages\PerksPage


### pages\PerksPage\PerksPage.module.scss

```scss
// src/pages/PerksPage/PerksPage.module.scss
@import '../../styles/variables';

.perksPage {
  // Padding handled by page container (.container.pageWrapper)
  h1 {
    text-align: center;
    color: var(--color-primary);
    margin-bottom: $spacing-sm;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: $spacing-sm;
    font-size: $font-size-h2; // Match other page titles
    font-weight: 600;
    svg { width: 1.2em; height: 1.2em; } // Slightly larger icon in title
  }
  .subtitle {
    text-align: center;
    color: var(--color-text-secondary);
    margin-bottom: $spacing-xl;
    font-size: $font-size-lg;
    line-height: $line-height-base;
    max-width: 650px;
    margin-left: auto;
    margin-right: auto;
  }
}

// --- Current Plan Info Box ---
.currentPlanBox {
  // Similar to info boxes in Profile/Admin
  background-color: var(--color-primary-light); // Use primary light background
  border: 1px solid var(--color-primary); // Use primary border
  border-left-width: 5px; // Thicker left border accent
  padding: $spacing-lg;
  margin-bottom: $spacing-xxl; // More space before the grid
  border-radius: $border-radius-md; // Standard radius

  h2 {
    margin-top: 0;
    margin-bottom: $spacing-sm;
    font-size: $font-size-lg; // Smaller heading inside box
    font-weight: 600;
    color: var(--color-primary-dark); // Darker primary color text
  }
  p {
    margin-bottom: $spacing-xs;
    color: var(--color-text-primary); // Standard text color
    font-size: $font-size-base;
  }
  .planName {
    font-weight: 600;
    color: var(--color-primary-dark);
  }
  .expiredMessage { // Specific style for expired message within this box
      color: var(--color-warning-dark); // Use warning color scheme
      font-size: $font-size-sm;
      font-weight: 500;
      margin-top: $spacing-sm;
      display: inline-flex;
      align-items: center;
      gap: $spacing-xs;
      padding: $spacing-xs $spacing-sm;
      background-color: var(--color-warning-light);
      border-radius: $border-radius-sm;
      border: 1px solid var(--color-warning);
      svg { width: 14px; height: 14px; }
  }
  .currentLimits {
    font-size: $font-size-sm;
    color: var(--color-text-secondary);
    margin-top: $spacing-md; // Space above limits
    padding-top: $spacing-sm; // Space within limit area
    border-top: 1px dashed var(--color-border-secondary); // Separator

    strong { color: var(--color-text-primary); font-weight: 600; }
  }
}

.planName { // For styling the plan name in currentPlanBox
  font-weight: 700; // Bolder plan name
}
.cycleIndicator { // For styling "(Monthly)" or "(Yearly)" next to plan name
  font-size: 0.9em;
  font-weight: 500;
  color: var(--color-text-secondary);
}


.billingCycleToggle {
display: flex;
justify-content: center;
margin-bottom: $spacing-md;
background-color: var(--color-bg-primary); // Slightly different from card for contrast
border: 1px solid var(--color-border-secondary);
border-radius: $border-radius-pill;
overflow: hidden; // Clip buttons to rounded corners
// width: fit-content; // If you want it to not be full width
// margin-left: auto;
// margin-right: auto;
}

.cycleButton {
padding: $spacing-sm $spacing-md; // Adjust padding
font-size: $font-size-sm;
font-weight: 500;
color: var(--color-text-secondary);
background-color: transparent;
border: none; // No individual borders
// border-right: 1px solid var(--color-border-secondary); // Separator line
cursor: pointer;
transition: background-color 0.2s ease, color 0.2s ease;
flex: 1; // Make buttons take equal space
text-align: center;
position: relative; // For savings hint

// &:last-child {
//   border-right: none;
// }

&:not(.active):hover {
    background-color: var(--color-bg-tertiary);
    color: var(--color-text-primary);
}

&.active {
  color: var(--color-text-inverse);
  background-color: var(--color-primary);
  font-weight: 600; // Bolder active
}
}
.cycleSavingsHint { // Small hint on the button itself
  display: block;
  font-size: 0.7rem;
  font-weight: normal;
  opacity: 0.7;
  line-height: 1;
}

// --- Tiers Grid ---
.tiersGrid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); // Responsive columns
  gap: $spacing-xl; // Generous gap between cards
  align-items: stretch; // Make cards equal height
}

// --- Tier Card Styling ---
.tierCard {
  background-color: var(--color-bg-secondary); // Use secondary background for cards
  border: $border-width-lg solid var(--color-border-primary); // Thicker border
  border-radius: $border-radius-lg; // Larger radius
  padding: $spacing-lg;
  display: flex;
  flex-direction: column;
  box-shadow: var(--shadow-sm); // Subtle shadow
  transition: transform 0.2s ease, box-shadow 0.2s ease, border-color 0.2s ease;
  position: relative;

  &:hover {
    transform: translateY(-6px); // More lift on hover
    box-shadow: var(--shadow-lg); // Larger shadow on hover
  }

  // --- Current Tier Highlight ---
  &.currentTier {
    border-color: var(--color-primary); // Highlight border
    box-shadow: var(--shadow-md); // Slightly more shadow
    // transform: scale(1.02); // Optional subtle scale
    // Add a badge/indicator if desired
     &::after {
        content: 'Current Plan';
        position: absolute;
        top: $spacing-md;
        right: $spacing-md;
        background-color: var(--color-primary);
        color: var(--color-text-inverse);
        padding: $spacing-xs $spacing-sm;
        border-radius: $border-radius-pill;
        font-size: 0.7rem;
        font-weight: 600;
        letter-spacing: 0.5px;
     }
     &.popularTier {
      border-color: var(--color-warning); // Highlight popular tier
      box-shadow: var(--shadow-md), 0 0 0 2px var(--color-warning-light);
  }
  }

  .popularBadge {
    position: absolute;
    top: -1px; // Adjust to overlap border nicely
    right: $spacing-md;
    background-color: var(--color-warning);
    color: var(--color-text-inverse);
    padding: $spacing-xs $spacing-sm;
    font-size: 0.7rem;
    font-weight: 700;
    border-radius: 0 0 $border-radius-sm $border-radius-sm;
    letter-spacing: 0.5px;
    text-transform: uppercase;
    box-shadow: var(--shadow-sm);
}

  h3 { // Tier Name
    font-size: 1.5rem; // Larger tier name
    font-weight: 700; // Bold
    color: var(--color-text-primary); // Use primary text
    margin-top: 0;
    margin-bottom: $spacing-xs;
    text-align: center;
  }
}

.tierPrice {
  font-size: 2.25rem; // Larger price
  font-weight: 700;
  color: var(--color-primary); // Highlight price color
  text-align: center;
  margin-bottom: $spacing-xs;
  line-height: 1.1;

  .tierDuration { // Suffix like "/ year"
    font-size: $font-size-base; // Smaller duration text
    font-weight: 400;
    color: var(--color-text-secondary);
    margin-left: $spacing-xs;
  }
  .billingCycleText { // "/month" or "/year" after the price
    font-size: $font-size-base; // Readable but smaller than price
    font-weight: 400;
    color: var(--color-text-secondary);
    margin-left: $spacing-xs;
  }
}

.tierDescription {
  font-size: $font-size-sm;
  color: var(--color-text-secondary);
  text-align: center;
  margin-bottom: $spacing-lg;
  min-height: 45px; // Ensure space for description
}

.savingsText {
  font-size: $font-size-sm;
  color: var(--color-success-dark);
  font-weight: 600; // Bolder savings text
  text-align: center;
  margin-top: $spacing-xs; // Closer to price
  margin-bottom: $spacing-sm;
  height: 1.6em; // Reserve space
  background-color: var(--color-success-light); // Subtle bg for savings
  padding: $spacing-xs;
  border-radius: $border-radius-sm;
  display: inline-block; // Only as wide as content
}

.tierFeatures {
  list-style: none;
  padding: 0;
  margin: 0 0 $spacing-lg 0;
  flex-grow: 1; // Push action button down

  li {
    display: flex;
    align-items: flex-start;
    gap: $spacing-sm;
    margin-bottom: $spacing-sm;
    font-size: $font-size-sm;
    color: var(--color-text-primary); // Standard text for features
    text-align: left;

    svg { // Checkmark icon
      color: var(--color-success); // Use success color
      flex-shrink: 0;
      margin-top: 4px; // Align icon
      width: 16px;
      height: 16px;
    }
  }
}

.tierLimits {
   border-top: 1px dashed var(--color-border-secondary);
   padding-top: $spacing-md;
   margin-top: auto; // Push limits section just above button
   margin-bottom: $spacing-lg;
   font-size: $font-size-sm;
   color: var(--color-text-secondary);
   text-align: center;
   p { margin-bottom: $spacing-xs; font-weight: 500; }
   strong { color: var(--color-text-primary); }
}

.tierAction {
   // margin-top: auto; // Now handled by limits spacing potentially
   button { width: 100%; } // Button takes full width
}

// Security Footer
.securityFooter {
    margin-top: $spacing-xxl;
    text-align: center;
    padding: $spacing-lg;
    background-color: var(--color-bg-secondary);
    border-radius: $border-radius-md;
    border: 1px solid var(--color-border-primary);
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: $spacing-sm;
    font-size: $font-size-sm;
    color: var(--color-text-secondary);

    svg {
        color: var(--color-success); // Green shield
        width: 28px;
        height: 28px;
        margin-bottom: $spacing-xs;
    }

    a {
        color: var(--color-text-link);
        font-weight: 500;
    }
}
```

---

### pages\PerksPage\PerksPage.tsx

```typescript
// src/pages/PerksPage/PerksPage.tsx
import React, { useState, useEffect, useMemo, useRef } from 'react';
import MainLayout from '../../layouts/MainLayout';
import { useAuth } from '../../hooks/useAuth';
import { getTierConfigs, getPaymentUPIDetails } from '../../services/configService'; // Updated import
import { logPaymentForVerification, hasPendingVerification } from '../../services/paymentService';
import { TierConfig, UserData, TierPricingOption, PaidTierConfig, LogPaymentData } from '../../types'; // Ensure types are correct
import Button from '../../components/common/Button/Button';
import LoadingSpinner from '../../components/common/LoadingSpinner/LoadingSpinner';
import PaymentModal from '../../components/common/PaymentModal/PaymentModal';
import { useToast } from '../../components/common/Toast';
import styles from './PerksPage.module.scss';
import pageStyles from '../PageStyles.module.scss';
import { FiCheck, FiZap, FiShield, FiInfo, FiAward } from 'react-icons/fi';
import { Timestamp } from 'firebase/firestore';
import { logAnalyticsEvent } from '../../services/firebase'; // For analytics
import { Link } from 'react-router-dom';

// Helper to get initial or recommended pricing
const getInitialSelectedPricing = (tier: TierConfig): TierPricingOption | undefined => {
    if (!tier.pricingOptions || tier.pricingOptions.length === 0) return undefined;
    const recommended = tier.recommendedCycle ? tier.pricingOptions.find(opt => opt.billingCycle === tier.recommendedCycle) : undefined;
    return recommended || tier.pricingOptions.find(opt => opt.billingCycle === 'yearly') || tier.pricingOptions[0];
};

// Helper to format expiry date
const formatExpiry = (expiry: Timestamp | Date | null): string => {
    if (!expiry) return 'N/A';
    const date = expiry instanceof Timestamp ? expiry.toDate() : expiry;
    return date.toLocaleDateString(undefined, { year: 'numeric', month: 'short', day: 'numeric' });
};

// Helper to determine effective tier (can be moved to utils)
const getEffectiveTier = (userData: UserData | null, tierConfigs: TierConfig[]): TierConfig | undefined => {
    if (!tierConfigs || tierConfigs.length === 0) return undefined;
    const freeTier = tierConfigs.find(t => t.id === 'free');
    if (!userData) return freeTier;
    const currentLevelId = userData.perkLevel || 'free';
    const expiryDate = userData.perkExpiry instanceof Timestamp ? userData.perkExpiry.toDate() : userData.perkExpiry;
    const isExpired = !!expiryDate && expiryDate < new Date();
    const effectiveLevelId = isExpired ? 'free' : currentLevelId;
    return tierConfigs.find(t => t.id === effectiveLevelId) || freeTier;
};


// Interface for the temporary payment details held in state
interface PendingPaymentDetails {
    tier: PaidTierConfig; // The base tier being purchased
    selectedPricingOption: TierPricingOption; // The specific monthly/yearly option
    upiUrl: string;
    expectedNote: string;
}


const PerksPage: React.FC = () => {
    const { currentUser, userData, isLoading: authLoading } = useAuth();
    const { addToast } = useToast();

    const [tierConfigs, setTierConfigs] = useState<TierConfig[]>([]);
    const [isLoadingTiers, setIsLoadingTiers] = useState<boolean>(true);
    const [isCheckingPending, setIsCheckingPending] = useState<boolean>(false);
    const [paymentModalOpen, setPaymentModalOpen] = useState<boolean>(false);
    const [paymentInitiating, setPaymentInitiating] = useState<string | null>(null); // Stores tier.id being initiated
    const prevPerkLevelRef = useRef<UserData['perkLevel'] | undefined>(userData?.perkLevel);

    // State for temporary payment details before modal
    const [pendingPaymentDetails, setPendingPaymentDetails] = useState<PendingPaymentDetails | null>(null);

    // --- NEW State to manage selected billing cycle for EACH tier ---
    const [selectedCycles, setSelectedCycles] = useState<Record<string, 'monthly' | 'yearly'>>({});

    // Fetch Tiers and initialize selectedCycles
    useEffect(() => {
        let isMounted = true;
        setIsLoadingTiers(true);
        getTierConfigs()
            .then(configs => {
                if (isMounted) {
                    setTierConfigs(configs);
                    const initialCycles: Record<string, 'monthly' | 'yearly'> = {};
                    configs.forEach(tier => {
                        if (tier.id !== 'free' && tier.pricingOptions && tier.pricingOptions.length > 0) {
                            const initialOption = getInitialSelectedPricing(tier);
                            if (initialOption) {
                                initialCycles[tier.id] = initialOption.billingCycle;
                            }
                        }
                    });
                    setSelectedCycles(initialCycles);
                }
            })
            .catch(err => {
                if (isMounted) addToast("Could not load perk plans. Please try again.", "error");
               //console.error(err);
            })
            .finally(() => {
                if (isMounted) setIsLoadingTiers(false);
            });
        return () => { isMounted = false };
    }, [addToast]);

    // Effect to show toast on perk level change
    useEffect(() => {
        const currentPerk = userData?.perkLevel;
        const prevPerk = prevPerkLevelRef.current;
        if (currentPerk && prevPerk !== undefined && currentPerk !== prevPerk && currentPerk !== 'free') {
            const tierName = tierConfigs.find(t => t.id === currentPerk)?.name || currentPerk.charAt(0).toUpperCase() + currentPerk.slice(1);
            const cycleText = userData?.currentBillingCycle ? ` (${userData.currentBillingCycle})` : '';
            addToast(`Your ${tierName}${cycleText} plan is now active! 🎉`, 'success', 7000);
        }
        prevPerkLevelRef.current = currentPerk;
    }, [userData?.perkLevel, userData?.currentBillingCycle, addToast, tierConfigs]);

    const effectiveCurrentTier = useMemo(() => getEffectiveTier(userData, tierConfigs), [userData, tierConfigs]);
    const isCurrentPlanExpired = useMemo(() => {
        if (!userData?.perkExpiry || effectiveCurrentTier?.id === 'free') return false; // No expiry for free, or current is free
        const expiryDate = userData.perkExpiry instanceof Timestamp ? userData.perkExpiry.toDate() : userData.perkExpiry;
        return expiryDate < new Date();
    }, [userData?.perkExpiry, effectiveCurrentTier?.id]);

    const handleCycleChange = (tierId: string, cycle: 'monthly' | 'yearly') => {
        setSelectedCycles(prev => ({ ...prev, [tierId]: cycle }));
    };

    const handleTierSelection = async (tier: TierConfig) => {
        if (tier.id === 'free') {
            addToast("The Free plan is automatically active.", "info");
            return;
        }
        if (!currentUser || !userData) {
            addToast("Please log in to select a plan.", "error");
            return;
        }
        if (paymentInitiating) return; // Already processing

        const selectedCycleValue = selectedCycles[tier.id];
        const selectedPricingOption = tier.pricingOptions.find(opt => opt.billingCycle === selectedCycleValue);

        if (!selectedPricingOption) {
            addToast("Please select a billing cycle (Monthly/Yearly) for this plan.", "warning");
            return;
        }
        
        // Check if it's the exact same plan and cycle, not expired
        const isSameCurrentActivePlan = effectiveCurrentTier?.id === tier.id &&
                                     userData?.currentBillingCycle === selectedPricingOption.billingCycle &&
                                     !isCurrentPlanExpired;
        if (isSameCurrentActivePlan) {
            addToast("This is already your active plan and billing cycle.", "info");
            return;
        }


        setPaymentInitiating(tier.id);
        setIsCheckingPending(true);
        setPendingPaymentDetails(null);

        try {
            const isPendingDB = await hasPendingVerification(currentUser.uid);
            if (isPendingDB) {
                addToast("Verification pending for a previous payment. Please wait.", "warning");
                return;
            }

            const upiConfig = await getPaymentUPIDetails();
            if (!upiConfig?.upiId || !upiConfig?.payeeName) {
                throw new Error("Payment gateway details are currently unavailable. Please try again later.");
            }
            const { upiId: YOUR_UPI_ID, payeeName: YOUR_PAYEE_NAME } = upiConfig;
            //const notePrefix = upiConfig.notePrefix || "P";

            const timestamp = Date.now();
            const randomPart = Math.random().toString(36).substring(2, 6).toUpperCase();
            const shortUserId = currentUser.uid.substring(currentUser.uid.length - 5).toUpperCase();
            const expectedNote = `P-${shortUserId}-${tier.id.toUpperCase()}${selectedPricingOption.billingCycle.charAt(0).toUpperCase()}-${timestamp.toString().slice(-5)}${randomPart}`.substring(0, 20);

            const params = new URLSearchParams({
                pa: YOUR_UPI_ID,
                pn: YOUR_PAYEE_NAME,
                am: selectedPricingOption.priceINR.toFixed(2),
                cu: 'INR',
                tn: expectedNote,
            });
            const generatedUpiUrl = `upi://pay?${params.toString()}`;

            setPendingPaymentDetails({
                tier: tier as PaidTierConfig,
                selectedPricingOption: selectedPricingOption,
                upiUrl: generatedUpiUrl,
                expectedNote: expectedNote,
            });
            logAnalyticsEvent('perk_selection_modal_opened', { tier_id: tier.id, billing_cycle: selectedPricingOption.billingCycle });
            setPaymentModalOpen(true);
        } catch (error: any) {
           //console.error("Error during tier selection:", error);
            addToast(error.message || "Could not prepare the upgrade process.", "error");
        } finally {
            setIsCheckingPending(false);
            setPaymentInitiating(null);
        }
    };

    const handleConfirmPayment = async () => {
        if (!pendingPaymentDetails || !currentUser || !userData) {
            addToast("Critical error: Payment details missing. Please restart.", "error");
            setPaymentModalOpen(false);
            return;
        }

        const { tier, selectedPricingOption, expectedNote } = pendingPaymentDetails;

        setPaymentModalOpen(false);
        addToast("Submitting your payment for verification...", "info");

        try {
            const paymentDataToLog: LogPaymentData = {
                 userId: currentUser.uid,
                 userName: userData.displayName || userData.username,
                 userEmail: userData.email,
                 tierId: tier.id,
                 tierName: tier.name,
                 amount: selectedPricingOption.priceINR,
                 currency: 'INR' as const,
                 expectedNote: expectedNote,
                 billingCycle: selectedPricingOption.billingCycle,
                 durationMonthsPaid: selectedPricingOption.durationMonths,
             };

            const paymentId = await logPaymentForVerification(paymentDataToLog);
            addToast(`Payment submitted successfully (Ref: ${paymentId.substring(0,6)}...). Your perks will be active upon verification.`, 'success', 10000);
            logAnalyticsEvent('perk_payment_confirmed', {
                 payment_id_snippet: paymentId.substring(0,6),
                 tier_id: tier.id,
                 billing_cycle: selectedPricingOption.billingCycle,
                 amount: selectedPricingOption.priceINR,
            });
        } catch (error: any) {
            //console.error("Error logging payment for verification:", error);
             addToast(error.message || "Failed to submit payment. Please try again or contact support.", "error");
             logAnalyticsEvent('perk_payment_confirm_error', {
                 tier_id: tier.id,
                 billing_cycle: selectedPricingOption.billingCycle,
                 error_message: error.message,
             });
        } finally {
             setPendingPaymentDetails(null);
        }
    };

    const handleCancelPayment = () => {
         setPaymentModalOpen(false);
         logAnalyticsEvent('perk_payment_cancelled', {
             tier_id: pendingPaymentDetails?.tier.id || 'unknown',
             billing_cycle: pendingPaymentDetails?.selectedPricingOption.billingCycle || 'unknown',
         });
         setPendingPaymentDetails(null);
         addToast("Payment process cancelled.", "info");
    };

    if (authLoading || isLoadingTiers) {
        return (<MainLayout><div className={`${pageStyles.pageWrapper} container`} style={{ textAlign: 'center', paddingTop: '5rem' }}><LoadingSpinner size="large" /><p>Loading Perk Plans...</p></div></MainLayout>);
    }

    return (
        <MainLayout>
            <div className={`${pageStyles.pageWrapper} container ${styles.perksPage}`}>
                <h1><FiAward /> Premium Perks & Plans</h1>
                <p className={styles.subtitle}>Support the platform and unlock exclusive features. Choose a plan that fits your needs!</p>

                {userData && effectiveCurrentTier && (
                    <div className={styles.currentPlanBox}>
                        <h2>
                            {effectiveCurrentTier.id !== 'free' && !isCurrentPlanExpired ? 'Your Current Plan: ' : 'You are on the: '}
                            <span className={styles.planName}>{effectiveCurrentTier.name}</span>
                            {effectiveCurrentTier.id !== 'free' && userData.currentBillingCycle && !isCurrentPlanExpired && (
                                <span className={styles.cycleIndicator}> ({userData.currentBillingCycle.charAt(0).toUpperCase() + userData.currentBillingCycle.slice(1)})</span>
                            )}
                        </h2>
                        {isCurrentPlanExpired && userData.perkLevel !== 'free' && (
                            <p className={styles.expiredMessage}><FiInfo /> Your previous '{userData.perkLevel}' plan expired on: {formatExpiry(userData.perkExpiry as Date)}. Select a new plan to continue.</p>
                        )}
                        {effectiveCurrentTier.id !== 'free' && userData.perkExpiry && !isCurrentPlanExpired && (
                            <p>Active until: <strong>{formatExpiry(userData.perkExpiry)}</strong></p>
                        )}
                        {effectiveCurrentTier.id === 'free' && !isCurrentPlanExpired && (
                            <p>Upgrade to unlock more benefits!</p>
                        )}
                        <div className={styles.currentLimits}>
                            Your Limits:
                            Exam History: <strong>{effectiveCurrentTier.limits.examAttempts ?? 'Unlimited'}</strong> | Hosted Sessions: <strong>{effectiveCurrentTier.limits.hostedSessions ?? 'Unlimited'}</strong>
                        </div>
                    </div>
                )}

                <div className={styles.tiersGrid}>
                    {tierConfigs.filter(t => t.id !== 'free').map(tier => {
                        const currentSelectedCycleForThisTier = selectedCycles[tier.id] || getInitialSelectedPricing(tier)?.billingCycle || 'yearly';
                        const displayPricingOption = tier.pricingOptions.find(opt => opt.billingCycle === currentSelectedCycleForThisTier) || tier.pricingOptions[0];

                        let savingsText = displayPricingOption.savingsText || '';
                        if (currentSelectedCycleForThisTier === 'yearly' && !savingsText) { // Calculate if not provided
                            const yearlyOpt = tier.pricingOptions.find(opt => opt.billingCycle === 'yearly');
                            const monthlyOpt = tier.pricingOptions.find(opt => opt.billingCycle === 'monthly');
                            if (yearlyOpt && monthlyOpt) {
                                const totalMonthlyCost = monthlyOpt.priceINR * 12;
                                if (totalMonthlyCost > yearlyOpt.priceINR) {
                                    const savingPercent = Math.round(((totalMonthlyCost - yearlyOpt.priceINR) / totalMonthlyCost) * 100);
                                    if (savingPercent > 0) savingsText = `Save ${savingPercent}% with yearly!`;
                                }
                            }
                        }
                        
                        const isCurrentActivePlanAndCycle = effectiveCurrentTier?.id === tier.id &&
                                                       userData?.currentBillingCycle === displayPricingOption.billingCycle &&
                                                       !isCurrentPlanExpired;
                        
                        let buttonText = `Choose ${tier.name}`;
                        if (isCurrentActivePlanAndCycle) buttonText = "Current Plan";
                        else if (effectiveCurrentTier && displayPricingOption && (effectiveCurrentTier.pricingOptions.find(opt => opt.billingCycle === effectiveCurrentTier.recommendedCycle)?.priceINR || 0) < displayPricingOption.priceINR) {
                            buttonText = `Get ${tier.name}`;
                         }

                        return (
                            <div key={tier.id} className={`${styles.tierCard} ${isCurrentActivePlanAndCycle ? styles.currentTier : ''} ${tier.isPopular ? styles.popularTier : ''}`}>
                                {tier.isPopular && <div className={styles.popularBadge}>POPULAR</div>}
                                <h3>{tier.name}</h3>

                                {tier.pricingOptions.length > 1 && (
                                    <div className={styles.billingCycleToggle}>
                                        {tier.pricingOptions.map(opt => (
                                            <button
                                                key={opt.billingCycle}
                                                className={`${styles.cycleButton} ${currentSelectedCycleForThisTier === opt.billingCycle ? styles.active : ''}`}
                                                onClick={() => handleCycleChange(tier.id, opt.billingCycle)}
                                                aria-pressed={currentSelectedCycleForThisTier === opt.billingCycle}
                                            >
                                                {opt.billingCycle.charAt(0).toUpperCase() + opt.billingCycle.slice(1)}
                                                {opt.savingsText && currentSelectedCycleForThisTier !== opt.billingCycle && // Show savings hint on inactive yearly button
                                                    <span className={styles.cycleSavingsHint}>{opt.savingsText.split(' ')[0]} {opt.savingsText.split(' ')[1]}</span>
                                                }
                                            </button>
                                        ))}
                                    </div>
                                )}

                                {displayPricingOption && (
                                  <>
                                    <p className={styles.tierPrice}>
                                        <span className={styles.priceValue}>₹{displayPricingOption.priceINR}</span>
                                        <span className={styles.billingCycleText}>
                                            {displayPricingOption.displaySuffix || (displayPricingOption.billingCycle === 'monthly' ? '/month' : '/year')}
                                        </span>
                                    </p>
                                    {savingsText && <p className={styles.savingsText}>{savingsText}</p>}
                                  </>
                                )}
                                <p className={styles.tierDescription}>{tier.description}</p>
                                <ul className={styles.tierFeatures}>
                                    {tier.features.map((feature, index) => {
                                        const currentTierPrice = effectiveCurrentTier?.pricingOptions?.find(opt => opt.billingCycle === (selectedCycles[effectiveCurrentTier.id!] || getInitialSelectedPricing(effectiveCurrentTier!)?.billingCycle))?.priceINR ?? (effectiveCurrentTier?.id === 'free' ? 0 : Infinity);
                                        const newOptionPrice = displayPricingOption?.priceINR ?? Infinity;
                                        
                                        const isNewOrBetter = effectiveCurrentTier &&
                                            !effectiveCurrentTier.features.includes(feature) &&
                                            (currentTierPrice < newOptionPrice);
                                            return (
                                            <li key={index}>
                                                {isNewOrBetter ? <FiZap /> : <FiCheck />} {feature}
                                            </li>
                                        );
                                    })}
                                </ul>
                                <div className={styles.tierLimits}>
                                    <p>Exam History: <strong>{tier.limits.examAttempts ?? 'Unlimited'}</strong></p>
                                    <p>Hosted Sessions: <strong>{tier.limits.hostedSessions ?? 'Unlimited'}</strong></p>
                                </div>
                                <div className={styles.tierAction}>
                                    <Button
                                        variant={isCurrentActivePlanAndCycle ? 'secondary' : 'primary'}
                                        onClick={() => handleTierSelection(tier)}
                                        disabled={isCurrentActivePlanAndCycle || paymentInitiating === tier.id || isCheckingPending}
                                        loading={paymentInitiating === tier.id && currentSelectedCycleForThisTier === selectedCycles[tier.id]}
                                    >
                                        {buttonText} {displayPricingOption && !isCurrentActivePlanAndCycle && `(${displayPricingOption.billingCycle})`}
                                    </Button>
                                </div>
                            </div>
                        );
                    })}
                </div>
                <div className={styles.securityFooter}> <FiShield /> <span>Secure UPI Payments.</span> <Link to="/privacy-policy">Privacy Policy</Link> </div>
            </div>

             {paymentModalOpen && pendingPaymentDetails && pendingPaymentDetails.selectedPricingOption && (
                <PaymentModal
                    isOpen={paymentModalOpen}
                    onClose={handleCancelPayment}
                    onConfirm={handleConfirmPayment}
                    tierName={`${pendingPaymentDetails.tier.name} (${pendingPaymentDetails.selectedPricingOption.billingCycle})`}
                    amount={pendingPaymentDetails.selectedPricingOption.priceINR}
                    upiUrl={pendingPaymentDetails.upiUrl}
                    expectedNote={pendingPaymentDetails.expectedNote}
                />
             )}
        </MainLayout>
    );
};

export default PerksPage;
```

---

## pages\PrivacyPage


### pages\PrivacyPage\PrivacyPage.tsx

```typescript
// src/pages/PrivacyPage/PrivacyPage.tsx
import React from 'react';
import MainLayout from '../../layouts/MainLayout';
import pageStyles from '../PageStyles.module.scss';
import staticStyles from '../StaticPage.module.scss';
import { Link } from 'react-router-dom'; // For internal links

const PrivacyPage: React.FC = () => {
  const lastUpdatedDate = "May 08, 2025"; // <-- UPDATE THIS DATE

  return (
    <MainLayout>
      <div className={`${pageStyles.pageWrapper} container ${staticStyles.pageWrapperOverride}`}>
        <div className={staticStyles.staticPageContainer}>
          {/* START: Paste content below */}

          <h1>Privacy Policy - MyServices Portal</h1>
          <p className={staticStyles.lastUpdated}>Last updated: {lastUpdatedDate}</p>

          <p className={`${staticStyles.disclaimer} ${staticStyles['disclaimer--warning']}`}>
            <strong>Scope:</strong> This Privacy Policy describes how Samkarya ("us", "we", or "our") collects, uses, and protects your information when you use the MyServices Portal ("Portal", "Service"). This policy is the primary privacy document for your account. Services accessed through the portal (like Examify) may have supplementary privacy details found on their respective sites, but your core account data is governed by this policy.
          </p>

          <h2>1. Information We Collect</h2>
          <p>We collect information necessary to provide and improve the Portal service:</p>
          <ul>
            <li>
              <strong>Account Information:</strong> When you register, we collect your email address, chosen username, and display name. Your password is processed and stored securely by Google Firebase Authentication; we do not have access to your plain-text password.
            </li>
            <li>
             <strong>Perk & Subscription Information:</strong> We store your current perk level (e.g., 'free', 'supporter') and the expiry date (if applicable) associated with your account in Firestore.
           </li>
           <li>
           <strong>Payment Information (Verification Records):</strong> When you confirm that you have initiated a payment for a premium perk via UPI, we create a record in our Firestore database containing your user ID, the selected tier, the payment amount, the unique transaction note (`expectedNote`) required for verification, and timestamps related to your confirmation. <b>We do not collect or store your bank account number, UPI PIN, or the full details of your UPI transaction itself.</b> We only store the record indicating you have claimed to make a payment associated with the specific `expectedNote`.
            </li>
            <li>
              <strong>Profile Information:</strong> Information you provide or update in your user profile, primarily your display name.
            </li>
            <li>
              <strong>Usage Data:</strong> We automatically collect some information when you use the Portal, such as your IP address, browser type, device information, pages visited, and timestamps. This is collected via standard web server logs (Firebase Hosting) and potentially Google Analytics (if enabled) to monitor service performance and security.
            </li>
            <li>
              <strong>Contact Form Submissions:</strong> If you use the contact form, we collect your name, email address, subject, and the message content you provide in order to respond to your inquiry. This data is stored securely in our Firestore database.
            </li>
            <li>
              <strong>Cookies:</strong> We use essential cookies (via Firebase Authentication) to keep you logged in securely. We do not typically use tracking cookies for advertising directly on the Portal itself. See Section 6 for more details.
            </li>
          </ul>

          <h2>2. How We Use Your Information</h2>
          <p>We use the information we collect for the following purposes:</p>
          <ul>
            <li>To operate and maintain the Portal service.</li>
            <li>To authenticate you and manage your account securely.</li>
            <li>To allow access to Linked Services using Single Sign-On.</li>
            <li>To respond to your inquiries submitted via the contact form.</li>
            <li>To process and verify payments submitted for perk upgrades (by matching the `expectedNote`).</li>
            <li>To grant access to features based on your perk level and subscription status.</li>
            <li>To personalize your experience (displaying name, showing relevant plan info).</li>
            <li>To monitor usage, analyze trends, and improve the Portal's performance and features (often using aggregated or anonymized data).</li>
            <li>To maintain the security and integrity of the Portal.</li>
            <li>To comply with legal obligations.</li>
          </ul>

          <h2>3. Data Storage and Security</h2>
          <ul>
          <li><strong>Storage:</strong> Your account information, profile data, perk status, payment verification records, and contact submissions are stored using Google Cloud Platform services (primarily Firebase Authentication and Firestore database) located in secure data centers. Application configuration data is also stored in Firestore.</li>
            <li><strong>Security Measures:</strong> We utilize Firebase security features, including Firestore Security Rules, to protect your data from unauthorized access. We implement reasonable administrative and technical safeguards.</li>
            <li><strong>Disclaimer:</strong> Despite our efforts, no online service can be 100% secure. We cannot guarantee the absolute security of your information.</li>
          </ul>

          <h2>4. Data Retention and Deletion</h2>
          <ul>
          <li><strong>Account Data:</strong> We retain your core account and profile information for as long as your account has a status of 'active' or 'suspended'. Perk history may be retained for service functionality.</li>
           <li><strong>Payment Verification Records:</strong> Records of payment attempts submitted for verification (`status: pending_verification`, `completed`, `rejected`) are retained for administrative, support, and accounting purposes for a reasonable period as required by operational needs and applicable regulations.</li>
            <li><strong>Contact Submissions:</strong> Contact form messages are retained as necessary to address your inquiry and for internal record-keeping, and may be deleted periodically.</li>
            <li><strong>Account Deletion Request ("Soft Delete"):</strong> You can request account deletion via your <Link to="/profile">Profile</Link> page. This marks your account status as 'deleted' in our database and prevents future logins after a brief grace period (if applicable during the session the request was made) or upon next login attempt. This action initiates the process for data removal.</li>
<li><strong>Permanent Deletion ("Purge"):</strong> An administrator will periodically review accounts marked as 'deleted' and perform a permanent purge of associated personal data (profile, username lock, payment verification records linked to the user ID, linked service data like Examify history) from our active Firestore database. The Firebase Authentication record associated with your email must be deleted manually by an administrator from the Firebase Console. Aggregated or anonymized usage data may be retained. There may be delays in purging data from backups.</li>
          </ul>

          <h2>5. Information Sharing and Disclosure</h2>
          <ul>
            <li><strong>Service Providers:</strong> We use Google Firebase for core infrastructure (authentication, database, hosting, analytics). Firebase's handling of data is governed by Google's Privacy Policy.</li>
            <li><strong>Legal Requirements:</strong> We may disclose your information if required to do so by law or in response to valid requests by public authorities (e.g., a court or government agency).</li>
            <li><strong>Business Transfers:</strong> If Samkarya is involved in a merger, acquisition, or asset sale, your Personal Data may be transferred.</li>
            <li><strong>No Sale of Data:</strong> We do not sell your personal information to third parties.</li>
          </ul>

          <h2>6. Cookies and Tracking Technologies</h2>
          <p>
            The Portal uses essential cookies provided by Firebase Authentication to manage your login sessions securely. We currently do not use third-party advertising cookies directly on the Portal. Linked Services (like the BCA Prep Blog hosted on Blogspot) may use their own cookies (e.g., Google AdSense), governed by their respective platform policies. You can manage cookie preferences through your browser settings.
          </p>

          <h2>7. Your Data Rights and Choices</h2>
          <p>
            You have rights concerning your personal data:
          </p>
          <ul>
            <li><strong>Access & Update:</strong> You can access and update your profile information (Display Name) via the <Link to="/profile">Profile</Link> page.</li>
            <li><strong>Deletion:</strong> You can request account deletion via the <Link to="/profile">Profile</Link> page.</li>
            <li><strong>Contact:</strong> For other requests or questions about your data, please use the <Link to="/contact">Contact Form</Link>.</li>
          </ul>

          <h2>8. Children's Privacy</h2>
          <p>
            Our Service is not intended for use by children under the age of 13. We do not knowingly collect personally identifiable information from children under 13. If you become aware that a child has provided us with Personal Data, please contact us.
          </p>

          <h2>9. Changes to This Privacy Policy</h2>
          <p>
            We may update this Privacy Policy from time to time. We will notify you of significant changes by posting the new policy on this page and updating the "Last updated" date. You are advised to review this Privacy Policy periodically.
          </p>

          <hr />

          <h2>10. Contact Us</h2>
          <p>If you have any questions about this Privacy Policy, please <Link to="/contact">contact us</Link> using the form provided.</p>

          {/* END: Paste content above */}
        </div>
      </div>
    </MainLayout>
  );
};

export default PrivacyPage;
```

---

## pages\ProfilePage


### pages\ProfilePage\ProfilePage.tsx

```typescript
// src/pages/ProfilePage/ProfilePage.tsx
import React from 'react';
import MainLayout from '../../layouts/MainLayout';
import Profile from '../../components/profile/Profile/Profile';
import styles from '../PageStyles.module.scss'; // Shared page styles

const ProfilePage: React.FC = () => {
  return (
    <MainLayout>
      <div className={`${styles.pageWrapper} container`}>
        <Profile />
      </div>
    </MainLayout>
  );
};

export default ProfilePage;
```

---

## pages\RegisterPage


### pages\RegisterPage\RegisterPage.tsx

```typescript
// src/pages/RegisterPage/RegisterPage.tsx
import React from 'react';
import MainLayout from '../../layouts/MainLayout';
import Register from '../../components/auth/Register/Register';
import styles from '../PageStyles.module.scss';

const RegisterPage: React.FC = () => {
  return (
    <MainLayout>
      <div className={`${styles.pageWrapper} container`}>
        <Register />
      </div>
    </MainLayout>
  );
};

export default RegisterPage;
```

---

### pages\StaticPage.module.scss

```scss
// src/pages/StaticPage.module.scss
@import '../styles/variables'; // SCSS variables for structure/layout

.staticPageContainer {
  background-color: var(--color-bg-secondary); // Use secondary background for content area
  padding: $spacing-xl $spacing-lg;
  border-radius: $border-radius-lg; // Match other main containers
  border: $border-width-base solid var(--color-border-primary);
  box-shadow: var(--shadow-md);
  max-width: 850px; // Allow slightly wider for text content
  margin: $spacing-xl auto; // Center container
  transition: background-color 0.2s ease, border-color 0.2s ease; // Theme transition
}

// --- Typography & Content Styling within the Container ---
.staticPageContainer {
  // Main Page Title (H1)
  h1 {
    font-size: $font-size-h2; // Slightly smaller than main site H1 perhaps
    color: var(--color-primary); // Use primary color for main title
    margin-bottom: $spacing-md; // Space below title
    padding-bottom: $spacing-sm;
    border-bottom: $border-width-lg solid var(--color-primary); // Thicker border under main title
    font-weight: 600;
  }

  // Section Titles (H2)
  h2 {
    font-size: $font-size-h3; // Next level down
    color: var(--color-text-primary);
    margin-top: $spacing-xl; // Generous space before sections
    margin-bottom: $spacing-md;
    padding-bottom: $spacing-xs;
    border-bottom: $border-width-base solid var(--color-border-secondary); // Subtle separator
    font-weight: 600;
  }

  // Sub-Section Titles (H3)
  h3 {
    font-size: $font-size-h4;
    color: var(--color-text-primary); // Use primary text color
    margin-top: $spacing-lg;
    margin-bottom: $spacing-sm;
    font-weight: 600;
  }

  // Paragraphs and List Items
  p, li {
    font-size: $font-size-base;
    line-height: 1.7; // Good line height for readability
    color: var(--color-text-secondary); // Slightly lighter text for content body
    margin-bottom: $spacing-md;

    // Make text primary color if nested directly under main container
    // Use with caution, might make text too dark overall
    // &:first-child { color: var(--color-text-primary); }
  }

  // Make direct text content slightly darker maybe?
  p {
      color: var(--color-text-primary);
  }

  // Links
  a {
    color: var(--color-text-link);
    text-decoration: underline; // Keep underline for static content links
    text-decoration-thickness: 1px;
    text-underline-offset: 3px; // Improve underline appearance
    font-weight: 500; // Make links slightly bolder
    transition: color 0.2s ease, text-decoration-color 0.2s ease;

    &:hover {
      color: var(--color-text-link-hover);
      text-decoration-color: var(--color-text-link-hover); // Match underline color
    }
  }

  // Lists
  ul, ol {
    padding-left: $spacing-xl; // Consistent list indent
    margin-bottom: $spacing-lg;
  }
  li {
    margin-bottom: $spacing-sm;
    color: var(--color-text-primary); // Ensure list text uses primary text color
  }
  // Specific styling for nested lists if needed
  ul ul, ol ol, ul ol, ol ul {
      margin-top: $spacing-sm;
      margin-bottom: $spacing-sm;
  }

  // Blockquotes (if used)
  blockquote {
    border-left: 4px solid var(--color-border-secondary);
    margin: $spacing-md 0 $spacing-md $spacing-sm; // Indent slightly
    padding: $spacing-sm $spacing-lg;
    color: var(--color-text-secondary);
    background-color: var(--color-bg-primary); // Use primary bg to contrast container bg
    font-style: italic;
    border-radius: $border-radius-sm;

    p {
        margin-bottom: 0;
        color: inherit; // Inherit blockquote color
    }
  }

   // Horizontal Rules
   hr {
       border: 0;
       height: $border-width-base;
       background-color: var(--color-border-secondary); // Use secondary border
       margin: $spacing-xl 0;
   }

   // Last Updated Styling
   .lastUpdated {
     font-size: $font-size-sm;
     color: var(--color-text-tertiary); // Muted color
     margin-top: -$spacing-xs; // Pull closer to the title
     margin-bottom: $spacing-lg;
     display: block;
     text-align: left; // Ensure alignment
   }

   // Disclaimer/Warning Box Styling (Example for Privacy/Terms)
   .disclaimer {
       padding: $spacing-md $spacing-lg;
       margin: $spacing-lg 0;
       border-radius: $border-radius-md;
       border-width: $border-width-base;
       border-style: solid;
       border-left-width: 4px; // Thicker left border
       font-size: $font-size-sm;

       // Default style (like info)
       background-color: var(--color-info-light);
       border-color: var(--color-info);
       color: var(--color-info-dark);

       // Modifier for warning/error style (apply class in component)
       &.disclaimer--warning {
           background-color: var(--color-warning-light);
           border-color: var(--color-warning);
           color: var(--color-warning-dark);
       }
        &.disclaimer--error {
           background-color: var(--color-error-light);
           border-color: var(--color-error);
           color: var(--color-error-dark);
       }

       strong { // Make strong text inside disclaimer more prominent
           color: inherit; // Inherit the disclaimer's text color
           font-weight: 600;
       }
       p { margin-bottom: $spacing-xs; &:last-child { margin-bottom: 0; } }
   }
}

// Override default page padding from PageStyles.module.scss if needed
// This ensures the staticPageContainer itself provides the main padding/margin
.pageWrapperOverride {
  padding-top: 0;
  padding-bottom: 0;
}
```

---

## pages\TermsPage


### pages\TermsPage\TermsPage.tsx

```typescript
// src/pages/TermsPage/TermsPage.tsx
import React from 'react';
import MainLayout from '../../layouts/MainLayout';
import pageStyles from '../PageStyles.module.scss';
import staticStyles from '../StaticPage.module.scss';
import { Link } from 'react-router-dom'; // For internal links

const TermsPage: React.FC = () => {
  const lastUpdatedDate = "May 08, 2025"; // <-- UPDATE THIS DATE

  return (
    <MainLayout>
      <div className={`${pageStyles.pageWrapper} container ${staticStyles.pageWrapperOverride}`}>
        <div className={staticStyles.staticPageContainer}>
          {/* START: Paste content below */}

          <h1>Terms of Service - MyServices Portal</h1>
          <p className={staticStyles.lastUpdated}>Last updated: {lastUpdatedDate}</p>

          <p className={`${staticStyles.disclaimer} ${staticStyles['disclaimer--error']}`}>
             <strong>Important:</strong> These Terms govern your use of the MyServices Portal and your account. By using the portal, you also agree to any specific terms applicable to the individual services you access through it (like Examify).
          </p>

          <h2>1. Agreement to Terms</h2>
          <p>
            Welcome to the MyServices Portal ("Portal", "Service") operated by Samkarya ("us", "we", or "our"). These Terms of Service ("Terms") govern your access to and use of the Portal, including account creation, management, and access to linked services.
          </p>
          <p>
            By accessing or using the Portal, creating an account, or clicking to accept or agree to the Terms when this option is made available to you, you accept and agree to be bound and abide by these Terms and our <Link to="/privacy-policy">Privacy Policy</Link>, incorporated herein by reference. If you do not agree to these Terms or the Privacy Policy, you must not access or use the Portal.
          </p>

          <h2>2. Account Registration and Security</h2>
          <ul>
            <li><strong>Eligibility:</strong> You must be at least 13 years old to create an account.</li>
            <li><strong>Accuracy:</strong> You agree to provide accurate, current, and complete information during the registration process and to update such information to keep it accurate, current, and complete.</li>
            <li><strong>Username:</strong> You may not select a username that is offensive, infringes on anyone's rights, or impersonates another person. We reserve the right to reclaim usernames.</li>
            <li><strong>Password Security:</strong> You are responsible for safeguarding your password and for any activities or actions under your account. You agree not to disclose your password to any third party and to notify us immediately of any unauthorized use.</li>
            <li><strong>Account Use:</strong> Your account is personal to you and you may not share account information or allow others to access your account.</li>
          </ul>

          <h2>3. Use of the Portal Service</h2>
          <p>You are granted a limited, non-exclusive, non-transferable, revocable license to access and use the Portal strictly for its intended purposes: managing your account, accessing linked services, and potentially upgrading to premium service tiers ("Perks") provided by Samkarya.</p>
          <p>You agree not to:</p>
          <ul>
            <li>Use the Portal for any illegal or unauthorized purpose.</li>
            <li>Attempt to gain unauthorized access to the Portal, other user accounts, or computer systems or networks connected to the Portal.</li>
            <li>Interfere with or disrupt the integrity or performance of the Portal.</li>
            <li>Use any robot, spider, scraper, or other automated means to access the Portal for any purpose without our express written permission.</li>
          </ul>

          <h2>4. Access to Linked Services</h2>
          <p>
            The Portal provides convenient access to various services offered by Samkarya, such as the <a href="https://examify.web.app" target="_blank" rel="noopener noreferrer">Examify Exam Simulator</a> and the <a href="https://bcaexamprep.blogspot.com/" target="_blank" rel="noopener noreferrer">BCA Exam Prep Blog</a> ("Linked Services").
          </p>
          <p>
            Your use of any Linked Service is subject to these main Portal Terms AND any additional terms, conditions, or policies presented within or specific to that Linked Service. By accessing a Linked Service through this Portal, you agree to comply with its specific terms as well. We are not responsible for the content, features, or practices of Linked Services governed by separate terms.
          </p>

          <h2>5. Intellectual Property (Portal)</h2>
          <p>
            The Portal, including its design, underlying code, text, graphics, logos (e.g., "MyServices Portal", "Samkarya"), and features, are the exclusive property of Samkarya and its licensors, protected by copyright and other intellectual property laws. You may not copy, modify, distribute, sell, or lease any part of our Portal or included software.
          </p>

          <h2>6. User Data, History, and Limits</h2>
          <p>Your use of the Portal involves the collection, storage, and processing of personal data as described in our <Link to="/privacy-policy">Privacy Policy</Link>. Data generated through Linked Services (e.g., Examify attempt history) is associated with your Portal account. Access to certain features or higher usage limits may depend on your selected service tier ("Perk Level"). We reserve the right to modify features and limits associated with any tier upon reasonable notice.</p>

          <h2>7. Premium Perks and Payments</h2>
          <ul>
          <li><strong>Subscription Tiers:</strong> We offer optional premium subscription tiers ("Perks") which grant enhanced features or usage limits. These tiers may be available with different billing cycles (e.g., monthly, yearly) at different price points. Details, pricing, and duration of current tiers and their billing options are available on the <Link to="/perks">Perks Page</Link>.</li>
              <li><strong>Payment Process:</strong> Payments for Perks are processed via UPI (Unified Payments Interface). When you initiate an upgrade, you will be presented with payment instructions, including a QR code and a unique transaction note (`expectedNote`).</li>
              <li><strong>Payment Confirmation:</strong> You must complete the payment using your UPI app, ensuring the amount and the unique transaction note (`expectedNote`) match exactly what is displayed in our portal. After completing the payment in your app, you must return to our portal and click the confirmation button ("I've Made the Payment").</li>
              <li><strong>Verification:</strong> We will attempt to verify your payment based on the confirmed transaction details and the unique `expectedNote`. Perk activation is subject to successful verification by our administrators or automated systems. Verification may take time (minutes to hours). We are not responsible for payment failures due to incorrect information entered by you in your UPI app (especially the note/remark).</li>
              <li><strong>No Refunds:</strong> Payments made for subscription tiers are generally non-refundable, except where required by applicable law.</li>
              <li><strong>Pricing Changes:</strong> We reserve the right to change subscription fees upon reasonable prior notice.</li>
          </ul>

          <h2>8. Termination</h2>
          <p>
          We may terminate or suspend your account (setting status to 'suspended' or initiating deletion) and bar access to the Portal and potentially Linked Services immediately, without prior notice or liability, under our sole discretion, for any reason, including if you breach these Terms. You may request account deletion at any time via the <Link to="/profile">Profile</Link> page, subject to security requirements (e.g., recent login). Upon your account status changing to 'deleted' or 'suspended', your right to use the Portal and access associated services may cease immediately or after any applicable grace period determined by us. Termination details are further described in the <Link to="/privacy-policy#retention">Data Retention and Deletion</Link> section of our Privacy Policy.
          </p>

          <h2>9. Disclaimers</h2>
          <p>
            The Portal is provided on an "AS IS" and "AS AVAILABLE" basis. We make no warranties, express or implied, regarding the Portal's reliability, availability, or suitability for your needs. We do not guarantee that the Portal will be error-free or uninterrupted.
          </p>

          <h2>10. Limitation of Liability</h2>
          <p>
            To the fullest extent permitted by applicable law, Samkarya shall not be liable for any indirect, incidental, special, consequential, or punitive damages, or any loss of profits or revenues, whether incurred directly or indirectly, or any loss of data, use, goodwill, or other intangible losses, resulting from your access to or use of or inability to access or use the Portal.
          </p>

          <h2>11. Changes to Terms</h2>
          <p>
            We reserve the right, at our sole discretion, to modify or replace these Terms at any time. If a revision is material, we will make reasonable efforts to provide at least 30 days' notice prior to any new terms taking effect. By continuing to access or use our Service after any revisions become effective, you agree to be bound by the revised terms.
          </p>

          <h2>12. Governing Law</h2>
          <p>
            These Terms shall be governed and construed in accordance with the laws of India, without regard to its conflict of law provisions.
          </p>

          <hr />

          <h2>13. Contact Us</h2>
          <p>If you have any questions about these Terms, please <Link to="/contact">contact us</Link>.</p>

          {/* END: Paste content above */}
        </div>
      </div>
    </MainLayout>
  );
};

export default TermsPage;
```

---

### reportWebVitals.ts

```typescript
import { ReportHandler } from 'web-vitals';

const reportWebVitals = (onPerfEntry?: ReportHandler) => {
  if (onPerfEntry && onPerfEntry instanceof Function) {
    import('web-vitals').then(({ getCLS, getFID, getFCP, getLCP, getTTFB }) => {
      getCLS(onPerfEntry);
      getFID(onPerfEntry);
      getFCP(onPerfEntry);
      getLCP(onPerfEntry);
      getTTFB(onPerfEntry);
    });
  }
};

export default reportWebVitals;

```

---

## routes


### routes\AdminRoute.tsx

```typescript
// src/routes/AdminRoute.tsx
import React, { useState, useEffect, ReactNode } from 'react';
import { Navigate, useLocation } from 'react-router-dom';
import { useAuth } from '../hooks/useAuth';
import { checkAdminStatus } from '../utils/adminCheck'; // Adjust path
import LoadingSpinner from '../components/common/LoadingSpinner/LoadingSpinner'; // Adjust path

interface AdminRouteProps {
    children: ReactNode;
}

const AdminRoute: React.FC<AdminRouteProps> = ({ children }) => {
    const { currentUser, userData, isLoading: isAuthLoading } = useAuth();
    const [isAdmin, setIsAdmin] = useState<boolean | null>(null); // Use null initial state
    const location = useLocation();

    useEffect(() => {
        // Reset admin status when user changes
        setIsAdmin(null);

        if (!isAuthLoading && currentUser && userData?.status !== 'deleted') {
            // Only check if auth is loaded, user exists, and user is not deleted
            checkAdminStatus(currentUser.uid).then(status => {
                setIsAdmin(status);
            });
        } else if (!isAuthLoading && (!currentUser || userData?.status === 'deleted')) {
            // If auth loaded and no user OR user is deleted, definitely not admin
            setIsAdmin(false);
        }
        // Dependency array includes things that signal when to re-check
    }, [currentUser, userData, isAuthLoading]);

    // --- Loading States ---
    if (isAuthLoading || isAdmin === null) {
        // Show loading if Auth is loading OR admin check is pending
        return (
            <div style={{ display: 'flex', justifyContent: 'center', alignItems: 'center', height: 'calc(100vh - 120px)' }}>
                <LoadingSpinner size="large" />
            </div>
        );
    }

    // --- Redirect Logic ---
    if (!currentUser || userData?.status === 'deleted' || !isAdmin) {
        // Redirect if not logged in OR user is deleted OR explicitly not an admin
        // Preserve the intended location for potential login redirect
        //console.log("Redirecting: Not an Admin, deleted user, or not logged in."); // Debug log
        return <Navigate to="/login" state={{ from: location }} replace />;
    }

    // --- Render Children ---
    // If loading is done, user exists, not deleted, and isAdmin is true
    return <>{children}</>;
};

export default AdminRoute;
```

---

### routes\AppRoutes.tsx

```typescript
// src/routes/AppRoutes.tsx
import React, { ReactNode, Suspense, lazy } from 'react';
import { Routes, Route, Navigate, useLocation } from 'react-router-dom';
import { useAuth } from '../hooks/useAuth';
import LoadingSpinner from '../components/common/LoadingSpinner/LoadingSpinner';

// Import AdminRoute separately since it uses conditional logic
import AdminRoute from './AdminRoute';

// Lazy load page components
const LoginPage = lazy(() => import('../pages/LoginPage/LoginPage'));
const RegisterPage = lazy(() => import('../pages/RegisterPage/RegisterPage'));
const ForgotPasswordPage = lazy(() => import('../pages/ForgotPasswordPage/ForgotPasswordPage'));
const ProfilePage = lazy(() => import('../pages/ProfilePage/ProfilePage'));
const DashboardPage = lazy(() => import('../pages/DashboardPage/DashBoardPage'));
const NotFoundPage = lazy(() => import('../pages/NotFoundPage/NotFoundPage'));
const AboutPage = lazy(() => import('../pages/AboutPage/AboutPage'));
const PrivacyPage = lazy(() => import('../pages/PrivacyPage/PrivacyPage'));
const TermsPage = lazy(() => import('../pages/TermsPage/TermsPage'));
const ContactPage = lazy(() => import('../pages/ContactPage/ContactPage'));
const LandingPage = lazy(() => import('../pages/LandingPage/LandingPage'));
const PerksPage = lazy(() => import('../pages/PerksPage/PerksPage'));

// Admin layouts and pages
const AdminLayout = lazy(() => import('../layouts/AdminLayout'));
const AdminUsersPage = lazy(() => import('../pages/Admin/AdminUsersPage'));
const AdminContactsPage = lazy(() => import('../pages/Admin/AdminContactsPage'));
const DeletedUsersPage = lazy(() => import('../pages/Admin/DeletedUsersPage'));
const AdminDashboardPage = lazy(() => import('../pages/Admin/AdminDashboardPage'));
const AdminPaymentsPage = lazy(() => import('../pages/Admin/AdminPaymentsPage'));
const AdminConfigurationsPage = lazy(() => import('../pages/Admin/AdminConfigurationsPage'));
// Loading fallback component for Suspense
const PageLoader = () => (
  <div style={{ display: 'flex', justifyContent: 'center', alignItems: 'center', height: 'calc(100vh - 120px)' }}>
    <LoadingSpinner size="large" />
  </div>
);

// Wrapper for routes that require authentication
const ProtectedRoute: React.FC<{ children: ReactNode }> = ({ children }) => {
  const { currentUser, userData, isLoading } = useAuth();
  const location = useLocation();

  if (isLoading) {
    return <PageLoader />;
  }

  // Check for deleted user status - redirect to login if user is deleted or not authenticated
  if (!currentUser || userData?.status === 'deleted') {
    // Redirect to login page, saving the intended destination
    return <Navigate to="/login" state={{ from: location }} replace />;
  }

  // User is authenticated and not deleted, render the requested component
  return <>{children}</>;
};

// Wrapper for routes accessible only to non-authenticated users (like login/register)
const PublicRoute: React.FC<{ children: ReactNode }> = ({ children }) => {
  const { currentUser, userData, isLoading } = useAuth();

  if (isLoading) {
    return <PageLoader />;
  }

  // Consider deleted users as "not logged in" for public routes
  if (currentUser && userData?.status !== 'deleted') {
    // User is logged in and not deleted, redirect them away from public-only pages
    return <Navigate to="/dashboard" replace />;
  }

  // User is not authenticated or has deleted status, render the public component
  return <>{children}</>;
};

const AppRoutes: React.FC = () => {
  return (
    <Suspense fallback={<PageLoader />}>
      <Routes>
        {/* Public Routes */}
        <Route
          path="/login"
          element={<PublicRoute><LoginPage /></PublicRoute>}
        />
        <Route
          path="/register"
          element={<PublicRoute><RegisterPage /></PublicRoute>}
        />
        <Route
          path="/forgot-password"
          element={<PublicRoute><ForgotPasswordPage /></PublicRoute>}
        />
        <Route
          path="/"
          element={<PublicRoute><LandingPage /></PublicRoute>}
        />

        {/* Protected Routes */}
        <Route
          path="/dashboard"
          element={<ProtectedRoute><DashboardPage /></ProtectedRoute>}
        />
        <Route
          path="/profile"
          element={<ProtectedRoute><ProfilePage /></ProtectedRoute>}
        />
        <Route
          path="/perks"
          element={<ProtectedRoute><PerksPage /></ProtectedRoute>}
        />

        {/* Static Informational Pages (Public) */}
        <Route 
          path="/about" 
          element={
            <Suspense fallback={<PageLoader />}>
              <AboutPage />
            </Suspense>
          } 
        />
        <Route 
          path="/privacy-policy" 
          element={
            <Suspense fallback={<PageLoader />}>
              <PrivacyPage />
            </Suspense>
          } 
        />
        <Route 
          path="/terms-of-service" 
          element={
            <Suspense fallback={<PageLoader />}>
              <TermsPage />
            </Suspense>
          } 
        />
        <Route 
          path="/contact" 
          element={
            <Suspense fallback={<PageLoader />}>
              <ContactPage />
            </Suspense>
          } 
        />

        {/* Admin Routes */}
        <Route
          path="/admin"
          element={
            <AdminRoute>
              <Suspense fallback={<PageLoader />}>
                <AdminLayout />
              </Suspense>
            </AdminRoute>
          }
        >
          {/* Index route for /admin */}
          <Route index element={<AdminDashboardPage />} />
          {/* Nested routes render inside AdminLayout's <Outlet /> */}
          <Route path="users" element={<AdminUsersPage />} />
          <Route path="contacts" element={<AdminContactsPage />} />
          <Route path="deleted-users" element={<DeletedUsersPage />} />
          <Route path="payments" element={<AdminPaymentsPage />} />
          <Route path="configurations" element={<AdminConfigurationsPage />} />
        </Route>

        {/* Handle root path redirect */}
        <Route path="/" element={<Navigate to="/login" replace />} />
        
        {/* Catch-all Not Found Route */}
        <Route 
          path="*" 
          element={
            <Suspense fallback={<PageLoader />}>
              <NotFoundPage />
            </Suspense>
          } 
        />
      </Routes>
    </Suspense>
  );
};

export default AppRoutes;
```

---

## services


### services\adminService.ts

```typescript
// src/services/adminService.ts
import {
    collection, query, orderBy, limit, startAfter, getDocs, where,
    QueryDocumentSnapshot, DocumentData, doc, updateDoc, serverTimestamp,
    Timestamp, QueryConstraint, collectionGroup, onSnapshot,
    writeBatch,
    getDoc,
    setDoc
} from 'firebase/firestore';
import { db } from './firebase';
import { UserData, ContactSubmission, TierConfig, PaymentAttempt, PaidTierId } from '../types';
import { Unsubscribe } from 'firebase/auth';
import { DEFAULT_CONFIG_DOCS, DEFAULT_TIERS } from '../config/appDefaults';

// Define Orphan Types
export interface OrphanedAttempt {
    id: string; // attemptId
    path: string; // Full path for deletion
    userId: string;
    examTitle?: string;
    attemptTimestamp?: Timestamp;
    // Add other relevant fields for display
}

export interface OrphanedParticipant {
    id: string; // participantId (which is userId)
    path: string; // Full path for deletion
    participantId: string; // Stored as field in the document
    sessionId: string; // Need session ID to know which groupExam it belongs to
    joinedAt?: Timestamp;
    status?: 'joined' | 'started' | 'completed'; // Display status
    displayName?: string;
    // Add other relevant fields for display
}

export const USERS_PER_PAGE = 15;

interface GetUsersAdminOptions {
    statusFilter: 'active' | 'suspended' | 'deleted';
    limitPerPage?: number;
    startAfterDoc?: QueryDocumentSnapshot<DocumentData> | null;
    // searchTerm?: string; // Defer complex search implementation for now
}

interface GetUsersAdminResult {
    users: UserData[];
    lastVisible: QueryDocumentSnapshot<DocumentData> | null;
    hasMore: boolean;
}

/**
 * Fetches a paginated list of users based on status filter.
 */
export const getUsersAdmin = async (options: GetUsersAdminOptions): Promise<GetUsersAdminResult> => {
    const {
        statusFilter,
        limitPerPage = USERS_PER_PAGE,
        startAfterDoc = null,
        // searchTerm = '' // For future search implementation
    } = options;

    const constraints: QueryConstraint[] = [
        where('status', '==', statusFilter),
        orderBy('createdAt', 'desc'), // Default sort
        limit(limitPerPage)
    ];

    if (startAfterDoc) {
        constraints.push(startAfter(startAfterDoc));
    }

    // Build the query
    const usersQuery = query(collection(db, 'users'), ...constraints);

    try {
        const documentSnapshots = await getDocs(usersQuery);

        const fetchedUsers = documentSnapshots.docs.map(docSnapshot => {
            const data = docSnapshot.data();
            // Convert Firestore Timestamps to JS Dates for easier handling in components
            const createdAt = data.createdAt instanceof Timestamp ? data.createdAt.toDate() : null;
            const updatedAt = data.updatedAt instanceof Timestamp ? data.updatedAt.toDate() : null;

            return {
                ...data,
                uid: docSnapshot.id,
                createdAt: createdAt,
                updatedAt: updatedAt,
            } as UserData;
        });

        const lastDoc = documentSnapshots.docs[documentSnapshots.docs.length - 1] || null;
        const morePagesExist = fetchedUsers.length === limitPerPage;

        return {
            users: fetchedUsers,
            lastVisible: lastDoc,
            hasMore: morePagesExist,
        };
    } catch (error) {
       console.error("Error fetching users (admin):", error);
        throw new Error("Failed to fetch user list."); // Re-throw for component handling
    }
};

/**
 * Updates the status field of a user document (admin action).
 */
export const updateUserStatusAdmin = async (userId: string, newStatus: 'active' | 'suspended'): Promise<void> => {
    if (!userId || !newStatus) {
        throw new Error("User ID and new status are required.");
    }
    // Ensure only allowed statuses are set by admin directly here
    if (newStatus !== 'active' && newStatus !== 'suspended') {
        throw new Error("Invalid status provided for admin update.");
    }

    try {
        const userDocRef = doc(db, 'users', userId);
        await updateDoc(userDocRef, {
            status: newStatus,
            updatedAt: serverTimestamp() // Always update the timestamp
        });
    } catch (error) {
       //console.error(`Error updating status for user ${userId}:`, error);
        throw new Error(`Failed to update status for user ${userId}.`); // Re-throw
    }
};

interface GetDeletedUsersAdminOptions {
    limitPerPage?: number;
    startAfterDoc?: QueryDocumentSnapshot<DocumentData> | null;
}

interface GetDeletedUsersAdminResult {
    users: UserData[];
    lastVisible: QueryDocumentSnapshot<DocumentData> | null;
    hasMore: boolean;
}

/**
 * Fetches a paginated list of deleted users.
 */
export const getDeletedUsersAdmin = async (
    options: GetDeletedUsersAdminOptions
): Promise<GetDeletedUsersAdminResult> => {
    const {
        limitPerPage = USERS_PER_PAGE,
        startAfterDoc = null
    } = options;

    const constraints: QueryConstraint[] = [
        where('status', '==', 'deleted'),
        orderBy('deletedAt', 'desc'), // Order by deletion request time
        limit(limitPerPage)
    ];

    if (startAfterDoc) {
        constraints.push(startAfter(startAfterDoc));
    }

    const deletedUsersQuery = query(collection(db, 'users'), ...constraints);

    try {
        const documentSnapshots = await getDocs(deletedUsersQuery);
        const fetchedUsers = documentSnapshots.docs.map(docSnapshot => {
            const data = docSnapshot.data();
            const createdAt = data.createdAt instanceof Timestamp ? data.createdAt.toDate() : null;
            const updatedAt = data.updatedAt instanceof Timestamp ? data.updatedAt.toDate() : null;
            const deletedAt = data.deletedAt instanceof Timestamp ? data.deletedAt.toDate() : null; // Include deletedAt

            return {
                ...data,
                uid: docSnapshot.id,
                createdAt: createdAt,
                updatedAt: updatedAt,
                deletedAt: deletedAt, // Add to return type if needed
            } as UserData; // Adjust UserData type if adding deletedAt
        });

        const lastDoc = documentSnapshots.docs[documentSnapshots.docs.length - 1] || null;
        const morePagesExist = fetchedUsers.length === limitPerPage;

        return {
            users: fetchedUsers,
            lastVisible: lastDoc,
            hasMore: morePagesExist,
        };
    } catch (error) {
       console.error("Error fetching deleted users (admin):", error);
        throw new Error("Failed to fetch deleted user list.");
    }
};

/**
 * Fetches all exam attempts for a specific user.
 * Note: This reads from the potentially orphaned subcollection.
 */
export const getUserAttemptsAdmin = async (userId: string): Promise<OrphanedAttempt[]> => {
    if (!userId) return [];
    try {
        const attemptsRef = collection(db, `examSimulator/${userId}/attempts`);
        // No specific filtering needed here unless adding more options
        const q = query(attemptsRef, orderBy("attemptTimestamp", "desc"));
        const querySnapshot = await getDocs(q);

        const attempts: OrphanedAttempt[] = [];
        querySnapshot.forEach((docSnap) => {
            attempts.push({
                id: docSnap.id,
                path: docSnap.ref.path, // Include path
                userId: userId,
                ...(docSnap.data() as Omit<OrphanedAttempt, 'id' | 'path' | 'userId'>)
            });
        });
        return attempts;
    } catch (error) {
       //console.error(`Error fetching attempts for user ${userId}:`, error);
        // Return empty array or throw? Returning empty is safer for the UI.
        return [];
    }
};

/**
 * Fetches all group participation records for a specific user using a collection group query.
 * Since participant ID is equal to user ID, we can use a collection group query with where clause.
 */
export const getUserGroupParticipationsAdmin = async (userId: string): Promise<OrphanedParticipant[]> => {
    if (!userId) return [];
    try {
        // Since participant ID equals user ID, we can query for documents where the ID equals userId
        // We need a collection group query to search across all participants subcollections
        const q = query(collectionGroup(db, 'participants'), where("participantId", "==", userId));
        const querySnapshot = await getDocs(q);
        
        const participations: OrphanedParticipant[] = [];
        querySnapshot.forEach((docSnap) => {
            // Extract session ID from path segments
            const pathSegments = docSnap.ref.path.split('/');
            // Assuming path format: "groupExams/{examId}/sessions/{sessionId}/participants/{participantId}"
            const sessionId = pathSegments[pathSegments.length - 3]; 
            
            participations.push({
                id: docSnap.id, // This is the participantId which equals userId
                path: docSnap.ref.path,
                sessionId: sessionId,
                participantId: userId, // Explicitly set for clarity
                ...(docSnap.data() as Omit<OrphanedParticipant, 'id' | 'path' | 'sessionId' | 'participantId'>)
            });
        });
        
        return participations;
    } catch (error) {
       console.error(`Error fetching group participations:`, error);
        return []; // Return empty on error
    }
};

/**
 * Listens for real-time updates to contact submissions based on a filter.
 * @param filter The status to filter by ('new', 'read', 'archived', 'all').
 * @param callback Function to be called with the fetched submissions array.
 * @param onError Callback for handling errors during snapshot listening.
 * @returns The unsubscribe function from onSnapshot.
 */
export const listenToSubmissions = (
    filter: 'new' | 'read' | 'archived' | 'all',
    callback: (submissions: ContactSubmission[]) => void,
    onError: (error: Error) => void
): Unsubscribe => {

    const constraints: QueryConstraint[] = [
        orderBy('submittedAt', 'desc') // Always order by newest
    ];

    if (filter !== 'all') {
        constraints.push(where('status', '==', filter));
    }

    const submissionsQuery = query(collection(db, 'contactSubmissions'), ...constraints);

    const unsubscribe = onSnapshot(submissionsQuery, (querySnapshot) => {
        const fetchedSubmissions = querySnapshot.docs.map(docSnap => ({
            id: docSnap.id,
            ...docSnap.data(),
            // Keep submittedAt as Timestamp for potential further processing if needed
        })) as ContactSubmission[];
        callback(fetchedSubmissions); // Pass the results to the callback
    }, (error) => {
       console.error("Error listening to contact submissions:", error);
        onError(new Error("Failed to fetch contact submissions in real-time."));
    });

    return unsubscribe; // Return the cleanup function
};

/**
 * Performs CLIENT-SIDE deletion of associated Firestore data for a user.
 * WARNING: Does NOT delete the Firebase Auth record.
 * @param userId The UID of the user whose data is to be purged.
 * @param username The username for deleting the username lock.
 * @param attempts Array of OrphanedAttempt objects for the user.
 * @param participants Array of OrphanedParticipant objects for the user.
 */
export const purgeFirestoreDataClientSide = async (
    userId: string,
    username: string,
    attempts: OrphanedAttempt[],
    participants: OrphanedParticipant[]
): Promise<{ success: boolean; message: string }> => {
    if (!userId || !username) {
        throw new Error("User ID and Username required for purging.");
    }

    //console.log(`Starting CLIENT-SIDE purge for user: ${userId}`);
    const batch = writeBatch(db);

    try {
        // --- Delete Exam Attempts ---
        if (attempts && attempts.length > 0) {
            //console.log(`Deleting ${attempts.length} attempt documents...`);
            attempts.forEach(attempt => {
                batch.delete(doc(db, attempt.path)); // Delete using full path
            });
        }
         // Also delete the parent simulator doc (might be empty)
        const simulatorDocRef = doc(db, `examSimulator/${userId}`);
        batch.delete(simulatorDocRef);

        // --- Delete Group Participations ---
        if (participants && participants.length > 0) {
            //console.log(`Deleting ${participants.length} participant documents...`);
             participants.forEach(part => {
                batch.delete(doc(db, part.path)); // Delete using full path
            });
        }

        // --- Delete User Document ---
        //console.log("Deleting user document...");
        const userDocRef = doc(db, `users/${userId}`);
        batch.delete(userDocRef);

        // --- Delete Username Lock ---
        //console.log("Deleting username document...");
        const usernameDocRef = doc(db, `usernames/${username.toLowerCase()}`);
        batch.delete(usernameDocRef);

        // --- Commit Firestore Deletions ---
        //console.log(`Committing Firestore deletions for ${userId}...`);
        await batch.commit();
        //console.log(`Firestore data purged successfully for user ${userId}.`);

        return { success: true, message: `Firestore data for ${username} purged. Auth record remains.` };

    } catch (error: any) {
       //console.error(`Error during client-side Firestore purge for user ${userId}:`, error);
        throw new Error(`Failed to purge Firestore data: ${error.message}`);
    }
};

/**
 * Updates the status of a specific contact submission.
 * @param submissionId The ID of the contact submission document.
 * @param newStatus The new status ('read' or 'archived').
 */
export const updateSubmissionStatus = async (
    submissionId: string,
    newStatus: 'read' | 'archived'
): Promise<void> => {
    if (!submissionId || (newStatus !== 'read' && newStatus !== 'archived')) {
        throw new Error("Invalid submission ID or status provided.");
    }
    try {
        const submissionDocRef = doc(db, 'contactSubmissions', submissionId);
        await updateDoc(submissionDocRef, {
            status: newStatus,
            // You could add an 'updatedAt' or 'actionTakenAt' timestamp here:
            // updatedAt: serverTimestamp()
        });
    } catch (error) {
       //console.error(`Error updating submission ${submissionId} status to ${newStatus}:`, error);
        throw new Error(`Failed to update submission status.`);
    }
};

/**
 * ADMIN FUNCTION: Initializes or overwrites ALL configuration documents
 * in the `configuration` collection based on the defaults in appDefaults.ts.
 * USE WITH EXTREME CAUTION.
 */
export const initializeAllConfigurations = async (): Promise<{ success: boolean; message: string; errors: string[] }> => {
   //console.warn("ADMIN: Attempting to initialize/reset ALL Firestore configurations!");
    const batch = writeBatch(db);
    const configCollectionRef = collection(db, 'configuration');
    const errors: string[] = [];

    try {
        // Iterate over the default configuration object
        for (const [docId, docData] of Object.entries(DEFAULT_CONFIG_DOCS)) {
            try {
                const docRef = doc(configCollectionRef, docId);
                // Use setDoc with merge: false (the default) to completely overwrite
                batch.set(docRef, docData);
                //console.log(`ADMIN: Queued overwrite for configuration/${docId}`);
            } catch (loopError: any) {
               //console.error(`ADMIN: Error preparing batch for configuration/${docId}:`, loopError);
                errors.push(`Failed to prepare ${docId}: ${loopError.message}`);
            }
        }

        if (errors.length > 0) {
             throw new Error("Errors occurred while preparing configuration batch.");
        }

        // Commit the batch write
        await batch.commit();
        //console.log("ADMIN: Successfully committed configuration initialization batch.");
        return { success: true, message: "All configurations reset to defaults successfully.", errors: [] };

    } catch (error: any) {
       //console.error("ADMIN: Error initializing all configurations:", error);
         // Add the main commit error if different from preparation errors
         if (!errors.includes(error.message)) {
             errors.push(`Batch commit failed: ${error.message}`);
         }
        return { success: false, message: "Failed to reset configurations.", errors };
    }
};

/**
 * ADMIN/SERVER FUNCTION: Fetches the tier configurations directly from Firestore.
 * Avoids client-side cache. Useful for server-side logic or admin panels.
 * Renamed to avoid conflict with client-side cached version.
 * @returns Promise<TierConfig[]> An array of tier configurations.
 */
export const getTierConfigurationsDirect = async (): Promise<TierConfig[]> => {
    try {
        // --- UPDATED PATH ---
        const configRef = doc(db, 'configuration', 'tiers');
        const docSnap = await getDoc(configRef);

        if (docSnap.exists()) {
            const data = docSnap.data();
             if (data?.tiers && Array.isArray(data.tiers)) {
                 return data.tiers as TierConfig[];
             }
        }
       //console.warn("ADMIN: Tier configuration document ('configuration/tiers') not found or invalid!");
        // Fallback to default config? Or throw error for admin? Let's return default for now.
        return DEFAULT_TIERS;
    } catch (error) {
       //console.error("ADMIN: Error fetching tier configurations directly:", error);
        throw new Error("Could not load tier configurations from Firestore."); // Throw error for admin context
    }
};

/**
 * Approves a pending payment (Admin Action) - UPDATED FOR NEW CONFIG SERVICE
 * 
 * Fetches tier config using the DIRECT function to ensure latest duration.
 */
export const approvePaymentAdmin = async (paymentId: string, adminUid: string): Promise<void> => {
    if (!paymentId || !adminUid) {
        throw new Error("Payment ID and Admin UID are required.");
    }

    const paymentDocRef = doc(db, 'payments', paymentId);
    let userId: string | null = null;
    let tierIdFromPayment: PaidTierId; // Expect 'basic', 'pro', or 'elite'
    let billingCycleFromPayment: 'monthly' | 'yearly';
    let durationMonthsForThisPayment: number; // This comes from the payment record

    try {
        // --- Step 1: Fetch Payment Details ---
        //console.log(`[Admin][Approve] Fetching payment details for ${paymentId}`);
        const paymentSnap = await getDoc(paymentDocRef);
        if (!paymentSnap.exists()) {
            throw new Error("Payment record not found.");
        }
        const paymentData = { id: paymentSnap.id, ...paymentSnap.data() } as PaymentAttempt;
        userId = paymentData.userId;
        tierIdFromPayment = paymentData.tierId; // This SHOULD be 'basic', 'pro', or 'elite'
        billingCycleFromPayment = paymentData.billingCycle;
        durationMonthsForThisPayment = paymentData.durationMonthsPaid; 
        
        if (!userId || !tierIdFromPayment || !billingCycleFromPayment || durationMonthsForThisPayment === undefined) {
            throw new Error("Payment record missing essential user, tier, cycle, or duration information.");
        }
        if (paymentData.status !== 'pending_verification') {
            throw new Error(`Payment status is '${paymentData.status}', not 'pending_verification'. Cannot approve.`);
        }
        //console.log(`[Admin][Approve] Payment details fetched for user ${userId}, tier ${tierIdFromPayment}. Duration from payment: ${durationMonthsForThisPayment} months.`);

        // --- Step 3: Calculate Expiry Date ---
        let newExpiry: Timestamp | null = null;
        if (durationMonthsForThisPayment > 0) {
            const expiryDate = new Date(); // Start from now
            expiryDate.setMonth(expiryDate.getMonth() + durationMonthsForThisPayment);
            expiryDate.setHours(23, 59, 59, 999); // Set to end of day for consistency
            newExpiry = Timestamp.fromDate(expiryDate);
            //console.log(`[Admin][Approve] Calculated new expiry: ${newExpiry?.toDate().toISOString()}`);
        } else {
           //console.warn(`Payment ${paymentId} has invalid durationMonthsPaid (${durationMonthsForThisPayment}). Perk will not have an expiry if set to 0 or less.`);
            // For a 0-month duration (e.g. a lifetime special offer, though not in current plan), newExpiry would be null or far future.
            // Here, we'll assume positive duration for standard perks. If 0, newExpiry remains null.
        }

        // --- Step 4: Prepare Batch Write ---
        const batch = writeBatch(db);
        const userDocRef = doc(db, 'users', userId);

        // a) Update Payment Document
        batch.update(paymentDocRef, {
            status: 'completed' as const,
            processedAt: serverTimestamp(),
            adminProcessorUid: adminUid,
            rejectionReason: null // Clear any previous rejection reason
        });
        //console.log(`[Admin][Approve] Batch: Added payment ${paymentId} update.`);

        // b) Update User Document
        // The `tierIdFromPayment` correctly holds 'basic', 'pro', or 'elite'
        batch.update(userDocRef, {
            perkLevel: tierIdFromPayment, 
            perkExpiry: newExpiry,
            currentBillingCycle: billingCycleFromPayment, // Store the cycle for which payment was made
            updatedAt: serverTimestamp()
        });
        //console.log(`[Admin][Approve] Batch: Added user ${userId} perks update (Tier: ${tierIdFromPayment}, Cycle: ${billingCycleFromPayment}).`);

        // --- Step 5: Commit Batch Write ---
        //console.log(`[Admin][Approve] Committing batch write for payment ${paymentId} and user ${userId}...`);
        await batch.commit();
        //console.log(`ADMIN: Payment ${paymentId} approved for user ${userId}. Tier set to ${tierIdFromPayment}.`);

    } catch (error: any) {
       //console.error(`ADMIN Error approving payment ${paymentId}:`, error);
        if (error.message.includes("Config for tier") || error.message.includes("missing user or tier")) {
            throw error; // Rethrow specific, informative errors
        }
        if (error.code === 'permission-denied') { // Firestore permission error
             throw new Error(`Permission denied. Ensure the admin (${adminUid}) has rights to update user and payment documents.`);
        }
        throw new Error(`Failed to complete approval process: ${error.message}`);
    }
};

/**
 * Rejects a pending payment (Admin Action).
 * Sets status to 'rejected'.
 * @param paymentId The ID of the payment document.
 * @param adminUid The UID of the admin performing the action.
 * @param reason Optional reason for rejection.
 */
export const rejectPaymentAdmin = async (paymentId: string, adminUid: string, reason?: string): Promise<void> => {
    if (!paymentId || !adminUid) {
        throw new Error("Payment ID and Admin UID are required.");
    }
    try {
        const paymentDocRef = doc(db, 'payments', paymentId);
        const updateData: any = {
            status: 'rejected',
            processedAt: serverTimestamp() as Timestamp,
            adminProcessorUid: adminUid,
        };
        if (reason) {
            updateData.rejectionReason = reason;
        }
        await updateDoc(paymentDocRef, updateData);
        //console.log(`Admin ${adminUid} rejected payment ${paymentId}. Reason: ${reason || 'N/A'}`);
    } catch (error) {
       //console.error(`Error rejecting payment ${paymentId} by admin ${adminUid}:`, error);
        throw new Error("Failed to reject payment.");
    }
};

// --- NEW Function to Listen for Pending Payments (Similar to listenToSubmissions) ---
/**
 * Listens for real-time updates to payments pending verification.
 * @param callback Function to be called with the fetched payments array.
 * @param onError Callback for handling errors during snapshot listening.
 * @returns The unsubscribe function from onSnapshot.
 */
export const listenToPendingPayments = (
    callback: (payments: PaymentAttempt[]) => void,
    onError: (error: Error) => void
): Unsubscribe => {

    const constraints: QueryConstraint[] = [
        where('status', '==', 'pending_verification'),
        orderBy('userConfirmedAt', 'asc') // Show oldest pending first
    ];

    const paymentsQuery = query(collection(db, 'payments'), ...constraints);

    const unsubscribe = onSnapshot(paymentsQuery, (querySnapshot) => {
        const fetchedPayments = querySnapshot.docs.map(docSnap => {
            const data = docSnap.data();

            return {
                id: docSnap.id,
                ...data,
                createdAt: data.createdAt, // Keep original Timestamp for potential reference
                userConfirmedAt: data.userConfirmedAt, // Keep original
                 // Add typed dates for easier display if needed
                 // createdAtDate: createdAt,
                 // userConfirmedAtDate: userConfirmedAt,
            } as PaymentAttempt; // Cast, ensure PaymentAttempt type is correct
        });
        callback(fetchedPayments);
    }, (error) => {
       console.error("Error listening to pending payments:", error);
        onError(new Error("Failed to fetch pending payments in real-time."));
    });

    return unsubscribe;
};
// --- MODIFIED/NEW Function to Listen for Payments by Status ---
/**
 * Listens for real-time updates to payments based on a filter.
 * @param filter The status to filter by ('pending_verification', 'completed', 'rejected', 'expired', 'pending_user_action', 'all').
 * @param callback Function to be called with the fetched payments array.
 * @param onError Callback for handling errors during snapshot listening.
 * @returns The unsubscribe function from onSnapshot.
 */
export const listenToPaymentsByStatus = (
    filter: PaymentAttempt['status'] | 'all', // Use type from PaymentAttempt
    callback: (payments: PaymentAttempt[]) => void,
    onError: (error: Error) => void
): Unsubscribe => {

    const constraints: QueryConstraint[] = [
        //orderBy('createdAt', 'desc') // Order by creation time generally
        // Optionally, adjust sorting based on filter (e.g., userConfirmedAt for pending)
        // if (filter === 'pending_verification') {
        //     constraints = [orderBy('userConfirmedAt', 'asc')];
        // } else {
        //     constraints = [orderBy('createdAt', 'desc')];
        // }
    ];

    if (filter !== 'all') {
        constraints.push(where('status', '==', filter));
    }

    const paymentsQuery = query(collection(db, 'payments'), ...constraints);

    const unsubscribe = onSnapshot(paymentsQuery, (querySnapshot) => {
        const fetchedPayments = querySnapshot.docs.map(docSnap => {
            const data = docSnap.data();
            // Convert Timestamps if needed for display, keep original otherwise
            return {
                id: docSnap.id,
                ...data,
                // Example: Add JS Date versions if helpful
                // createdAtDate: data.createdAt instanceof Timestamp ? data.createdAt.toDate() : null,
                // userConfirmedAtDate: data.userConfirmedAt instanceof Timestamp ? data.userConfirmedAt.toDate() : null,
                // processedAtDate: data.processedAt instanceof Timestamp ? data.processedAt.toDate() : null,
            } as PaymentAttempt;
        });
        callback(fetchedPayments);
    }, (error) => {
       //console.error(`Error listening to payments with filter "${filter}":`, error);
        onError(new Error(`Failed to fetch payments (${filter}).`));
    });

    return unsubscribe;
};

/**
 * Downgrades a user's perks to 'free' and clears the expiry date (Admin Action).
 * @param userId The UID of the user to downgrade.
 */
export const downgradeUserPerksAdmin = async (userId: string): Promise<void> => {
    if (!userId) {
        throw new Error("User ID is required to downgrade perks.");
    }

    try {
        const userDocRef = doc(db, 'users', userId);
        await updateDoc(userDocRef, {
            perkLevel: 'free',
            perkExpiry: null, // Explicitly set expiry to null
            updatedAt: serverTimestamp() // Always update timestamp
        });
        //console.log(`Admin action: User ${userId} perks downgraded to free.`);
    } catch (error: any) {
       //console.error(`Error downgrading perks for user ${userId}:`, error);
        throw new Error(`Failed to downgrade perks for user ${userId}.`);
    }
};
/**
 * ADMIN FUNCTION: Fetches a specific configuration document.
 * @param docId The ID of the configuration document (e.g., 'tiers', 'global').
 */
export const getSpecificConfigAdmin = async (docId: string): Promise<any | null> => {
    try {
        const configRef = doc(db, 'configuration', docId);
        const docSnap = await getDoc(configRef);
        if (docSnap.exists()) {
            //console.log(`ADMIN: Fetched configuration/${docId}`);
            return docSnap.data();
        } else {
           //console.warn(`ADMIN: Configuration document 'configuration/${docId}' not found.`);
            // Option: Initialize with default if not found?
            // For now, return null, editor page can offer to init
            const defaultConfigForDoc = (DEFAULT_CONFIG_DOCS as Record<string, any>)[docId];
            if (defaultConfigForDoc) {
                 //console.log(`ADMIN: Initializing configuration/${docId} with defaults as it was not found.`);
                 await setDoc(configRef, defaultConfigForDoc); // Initialize if not found
                 return defaultConfigForDoc; // Return the default
            }
            return null;
        }
    } catch (error) {
       //console.error(`ADMIN: Error fetching configuration/${docId}:`, error);
        throw new Error(`Failed to fetch '${docId}' configuration.`);
    }
};

/**
 * ADMIN FUNCTION: Updates/Overwrites a specific configuration document.
 * @param docId The ID of the configuration document.
 * @param data The new data object for the document.
 */
export const updateSpecificConfigAdmin = async (docId: string, data: any): Promise<void> => {
    try {
        const configRef = doc(db, 'configuration', docId);
        // Using setDoc will overwrite the entire document with the new data.
        // Use updateDoc if you only want to merge specific fields.
        // For config management, full overwrite is often intended.
        await setDoc(configRef, data);
        //console.log(`ADMIN: Configuration 'configuration/${docId}' updated successfully.`);
        // Consider clearing client-side cache for this specific config if applicable
        // clearConfigCacheForKey(docId);
    } catch (error) {
       //console.error(`ADMIN: Error updating configuration/${docId}:`, error);
        throw new Error(`Failed to update '${docId}' configuration.`);
    }
};
```

---

### services\configService.ts

```typescript
// src/services/configService.ts
import { doc, getDoc, DocumentData, DocumentSnapshot } from 'firebase/firestore';
import { db } from './firebase';
import { TierConfig, UserService,} from '../types';

// --- Type Definitions specific to configuration documents ---
// (Alternatively, define these in types/index.ts)

interface TierDetailsDoc {
    tiers: TierConfig[];
}

interface ServicesDoc {
    defaultServices?: UserService[]; // Make optional if sometimes missing
    availableServices?: string[];
}

interface PaymentConfigDoc {
    upiDetails?: {
        upiId: string;
        payeeName: string;
        notePrefix?: string; // Optional prefix
    };
    supportedCurrencies?: string[];
    verificationTimeoutHours?: number;
}

interface GlobalSettingsDoc {
     settings?: {
         maintenanceMode: boolean;
         maintenanceMessage?: string;
         supportEmail?: string;
         // ... other global settings
     };
     features?: {
         perksEnabled: boolean;
         contactFormEnabled: boolean;
         [key: string]: boolean; // Allow arbitrary feature flags
     };
}

/* Service-specific settings example type
interface ExamifySettings {
    maxAttemptsHistoryFree: number;
    maxAttemptsHistorySupporter: number;
    maxAttemptsHistoryPro: number | null; // Use explicit type from TierLimitConfig or redefine
    defaultExamDurationMinutes?: number;
    resultsDisplayMode?: 'simple' | 'detailed';
    allowCustomUploads?: Array<'free' | 'supporter' | 'pro' | 'business'>;
    // Add other examify settings...
}*/


// --- Simple In-Memory Cache ---
// Use a more robust caching strategy (Context, Zustand, React Query) in a real app if needed.
const configCache: Map<string, any> = new Map();
const CACHE_DURATION_MS = 5 * 60 * 1000; // Cache for 5 minutes

interface CacheEntry {
    data: any;
    timestamp: number;
}

const setCache = (key: string, data: any) => {
    const entry: CacheEntry = { data, timestamp: Date.now() };
    configCache.set(key, entry);
};

const getCache = <T>(key: string): T | null => {
    const entry = configCache.get(key) as CacheEntry | undefined;
    if (!entry) return null;

    const isExpired = (Date.now() - entry.timestamp) > CACHE_DURATION_MS;
    if (isExpired) {
        configCache.delete(key);
        return null;
    }
    return entry.data as T;
};

/** Helper to fetch and cache a config document */
const fetchConfigDoc = async (docId: string): Promise<DocumentSnapshot<DocumentData>> => {
    const docRef = doc(db, 'configuration', docId);
    // Note: getDoc isn't easily cacheable itself if offline persistence matters,
    // but we cache the *data* result.
    return await getDoc(docRef);
};

// --- Exported Service Functions ---

/** Fetches Tier Configurations (with cache) */
export const getTierConfigs = async (): Promise<TierConfig[]> => {
    const cacheKey = 'tiers';
    const cachedData = getCache<TierConfig[]>(cacheKey);
    if (cachedData) {
        //console.log("[ConfigService] Returning cached Tiers");
        return cachedData;
    }

    try {
        const docSnap = await fetchConfigDoc('tiers');
        if (docSnap.exists()) {
            const data = docSnap.data() as TierDetailsDoc;
            if (data?.tiers && Array.isArray(data.tiers)) {
                const tiersData = data.tiers;
                setCache(cacheKey, tiersData);
                //console.log("[ConfigService] Fetched Tiers from Firestore");
                return tiersData;
            } else {
                //console.warn("Tiers document exists but 'tiers' field is missing or not an array.");
                 return [];
            }
        } else {
           //console.warn("Tiers configuration document ('configuration/tiers') not found!");
            return []; // Return empty array or default config from code? Empty is safer.
        }
    } catch (error) {
       //console.error("Error fetching tier configurations:", error);
        // Don't throw here, allow fallback if possible in calling component
        return []; // Return empty on error
    }
};

/** Fetches Default Services List (with cache) */
export const getDefaultServices = async (): Promise<UserService[]> => {
    const cacheKey = 'defaultServices';
    const cachedData = getCache<UserService[]>(cacheKey);
    if (cachedData) {
        //console.log("[ConfigService] Returning cached Default Services");
        return cachedData;
    }

    try {
        const docSnap = await fetchConfigDoc('services');
        if (docSnap.exists()) {
             const data = docSnap.data() as ServicesDoc;
             if (data?.defaultServices && Array.isArray(data.defaultServices)) {
                const servicesData = data.defaultServices;
                setCache(cacheKey, servicesData);
                //console.log("[ConfigService] Fetched Default Services from Firestore");
                return servicesData;
             } else {
                //console.warn("Services document exists but 'defaultServices' field is missing or invalid.");
                 return [];
             }
        } else {
           //console.warn("Services configuration document ('configuration/services') not found!");
            return [];
        }
    } catch (error) {
       //console.error("Error fetching default services:", error);
        return []; // Return empty on error
    }
};

/** Fetches Payment UPI Details (with cache) */
export const getPaymentUPIDetails = async (): Promise<{ upiId: string; payeeName: string } | null> => {
    const cacheKey = 'paymentUPIDetails';
    const cachedData = getCache<{ upiId: string; payeeName: string }>(cacheKey);
    if (cachedData) {
        //console.log("[ConfigService] Returning cached UPI Details");
        return cachedData;
    }
    try {
        const docSnap = await fetchConfigDoc('payments');
        if (docSnap.exists()) {
            const data = docSnap.data() as PaymentConfigDoc;
            if (data?.upiDetails?.upiId && data?.upiDetails?.payeeName) {
                const upiData = data.upiDetails;
                setCache(cacheKey, upiData)
                //console.log("[ConfigService] Fetched UPI Details from Firestore");
                return upiData;
            }
        }
       //console.warn("Payment configuration document or upiDetails field not found!");
        return null;
    } catch (error) {
       //console.error("Error fetching UPI details:", error);
        return null; // Don't throw, allow graceful failure
    }
};


/** Fetches settings for a specific service (e.g., 'examify') */
export const getServiceSettings = async <T>(serviceId: string): Promise<T | null> => {
    const cacheKey = `serviceSettings_${serviceId}`;
    const cachedData = getCache<T>(cacheKey);
    if (cachedData) {
        //console.log(`[ConfigService] Returning cached Settings for ${serviceId}`);
        return cachedData;
    }
    try {
        const docSnap = await fetchConfigDoc(serviceId);
        if (docSnap.exists()) {
            const settingsData = docSnap.data()?.settings as T ?? null;
            if (settingsData) setCache(cacheKey, settingsData);
            //console.log(`[ConfigService] Fetched Settings for ${serviceId} from Firestore`);
            return settingsData;
        } else {
           //console.warn(`Configuration document for service '${serviceId}' not found!`);
            return null;
        }
    } catch (error) {
       //console.error(`Error fetching settings for service ${serviceId}:`, error);
        return null; // Return null on error
    }
};

/** Fetches global settings */
 export const getGlobalSettings = async (): Promise<GlobalSettingsDoc | null> => {
    const cacheKey = 'globalSettings';
    const cachedData = getCache<GlobalSettingsDoc>(cacheKey);
    if (cachedData) {
        //console.log("[ConfigService] Returning cached Global Settings");
        return cachedData;
    }
     try {
         const docSnap = await fetchConfigDoc('global');
         if (docSnap.exists()) {
             const globalData = docSnap.data() as GlobalSettingsDoc ?? null;
             if (globalData) setCache(cacheKey, globalData);
             //console.log("[ConfigService] Fetched Global Settings from Firestore");
             return globalData;
         } else {
            //console.warn("Global configuration document not found!");
             return null;
         }
     } catch (error) {
        //console.error("Error fetching global settings:", error);
         return null; // Return null on error
     }
 }

/** Clears the local configuration cache */
export const clearConfigCache = (): void => {
    //console.log("[ConfigService] Clearing configuration cache.");
    configCache.clear();
};

// --- Example Usage ---
// async function loadData() {
//     const tiers = await getTierConfigs();
//     const defaultServices = await getDefaultServices();
//     const examifySettings = await getServiceSettings<ExamifySettings>('examify');
//     const globalConfig = await getGlobalSettings();
// }
```

---

### services\firebase.ts

```typescript
// src/services/firebase.ts
import { initializeApp, FirebaseApp } from 'firebase/app';
import {
    getAuth,
    signInWithEmailAndPassword,
    createUserWithEmailAndPassword,
    signOut,
    sendPasswordResetEmail,
    updateProfile,
    onAuthStateChanged, // Import this
    Auth,
    sendEmailVerification,
    User as FirebaseUser, // Rename to avoid conflict with our UserData
    connectAuthEmulator // Import connectAuthEmulator
} from 'firebase/auth';
import {
    getFirestore,
    doc,
    getDoc,
    serverTimestamp,
    Firestore,
    updateDoc, writeBatch,
    collection,
    addDoc,
    connectFirestoreEmulator, // Import connectFirestoreEmulator
    Timestamp
} from 'firebase/firestore';
import { UserData, UserService } from '../types'; // Import our UserData type
import { getAnalytics, Analytics, logEvent, setAnalyticsCollectionEnabled } from "firebase/analytics"; // Import setAnalyticsCollectionEnabled

const firebaseConfig = {
    apiKey: process.env.REACT_APP_FIREBASE_API_KEY,
    authDomain: process.env.REACT_APP_FIREBASE_AUTH_DOMAIN,
    projectId: process.env.REACT_APP_FIREBASE_PROJECT_ID,
    storageBucket: process.env.REACT_APP_FIREBASE_STORAGE_BUCKET,
    messagingSenderId: process.env.REACT_APP_FIREBASE_MESSAGING_SENDER_ID,
    appId: process.env.REACT_APP_FIREBASE_APP_ID,
    measurementId: process.env.REACT_APP_FIREBASE_MEASUREMENT_ID
};

// Validate config (basic check)
if (!firebaseConfig.apiKey || !firebaseConfig.projectId) {
   //console.error("Firebase config is missing. Ensure your .env file is set up correctly.");
}
if (!firebaseConfig.measurementId) {
    // Measurement ID is optional for basic auth/firestore, but needed for Analytics
   //console.warn("Firebase measurementId (REACT_APP_FIREBASE_MEASUREMENT_ID) is missing in .env. Analytics will not be initialized.");
}

// Initialize Firebase
const app: FirebaseApp = initializeApp(firebaseConfig);
export const auth: Auth = getAuth(app);
export const db: Firestore = getFirestore(app);
export let analytics: Analytics | null = null; // Use 'let' and allow null

// --- Emulator Connection Logic ---
// This check ensures emulators are only used in development
if (process.env.NODE_ENV === 'development') {
    //console.log("Development environment detected, connecting to Firebase Emulators...");
    try {
        // Make sure ports match your firebase.json or defaults
        connectAuthEmulator(auth, 'http://localhost:9099', { disableWarnings: true });
        connectFirestoreEmulator(db, 'localhost', 8080); // Hostname and port separate for Firestore
        //console.log("Connected to Auth and Firestore Emulators.");

        // Handle Analytics Locally (Option 1: Disable Collection)
        // This prevents sending hits to Google Analytics during development.
        if (firebaseConfig.measurementId) {
            try {
                // Initialize analytics but disable collection immediately
                analytics = getAnalytics(app);
                setAnalyticsCollectionEnabled(analytics, false);
                //console.log("Firebase Analytics initialized BUT collection DISABLED for local development.");
            } catch (error) {
               //console.error("Error initializing Firebase Analytics locally:", error);
            }
        }

    } catch (error) {
       //console.error("Error connecting to Firebase Emulators:", error);
    }
} else {
    // --- Production Analytics Initialization ---
    // Only initialize fully in production (or non-development environments)
    if (firebaseConfig.measurementId) {
        try {
            analytics = getAnalytics(app);
            //console.log("Firebase Analytics initialized for production.");
            // logEvent(analytics, 'app_initialized_production'); // Optional: Log prod init
        } catch (error) {
           //console.error("Error initializing Firebase Analytics for production:", error);
        }
    }
}

// --- Authentication Functions ---

export const loginUser = async (email: string, password: string): Promise<void> => {
    await signInWithEmailAndPassword(auth, email, password); // Return void promise
};

export const registerUser = async (
    email: string,
    password: string,
    username: string,
    displayName: string
): Promise<void> => {
    const lowerCaseUsername = username.toLowerCase();

    // --- Step 1: Check Username Uniqueness ---
    const usernameDocRef = doc(db, 'usernames', lowerCaseUsername);
    const usernameDocSnap = await getDoc(usernameDocRef);

    if (usernameDocSnap.exists()) {
        // Username already exists, throw specific error
        throw new Error('Username already taken');
    }

    // --- Step 2: Create User in Firebase Auth ---
    const userCredential = await createUserWithEmailAndPassword(auth, email, password);
    const user = userCredential.user;

    // --- Step 3: Create Firestore Documents (Atomically using Batch Write) ---
    try {
        const batch = writeBatch(db); // Create a batch

        // a) Prepare /users/{userId} document
        const userDocRef = doc(db, 'users', user.uid);
        const newUser = {
            uid: user.uid,
            email: email,
            username: lowerCaseUsername, // Store consistent case
            displayName: displayName,
            createdAt: serverTimestamp(),
            updatedAt: serverTimestamp(),
            services: [] as UserService[],
            status: 'active', 
            perkLevel: 'free',  
            perkExpiry: null,
            currentBillingCycle: null, 
        };
        batch.set(userDocRef, newUser); // Add user doc set to batch

        // b) Prepare /usernames/{lowerCaseUsername} document
        const newUsernameDocRef = doc(db, 'usernames', lowerCaseUsername); // Ref is already defined above
        batch.set(newUsernameDocRef, { uid: user.uid }); // Add username doc set to batch

        // c) Commit the batch write
        await batch.commit();

        // --- Step 4: Update Firebase Auth Profile (Optional, after Firestore success) ---
        await updateProfile(user, {
            displayName: displayName,
        });

    } catch (firestoreError) {
        // Handle potential Firestore errors during batch commit
        // Optionally try to delete the Auth user if Firestore fails (complex cleanup)
       //console.error("Firestore write failed after auth creation:", firestoreError);
        // Consider deleting the just-created user: await user.delete();
        throw new Error('Registration failed during database setup.'); // Re-throw generic error
    }
};


export const logoutUser = (): Promise<void> => {
    return signOut(auth);
};

export const resetPassword = (email: string): Promise<void> => {
    return sendPasswordResetEmail(auth, email);
};

//Send Verification Email function
export const sendUserEmailVerification = async (): Promise<void> => {
    const user = auth.currentUser;
    if (user) {
        await sendEmailVerification(user);
    } else {
        throw new Error("No user is currently signed in.");
    }
};

// --- UPDATED: Account Deletion Function (Soft Delete) ---
/**
 * Marks a user account for deletion by setting their status to 'deleted'.
 * Actual data purging and Auth deletion must be handled by an admin or Cloud Function.
 * @param userId The UID of the user to mark for deletion.
 * @param username The username (required for user messaging, potentially future cleanup link).
 */
export const deleteUserAccount = async (userId: string, username: string): Promise<void> => {
    const user = auth.currentUser;

    if (!user || user.uid !== userId) {
        throw new Error("Current user does not match user requested for deletion or is not signed in.");
    }
     if (!username) {
         // We still need the username to prevent re-registration easily later if desired.
         // Fetch it if not provided? For now, let's make it required by the caller.
         throw new Error("Username is required for soft deletion process.");
     }

    // *** ONLY update the status in Firestore ***
    try {
        const userDocRef = doc(db, 'users', userId);
        await updateDoc(userDocRef, {
            deletedAt: serverTimestamp() ,// Add a timestamp for when deletion was requested
            status: 'deleted',
            // --- Optional Anonymization (DO NOT implement initially unless specifically needed) ---
            // email: `deleted_${userId}@deleted.user`, // Example anonymization
            // displayName: 'Deleted User',
            // --- End Optional Anonymization ---
        });
        //console.log(`User ${userId} marked as deleted.`);
        //logoutUser();
        // ** IMPORTANT: DO NOT delete the /usernames document here **
        // ** DO NOT call deleteUser(user) here **
        logoutUser();

    } catch (firestoreError) {
       //console.error("Failed to mark user as deleted in Firestore:", firestoreError);
        throw new Error("Failed to mark account for deletion. Please try again.");
    }
};

// --- Firestore Functions ---

export const getUserData = async (userId: string): Promise<UserData | null> => {
    if (!userId) return null;
    const userDocRef = doc(db, 'users', userId);
    const userSnapshot = await getDoc(userDocRef);

    if (userSnapshot.exists()) {
        // Ensure data matches UserData type, provide defaults if necessary
        const data = userSnapshot.data();
        const createdAt = data.createdAt instanceof Timestamp ? data.createdAt.toDate() : null;
        const updatedAt = data.updatedAt instanceof Timestamp ? data.updatedAt.toDate() : null;
        const deletedAt = data.deletedAt instanceof Timestamp ? data.deletedAt.toDate() : null;
        // --- NEW: Convert perkExpiry safely ---
        const perkExpiry = data.perkExpiry instanceof Timestamp ? data.perkExpiry.toDate() : null;
        return {
            uid: userId,
                email: data.email ?? '',
                username: data.username ?? '',
                displayName: data.displayName ?? 'N/A',
                services: data.services ?? [],
                status: data.status ?? 'active',
                createdAt: createdAt,
                updatedAt: updatedAt,
                deletedAt: deletedAt,
                perkLevel: data.perkLevel ?? 'free',
                perkExpiry: perkExpiry,             
        } as UserData;
    } else {
       //console.warn(`No user data found in Firestore for UID: ${userId}`);
        return null;
    }
};
/**
 * Updates user data in Firestore and Firebase Auth Profile (if applicable).
 * @param userId The Firebase Auth user ID.
 * @param data An object containing fields to update (e.g., { displayName: 'New Name' }).
 */
export const updateUserProfileData = async (userId: string, data: { displayName?: string /* add other editable fields here */ }): Promise<void> => {
    if (!userId) {
        throw new Error("User ID is required to update profile data.");
    }

    const userDocRef = doc(db, 'users', userId);
    const updatePayload: any = {
        ...data,
        updatedAt: serverTimestamp(),
    };

    // 1. Update Firestore document
    await updateDoc(userDocRef, updatePayload);
    //console.log("Firestore user data updated.");

    // 2. Update Firebase Auth profile if displayName is changed
    if (data.displayName && auth.currentUser && auth.currentUser.uid === userId) {
        try {
            await updateProfile(auth.currentUser, {
                displayName: data.displayName,
            });
            //console.log("Firebase Auth profile updated.");
        } catch (error) {
           //console.error("Failed to update Firebase Auth profile:", error);
            // Decide how to handle this: maybe log it, maybe try to rollback Firestore (complex),
            // or just accept that they might be out of sync temporarily.
            // For now, we just log the error.
            throw new Error("Failed to update Auth profile, Firestore data was updated."); // Optionally re-throw
        }
    }
};

// --- Auth State Listener ---

// Export a function to subscribe to auth state changes
export const onAuthUserStateChanged = (callback: (user: FirebaseUser | null) => void) => {
    return onAuthStateChanged(auth, callback);
};

// --- Contact Form Submission ---
interface ContactSubmissionPayload {
    userId: string;
    userEmail: string;
    userName: string;
    subject: string;
    message: string;
  }
  
  export const submitContactForm = async (formData: ContactSubmissionPayload): Promise<void> => {
      if (!auth.currentUser) {
          throw new Error("Authentication required to submit form.");
      }
       // Double-check userId matches authenticated user, although formData.userId should be set correctly before calling
      if (formData.userId !== auth.currentUser.uid) {
          throw new Error("User ID mismatch. Cannot submit form for another user.");
      }
  
      try {
          const submissionsRef = collection(db, 'contactSubmissions');
          await addDoc(submissionsRef, {
              ...formData, // Contains userId, userName, userEmail, subject, message
              submittedAt: serverTimestamp(), // Add server timestamp on creation
              status: 'new'
          });
          
           //console.log("Contact form submitted successfully to Firestore.");
           
      } catch (error) {
         //console.error("Error submitting contact form to Firestore:", error);
          // Re-throw the error to be handled by the component
          throw new Error("Failed to save submission data.");
      }
  };

// --- Analytics Logging Helper ---
export const logAnalyticsEvent = (eventName: string, eventParams?: { [key: string]: any }) => {
    // Only log if analytics is initialized and collection is potentially enabled
    // Note: `setAnalyticsCollectionEnabled(analytics, false)` in dev only stops sending to GA,
    // the logEvent function itself might still run.
    if (analytics) { // Check if analytics object exists
        try {
            logEvent(analytics, eventName, eventParams);
            // Optional: Console log in dev to see events even if collection is off/analytics object exists
            // This helps verify events are being triggered locally.
            if (process.env.NODE_ENV === 'development') {
                //console.log(`%c[Analytics Event (Dev)]%c ${eventName}`, 'color: blue; font-weight: bold;', 'color: inherit;', eventParams || '');
            }
        } catch (error) {
           //console.error(`Failed to log analytics event "${eventName}":`, error);
        }
    } else {
        // If analytics isn't even initialized (e.g., no measurementId or error during init)
        //console.warn("Analytics not initialized, event not logged:", eventName);
    }
};
```

---

### services\paymentService.ts

```typescript
// src/services/paymentService.ts
import {
    collection, addDoc, serverTimestamp, query,
    where, getDocs, limit, Timestamp, orderBy
} from 'firebase/firestore';
import { db } from './firebase';
import { PaymentAttempt } from '../types';

// Type for data needed WHEN logging a payment for verification
// Omits fields automatically added or not relevant until processing
type LogPaymentData = Omit<PaymentAttempt,
    'id' | 'createdAt' | 'status' | // Status will be set here
    'processedAt' | 'adminProcessorUid' | 'rejectionReason' | // Added by admin
    'paymentGatewayRef' | // Future use
    'userConfirmedAt' // Will be set here
>;

/**
 * Creates a new payment attempt document in Firestore with status 'pending_verification',
 * only after the user confirms they have made the payment.
 * @param paymentData Data for the payment attempt being logged.
 * @returns Promise<string> The ID of the newly created payment document.
 */
export const logPaymentForVerification = async (paymentData: LogPaymentData): Promise<string> => {
    if (!paymentData.userId || !paymentData.tierId || !paymentData.expectedNote) {
        throw new Error("Missing essential data to log payment for verification.");
    }
    try {
        const paymentRef = collection(db, 'payments');
        const dataToSave = {
            ...paymentData, // Includes user info, tier info, amount, currency, expectedNote
            status: 'pending_verification' as const, // Set status directly
            createdAt: serverTimestamp(), // When the user *initiated* the flow (useful metadata)
            userConfirmedAt: serverTimestamp(), // When the user *confirmed* payment
        };

        const docRef = await addDoc(paymentRef, dataToSave);
        //console.log("Payment logged for verification with ID:", docRef.id);
        return docRef.id;
    } catch (error: any) {
       //console.error("Error logging payment for verification:", error);
        throw new Error("Could not submit payment for verification.");
    }
};

/**
 * Checks if a user has a payment currently pending verification.
 * @param userId The user's UID.
 * @returns Promise<boolean> True if a pending verification payment exists, false otherwise.
 */
export const hasPendingVerification = async (userId: string): Promise<boolean> => {
    try {
        const q = query(
            collection(db, 'payments'),
            where('userId', '==', userId),
            where('status', '==', 'pending_verification'),
            limit(1) // We only need to know if at least one exists
        );
        const snapshot = await getDocs(q);
        return !snapshot.empty; // Return true if the snapshot is NOT empty
    } catch (error) {
       //console.error("Error checking for pending verification:", error);
        throw new Error("Could not check for existing pending payments.");
    }
};

/**
 * Fetches the payment history for a specific user.
 * @param userId The user's UID.
 * @param resultsLimit Optional limit for the number of results.
 * @returns Promise<PaymentAttempt[]> Array of payment attempts for the user.
 */
export const getUserPaymentHistory = async (userId: string, resultsLimit = 10): Promise<PaymentAttempt[]> => {
    if (!userId) {
        throw new Error("User ID is required to fetch payment history.");
    }
    try {
        const q = query(
            collection(db, 'payments'),
            where('userId', '==', userId),
            orderBy('userConfirmedAt', 'desc'), // Order by confirmation time
            limit(resultsLimit)
        );
        const snapshot = await getDocs(q);

        const history = snapshot.docs.map(docSnap => {
            const data = docSnap.data();
            if (!data.createdAt || !(data.createdAt instanceof Timestamp)) {
               //console.warn(`Payment Doc (${docSnap.id}) missing or has invalid createdAt:`, data.createdAt);
            }
            return {
                id: docSnap.id,
                ...data
            } as PaymentAttempt;
        });
        return history;
    } catch (error) {
       console.error("Error fetching payment history for user:", error);
        throw new Error("Could not fetch your payment history.");
    }
};
```

---

### setupTests.ts

```typescript
// jest-dom adds custom jest matchers for asserting on DOM nodes.
// allows you to do things like:
// expect(element).toHaveTextContent(/react/i)
// learn more: https://github.com/testing-library/jest-dom
import '@testing-library/jest-dom';

```

---

## styles


### styles\index.scss

```scss
// src/index.scss

// 1. Import CSS Variable Definitions and SCSS Variables
@import './styles/variables';

// 2. Import Base Styles (which use the CSS Variables)
@import './styles/base';

// 3. Future: Import component-specific base styles if needed
// @import './components/common/Button/button-base.scss';

// Note: Component-specific styles using CSS Modules will automatically work
// as long as the components use the defined CSS variables.
```

---

### styles\_base.scss

```scss
// src/styles/_base.scss
@import 'variables'; // Import SCSS variables for structure/layout

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  // Transition core properties for theme switching smoothness
  transition: background-color 0.2s ease-in-out, color 0.2s ease-in-out, border-color 0.2s ease-in-out;
}

html {
  font-size: 100%; // 16px browser default
  scroll-behavior: smooth; // Smooth scrolling
}

body {
  font-family: $font-family-base;
  font-size: $font-size-base;
  line-height: $line-height-base;
  color: var(--color-text-primary);       // Use CSS Var
  background-color: var(--color-bg-primary); // Use CSS Var
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
}

#root {
  display: flex;
  flex-direction: column;
  flex-grow: 1; // Ensure #root takes full height
}

// --- Links ---
a {
  color: var(--color-text-link);
  text-decoration: none; // Remove default underline
  transition: color 0.2s ease;

  &:hover {
    color: var(--color-text-link-hover);
    text-decoration: underline; // Add underline on hover for clarity
  }
}

// --- Headings ---
h1, h2, h3, h4, h5, h6 {
  font-family: $font-family-heading;
  color: var(--color-text-primary);
  line-height: $line-height-heading;
  margin-bottom: $spacing-md; // Default margin
  font-weight: 600; // Slightly bolder headings
}

h1 { font-size: $font-size-h1; }
h2 { font-size: $font-size-h2; }
h3 { font-size: $font-size-h3; }
h4 { font-size: $font-size-h4; }
// h5, h6 use base font size or slightly larger

// --- Paragraphs & Text ---
p {
  margin-bottom: $spacing-md;
}

strong, b {
  font-weight: 600;
}

// --- Lists ---
ul, ol {
  padding-left: $spacing-lg;
  margin-bottom: $spacing-md;
  li {
    margin-bottom: $spacing-sm;
  }
}

// --- Forms ---
button {
  cursor: pointer;
  font-family: inherit;
  border: none;
  background: none;
  color: inherit; // Inherit text color by default
}

input, textarea, select, button {
  font-family: inherit;
  font-size: inherit;
  line-height: inherit;
}

// Basic interactive element focus style (will be overridden by specific components)
*:focus-visible {
  outline: none;
  box-shadow: var(--shadow-focus-ring);
  border-radius: $border-radius-sm; // Apply radius to the focus ring itself
}

// --- Horizontal Rule ---
hr {
  border: 0;
  height: $border-width-base;
  background-color: var(--color-border-primary);
  margin: $spacing-xl 0;
}

// --- Container ---
.container {
  width: 100%;
  max-width: $breakpoint-xl; // Adjusted max-width
  margin-left: auto;
  margin-right: auto;
  padding-left: $spacing-md;
  padding-right: $spacing-md;

  @media (min-width: $breakpoint-lg) {
      padding-left: $spacing-lg;
      padding-right: $spacing-lg;
  }
}

// --- Alert Styles (Refined) ---
.alert {
  padding: $spacing-sm $spacing-md;
  margin-bottom: $spacing-lg; // More space below alerts
  border-radius: $border-radius-md;
  border: $border-width-base solid transparent;
  display: flex; // Align icon and text nicely
  align-items: center;
  gap: $spacing-sm;
  font-size: $font-size-sm;

  // Example Icon styling (requires adding icons in the component)
  // svg {
  //   flex-shrink: 0;
  //   width: 18px;
  //   height: 18px;
  // }

  &.alert-error {
    color: var(--color-error-dark);
    background-color: var(--color-error-light);
    border-color: var(--color-error); // Use main status color for border
    // svg { color: var(--color-error); }
  }
  &.alert-success {
    color: var(--color-success-dark);
    background-color: var(--color-success-light);
    border-color: var(--color-success);
    // svg { color: var(--color-success); }
  }
   &.alert-info {
    color: var(--color-info-dark);
    background-color: var(--color-info-light);
    border-color: var(--color-info);
    // svg { color: var(--color-info); }
   }
   &.alert-warning {
    color: var(--color-warning-dark);
    background-color: var(--color-warning-light);
    border-color: var(--color-warning);
    // svg { color: var(--color-warning); }
   }
}
```

---

### styles\_variables.scss

```scss
// src/styles/_variables.scss

// --- SCSS Variables (for structure, layout, media queries - things NOT changing with theme) ---

// Fonts (Keep SCSS for easy reference in mixins/functions if needed)
$font-family-base: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji';
$font-family-heading: $font-family-base; // Use same or different heading font
$font-size-base: 1rem;     // 16px
$font-size-sm: 0.875rem;  // 14px
$font-size-lg: 1.125rem;  // 18px
$font-size-xl: 1.25rem;   // 20px
$font-size-h1: 2.5rem;    // 40px
$font-size-h2: 2rem;      // 32px
$font-size-h3: 1.75rem;   // 28px
$font-size-h4: 1.375rem;  // 22px
$line-height-base: 1.6;
$line-height-heading: 1.3;

// Spacing (Keep SCSS for use in calculations)
$spacing-unit: 8px;
$spacing-xs: $spacing-unit * 0.5; // 4px
$spacing-sm: $spacing-unit;       // 8px
$spacing-md: $spacing-unit * 2;   // 16px
$spacing-lg: $spacing-unit * 3;   // 24px
$spacing-xl: $spacing-unit * 4;   // 32px
$spacing-xxl: $spacing-unit * 6;  // 48px

// Borders
$border-radius-sm: 4px;
$border-radius-md: 8px;
$border-radius-lg: 16px;
$border-radius-pill: 9999px;
$border-width-base: 1px;
$border-width-lg: 2px;

// Z-index (Keep SCSS)
$z-index-header: 1000;
$z-index-modal-backdrop: 1050;
$z-index-modal-content: 1055;
$z-index-toast: 1100;
$z-index-spinner-overlay: 1200;

// Breakpoints (Keep SCSS)
$breakpoint-sm: 576px;
$breakpoint-md: 768px;
$breakpoint-lg: 992px;
$breakpoint-xl: 1200px;
$breakpoint-xxl: 1400px;

// --- CSS Variables (for Theming - Colors, Shadows) ---
// Define variables within :root (light theme) and .dark-theme scopes

:root {
  // --- Light Theme ---
  // Core Palette
  --color-primary: #007aff; // Example: Modern Blue
  --color-primary-light: #e6f2ff;
  --color-primary-dark: #005ecb;
  --color-secondary: #ff3b30; // Example: Modern Red/Accent
  --color-secondary-light: #ffebee;
  --color-secondary-dark: #c60000;

  // Text Palette
  --color-text-primary: #1c1c1e;     // Near black
  --color-text-secondary: #636366;   // Medium gray
  --color-text-tertiary: #aeaeb2;    // Lighter gray
  --color-text-placeholder: #c7c7cc; // Placeholder gray
  --color-text-inverse: #ffffff;     // Text on dark backgrounds
  --color-text-link: var(--color-primary);
  --color-text-link-hover: var(--color-primary-dark);

  // Background Palette
  --color-bg-primary: #ffffff;       // Primary page background
  --color-bg-secondary: #f2f2f7;     // Slightly off-white for cards/sections
  --color-bg-tertiary: #e5e5ea;      // Even grayer background element
  --color-bg-inverse: var(--color-text-primary); // For elements needing dark bg

  // Status Palette
  --color-success: #34c759;
  --color-success-light: #eaf9ee;
  --color-success-dark: #2a9a47;
  --color-error: #ff3b30;           // Same as secondary in this example
  --color-error-light: #ffebee;
  --color-error-dark: #c60000;
  --color-warning: #ff9500;
  --color-warning-light: #fff6e6;
  --color-warning-dark: #cc7a00;
  --color-info: #007aff;             // Same as primary in this example
  --color-info-light: #e6f2ff;
  --color-info-dark: #005ecb;

  // Border Palette
  --color-border-primary: #dcdcdc;   // Subtle border
  --color-border-secondary: #c7c7cc; // Slightly stronger border
  --color-border-input: var(--color-border-secondary);
  --color-border-input-focus: var(--color-primary);

  // Shadow Palette (Example - adjust values)
  --shadow-sm: 0 1px 2px rgba(0, 0, 0, 0.05);
  --shadow-md: 0 4px 8px rgba(0, 0, 0, 0.1);
  --shadow-lg: 0 10px 20px rgba(0, 0, 0, 0.1);
  --shadow-focus-ring: 0 0 0 3px rgba(0, 122, 255, 0.3); // Corresponds to --color-primary
}

.dark-theme {
  // --- Dark Theme --- (Invert/Adjust values)
  // Core Palette
  --color-primary: #0a84ff; // Brighter blue for dark mode
  --color-primary-light: #1a3e68; // Darker background for light elements
  --color-primary-dark: #3f9dff;
  --color-secondary: #ff453a; // Brighter red
  --color-secondary-light: #5a1d1a;
  --color-secondary-dark: #ff7066;

  // Text Palette
  --color-text-primary: #ffffff;     // White text
  --color-text-secondary: #aeaeb2;   // Light gray
  --color-text-tertiary: #636366;    // Medium dark gray
  --color-text-placeholder: #8e8e93;
  --color-text-inverse: #000000;     // Text on light backgrounds (if needed)
  --color-text-link: var(--color-primary);
  --color-text-link-hover: var(--color-primary-dark);

  // Background Palette
  --color-bg-primary: #000000;       // Black background
  --color-bg-secondary: #1c1c1e;     // Near black for cards
  --color-bg-tertiary: #2c2c2e;      // Slightly lighter dark gray
  --color-bg-inverse: var(--color-text-primary); // White for elements needing light bg

  // Status Palette
  --color-success: #30d158;
  --color-success-light: #1a4d25;
  --color-success-dark: #49e070;
  --color-error: #ff453a;
  --color-error-light: #5a1d1a;
  --color-error-dark: #ff7066;
  --color-warning: #ff9f0a;
  --color-warning-light: #68410a;
  --color-warning-dark: #ffb33c;
  --color-info: #0a84ff;
  --color-info-light: #1a3e68;
  --color-info-dark: #3f9dff;

  // Border Palette
  --color-border-primary: #3a3a3c;   // Darker border
  --color-border-secondary: #48484a; // Slightly lighter dark border
  --color-border-input: var(--color-border-secondary);
  --color-border-input-focus: var(--color-primary);

  // Shadow Palette (Shadows are less prominent on dark backgrounds)
  --shadow-sm: 0 1px 2px rgba(0, 0, 0, 0.15);
  --shadow-md: 0 4px 8px rgba(0, 0, 0, 0.25);
  --shadow-lg: 0 10px 20px rgba(0, 0, 0, 0.3);
  --shadow-focus-ring: 0 0 0 3px rgba(10, 132, 255, 0.4); // Corresponds to dark --color-primary
}
```

---

## types


### types\index.ts

```typescript
// src/types/index.ts
import { User as FirebaseUser } from 'firebase/auth';
import { Timestamp } from 'firebase/firestore';

// Firestore User Data Structure
export interface UserData {
  uid: string; // Keep uid consistent with FirebaseUser
  email: string;
  username: string;
  displayName: string;
  createdAt: Timestamp | Date | null;
  updatedAt: Timestamp | Date | null;
  services: UserService[]; // Array of services user has access to
  status?: 'active' | 'suspended' | 'deleted';
  deletedAt?: Timestamp | Date | null;
  perkLevel: 'free' | PaidTierId;
  perkExpiry: Timestamp | Date | null;
  currentBillingCycle?: 'monthly' | 'yearly' | null;
}

// Structure for a service linked to a user
export interface UserService {
  id: string;         // e.g., 'blog', 'exam-simulator'
  name: string;       // e.g., 'Google Blogger', 'Exam Simulator'
  description: string;
  url: string;        // External URL or internal path
  icon: string;       // Identifier for the icon (e.g., 'blog', 'exam') or path
}

export interface PaymentAttempt {
  id: string;
  userId: string;
  userName?: string;
  userEmail?: string;
  tierId: PaidTierId;
  tierName: string;
  amount: number;
  currency: 'INR';
  status: 'pending_verification' | 'completed' | 'rejected'; // Simplified
  expectedNote: string;
  billingCycle: 'monthly' | 'yearly'; // <<< NEW
  durationMonthsPaid: number; // <<< NEW (1 or 12)
  createdAt: Timestamp;
  userConfirmedAt: Timestamp;
  processedAt?: Timestamp | null;
  adminProcessorUid?: string | null;
  rejectionReason?: string | null;
}

export type LogPaymentData = Omit<PaymentAttempt,
    'id' | 'status' | 'createdAt' | 'userConfirmedAt' | // Set by service
    'processedAt' | 'adminProcessorUid' | 'rejectionReason' // Set by admin action
    // | 'paymentGatewayRef' // Optional future field
>;

export type PaidTierId = 'basic' | 'pro' | 'elite';  

export interface TierLimitConfig { // Define limits structure clearly
  examAttempts: number | null;
  hostedSessions: number | null;
  //maxParticipantsPerSession: number | null;
}
export interface TierPricingOption {
  billingCycle: 'monthly' | 'yearly';
  priceINR: number;
  durationMonths: number; // 1 for monthly, 12 for yearly
  // Optional fields for display:
  displaySuffix?: string; // e.g., "/mo" or "/yr"
  savingsText?: string; // e.g., "Save 20%"
}

// --- NEW: Tier Configuration ---
export interface TierConfig {
  id: 'free' | PaidTierId;
  name: string;
  pricingOptions: TierPricingOption[]; // Array of pricing options
  description: string;
  features: string[];
  limits: TierLimitConfig;
  isPopular?: boolean; // Optional flag for UI highlighting
  recommendedCycle?: 'monthly' | 'yearly'; // Optional default selection hint
}

export type PaidTierConfig = Omit<TierConfig, 'id'> & {
  id: PaidTierId;
};

//error type for Profile form
export interface ProfileErrors {
    displayName?: string;
    deleteConfirm?: string;
    // Add other fields if they become editable
    general?: string;
}

// Auth Context Structure
export interface AuthContextType {
  currentUser: FirebaseUser | null; // Firebase auth user object
  userData: UserData | null;        // Additional user data from Firestore
  isLoading: boolean;               // Loading state for initial auth check
  login: (email: string, password: string) => Promise<void>;
  register: (email: string, password: string, username: string, displayName: string) => Promise<void>;
  logout: () => Promise<void>;
  resetPassword: (email: string) => Promise<void>;
}

// Props for form container components
export interface AuthFormContainerProps {
  children: React.ReactNode;
  title: string;
  subtitle?: string;
  className?: string; // Allow custom styling
}

// Generic type for form validation errors
export type FormErrors<T> = {
  [K in keyof T]?: string;
} & { general?: string }; // Optional general error message

// Basic props for common Button component
export interface ButtonProps extends React.ButtonHTMLAttributes<HTMLButtonElement> {
  variant?: 'primary' | 'secondary' | 'outline' | 'danger' | 'text'; // Added 'danger', 'text' variants
  size?: 'small' | 'medium' | 'large';
  loading?: boolean;
  fullWidth?: boolean;
  // className prop is implicitly included via React.ButtonHTMLAttributes
}

// Basic props for common Input component
export interface InputProps extends React.InputHTMLAttributes<HTMLInputElement> {
  label?: string;
  error?: string;
  icon?: React.ReactNode; // Optional icon element (typically placed left)
  containerClassName?: string; // Optional class for the outer div
  inputClassName?: string;     // Optional class for the input element itself
  canToggleVisibility?: boolean; // For password inputs
  // Ensure id is included via InputHTMLAttributes
}

// Basic props for common Textarea component
export interface TextareaProps extends React.TextareaHTMLAttributes<HTMLTextAreaElement> {
  label?: string;
  error?: string;
  containerClassName?: string; // Optional class for the outer div
  textareaClassName?: string;    // Optional class for the textarea element itself
}

// Type for Contact Form data state
export interface ContactFormData {
  name: string;
  email: string;
  subject: string;
  message: string;
}
// --- Contact Form Submission ---
export interface ContactSubmission {
  id: string; // Firestore Document ID
  userId: string;
  userEmail: string;
  userName: string;
  subject: string;
  message: string;
  submittedAt: Timestamp; // Keep as Timestamp from Firestore
  status: 'new' | 'read' | 'archived'; // Add status field
  // Add optional fields later if needed
  // adminNotes?: string;
  // repliedAt?: Timestamp;
}
```

---

## utils


### utils\adminCheck.ts

```typescript
// src/utils/adminCheck.ts
import { doc, getDoc } from 'firebase/firestore';
import { db } from '../services/firebase'; // Adjust path if necessary

/**
 * Checks if a given user ID exists in the admins collection.
 * @param userId The UID of the user to check.
 * @returns Promise<boolean> True if the user is an admin, false otherwise.
 */
export const checkAdminStatus = async (userId: string): Promise<boolean> => {
    if (!userId) {
        // If no userId is provided, they cannot be an admin
        return false;
    }
    try {
        const adminDocRef = doc(db, 'admins', userId);
        const adminDocSnap = await getDoc(adminDocRef);
        // User is admin if the document with their UID exists in the admins collection
        return adminDocSnap.exists();
    } catch (error) {
       //console.error("Error checking admin status:", error);
        // Treat errors as non-admin for safety
        return false;
    }
};
```

---

### utils\validators.ts

```typescript
// src/utils/validators.ts

// Email validation
export const validateEmail = (email: string): boolean => {
    // Basic regex, consider using a more robust library for production
    const regex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
    return regex.test(email);
};
  
// Password validation (example: at least 8 chars, 1 upper, 1 lower, 1 num)
export const validatePassword = (password: string): boolean => {
    const regex = /^(?=.*[a-z])(?=.*[A-Z])(?=.*\d)[a-zA-Z\d]{8,}$/;
    return regex.test(password);
};
// Message describes the *requirement* clearly
export const passwordRequirementString = "Use 8+ characters with uppercase, lowercase, and a number.";

// Password strength check
export interface PasswordStrength {
    score: number;       // 0-4 score
    label: string;       // Text label like "Weak", "Medium", etc.
    color: string;       // Color code for the visual indicator
}

export const checkPasswordStrength = (password: string): PasswordStrength => {
    // Default state for empty password
    if (!password) {
        return { score: 0, label: '', color: 'transparent' };
    }

    // Initialize score
    let score = 0;

    // Length check (basic)
    if (password.length >= 8) score += 1;
    if (password.length >= 12) score += 1;
  
    // Character type checks
    if (/[a-z]/.test(password)) score += 0.5;
    if (/[A-Z]/.test(password)) score += 0.5;
    if (/\d/.test(password)) score += 0.5;
    if (/[^a-zA-Z0-9]/.test(password)) score += 1; // Special characters
  
    // Variety check (prevent repetition)
    const uniqueChars = new Set(password).size;
    const varietyRatio = uniqueChars / password.length;
    if (varietyRatio > 0.7) score += 1;

    // Cap score at 4
    score = Math.min(4, Math.floor(score));
  
    // Map score to labels and colors
    const strengthMap: Record<number, { label: string; color: string }> = {
        0: { label: 'Very Weak', color: '#ff4d4f' },
        1: { label: 'Weak', color: '#faad14' },
        2: { label: 'Medium', color: '#fadb14' },
        3: { label: 'Strong', color: '#52c41a' },
        4: { label: 'Very Strong', color: '#1890ff' }
    };
  
    return {
        score,
        label: strengthMap[score].label,
        color: strengthMap[score].color
    };
};

// Username validation (example: 3-20 chars, letters, numbers, underscores)
export const validateUsername = (username: string): boolean => {
    // Allow letters, numbers, underscore, hyphen, between 3 and 20 chars
    const regex = /^[a-zA-Z0-9_-]{3,20}$/;
    return regex.test(username);
};
export const usernameRequirementString = "3-20 characters. Letters, numbers, underscores, hyphens allowed.";
  
  
// --- Form Specific Validators ---
  
// Login Form Validation
export interface LoginErrors {
    email?: string;
    password?: string;
    general?: string; // For errors not specific to a field
}
  
export const validateLoginForm = (email: string, password: string): LoginErrors => {
    const errors: LoginErrors = {};
  
    if (!email.trim()) {
        errors.email = 'Email is required';
    } else if (!validateEmail(email)) {
        errors.email = 'Please enter a valid email address';
    }
  
    if (!password) {
        errors.password = 'Password is required';
    }
    // Add more password checks if needed (e.g., minimum length locally)
  
    return errors;
};
  
  
// Registration Form Validation
export interface RegisterErrors {
    email?: string;
    username?: string;
    displayName?: string;
    password?: string;
    confirmPassword?: string;
    terms?: string; // <<< ADD THIS LINE (optional string for terms error)
    general?: string;
}

export const validateRegisterForm = (
    email: string, username: string, displayName: string, password: string, confirmPassword: string
): RegisterErrors => {
    const errors: RegisterErrors = {};

    // Email
    if (!email.trim()) errors.email = 'Email address is required.';
    else if (!validateEmail(email)) errors.email = 'Please enter a valid email address format.';

    // Username
    if (!username.trim()) errors.username = 'Username is required.';
    else if (!validateUsername(username)) errors.username = `Username must be 3-20 characters (letters, numbers, -, _).`; // More specific message

    // Display Name
    if (!displayName.trim()) errors.displayName = 'Display Name is required.';
    else if (displayName.length < 2 || displayName.length > 50) errors.displayName = 'Must be between 2 and 50 characters.';

    // Password
    if (!password) errors.password = 'Password is required.';
    else if (!validatePassword(password)) errors.password = passwordRequirementString; // Reuse requirement string

    // Confirm Password
    if (!confirmPassword) errors.confirmPassword = 'Please confirm your password.';
    else if (password && password !== confirmPassword) errors.confirmPassword = 'Passwords do not match.'; // Check if base password exists

    return errors;
};
  
  
// Forgot Password Form Validation
export interface ForgotPasswordErrors {
    email?: string;
    general?: string;
}
  
export const validateForgotPasswordForm = (email: string): ForgotPasswordErrors => {
    const errors: ForgotPasswordErrors = {};
  
    if (!email.trim()) {
        errors.email = 'Email is required';
    } else if (!validateEmail(email)) {
        errors.email = 'Please enter a valid email address';
    }
  
    return errors;
};

// --- Contact Form Validation ---
export interface ContactFormErrors {
    name?: string;
    email?: string;
    subject?: string;
    message?: string;
    general?: string;
}

export const validateContactForm = (
    name: string,
    email: string,
    subject: string,
    message: string
): ContactFormErrors => {
    const errors: ContactFormErrors = {};

    // Name
    if (!name.trim()) {
        errors.name = 'Name is required';
    } else if (name.trim().length > 100) { // Match rule limit
        errors.name = 'Name cannot exceed 100 characters.';
    }

    // Email
    if (!email.trim()) {
        errors.email = 'Email is required';
    } else if (!validateEmail(email)) {
        errors.email = 'Please enter a valid email address';
    }

    // Subject
    if (!subject.trim()) {
        errors.subject = 'Subject is required';
    } else if (subject.trim().length > 150) { // Match rule limit
        errors.subject = 'Subject cannot exceed 150 characters.';
    }

    // Message
    if (!message.trim()) {
        errors.message = 'Message is required';
    } else if (message.trim().length > 2000) { // Match rule limit
        errors.message = 'Message cannot exceed 2000 characters.';
    }

    return errors;
};
```

---
