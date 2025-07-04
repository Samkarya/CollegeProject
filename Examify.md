## Project Structure

```
├── 📄 App.scss
├── 📄 App.tsx
├── 📁 **assets/**
│   └── 📁 **images/**
├── 📁 **components/**
│   ├── 📁 **AuthModal/**
│   │   ├── 📄 AuthModal.module.scss
│   │   └── 📄 AuthModal.tsx
│   ├── 📁 **BlogPostPreview/**
│   │   ├── 📄 BlogPostPreview.module.scss
│   │   └── 📄 BlogPostPreview.tsx
│   ├── 📁 **CookieConsent/**
│   │   ├── 📄 CookieConsent.module.scss
│   │   └── 📄 CookieConsent.tsx
│   ├── 📁 **CustomExamInput/**
│   │   ├── 📄 CustomExamInput.module.scss
│   │   └── 📄 CustomExamInput.tsx
│   ├── 📁 **ErrorMessage/**
│   │   ├── 📄 ErrorMessage.module.scss
│   │   └── 📄 ErrorMessage.tsx
│   ├── 📁 **ExamControls/**
│   │   ├── 📄 ExamControls.module.scss
│   │   └── 📄 ExamControls.tsx
│   ├── 📁 **ExamTimer/**
│   │   ├── 📄 ExamTimer.module.scss
│   │   └── 📄 ExamTimer.tsx
│   ├── 📁 **Footer/**
│   │   ├── 📄 Footer.module.scss
│   │   └── 📄 Footer.tsx
│   ├── 📁 **Header/**
│   │   ├── 📄 Header.module.scss
│   │   └── 📄 Header.tsx
│   ├── 📁 **Layout/**
│   │   └── 📄 Layout.tsx
│   ├── 📁 **Leaderboard/**
│   │   ├── 📄 Leaderboard.module.scss
│   │   └── 📄 Leaderboard.tsx
│   ├── 📁 **MarkdownRenderer/**
│   │   └── 📄 MarkdownRenderer.tsx
│   ├── 📁 **Modal/**
│   │   ├── 📄 ConfirmationModal.module.scss
│   │   └── 📄 ConfirmationModal.tsx
│   ├── 📁 **MonitoringIndicator/**
│   │   ├── 📄 MonitoringIndicator.module.scss
│   │   └── 📄 MonitoringIndicator.tsx
│   ├── 📁 **NavigationPalette/**
│   │   ├── 📄 NavigationPalette.module.scss
│   │   └── 📄 NavigationPalette.tsx
│   ├── 📁 **OfficialExamSelector/**
│   │   ├── 📄 OfficialExamSelector.module.scss
│   │   └── 📄 OfficialExamSelector.tsx
│   ├── 📁 **QuestionDisplay/**
│   │   ├── 📄 QuestionDisplay.module.scss
│   │   └── 📄 QuestionDisplay.tsx
│   ├── 📁 **RegistrationModal/**
│   │   ├── 📄 RegistrationModal.module.scss
│   │   └── 📄 RegistrationModal.tsx
│   ├── 📁 **ReviewPalette/**
│   │   ├── 📄 ReviewPalette.module.scss
│   │   └── 📄 ReviewPalette.tsx
│   ├── 📁 **ReviewQuestionDisplay/**
│   │   ├── 📄 ReviewQuestionDisplay.module.scss
│   │   └── 📄 ReviewQuestionDisplay.tsx
│   ├── 📁 **SessionMonitor/**
│   │   ├── 📄 SessionMonitor.module.scss
│   │   └── 📄 SessionMonitor.tsx
│   ├── 📁 **Spinner/**
│   │   ├── 📄 Spinner.module.scss
│   │   └── 📄 Spinner.tsx
│   └── 📁 **SubmitExamButton/**
│       ├── 📄 SubmitExamButton.module.scss
│       └── 📄 SubmitExamButton.tsx
├── 📄 constants.ts
├── 📁 **contexts/**
│   ├── 📄 AuthContext.tsx
│   └── 📄 ExamContext.tsx
├── 📁 **hooks/**
│   ├── 📄 useAntiCheatMonitor.ts
│   ├── 📄 useExamConfig.ts
│   └── 📄 useUserPerks.ts
├── 📄 index.tsx
├── 📁 **pages/**
│   ├── 📁 **AntiCheatingSandboxPage/**
│   │   ├── 📄 AntiCheatingSandboxPage.module.scss
│   │   └── 📄 AntiCheatingSandboxPage.tsx
│   ├── 📁 **BlogListPage/**
│   │   ├── 📄 BlogListPage.module.scss
│   │   └── 📄 BlogListPage.tsx
│   ├── 📁 **BlogPostPage/**
│   │   ├── 📄 BlogPostPage.module.scss
│   │   └── 📄 BlogPostPage.tsx
│   ├── 📁 **ExamPage/**
│   │   ├── 📄 ExamPage.module.scss
│   │   └── 📄 ExamPage.tsx
│   ├── 📁 **ExamSelectionPage/**
│   │   ├── 📄 ExamSelectionPage.module.scss
│   │   └── 📄 ExamSelectionPage.tsx
│   ├── 📁 **GroupExamDetailPage/**
│   │   ├── 📄 GroupExamDetailPage.module.scss
│   │   └── 📄 GroupExamDetailPage.tsx
│   ├── 📁 **GroupExamSessionPage/**
│   │   ├── 📄 GroupExamSessionPage.module.scss
│   │   └── 📄 GroupExamSessionPage.tsx
│   ├── 📁 **GroupExamSetupPage/**
│   │   ├── 📄 GroupExamSetupPage.module.scss
│   │   └── 📄 GroupExamSetupPage.tsx
│   ├── 📁 **GroupExamSharePage/**
│   │   ├── 📄 GroupExamSharePage.module.scss
│   │   └── 📄 GroupExamSharePage.tsx
│   ├── 📁 **GroupExamWaitingPage/**
│   │   ├── 📄 GroupExamWaitingPage.module.scss
│   │   └── 📄 GroupExamWaitingPage.tsx
│   ├── 📁 **HomePage/**
│   │   ├── 📄 HomePage.module.scss
│   │   └── 📄 HomePage.tsx
│   ├── 📁 **HostDashboardPage/**
│   │   ├── 📄 HostDashboardPage.module.scss
│   │   └── 📄 HostDashboardPage.tsx
│   ├── 📁 **JoinGroupExamPage/**
│   │   ├── 📄 JoinGroupExamPage.module.scss
│   │   └── 📄 JoinGroupExamPage.tsx
│   ├── 📁 **NotFoundPage/**
│   │   ├── 📄 NotFoundPage.module.scss
│   │   └── 📄 NotFoundPage.tsx
│   ├── 📁 **ProfilePage/**
│   │   ├── 📄 ProfilePage.module.scss
│   │   └── 📄 ProfilePage.tsx
│   ├── 📁 **ResultsPage/**
│   │   ├── 📄 ResultsPage.module.scss
│   │   └── 📄 ResultsPage.tsx
│   ├── 📁 **ReviewPage/**
│   │   ├── 📄 ReviewPage.module.scss
│   │   └── 📄 ReviewPage.tsx
│   └── 📁 **StaticPages/**
│       ├── 📄 AboutPage.tsx
│       ├── 📄 ContactPage.tsx
│       ├── 📄 PrivacyPolicyPage.tsx
│       ├── 📄 StaticPages.module.scss
│       └── 📄 TermsOfServicePage.tsx
├── 📄 reportWebVitals.ts
├── 📁 **routes/**
│   └── 📄 AppRoutes.tsx
├── 📁 **services/**
│   ├── 📄 configService.ts
│   ├── 📄 firebase.ts
│   └── 📄 firestoreService.ts
├── 📁 **styles/**
│   ├── 📄 _base.scss
│   ├── 📄 _mixins.scss
│   ├── 📄 _palette-common.scss
│   ├── 📄 _utilities.scss
│   └── 📄 _variables.scss
├── 📁 **types/**
│   └── 📄 index.tsx
└── 📁 **utils/**
    └── 📄 formatters.ts
```

## File Contents

The following sections contain the content of each file in the project.


### App.scss

```scss
// src/App.scss (or index.scss if you prefer)

// 1. Variables and Mixins first (no output on their own)
@import './styles/variables';
@import './styles/mixins';

// 2. Base styles (resets, html, body, typography)
@import './styles/base';

// 3. Utility classes
@import './styles/utilities';

// 4. Component-specific styles (import these within component files or here later)
// Example: @import './components/Button/Button.module.scss';
// Example: @import './pages/HomePage/HomePage.module.scss';

// 5. App-specific global adjustments (use sparingly)
#root {
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    background-color: $body-bg; // Use the new body background
  }
  
  main {
    flex-grow: 1; // Ensure main content takes available space
    width: 100%;
    // Use the new $spacers map for padding
    padding: map-get($spacers, 4) map-get($spacers, 3); // Default (Mobile) py-4 px-3
  
    @include media-breakpoint-up(md) {
      padding: map-get($spacers, 5) map-get($spacers, 4); // Medium screens and up py-5 px-4
    }
    @include media-breakpoint-up(lg) {
      padding: map-get($spacers, 6) map-get($spacers, 5); // Large screens and up py-6 px-5
    }
  }
  
  @keyframes spin {
    0% { transform: rotate(0deg); }
    100% { transform: rotate(360deg); }
  }
  
  .spin-icon {
    display: inline-block;
    animation: spin 1s linear infinite;
    vertical-align: middle;
    // margin-bottom: -2px; // Keep or adjust based on font alignment
  }

  .sr-only {
    position: absolute;
    width: 1px;
    height: 1px;
    padding: 0;
    margin: -1px;
    overflow: hidden;
    clip: rect(0, 0, 0, 0);
    white-space: nowrap;
    border-width: 0;
  }

// --- NEW: CSS Rule for Ad-Free Experience ---
// This rule will hide any elements with the class .ad-placeholder-class
// when the .ads-hidden class is present on an ancestor (e.g., #examify-app-wrapper).
.ads-hidden {
  .ad-placeholder-class { // Replace .ad-placeholder-class with the actual class used for your ad containers
    display: none !important; // Use !important to ensure it overrides other display properties
    // visibility: hidden !important; // Alternative if display:none causes layout shifts
    // Consider adding more specific selectors if .ad-placeholder-class is too generic
    // e.g., .ads-hidden .some-specific-ad-wrapper .ad-placeholder-class { ... }
  }
}
```

---

### App.tsx

```typescript
// src/App.tsx
import { useEffect, useState } from 'react';
import { BrowserRouter as Router } from 'react-router-dom';
import { ToastContainer, toast } from 'react-toastify';
import 'react-toastify/dist/ReactToastify.css';
import 'katex/dist/katex.min.css';
import './App.scss'; // Main App SCSS

// Contexts and Global Components
import AuthModal from './components/AuthModal/AuthModal';
import { AuthProvider } from './contexts/AuthContext';
import { ExamProvider } from './contexts/ExamContext';
import AppRoutes from './routes/AppRoutes';
import CookieConsent from './components/CookieConsent/CookieConsent';

// *** NEW: Import useUserPerks ***
import { useUserPerks } from './hooks/useUserPerks'; // Adjust path if needed

// Constants
const OFFLINE_TOAST_ID = 'offline-toast';

// --- NEW: RootApp component to use hooks inside AuthProvider/ExamProvider context ---
const RootApp = () => {
  // *** NEW: Get adFreeExperience perk ***
  const { features: perkFeatures, isLoadingPerks } = useUserPerks();

  // Class for ad display based on perk
  const adVisibilityClass = !isLoadingPerks && perkFeatures.adFreeExperience ? 'ads-hidden' : '';

  return (
    // *** NEW: Apply adVisibilityClass to a wrapper or the #root element (if accessible here) ***
    // Applying to a div that wraps everything inside ExamProvider for clarity
    // If #root is directly manipulated, ensure it's safe and doesn't conflict with React's root rendering.
    // This example adds a wrapper div.
    <div id="examify-app-wrapper" className={adVisibilityClass}>
      <AuthModal />
      <AppRoutes />
      {/* Optional offline indicator can be uncommented if needed */}
      {/* {!isOnline && ( // Assuming isOnline is managed within App or passed down
        <div className="offline-indicator">
          Offline Mode
        </div>
      )} */}
      <CookieConsent />
    </div>
  );
};


function App() {
  const [, setIsOnline] = useState(navigator.onLine);

  useEffect(() => {
    const handleOnline = () => {
      setIsOnline(true);
      toast.dismiss(OFFLINE_TOAST_ID);
      toast.success('You are back online!', { autoClose: 3000 });
     //console.log('Network connection restored.');
    };

    const handleOffline = () => {
      setIsOnline(false);
      if (!toast.isActive(OFFLINE_TOAST_ID)) {
        toast.error('You are currently offline. Some features may be unavailable.', { 
          toastId: OFFLINE_TOAST_ID, autoClose: false, closeOnClick: false, draggable: false
        });
      }
      console.warn('Network connection lost.');
    };

    if (!navigator.onLine) { handleOffline(); }
    window.addEventListener('online', handleOnline);
    window.addEventListener('offline', handleOffline);
    return () => {
      window.removeEventListener('online', handleOnline);
      window.removeEventListener('offline', handleOffline);
      toast.dismiss(OFFLINE_TOAST_ID);
    };
  }, []);

  return (
    <AuthProvider>
      <ToastContainer
        position="top-right"
        autoClose={4000}
        hideProgressBar={false}
        newestOnTop={false}
        closeOnClick
        rtl={false}
        pauseOnFocusLoss
        draggable
        pauseOnHover
        theme="colored"
      />
      <Router>
        {/* ExamProvider needs to be inside AuthProvider because useUserPerks (used by RootApp) depends on AuthContext */}
        <ExamProvider>
          {/* RootApp now contains the main structure and uses useUserPerks */}
          <RootApp />
        </ExamProvider>
      </Router>
    </AuthProvider>
  );
}

export default App;
```

---

## assets


## assets\images


## components


## components\AuthModal


### components\AuthModal\AuthModal.module.scss

```scss
// src/components/AuthModal/AuthModal.module.scss
@import '../../styles/variables';
@import '../../styles/mixins';

.modalOverlay { // Re-styling based on ConfirmationModal's overlay
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background-color: rgba($gray-900, 0.5);
  // backdrop-filter: blur(3px); // Optional
  display: flex;
  justify-content: center;
  align-items: center;
  z-index: $zindex-modal; // Ensure AuthModal is also on this layer
  padding: map-get($spacers, 3);
  opacity: 0;
  visibility: hidden;
  transition: opacity 0.25s ease-out, visibility 0s 0.25s linear;

  &.open {
    opacity: 1;
    visibility: visible;
    transition: opacity 0.25s ease-out, visibility 0s linear;
  }
}

.modalContent { // Re-styling based on ConfirmationModal's content
  background-color: $component-bg;
  padding: map-get($spacers, 5); // p-5 (32px) for more spacing in AuthModal
  border-radius: $border-radius-xl;
  box-shadow: $box-shadow-xl;
  max-width: 420px; // Slightly adjusted max-width
  width: 100%;
  position: relative;
  text-align: center; // Center align content in AuthModal
  max-height: 90vh;
overflow-y: auto;
 display: flex;  
 flex-direction: column;

  .modalOverlay.open & {
    animation: modalSlideInUp 0.3s ease-out forwards; // Use same animation
  }
}

.closeButton { // Consistent close button style
  position: absolute;
  top: map-get($spacers, 3);    // Closer to edge
  right: map-get($spacers, 3);
  background: none;
  border: none;
  font-size: $font-size-base * 1.3; // Icon size
  color: $gray-400;
  cursor: pointer;
  line-height: 1;
  padding: map-get($spacers, 1); // p-1 for hit area
  border-radius: 50%;
  width: 36px;
  height: 36px;
  display: flex;
  align-items: center;
  justify-content: center;
  transition: background-color $transition-fast, color $transition-fast;


  &:hover {
    background-color: $gray-100;
    color: $gray-700;
  }
  @include focus-outline($primary-color);
}

.title {
  text-align: center;
  font-size: $h3-font-size; // Larger title (24px)
  font-weight: $font-weight-semibold;
  margin-top: 0;
  margin-bottom: map-get($spacers, 2); // mb-2
  color: $gray-800;
  flex-shrink: 0;
}

.message {
  text-align: center;
  color: $text-muted;
  margin-bottom: map-get($spacers, 4); // mb-4
  font-size: $font-size-base;
  line-height: 1.5;
}

.form {
  display: flex;
  flex-direction: column;
  gap: map-get($spacers, 3); // gap-3 (16px)
}

.formGroup {
  margin-bottom: 0; // Gap is handled by parent .form
  text-align: left; // Align labels left
}

.label {
  display: block;
  margin-bottom: map-get($spacers, 1); // mb-1 (4px)
  font-weight: $font-weight-medium;
  font-size: $font-size-base * 0.9; // Slightly smaller label
  color: $gray-700;
}

.input { // Apply new base input styles from _base.scss (or a dedicated input mixin)
  width: 100%;
  padding: map-get($spacers, 2) map-get($spacers, 3); // py-2 px-3
  border: 1px solid $border-color;
  border-radius: $border-radius; // Use standard radius
  font-size: $font-size-base;
  background-color: $white-color;
  transition: border-color $transition-fast, box-shadow $transition-fast;

  &:focus {
    outline: none;
    border-color: $primary-color;
    box-shadow: 0 0 0 3px rgba($primary-color, 0.2); // Consistent focus ring
  }
  &:disabled {
    background-color: $gray-100;
    opacity: 0.7;
    cursor: not-allowed;
  }
}

.submitButton {
  @include button-variant($primary-color); // Solid primary button
  padding: map-get($spacers, 2) map-get($spacers, 3); // py-2 px-3
  font-size: $font-size-base;
  font-weight: $font-weight-medium;
  margin-top: map-get($spacers, 2); // Add some space above button
  flex-shrink: 0;
  // &:disabled handled by mixin
}

.switchText {
  text-align: center;
  margin-top: map-get($spacers, 4); // mt-4
  font-size: $font-size-base * 0.9;
  color: $text-muted;
}

.switchLink {
  background: none;
  border: none;
  color: $link-color;
  font-weight: $font-weight-medium;
  text-decoration: underline; // Keep underline for clear affordance
  cursor: pointer;
  padding: 0 map-get($spacers, 1); // Add slight horizontal padding for tap target
  flex-shrink: 0;

  &:hover {
    color: $link-hover-color;
  }
  @include focus-outline($primary-color, 0px); // No offset for link-like buttons
}

.errorMessage { // For login error messages
  color: $danger-color;
  background-color: lighten($danger-color, 55%); // Lighter background
  border: 1px solid lighten($danger-color, 40%); // Softer border
  border-radius: $border-radius; // Consistent radius
  padding: map-get($spacers, 2) map-get($spacers, 3); // py-2 px-3
  flex-shrink: 0;
  text-align: center;
  font-size: $font-size-base * 0.9;
  margin-bottom: map-get($spacers, 2); // Add margin if it's at top of form
}
```

---

### components\AuthModal\AuthModal.tsx

```typescript
// src/components/AuthModal/AuthModal.tsx
import React, { useState, useEffect, useRef } from 'react';
import { useAuth } from '../../contexts/AuthContext';
import styles from './AuthModal.module.scss';
import { FaTimes } from 'react-icons/fa';
import Spinner from '../Spinner/Spinner';

const AuthModal: React.FC = () => {
    const {
        isLoginModalOpen,
        loginModalMessage,
        closeLoginModal,
        login,
        openRegistrationModal,
    } = useAuth();

    const [email, setEmail] = useState('');
    const [password, setPassword] = useState('');
    const [error, setError] = useState<string | null>(null);
    const [isSubmitting, setIsSubmitting] = useState(false);
    const modalOverlayRef = useRef<HTMLDivElement>(null);

    useEffect(() => {
        if (modalOverlayRef.current) {
            if (isLoginModalOpen) {
                modalOverlayRef.current.classList.add(styles.open);
                setError(null);
                setEmail('');
                setPassword('');
                setIsSubmitting(false);
            } else {
                modalOverlayRef.current.classList.remove(styles.open);
            }
        }
    }, [isLoginModalOpen]);

    const handleSubmit = async (event: React.FormEvent) => {
        event.preventDefault();
        setError(null);
        setIsSubmitting(true);

        try {
            await login(email, password);
            // closeLoginModal() will be called by AuthContext on successful login typically
        } catch (err: any) {
           //console.error('Login failed:', err);
            setError(err.message || 'An error occurred during login.');
            setIsSubmitting(false);
        }
    };

    const handleRegisterRedirect = (event: React.MouseEvent<HTMLAnchorElement>) => {
        event.preventDefault(); // Prevent default link behavior
        closeLoginModal(); // Close the login modal first
        openRegistrationModal(window.location.pathname + window.location.search); // Then trigger the redirect info toast
    };

    // Conditional rendering:
    // If you want animations on exit, this part needs more complex handling
    // (e.g., an additional state variable for "isAnimatingOut").
    // For now, this ensures it's not rendered when closed.
    if (!isLoginModalOpen && !modalOverlayRef.current?.classList.contains(styles.open)) {
         return null;
    }

    return (
        <div
            ref={modalOverlayRef}
            className={styles.modalOverlay}
            onClick={isSubmitting ? undefined : closeLoginModal}
        >
            <div
                className={styles.modalContent}
                onClick={(e) => e.stopPropagation()}
            >
                <button 
                    className={styles.closeButton} 
                    onClick={isSubmitting ? undefined : closeLoginModal} 
                    title="Close"
                    disabled={isSubmitting} // Disable close button during submission
                >
                    <FaTimes />
                </button>

                <h2 className={styles.title}>Login Required</h2>

                {loginModalMessage && <p className={styles.message}>{loginModalMessage}</p>}

                <form onSubmit={handleSubmit} className={styles.form}>
                    {error && <p className={styles.errorMessage}>{error}</p>}

                    <div className={styles.formGroup}>
                        <label htmlFor="email" className={styles.label}>Email</label>
                        <input
                            type="email"
                            id="email"
                            value={email}
                            onChange={(e) => setEmail(e.target.value)}
                            required
                            className={styles.input}
                            disabled={isSubmitting}
                            title={isSubmitting ? "Processing login..." : "Enter your email"}
                        />
                    </div>

                    <div className={styles.formGroup}>
                        <label htmlFor="password" className={styles.label}>Password</label>
                        <input
                            type="password"
                            id="password"
                            value={password}
                            onChange={(e) => setPassword(e.target.value)}
                            required
                            className={styles.input}
                            disabled={isSubmitting}
                            title={isSubmitting ? "Processing login..." : "Enter your password"}
                        />
                    </div>

                    <button type="submit" className={styles.submitButton} disabled={isSubmitting}>
                        {isSubmitting ? <Spinner size="1em" /> : 'Login'}
                    </button>
                </form>

                <p className={styles.switchText}>
                    Don't have an account?{' '} {/* Added space for better readability */}
                    {/*eslint-disable-next-line*/}
                    <a
                         href="#"
                         onClick={handleRegisterRedirect}
                        className={styles.switchLink}
                    >
                        Register here
                    </a>
                </p>
            </div>
        </div>
    );
};

export default AuthModal;
```

---

## components\BlogPostPreview


### components\BlogPostPreview\BlogPostPreview.module.scss

```scss
@import '../../styles/variables';
@import '../../styles/mixins';

.previewCard {
    background-color: $component-bg;
    border: 1px solid $border-color;
    border-radius: $border-radius-lg;
    padding: $spacer * 1.5;
    margin-bottom: $spacer * 2;
    box-shadow: 0 2px 5px rgba($black-color, 0.07);
    transition: transform 0.2s ease-out, box-shadow 0.2s ease-out;

    &:hover {
        transform: translateY(-3px);
        box-shadow: 0 4px 12px rgba($black-color, 0.1);
    }
}

.previewTitle {
    font-size: $h4-font-size;
    margin-top: 0;
    margin-bottom: $spacer * 0.5;

    a {
        text-decoration: none;
        color: $primary-color;
        &:hover {
            text-decoration: underline;
            color: darken($primary-color, 10%);
        }
    }
}

.previewMeta {
    font-size: $font-size-base * 0.85;
    color: $text-muted;
    margin-bottom: $spacer;
    display: flex;
    flex-wrap: wrap;
    gap: $spacer;

    span {
        display: inline-flex;
        align-items: center;
        gap: $spacer * 0.4;
    }
     svg {
         margin-bottom: -1px;
     }
}

.previewExcerpt {
    color: $text-color;
    margin-bottom: $spacer * 1.5;
    line-height: 1.6;
}

.previewTags {
    font-size: $font-size-base * 0.8;
    color: $text-muted;
    margin-bottom: $spacer * 1.5;
     display: flex;
     flex-wrap: wrap;
     align-items: center;
     gap: $spacer * 0.5;

     svg {
         margin-right: $spacer * 0.3;
     }
}

.tag {
    background-color: lighten($light-color, 3%);
    border: 1px solid $border-color;
    padding: $spacer * 0.2 $spacer * 0.5;
    border-radius: $border-radius-sm;
    color: $secondary-color;
}


.readMoreLink {
    @include button-variant(transparent, transparent); // Make it look like a link
    color: $link-color;
    text-decoration: none;
    font-weight: bold;
    padding: 0; // Remove button padding
    font-size: $font-size-base * 0.95;

    &:hover {
        color: $link-hover-color;
        text-decoration: underline;
        background-color: transparent; // Ensure no bg on hover
        border-color: transparent;
    }
}
```

---

### components\BlogPostPreview\BlogPostPreview.tsx

```typescript
// src/components/BlogPostPreview/BlogPostPreview.tsx
import React from 'react';
import { Link } from 'react-router-dom';
import { BlogPostMeta } from '../../types';
import styles from './BlogPostPreview.module.scss';
import { FaCalendarAlt, FaUser, FaTags } from 'react-icons/fa'; // Example icons

interface BlogPostPreviewProps {
    post: BlogPostMeta;
}

const BlogPostPreview: React.FC<BlogPostPreviewProps> = ({ post }) => {
    return (
        <article className={styles.previewCard}>
            <h2 className={styles.previewTitle}>
                <Link to={`/blog/${post.slug}`}>{post.title}</Link>
            </h2>
            <div className={styles.previewMeta}>
                <span title="Published Date"><FaCalendarAlt /> {new Date(post.date).toLocaleDateString('en-US', { year: 'numeric', month: 'long', day: 'numeric' })}</span>
                {post.author && <span title="Author"><FaUser /> {post.author}</span>}
            </div>
            <p className={styles.previewExcerpt}>{post.excerpt}</p>
            {post.tags && post.tags.length > 0 && (
                 <div className={styles.previewTags}>
                     <FaTags />
                     {post.tags.map(tag => (
                         <span key={tag} className={styles.tag}>{tag}</span>
                         // Could make tags links to a future tag filter page:
                         // <Link key={tag} to={`/blog/tag/${tag.toLowerCase()}`} className={styles.tag}>{tag}</Link>
                     ))}
                 </div>
            )}
            <Link to={`/blog/${post.slug}`} className={styles.readMoreLink}>
                Read More →
            </Link>
        </article>
    );
};

export default BlogPostPreview;
```

---

## components\CookieConsent


### components\CookieConsent\CookieConsent.module.scss

```scss
// src/components/CookieConsent/CookieConsent.module.scss
@import '../../styles/variables';
@import '../../styles/mixins';

.consentBanner {
  position: fixed;
  bottom: 0;
  left: 0;
  right: 0;
  // Using a light, slightly opaque background with a border and shadow
  background-color: rgba($component-bg, 0.95); // Slightly transparent white
  color: $text-color; // Dark text for readability on light background
  padding: map-get($spacers, 3) map-get($spacers, 4); // p-3 px-4
  z-index: $zindex-modal + 10; // Ensure it's above most content
  border-top: 1px solid $gray-200; // Subtle top border
  box-shadow: 0 -2px 10px rgba($black-color, 0.08); // Softer shadow
  display: flex;
  flex-direction: column; // Stack content and actions on mobile
  align-items: center;
  gap: map-get($spacers, 3); // gap-3
  // backdrop-filter: blur(4px); // Optional: If using rgba background

  @include media-breakpoint-up(md) {
    flex-direction: row; // Side by side on larger screens
    justify-content: space-between;
    padding: map-get($spacers, 3) map-get($spacers, 5); // py-3 px-5
  }
}

.consentContent {
  flex-grow: 1;
  text-align: center;

  @include media-breakpoint-up(md) {
    text-align: left;
    margin-right: map-get($spacers, 4); // Space between text and buttons
  }
}

.consentText {
  margin: 0;
  font-size: $font-size-base * 0.9; // Slightly smaller text
  line-height: 1.5;
  color: $gray-700; // Use a standard text color

  a { // Links within the consent text
    color: $primary-color; // Use primary color for links
    font-weight: $font-weight-medium;
    text-decoration: underline; // Underline for clarity

    &:hover {
      color: darken($primary-color, 10%);
    }
    @include focus-outline($primary-color);
  }
}

.consentActions {
  display: flex;
  gap: map-get($spacers, 2); // gap-2 (8px)
  flex-shrink: 0;
  width: 100%; // Full width on mobile for centering buttons
  justify-content: center;

  @include media-breakpoint-up(md) {
    width: auto;
    justify-content: flex-end;
  }
}

.consentButton { // Base styles for consent buttons
  padding: map-get($spacers, 2) map-get($spacers, 3); // py-2 px-3
  font-size: $font-size-base * 0.85; // Smaller button text
  font-weight: $font-weight-medium;
  min-width: 120px; // Good minimum width for buttons
  white-space: nowrap; // Prevent text wrapping in buttons

  // Specific variants
  &.acceptButton {
    @include button-variant($success-color); // Solid success (green)
  }

  &.declineButton {
    // Outline/Secondary style for Decline
    @include button-variant(
      transparent,      // bg
      $gray-300,       // border
      $gray-700,       // text
      $gray-100,       // hover-bg
      $gray-400,       // hover-border
      $gray-800,       // hover-text
      $gray-200,       // active-bg
      $gray-500,       // active-border
      0.65,
      true              // is-outline
    );
  }
}
```

---

### components\CookieConsent\CookieConsent.tsx

```typescript
// src/components/CookieConsent/CookieConsent.tsx
import React, { useState, useEffect } from 'react';
import styles from './CookieConsent.module.scss';
import { Link } from 'react-router-dom'; // For linking to privacy policy

const LOCAL_STORAGE_KEY = 'examify_cookie_consent';

const CookieConsent: React.FC = () => {
    const [isVisible, setIsVisible] = useState(false);

    useEffect(() => {
        // Check localStorage on mount
        const consentGiven = localStorage.getItem(LOCAL_STORAGE_KEY);
        if (!consentGiven) {
            setIsVisible(true); // Show banner if no consent stored
        }
    }, []);

    const handleAccept = () => {
        try {
            localStorage.setItem(LOCAL_STORAGE_KEY, 'true'); // Store consent
            setIsVisible(false);
            // Optional: Trigger analytics initialization or enable features here if needed
            // initializeAnalyticsIfNeeded();
            //console.log('Cookie consent accepted.');
        } catch (error) {
            console.error("Could not save cookie consent to localStorage:", error);
            // Still hide the banner visually even if localStorage fails
            setIsVisible(false);
        }
    };

    const handleDecline = () => {
         // Option 1: Just hide the banner (essential cookies might still be used)
         setIsVisible(false);
         //console.log('Cookie consent declined (banner hidden).');

         // Option 2: Store declined state (if you need to differentiate)
         // try {
         //     localStorage.setItem(LOCAL_STORAGE_KEY, 'false');
         //     setIsVisible(false);
         //     console.log('Cookie consent declined.');
         //     // Disable non-essential cookies/analytics here if implementing granular control
         // } catch (error) {
         //      console.error("Could not save cookie preference:", error);
         //      setIsVisible(false);
         // }
    };


    if (!isVisible) {
        return null; // Don't render anything if visible is false
    }

    return (
        <div className={styles.consentBanner} role="dialog" aria-live="polite" aria-label="Cookie Consent Banner">
            <div className={styles.consentContent}>
                <p className={styles.consentText}>
                    We use essential cookies for authentication and site functionality. We also use Google Analytics to understand usage and improve our service (anonymized data). By continuing to use this site, you agree to our use of cookies. See our <Link to="/privacy-policy" target="_blank" rel="noopener noreferrer">Privacy Policy</Link> for details.
                    {/* Alternative text for explicit consent:
                    This site uses cookies. Essential cookies ensure basic functionality. Analytics cookies help us improve. Choose "Accept" to agree to all cookies. */}
                </p>
            </div>
            <div className={styles.consentActions}>
                 {/* Optional: Add a Decline Button if needed */}
                 <button onClick={handleDecline} className={`${styles.consentButton} ${styles.declineButton}`}>
                    Decline
                 </button>
                <button onClick={handleAccept} className={`${styles.consentButton} ${styles.acceptButton}`}>
                    Accept & Close
                </button>
            </div>
        </div>
    );
};

export default CookieConsent;
```

---

## components\CustomExamInput


### components\CustomExamInput\CustomExamInput.module.scss

```scss
// src/components/CustomExamInput/CustomExamInput.module.scss
@import '../../styles/variables';
@import '../../styles/mixins';


// --- Header: Format Link & AI Prompt Button ---
.customInputHeader {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: map-get($spacers, 3); // mb-3
  flex-wrap: wrap;
  gap: map-get($spacers, 2);
}

.formatLink { // Link to format example
  font-size: $font-size-base * 0.85;
  color: $link-color;
  font-weight: $font-weight-medium;
  text-decoration: none;
  &:hover { text-decoration: underline; }
  @include focus-outline($primary-color, 1px);
}

.copyPromptButton { // Button to copy AI JSON generation prompt
  @include button-variant(
    lighten($info-color, 50%), // Light info background
    lighten($info-color, 35%), // Light info border
    darken($info-color, 15%),  // Dark info text
    lighten($info-color, 45%), // Hover bg
    lighten($info-color, 30%), // Hover border
    darken($info-color, 10%)   // Hover text
  );
  padding: map-get($spacers, 1) map-get($spacers, 2); // py-1 px-2
  font-size: $font-size-base * 0.8;
  border-radius: $border-radius-sm;
  gap: map-get($spacers, 1);
  svg { font-size: $font-size-base * 0.9; }
}

// --- File Input & Upload Button ---
.fileInput { // Keep hidden (as before)
  width: 0.1px; height: 0.1px; opacity: 0; overflow: hidden; position: absolute; z-index: -1;
}

.uploadButton { // This is the <label> styled as a button/dropzone
  // Using an outline style, but with custom colors for a "dropzone" feel
  @include button-variant(
    transparent,                  // bg
    $gray-300,                   // border
    $gray-600,                   // text
    $gray-50,                    // hover-bg
    $primary-color,              // hover-border (highlight with primary)
    $primary-color,              // hover-text
    $gray-100,                   // active-bg
    darken($primary-color, 5%),  // active-border
    0.65,
    true                          // is-outline (important for structure)
  );
  border-style: dashed;
  border-width: 2px; // Slightly thicker dashed border
  padding: map-get($spacers, 4) map-get($spacers, 3); // py-4 px-3, generous padding
  font-weight: $font-weight-medium;
  display: flex;
  flex-direction: column; // Stack icon and text
  align-items: center;
  justify-content: center;
  width: 100%;
  margin-bottom: map-get($spacers, 3);
  text-align: center;
  min-height: 120px; // Ensure decent height for dropzone

  svg { // Icon within the upload button
    font-size: $font-size-base * 2; // Larger icon
    margin-bottom: map-get($spacers, 2);
    color: $gray-400; // Muted icon color initially
    transition: color $transition-fast;
  }

  span { // Text within upload button
    font-size: $font-size-base * 0.95;
  }

  &:hover:not(:disabled) {
    // Hover styles are handled by button-variant mixin for border/text
    // We can add specific icon color change on hover
    svg { color: $primary-color; }
  }

  // Parsing state
  &.parsing {
    cursor: wait;
    border-style: solid; // Solid border during parsing
    border-color: $info-color;
    background-color: lighten($info-color, 55%);
    color: $info-color;
    svg { color: $info-color; } // Spinner should inherit this or be styled
  }
  // Disabled state (e.g., when paste area is active)
  // The button-variant mixin handles base :disabled, this is for custom .disabledButton class
  &.disabledButton { // Class applied via JS
    cursor: not-allowed !important;
    opacity: 0.5 !important;
    border-color: $gray-200 !important;
    background-color: $gray-50 !important;
    color: $gray-400 !important;
    svg { color: $gray-300 !important; }
    &:hover { // Prevent hover styles when custom-disabled
        border-color: $gray-200 !important;
        background-color: $gray-50 !important;
        color: $gray-400 !important;
        svg { color: $gray-300 !important; }
    }
  }
}

// --- OR Divider ---
.uploadOrPasteDivider {
  width: 100%;
  text-align: center;
  border-bottom: 1px solid $gray-200; // Lighter divider
  line-height: 0.1em;
  margin: map-get($spacers, 5) auto; // my-5, more vertical space
  color: $text-muted;

  span {
    background: $body-bg; // Match page background (or $component-bg if on a card)
    padding: 0 map-get($spacers, 2);
    font-size: $font-size-base * 0.9;
    font-weight: $font-weight-medium;
  }
}

// --- Paste Area ---
.togglePasteButton { // Button to show/hide paste area
  @include button-variant($primary-color); // Solid primary
  // Using styles similar to secondary action on HomePage
  // @include button-variant(transparent, $primary-color, $primary-color, $is-outline: true);
  display: flex; // Ensure it behaves like other buttons for width/centering
  align-items: center;
  justify-content: center;
  width: auto; // Fit content or set a min-width
  min-width: 220px;
  margin: 0 auto map-get($spacers, 3) auto; // Center it
  gap: map-get($spacers, 2);

  &.cancelPaste { // Style when it shows "Cancel" - more subtle
    @include button-text-variant($gray-600, rgba($gray-600, 0.05), $gray-700);
    // Or a subtle outline button:
    // @include button-variant(transparent, $gray-300, $gray-700, $is-outline: true);
  }
}

.pasteArea {
  width: 100%;
  margin-top: map-get($spacers, 3); // If toggle button isn't present
  display: flex;
  flex-direction: column;
  gap: map-get($spacers, 2);
}

.pasteTextarea {
  width: 100%;
  padding: map-get($spacers, 3); // p-3
  border: 1px solid $border-color;
  border-radius: $border-radius;
  font-family: $font-family-monospace;
  font-size: $font-size-base * 0.9;
  line-height: 1.5; // Increased for code readability
  resize: vertical;
  min-height: 180px; // Good minimum height for pasting code
  background-color: $white-color;
  box-shadow: $box-shadow-inset;
  transition: border-color $transition-fast, box-shadow $transition-fast;

  &:focus {
    outline: none;
    border-color: $primary-color;
    box-shadow: $box-shadow-inset, 0 0 0 3px rgba($primary-color, 0.2); // Combine inset with focus ring
  }
  &.errorBorder {
    border-color: $danger-color !important; // Important to override focus styles if needed
    &:focus {
      box-shadow: $box-shadow-inset, 0 0 0 3px rgba($danger-color, 0.2);
    }
  }
  &:disabled {
    background-color: $gray-100;
    cursor: not-allowed;
    opacity: 0.7;
  }
  &.validated { // When JSON is successfully parsed and validated
    border-color: $success-color !important;
    background-color: lighten($success-color, 58%);
    color: $gray-700; // Ensure text is readable
    cursor: default;
    &:focus {
      box-shadow: $box-shadow-inset, 0 0 0 3px rgba($success-color, 0.25);
    }
  }
}

.pasteActions { // Container for buttons below textarea
  display: flex;
  justify-content: flex-end; // Align buttons to the right
  align-items: center;
  gap: map-get($spacers, 2); // Gap between buttons
  margin-top: map-get($spacers, 1); // Small space above buttons
}

.clearButton, .cancelButton.secondaryButton { // For "Clear File", "Clear Paste", "Cancel Paste"
  // Using a text button style for these actions
  @include button-text-variant($gray-600, rgba($gray-600, 0.05), $gray-700);
  font-size: $font-size-base * 0.9;
  padding: map-get($spacers, 1) map-get($spacers, 2); // Smaller padding
  gap: map-get($spacers, 1);
  &.destructive { // If clear is more "danger" oriented
      @include button-text-variant($danger-color, rgba($danger-color, 0.05), darken($danger-color, 5%));
  }
}

.parseButton { // Button to validate pasted JSON
  @include button-variant($primary-color);
  // Padding and font size are set by the mixin, can override if needed
  // e.g., padding: map-get($spacers, 2) map-get($spacers, 3);
}


// --- Feedback Messages (Error, Success, Info) ---
// Use the new variables for consistency with global ErrorMessage component styling
// These extend the existing ErrorMessage component's style logic
// but are locally defined for CustomExamInput specific messages.
.errorMessage, .successMessage, .infoMessage {
  text-align: left;
  font-size: $font-size-base * 0.9;
  margin-top: map-get($spacers, 2); // mt-2, space above message
  padding: map-get($spacers, 2) map-get($spacers, 3); // py-2 px-3
  border-radius: $border-radius; // Standard radius
  display: flex;
  align-items: flex-start;
  gap: map-get($spacers, 2); // gap-2
  line-height: 1.5; // Better line height for messages
  border-width: $border-width;
  border-style: solid;

  svg { // Icon within the message
    font-size: $font-size-base * 1.1; // Standard icon size
    margin-top: 2px; // Align icon better
    flex-shrink: 0;
  }
}

.errorMessage {
  background-color: lighten($red-500, 50%);
  border-color: lighten($red-500, 30%);
  color: darken($red-500, 15%);
  svg { color: $red-500; }
}

.successMessage {
  background-color: lighten($green-500, 50%);
  border-color: lighten($green-500, 35%);
  color: darken($green-500, 20%);
  svg { color: $green-500; }

  // Customization for success box below file/paste inputs
  &.fullWidthCentered { // If you need a centered success message
      justify-content: center;
      text-align: center;
      margin-top: map-get($spacers, 3);
  }
}
.successBox { // Container for success message + clear button
    display: flex;
    flex-direction: column;
    align-items: stretch;
    gap: map-get($spacers, 2);
    margin-top: map-get($spacers, 2); // Ensure consistent spacing

    .successMessage { // Override margin for message inside box
        margin-top: 0;
    }
    .clearButton {
        align-self: flex-start; // Align clear button left if desired
        // @extend .destructive; // Make clear button red-themed text
    }
}


.infoMessage { // For "Please click validate" etc.
  background-color: lighten($sky-500, 50%);
  border-color: lighten($sky-500, 35%);
  color: darken($sky-500, 20%);
  svg { color: $sky-500; }
}

// Spin icon already global in App.scss, no need to redefine.
// .disabledContent can be used if parent doesn't handle fully.
.disabledContent {
  opacity: 0.6;
  pointer-events: none;
  filter: grayscale(30%); // Subtle grayscale
}
```

---

### components\CustomExamInput\CustomExamInput.tsx

```typescript
// src/components/CustomExamInput/CustomExamInput.tsx
import React, { useState, useCallback, useRef } from 'react';
import { FaUpload, FaCheckCircle, FaPaste, FaTimes, FaInfoCircle, FaCopy } from 'react-icons/fa';
import styles from './CustomExamInput.module.scss';
import { analytics } from '../../services/firebase';
import { logEvent } from 'firebase/analytics';
import { toast } from 'react-toastify';
import Spinner from '../Spinner/Spinner';
import ErrorMessage from '../ErrorMessage/ErrorMessage';

// --- UPDATED: AI Prompt Constant ---
const AI_JSON_GENERATION_PROMPT = `
Generate a valid JSON array containing [Number] practice questions for the [Exam Name/Subject] exam.

Each question object in the array must strictly follow this structure:
{
  "question_number": Number, // REQUIRED: Unique, sequential integer starting from 1
  "question_text": String,   // REQUIRED: Question text
  "options": Object,         // REQUIRED: e.g., {"a": "Option A", "b": "Option B"}
  "correct_answer": String,  // REQUIRED: Key matching the correct option (e.g., "b")
  "subject": String | null,    // Optional: e.g., "Physics" or null
  "topic": String | null,      // Optional: e.g., "Kinematics" or null
  "explanation": String | null, // Optional but preferred: Detailed explanation or null
  "difficulty": String | null, // Optional: "Easy", "Medium", or "Hard"
  "section_id": String | null  // Optional: e.g., "SectionA"
}

Formatting Rules for ALL String Values:
1.  Use LaTeX for Math: Inline $ ... $, Display $$ ... $$. IMPORTANT: Escape all LaTeX backslashes as \\\\ (e.g., use "\\\\frac", "\\\\sin").
2.  Use Markdown Code Blocks: Fenced \`\`\`language ... \`\`\`. IMPORTANT: Escape all newlines within code as \\\\n.
3.  Use Markdown Images: ![Alt Text](PLACEHOLDER_PATH). I will replace the placeholder later.

Here is ONE example object:
{
  "question_number": 1,
  "subject": "Mathematics",
  "topic": "Algebra",
  "difficulty": "Easy",
  "section_id": "AlgebraBasics",
  "question_text": "If $x + 5 = 12$, what is the value of $x$?",
  "options": { "a": "5", "b": "7", "c": "12", "d": "17" },
  "correct_answer": "b",
  "explanation": "Subtract 5 from both sides: $x + 5 - 5 = 12 - 5 \\\\implies x = 7$."
}

Generate [Number] question objects in a single valid JSON array, applying all rules, especially escaping. Ensure the final output is ONLY the JSON array itself, starting with '[' and ending with ']'.
`.trim();

interface CustomExamInputProps {
    isDisabled: boolean; // Passed from parent
    onFileValidated: (file: File) => void;
    onPasteValidated: (jsonString: string) => void;
    onInputCleared: () => void;
    onError: (source: 'file' | 'paste', message: string) => void;
}

const CustomExamInput: React.FC<CustomExamInputProps> = ({
    isDisabled,
    onFileValidated,
    onPasteValidated,
    onInputCleared,
    onError,
}) => {

    // --- Internal State ---
    const [uploadedFile, setUploadedFile] = useState<File | null>(null);
    const [uploadedFileName, setUploadedFileName] = useState<string>('');
    const [uploadError, setUploadError] = useState<string | null>(null);
    const [isParsingFile, setIsParsingFile] = useState<boolean>(false);

    const [showPasteArea, setShowPasteArea] = useState<boolean>(false);
    const [pastedJsonString, setPastedJsonString] = useState<string>('');
    const [pasteError, setPasteError] = useState<string | null>(null);
    const [isParsingPaste, setIsParsingPaste] = useState<boolean>(false);
    const [isPasteValidated, setIsPasteValidated] = useState<boolean>(false);

    const fileInputRef = useRef<HTMLInputElement>(null);
    
    const handleCopyAiPrompt = useCallback(() => {
        navigator.clipboard.writeText(AI_JSON_GENERATION_PROMPT)
            .then(() => {
                toast.success("AI prompt for JSON generation copied!");
                logEvent(analytics, 'ui_click', { element_id: 'copy_ai_json_prompt_guide' });
            })
            .catch(err => {
                toast.error("Could not copy AI prompt. Please try again or copy manually.");
            });
    }, []);

    // --- Validation Logic ---
    const validateJsonStructure = useCallback((jsonString: string): any[] => {
        let data: any[];
        try {
            data = JSON.parse(jsonString);
        } catch (err: any) {
            throw new SyntaxError(`Invalid JSON syntax: ${err.message}`);
        }

        if (!Array.isArray(data)) throw new Error("Invalid format: Top level must be an array `[]`.");
        if (data.length === 0) throw new Error("Invalid format: Exam must contain at least one question.");

        const questionNumbers = new Set<number>();
        let lastQuestionNumber = 0;

        data.forEach((q: any, index: number) => {
            const qNumForErrorDisplay = q.question_number !== undefined ? q.question_number : `(at index ${index})`;

            if (typeof q !== 'object' || q === null) throw new Error(`Invalid format: Item ${qNumForErrorDisplay} must be an object.`);

            // question_number validation
            if (typeof q.question_number !== 'number' || !Number.isInteger(q.question_number) || q.question_number <= 0) {
                throw new Error(`Invalid format: Question ${qNumForErrorDisplay} 'question_number' must be a positive integer.`);
            }
            if (questionNumbers.has(q.question_number)) {
                throw new Error(`Invalid format: Question number ${q.question_number} is duplicated. 'question_number' must be unique.`);
            }
            questionNumbers.add(q.question_number);
            if (q.question_number < lastQuestionNumber && lastQuestionNumber !== 0) {
                console.warn(`Warning: Question ${q.question_number} 'question_number' (${q.question_number}) is not strictly greater than the previous one (${lastQuestionNumber}). Consider reordering for best practice, though this is not a fatal error.`);
            }
            lastQuestionNumber = q.question_number;

            // question_text validation
            if (typeof q.question_text !== 'string' || q.question_text.trim() === '') {
                throw new Error(`Invalid format: Question ${q.question_number} 'question_text' must be a non-empty string.`);
            }

            // options validation
            if (typeof q.options !== 'object' || q.options === null || Object.keys(q.options).length < 2) {
                throw new Error(`Invalid format: Question ${q.question_number} 'options' must be an object with at least two key-value pairs.`);
            }
            for (const key in q.options) {
                if (typeof q.options[key] !== 'string') {
                     throw new Error(`Invalid format: Question ${q.question_number} option '${key}' value must be a string.`);
                }
            }

            // correct_answer validation
            if (typeof q.correct_answer !== 'string' || !q.options.hasOwnProperty(q.correct_answer)) {
                throw new Error(`Invalid format: Question ${q.question_number} 'correct_answer' ("${q.correct_answer}") must be a string matching one of its option keys.`);
            }

            // Optional fields validation
            if (q.hasOwnProperty('subject') && q.subject !== null && (typeof q.subject !== 'string' || q.subject.trim() === '')) {
                throw new Error(`Invalid format: Question ${q.question_number} 'subject', if present and not null, must be a non-empty string.`);
            }
            if (q.hasOwnProperty('topic') && q.topic !== null && (typeof q.topic !== 'string' || q.topic.trim() === '')) {
                throw new Error(`Invalid format: Question ${q.question_number} 'topic', if present and not null, must be a non-empty string.`);
            }
            if (q.hasOwnProperty('explanation') && q.explanation !== null && typeof q.explanation !== 'string') {
                throw new Error(`Invalid format: Question ${q.question_number} 'explanation', if present and not null, must be a string.`);
            }
            if (q.hasOwnProperty('difficulty') && q.difficulty !== null) {
                if (typeof q.difficulty !== 'string' || (q.difficulty !== '' && !['Easy', 'Medium', 'Hard'].includes(q.difficulty))) {
                    throw new Error(`Invalid format: Question ${q.question_number} 'difficulty', if present and not null, must be one of "Easy", "Medium", "Hard", or an empty string (for "Not specified"). Received: "${q.difficulty}"`);
                }
            }
            if (q.hasOwnProperty('section_id') && q.section_id !== null && (typeof q.section_id !== 'string' || q.section_id.trim() === '')) {
                throw new Error(`Invalid format: Question ${q.question_number} 'section_id', if present and not null, must be a non-empty string.`);
            }

            if (q.marks_positive !== undefined && typeof q.marks_positive !== 'number') {
                 console.warn(`Warning: Question ${q.question_number} has 'marks_positive' but it's not a number. This field is not standard and may be ignored.`);
            }
            if (q.marks_negative !== undefined && typeof q.marks_negative !== 'number') {
                 console.warn(`Warning: Question ${q.question_number} has 'marks_negative' but it's not a number. This field is not standard and may be ignored.`);
            }
        });
        return data;
    }, []);

    const resetLocalState = useCallback((type: 'file' | 'paste' | 'all') => {
        if (type === 'file' || type === 'all') {
            setUploadedFile(null);
            setUploadedFileName('');
            setUploadError(null);
            setIsParsingFile(false);
            if (fileInputRef.current) {
                fileInputRef.current.value = '';
            }
        }
        if (type === 'paste' || type === 'all') {
            setShowPasteArea(false);
            setPastedJsonString('');
            setPasteError(null);
            setIsParsingPaste(false);
            setIsPasteValidated(false);
        }
    }, []); 

    const handleValidationError = useCallback((err: any, source: 'file' | 'paste') => {
        const errorMessage = err instanceof SyntaxError ? `JSON Syntax Error: ${err.message}` : `JSON Format Error: ${err.message}`;
        if (source === 'file') {
            setUploadError(errorMessage);
            resetLocalState('file');
             logEvent(analytics, 'upload_custom_exam_fail', { error_message: errorMessage.substring(0, 100) });
        } else {
            setPasteError(errorMessage);
            setIsPasteValidated(false);
            logEvent(analytics, 'paste_custom_exam_fail', { error_message: errorMessage.substring(0, 100) });
        }
        onError(source, errorMessage); 
    }, [onError, resetLocalState]); 

    const parseAndValidateJsonFile = useCallback((file: File) => {
        setIsParsingFile(true);
        setUploadError(null); 
        setPasteError(null); 
        const reader = new FileReader();

        reader.onload = (e) => {
            const text = e.target?.result as string | null;
            let success = false; 
            try {
                if (text === null) throw new Error("Could not read file content.");
                validateJsonStructure(text);
                setUploadError(null);
                logEvent(analytics, 'upload_custom_exam_success', { file_size: file.size });
                onFileValidated(file); 
                success = true; 
            } catch (err: any) {
                handleValidationError(err, 'file');
                success = false; 
            } finally {
                setIsParsingFile(false);
                if (success && fileInputRef.current) {
                    fileInputRef.current.value = '';
                }
            }
        };
        reader.onerror = (e) => {
            const errMsg = "Failed to read the file.";
            resetLocalState('file'); 
            onError('file', errMsg);
            setIsParsingFile(false);
        };
        reader.readAsText(file);
    }, [validateJsonStructure, handleValidationError, onFileValidated, onError, resetLocalState]);

    const handleFileChange = useCallback((event: React.ChangeEvent<HTMLInputElement>) => {
         resetLocalState('paste'); 
         setShowPasteArea(false);
         setUploadError(null);
         setPasteError(null);

         const file = event.target.files?.[0];

         if (file) {
            logEvent(analytics, 'upload_custom_exam_start', { file_size: file.size });
             if (!file.name.endsWith('.json')) {
                 const msg = 'Invalid file type. Please upload a .json file.';
                 setUploadError(msg);
                 setUploadedFile(null); setUploadedFileName('');
                 onError('file', msg); 
                 if (fileInputRef.current) {
                    fileInputRef.current.value = '';
                 }
                 return;
             }
             const maxSize = 5 * 1024 * 1024;
             if (file.size > maxSize) {
                 const msg = `File is too large. Maximum size is 5MB.`;
                 setUploadError(msg);
                 setUploadedFile(null); setUploadedFileName('');
                 onError('file', msg); 
                 if (fileInputRef.current) {
                    fileInputRef.current.value = '';
                 }
                 return;
             }
             setUploadError(null);
             setPasteError(null);
             setShowPasteArea(false);
             setUploadedFile(file);
             setUploadedFileName(file.name);
             parseAndValidateJsonFile(file); 
         } else {
            resetLocalState('file');
            onInputCleared(); 
         }
     }, [resetLocalState, parseAndValidateJsonFile, onInputCleared, onError]); 

     const handleClearCustomInput = useCallback(() => {
        resetLocalState('all'); 
        onInputCleared();     
    }, [resetLocalState, onInputCleared]);

     const togglePasteArea = useCallback(() => {
        setShowPasteArea(prev => {
            const opening = !prev;
            if (opening) {
                resetLocalState('file'); 
                onInputCleared(); 
                setPasteError(null); 
            } else {
                handleClearCustomInput();
            }
            return opening;
        });
    }, [resetLocalState, onInputCleared, handleClearCustomInput]);

     const handlePasteChange = useCallback((event: React.ChangeEvent<HTMLTextAreaElement>) => {
        setPastedJsonString(event.target.value);
        setPasteError(null); 
        setIsPasteValidated(false);
        if (uploadedFile) {
             resetLocalState('file');
             onInputCleared(); 
        }
    }, [resetLocalState, onInputCleared, uploadedFile]);

     const handleParsePastedJson = useCallback(() => {
        if (!pastedJsonString.trim()) {
            const msg = "Paste area is empty.";
            setPasteError(msg);
            setIsPasteValidated(false);
            onError('paste', msg);
            return;
        }
        setUploadError(null);

        setIsParsingPaste(true);
        setPasteError(null);
        setTimeout(() => {
            try {
                validateJsonStructure(pastedJsonString);
                setPasteError(null); 
                setIsPasteValidated(true);
                toast.success("Pasted JSON format looks valid! You can now start the practice session.");
                logEvent(analytics, 'paste_custom_exam_success', { length: pastedJsonString.length });
                onPasteValidated(pastedJsonString); 
            } catch (err: any) {
                setIsPasteValidated(false);
                handleValidationError(err, 'paste');
            } finally {
                setIsParsingPaste(false);
            }
        }, 50);
    }, [pastedJsonString, validateJsonStructure, handleValidationError, onPasteValidated, onError]); 

    const isFileReady = uploadedFile !== null && !uploadError && !isParsingFile;
    const isPasteReadyAndValidated = pastedJsonString !== '' && !pasteError && !isParsingPaste && isPasteValidated;

    return (
        <div className={styles.customInputContainer}> 
            <div className={styles.customInputHeader}>
                <button 
                    type="button" 
                    onClick={handleCopyAiPrompt} 
                    className={styles.copyPromptButton} 
                    disabled={isDisabled}
                >
                    <FaCopy /> Copy AI Prompt Guide
                </button>
                <a 
                    href="#json-format-example" 
                    className={styles.formatLink} 
                    onClick={(e) => {
                        e.preventDefault(); 
                        document.getElementById('json-format-example')?.scrollIntoView({ behavior: 'smooth' });
                    }}
                >
                    (View Format)
                </a>
            </div>

            {!showPasteArea && (
                <>
                <label
                    htmlFor="custom-file-upload"
                    className={`${styles.uploadButton} ${isDisabled || isPasteReadyAndValidated ? styles.disabledButton : ''} ${isParsingFile ? styles.parsing : ''}`}
                    title={
                        isDisabled ? "Input disabled by parent selection" :
                        isPasteReadyAndValidated ? "Using validated pasted JSON" :
                        isParsingFile ? "Validating selected file..." :
                        uploadedFileName ? `Selected: ${uploadedFileName}` : "Choose a .json file"
                    }
                >
                    {isParsingFile ? <><Spinner size="1em" />  <span>Validating...</span></>
                        : <><FaUpload /><span>{uploadedFileName ? `File: ${uploadedFileName}` : 'Choose JSON File'}</span></>
                    }
                </label>
                    <input
                        id="custom-file-upload" 
                        type="file"
                        accept=".json"
                        onChange={handleFileChange}
                        disabled={isDisabled || isParsingFile || isPasteReadyAndValidated} 
                        title={ 
                            isDisabled ? "Input disabled" :
                            isPasteReadyAndValidated ? "Using validated pasted JSON" :
                            isParsingFile ? "Validating file..." : "File upload input"
                        }
                        className={styles.fileInput} 
                        ref={fileInputRef} 
                    />
                     <ErrorMessage type="info" message={uploadError} />
                        {isFileReady && (
                            <div className={styles.successBox}> 
                                <p className={styles.successMessage}><FaCheckCircle /> File ready!</p>
                                <button
                                    onClick={handleClearCustomInput}
                                    className={styles.destructive}
                                    title="Clear selected file"
                                >
                                    <FaTimes /> Clear File
                                </button>
                            </div>
                        )}
                </>
            )}

            {!isFileReady && !showPasteArea && ( 
            <div className={styles.uploadOrPasteDivider}>
                <span>OR</span>
            </div>
            )}

            {!showPasteArea && !isFileReady && ( 
                <button
                    onClick={togglePasteArea}
                    className={styles.togglePasteButton}
                    disabled={isDisabled || isParsingFile}
                    title={
                        isDisabled ? "Input disabled" :
                        isParsingFile ? "Cannot paste while validating file" :
                        "Paste custom JSON code"
                    }
                    aria-expanded={false}
                >
                    <FaPaste /> Paste JSON Code
                </button>
            )}

            {showPasteArea && (
                <div className={styles.pasteArea}>
                    <textarea
                        placeholder="Paste your JSON array here..."
                        value={pastedJsonString}
                        onChange={handlePasteChange}
                        rows={10}
                        className={`${styles.pasteTextarea} ${pasteError ? styles.errorBorder : ''} ${isPasteReadyAndValidated ? styles.validated : ''}`}
                        disabled={isDisabled || isParsingPaste || isPasteReadyAndValidated}
                        title={
                            isDisabled ? "Input disabled" :
                            isParsingPaste ? "Validating pasted content..." :
                            isPasteReadyAndValidated ? "JSON validated and ready" :
                            "Paste JSON array here"
                        }
                        aria-label="Paste JSON code area"
                        aria-describedby="paste-error-msg paste-success-msg paste-info-msg"
                        aria-invalid={!!pasteError}
                    />
                    <div className={styles.pasteActions}> 
                        {!isPasteReadyAndValidated ? (
                            <button onClick={togglePasteArea} className={`${styles.cancelButton} ${styles.secondaryButton}`}>
                                <FaTimes /> Cancel Paste
                            </button>
                        ) : (
                            <button onClick={handleClearCustomInput} className={`${styles.clearButton} ${styles.secondaryButton}`}>
                                <FaTimes /> Clear Pasted JSON
                            </button>
                        )}
                        <button
                            onClick={handleParsePastedJson}
                            disabled={isDisabled || !pastedJsonString || isParsingPaste || isPasteReadyAndValidated}
                            title={
                                isDisabled ? "Input disabled" :
                                !pastedJsonString ? "Paste JSON content first" :
                                isParsingPaste ? "Validation in progress..." :
                                isPasteReadyAndValidated ? "JSON already validated" :
                                "Validate Pasted JSON"
                            }
                            className={styles.parseButton}
                        >
                            {isParsingPaste ? <><Spinner size="1em" /> Validating...</> : 'Validate Pasted JSON'}
                        </button>
                    </div>

                    <ErrorMessage type="info" message={pasteError} />
                    {!pasteError && pastedJsonString && !isPasteValidated && !isParsingPaste && (
                        <p id="paste-info-msg" className={styles.infoMessage}>
                            <FaInfoCircle /> Please click 'Validate' to check the JSON format.
                        </p>
                    )}
                    {isPasteReadyAndValidated && (
                        <p id="paste-success-msg" className={styles.successMessage}>
                            <FaCheckCircle /> Validated JSON is ready. You can now start the practice session.
                        </p>
                    )}
                </div>
            )}
        </div>
    );
};

export default CustomExamInput;
```

---

## components\ErrorMessage


### components\ErrorMessage\ErrorMessage.module.scss

```scss
// src/components/ErrorMessage/ErrorMessage.module.scss
@import '../../styles/variables';
@import '../../styles/mixins'; // For focus-outline if actions have focusable elements

.messageContainer {
  display: flex;
  align-items: flex-start; // Align icon to the top of the text block
  gap: map-get($spacers, 2); // gap-2 (8px)
  padding: map-get($spacers, 3); // p-3 (16px)
  margin-bottom: map-get($spacers, 3); // Default bottom margin
  border-radius: $border-radius; // Standard radius (6px)
  border-width: $border-width;
  border-style: solid;

  &.text-center { // Kept for consistency if needed
    justify-content: center;
    text-align: center;
    align-items: center;
  }

  // --- Type-specific styles using new palette ---
  &.error {
    background-color: lighten($red-500, 50%); // Lighter red background
    border-color: lighten($red-500, 30%);   // Softer red border
    color: darken($red-500, 15%);           // Darker red text for contrast
    .messageIcon { color: $red-500; }       // Icon uses base danger color
  }
  &.warning {
    background-color: lighten($amber-500, 48%);
    border-color: lighten($amber-500, 30%);
    color: darken($amber-500, 25%); // Darker text on amber
    .messageIcon { color: $amber-500; }
  }
  &.info {
    background-color: lighten($sky-500, 50%);
    border-color: lighten($sky-500, 35%);
    color: darken($sky-500, 20%);
    .messageIcon { color: $sky-500; }
  }
  &.success {
    background-color: lighten($green-500, 50%);
    border-color: lighten($green-500, 35%);
    color: darken($green-500, 20%);
    .messageIcon { color: $green-500; }
  }
}

.messageIcon {
  font-size: $font-size-base * 1.25; // Slightly larger icon (20px if base is 16px)
  flex-shrink: 0;
  margin-top: 2px; // Fine-tune vertical alignment with first line of text
  line-height: 1; // Ensure icon itself doesn't add extra line height
}

.messageContent {
  flex-grow: 1;
  display: flex; // Use flex for title/text/actions column
  flex-direction: column;
  gap: map-get($spacers, 1); // Small gap between title and text
}

.messageTitle {
  display: block;
  font-weight: $font-weight-semibold; // Bolder title
  font-size: $font-size-base * 1.05;   // Slightly larger than body
  color: inherit; // Inherit themed text color
}

.messageText {
  margin: 0;
  font-size: $font-size-base;
  line-height: $line-height-base;
  color: inherit; // Inherit themed text color

  // For ReactNode messages, ensure direct children don't add extra margin
  & > *:first-child { margin-top: 0; }
  & > *:last-child { margin-bottom: 0; }

  p { // If paragraphs are used within ReactNode
    font-size: inherit; // Keep font size consistent
    line-height: inherit;
    margin-bottom: map-get($spacers, 2); // Add some space between paragraphs
    &:last-child { margin-bottom: 0; }
  }
  a { // Style links within messages
    font-weight: $font-weight-medium;
    text-decoration: underline;
    color: inherit; // Use the message's text color to ensure contrast
    &:hover {
      color: inherit; // Keep hover color also contrasted
      filter: brightness(85%); // Slightly darken on hover
    }
  }
}

.messageActions {
  margin-top: map-get($spacers, 2); // mt-2
  display: flex;
  justify-content: flex-end; // Align actions to the right
  gap: map-get($spacers, 2);  // gap-2

}
```

---

### components\ErrorMessage\ErrorMessage.tsx

```typescript
// src/components/ErrorMessage/ErrorMessage.tsx
import React from 'react';
import { 
    FaExclamationTriangle, // Error
    FaExclamationCircle,   // Warning
    FaInfoCircle,          // Info
    FaCheckCircle          // Success
} from 'react-icons/fa';
import styles from './ErrorMessage.module.scss';

interface ErrorMessageProps {
    /** The main message string to display */
    message: string | null | React.ReactNode; // Allow ReactNode for more complex messages
    /** Optional title for the message box */
    title?: string;
    /** Type of message, influences icon and styling */
    type?: 'error' | 'warning' | 'info' | 'success';
    /** Optional: Align text left/center */
    textAlign?: 'left' | 'center';
    /** Optional: Additional CSS class names */
    className?: string;
    /** Optional: ReactNode for actions like buttons */
    actions?: React.ReactNode;
    /** Optional: Hide icon */
    hideIcon?: boolean;
}

const ErrorMessage: React.FC<ErrorMessageProps> = ({
    message,
    title,
    type = 'error', // Default to error
    textAlign = 'left',
    className = '',
    actions,
    hideIcon = false,
}) => {
    if (!message) {
        return null;
    }

    const getIcon = () => {
        if (hideIcon) return null;
        switch (type) {
            case 'success':
                return <FaCheckCircle className={`${styles.messageIcon} ${styles.iconSuccess}`} aria-hidden="true" />;
            case 'warning':
                return <FaExclamationCircle className={`${styles.messageIcon} ${styles.iconWarning}`} aria-hidden="true" />;
            case 'info':
                return <FaInfoCircle className={`${styles.messageIcon} ${styles.iconInfo}`} aria-hidden="true" />;
            case 'error':
            default:
                return <FaExclamationTriangle className={`${styles.messageIcon} ${styles.iconError}`} aria-hidden="true" />;
        }
    };

    const containerClasses = `${styles.messageContainer} ${styles[type]} ${styles[`text-${textAlign}`]} ${className}`;
    const role = (type === 'error' || type === 'warning') ? 'alert' : 'status'; // Use alert for errors/warnings

    return (
        <div className={containerClasses} role={role}>
            {getIcon()}
            <div className={styles.messageContent}>
                {title && <strong className={styles.messageTitle}>{title}</strong>}
                {typeof message === 'string' ? (
                    <p className={styles.messageText}>{message}</p>
                ) : (
                    <div className={styles.messageText}>{message}</div> // Render ReactNode directly
                )}
                {actions && <div className={styles.messageActions}>{actions}</div>}
            </div>
        </div>
    );
};

export default ErrorMessage;
```

---

## components\ExamControls


### components\ExamControls\ExamControls.module.scss

```scss
// src/components/ExamControls/ExamControls.module.scss
@import '../../styles/variables';
@import '../../styles/mixins';

.controlsWrapper {
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap; // Allow wrapping on very small screens if space is tight
  gap: map-get($spacers, 2); // gap-2 (8px) between groups or wrapped buttons
  // Padding is handled by the parent .bottomControls area in ExamPage
}

.leftControls,
.rightControls {
  display: flex;
  align-items: center; // Ensure buttons align nicely if heights vary slightly
  gap: map-get($spacers, 2); // gap-2 (8px) between buttons within a group
  flex-wrap: nowrap; // Usually, don't want buttons within a group to wrap
}

.controlButton { // Base style for all control buttons
  padding: map-get($spacers, 2) map-get($spacers, 3); // py-2 px-3
  font-size: $font-size-base * 0.9; // Slightly smaller text
  font-weight: $font-weight-medium;
  // border-radius: $border-radius; // Handled by mixin
  display: inline-flex; // Already set by mixin usually, but good to ensure
  align-items: center;
  justify-content: center; // Center content if buttons grow
  gap: map-get($spacers, 2); // gap-2 for icon and text
  white-space: nowrap;
  min-width: 130px; // Ensure decent minimum width, adjust as needed
  flex-grow: 0; // Don't grow by default
  flex-shrink: 0;

  // --- Variants using the new button mixin ---

  // "Previous" and default "Mark for Review" button
  &.secondary {
    @include button-variant(
      transparent,        // bg
      $gray-400,         // border
      $gray-700,         // text
      $gray-100,         // hover-bg
      $gray-500,         // hover-border
      $gray-800,         // hover-text
      $gray-200,         // active-bg
      $gray-600,         // active-border
      0.65,
      true                // is-outline
    );
  }

  // "Save & Next" button
  &.primary { // Using primary color for Save & Next
    @include button-variant($primary-color);
  }
  // If you prefer green for "Save & Next":
  // &.primary {
  //   @include button-variant($success-color);
  // }


  // "Clear Response" button
  &.warning {
    // Outline style with warning color
    @include button-variant(
      transparent,
      $warning-color,  // Border is warning
      $warning-color,  // Text is warning
      lighten($warning-color, 45%), // Hover bg
      darken($warning-color, 5%),   // Hover border
      darken($warning-color, 10%),  // Hover text
      lighten($warning-color, 40%), // Active bg
      darken($warning-color, 10%),  // Active border
      0.65,
      true // is-outline
    );
    // Or a more subtle text button:
    // @include button-text-variant(darken($warning-color, 10%), rgba($warning-color, 0.1), darken($warning-color, 20%));
  }

  // When "Mark for Review" button indicates item IS marked
  &.marked {
    @include button-variant($info-color); // Solid info color when marked
    // Or an outline info style if preferred:
    // @include button-variant(transparent, $info-color, $info-color, $is-outline: true);
  }

  // --- States (disabled handled by mixin) ---
  // &:disabled {}

  .icon {
    font-size: $font-size-base * 1.1; // Icon size within button
    // vertical-align: middle; // Handled by flex align-items on button
  }
}

// Responsive adjustments (especially for when in fixed bottom bar on mobile)
@media (max-width: calc(map-get($grid-breakpoints, lg) - 1px)) {
 
  .leftControls, .rightControls {
    // Example: Make groups take more space or allow buttons to grow
    flex-grow: 1;
    // justify-content: space-around; // If you want to spread them out more
  }
  .controlButton {
    flex-grow: 1; // Allow buttons to take available space in the bar
    min-width: 0;  // Allow shrinking below defined min-width if necessary
    padding: map-get($spacers, 2) map-get($spacers, 1); // Adjust padding for smaller buttons
    font-size: $font-size-base * 0.85; // Even smaller text on mobile
    gap: map-get($spacers, 1);

    .icon { font-size: $font-size-base; } // Slightly smaller icon too
  }
}
```

---

### components\ExamControls\ExamControls.tsx

```typescript
// src/components/ExamControls/ExamControls.tsx
import React from 'react';
import { useExam } from '../../contexts/ExamContext';
import styles from './ExamControls.module.scss';
import { FaArrowLeft, FaArrowRight, FaBookmark, FaTimes, FaEraser } from 'react-icons/fa'; 

const ExamControls: React.FC = () => {
    const {
        questions,
        currentQuestionIndex,
        userAnswers,
        previousQuestion,
        nextQuestion,
        toggleMarkForReview,
        selectAnswer, // Used for 'Clear Response'
        examStatus
    } = useExam();

    const isExamActive = examStatus === 'active';
    const totalQuestions = questions.length;
    const currentQuestion = questions[currentQuestionIndex];
    const questionNumber = currentQuestion?.question_number; // Get current question number safely

    // Determine button states
    const canGoPrev = currentQuestionIndex > 0;
    const canGoNext = currentQuestionIndex < totalQuestions - 1;

    let isMarked = false;
    let hasAnswer = false;
    if (questionNumber !== undefined && userAnswers[questionNumber]) {
        isMarked = userAnswers[questionNumber].status === 'markedForReview';
        hasAnswer = userAnswers[questionNumber].selectedOption !== null;
    }

    const handleClearResponse = () => {
        if (!isExamActive || questionNumber === undefined) return;
        selectAnswer(questionNumber, null); // Call selectAnswer with null to clear
    };

    const handleMarkForReview = () => {
        if (!isExamActive || questionNumber === undefined) return;
        toggleMarkForReview(questionNumber);
    };

    const handleSaveAndNext = () => {
         // "Save" is implicit as selection updates context state via QuestionDisplay's onChange
         if (!isExamActive || !canGoNext) return;
         nextQuestion();
    }

    return (
        <div className={styles.controlsWrapper}>
            {/* Left Aligned Buttons */}
            <div className={styles.leftControls}>
                <button
                    onClick={previousQuestion}
                    disabled={!canGoPrev || !isExamActive}
                    className={`${styles.controlButton} ${styles.secondary}`}
                    title={
                               !isExamActive ? "Exam not active" :
                               !canGoPrev ? "Already at the first question" :
                               "Previous Question"
                           }
                >
                    <FaArrowLeft className={styles.icon} /> Previous
                </button>

                <button
                    onClick={handleClearResponse}
                    disabled={!hasAnswer || !isExamActive} // Disable if no answer selected
                    className={`${styles.controlButton} ${styles.warning}`}
                    title={
                               !isExamActive ? "Exam not active" :
                               !hasAnswer ? "No answer selected to clear" :
                               "Clear Selection"
                           }
                >
                    <FaEraser className={styles.icon} /> Clear Response
                </button>
            </div>

            {/* Right Aligned Buttons */}
            <div className={styles.rightControls}>
                 <button
                    onClick={handleMarkForReview}
                    disabled={!isExamActive || questionNumber === undefined}
                    className={`${styles.controlButton} ${styles.secondary} ${isMarked ? styles.marked : ''}`}
                    title={
                        !isExamActive ? "Exam not active" :
                        isMarked ? "Unmark Question" : "Mark for Review"
                    }
                >
                    {isMarked ? <FaTimes className={styles.icon} /> : <FaBookmark className={styles.icon} />}
                    {isMarked ? 'Unmark' : 'Mark for Review'}
                </button>

                <button
                     // This button primarily navigates; saving happens on selection change
                    onClick={handleSaveAndNext}
                    disabled={!canGoNext || !isExamActive}
                    className={`${styles.controlButton} ${styles.primary}`}
                    title={
                               !isExamActive ? "Exam not active" :
                               !canGoNext ? "Already at the last question" :
                               "Save Answer & Go to Next Question"
                           }
                >
                    Save & Next <FaArrowRight className={styles.icon} />
                </button>
            </div>
        </div>
    );
};
export default ExamControls;
```

---

## components\ExamTimer


### components\ExamTimer\ExamTimer.module.scss

```scss
// src/components/ExamTimer/ExamTimer.module.scss
@import '../../styles/variables';
@import '../../styles/mixins';

.timerWrapper {
  display: flex;
  align-items: center;
  justify-content: space-between; // Space out label and time
  gap: map-get($spacers, 2); // gap-2 (8px)
  // Padding is handled by parent .timerArea now
  // background-color: $component-bg; // Handled by parent .timerArea
  // border-radius: $border-radius; // Handled by parent .timerArea
  // border: 1px solid $border-color; // Handled by parent .timerArea
  font-size: $font-size-base; // Base font size for the component
  transition: background-color $transition-medium, color $transition-medium, border-color $transition-medium;
  width: 100%; // Take full width of its container
}

.icon {
  color: $primary-color; // Icon matches primary theme
  font-size: $font-size-base * 1.35; // Slightly larger icon (1.35rem)
  flex-shrink: 0;
  margin-right: map-get($spacers, 1); // Add a bit of space after icon
}

.label {
  color: $text-muted; // Muted label text
  font-weight: $font-weight-medium;
  white-space: nowrap;
  font-size: $font-size-base * 0.9; // Slightly smaller label
}

.timeDisplay {
  font-weight: $font-weight-semibold; // Bolder time
  color: $gray-800; // Dark text for time
  font-family: $font-family-monospace; // Keep monospaced font
  font-size: $font-size-base * 1.2; // Larger time digits (1.2rem)
  // min-width: 90px; // Ensure some space, adjust as needed for HH:MM:SS
  text-align: right;
  background-color: $gray-100; // Subtle background for the time itself
  padding: map-get($spacers, 1) map-get($spacers, 2); // py-1 px-2
  border-radius: $border-radius-sm; // Small radius for time background
}

// Low time warning style
.lowTime {
  // Instead of changing the whole wrapper, let's primarily change the time display
  // border-color: $danger-color; // Parent .timerArea could indicate this

  .icon {
    color: $danger-color; // Icon turns red
    // animation: pulseWarning 1.5s infinite ease-in-out; // Optional pulse
  }
  .label {
    color: darken($danger-color, 10%); // Label can also change color
  }
  .timeDisplay {
    color: $white-color; // White text on red background
    background-color: $danger-color; // Time background becomes red
    box-shadow: 0 0 8px rgba($danger-color, 0.5); // Add a glow
  }
}

// Optional keyframes for pulse animation
 @keyframes pulseWarning {
   0%, 100% { transform: scale(1); opacity: 1; }
   50% { transform: scale(1.1); opacity: 0.7; }
 }
```

---

### components\ExamTimer\ExamTimer.tsx

```typescript
// src/components/ExamTimer/ExamTimer.tsx
import React from 'react';
import { useExam } from '../../contexts/ExamContext';
import styles from './ExamTimer.module.scss';
import { FaRegClock } from 'react-icons/fa';

// Helper function to format seconds into HH:MM:SS or MM:SS
const formatTime = (totalSeconds: number | null): string => {
    if (totalSeconds === null || totalSeconds < 0) {
        return '--:--'; // Indicate not applicable or error
    }

    const hours = Math.floor(totalSeconds / 3600);
    const minutes = Math.floor((totalSeconds % 3600) / 60);
    const seconds = totalSeconds % 60;

    const paddedMinutes = String(minutes).padStart(2, '0');
    const paddedSeconds = String(seconds).padStart(2, '0');

    if (hours > 0) {
        const paddedHours = String(hours).padStart(2, '0');
        return `${paddedHours}:${paddedMinutes}:${paddedSeconds}`;
    } else {
        return `${paddedMinutes}:${paddedSeconds}`;
    }
};

const ExamTimer: React.FC = () => {
    const { examSettings, remainingTime, elapsedTime, examStatus } = useExam();

    // --- Safely check if the exam is timed ---
    // Use optional chaining (?.) and nullish coalescing (??)
    const isTimed = (examSettings?.timeLimitMinutes ?? 0) > 0;

    // --- Determine if the timer should turn red ---
    const lowTimeThreshold = 5 * 60; // 5 minutes in seconds
    const isLowTime = isTimed && // Must be a timed test
                       remainingTime !== null &&
                       remainingTime <= lowTimeThreshold;

    let displayTime: string;
    let label: string;

    if (examStatus !== 'active' && examStatus !== 'paused') {
        // Handle states before/after the exam
        if (examStatus === 'finished') {
            label = "Time Taken:";
            displayTime = formatTime(elapsedTime); // Show final elapsed time
        } else {
            // Safely access timeLimitMinutes for initial display
            label = "Time Limit:";
            const initialLimitSeconds = isTimed ? (examSettings?.timeLimitMinutes ?? 0) * 60 : null;
            displayTime = isTimed ? formatTime(initialLimitSeconds) : "No Limit";
        }
    } else if (isTimed) {
        // Exam active AND timed
        label = "Time Remaining:";
        displayTime = formatTime(remainingTime);
    } else {
        // Exam active BUT NOT timed
        label = "Time Elapsed:";
        displayTime = formatTime(elapsedTime);
    }


    return (
        <div className={`${styles.timerWrapper} ${isLowTime ? styles.lowTime : ''}`}>
            <FaRegClock className={styles.icon} />
            <span className={styles.label}>{label}</span>
            <span className={styles.timeDisplay}>{displayTime}</span>
        </div>
    );
};

export default ExamTimer;
```

---

## components\Footer


### components\Footer\Footer.module.scss

```scss
// src/components/Footer/Footer.module.scss
@import '../../styles/variables';
@import '../../styles/mixins';

.footer {
  background-color: $gray-800; // New darker gray background
  color: $gray-300; // Lighter gray text for better contrast on dark bg
  padding: map-get($spacers, 5) 0; // py-5 (32px top/bottom)
  font-size: $font-size-base * 0.9; // Slightly smaller base font for footer
  // margin-top: auto; // Keep this if footer needs to stick to bottom of viewport in flex layout
}

// Uses global .container class for max-width and horizontal padding
.footerContainer {
  display: flex;
  flex-direction: column; // Stack on mobile
  align-items: center;   // Center items on mobile
  text-align: center;    // Center text on mobile

  @include media-breakpoint-up(lg) {
    flex-direction: row; // Side-by-side on medium screens and up
    justify-content: space-between; // Copyright left, nav right
    align-items: center; // Vertically align items
    text-align: left;     // Align copyright text left on larger screens
  }
}

.copyright {
  margin-bottom: map-get($spacers, 3); // mb-3 (16px)
  font-size: $font-size-base * 0.85; // Slightly smaller copyright

  @include media-breakpoint-up(md) {
    margin-bottom: 0; // No bottom margin when side-by-side
  }
}

.footerNav {
  display: flex;
  flex-wrap: wrap; // Allow links to wrap on smaller screens
  justify-content: center; // Center links on mobile
  align-items: center;
  gap: map-get($spacers, 2) map-get($spacers, 3); // row-gap col-gap (8px 16px)

  @include media-breakpoint-up(md) {
    justify-content: flex-end; // Align links to the right on larger screens
    gap: map-get($spacers, 3); // Consistent gap for desktop
  }
}

.divider {
  // Consider removing dividers for a cleaner look if spacing is sufficient
  // If kept, make it subtle:
  color: $gray-600; // Darker subtle divider
  display: none; // Hide by default on mobile

  @include media-breakpoint-up(sm) { // Show on sm and up if desired
    display: inline;
  }
  @include media-breakpoint-up(md) {
    margin: 0 map-get($spacers, 1); // Add small margin around divider on desktop
  }
}

.footerLink {
  color: $gray-300; // Match footer text color
  text-decoration: none;
  transition: color $transition-fast;
  // padding: map-get($spacers, 1); // Smaller padding if dividers are used

  &:hover,
  &:focus { // Combine hover and focus for visual consistency
    color: $white-color; // Brighten link color on hover/focus
    text-decoration: underline; // Underline on hover/focus for clarity
  }
  @include focus-outline($white-color, 1px, 1px, solid, 0.7); // Focus outline for accessibility

  // Ensure visited link style is consistent if needed, though less critical for footer
  &:visited {
    color: $gray-300;
    &:hover,
    &:focus {
      color: $white-color;
    }
  }
}
```

---

### components\Footer\Footer.tsx

```typescript
import React from 'react';
import { Link } from 'react-router-dom';
import styles from './Footer.module.scss';

const Footer: React.FC = () => {
  const currentYear = new Date().getFullYear();
  
  return (
    <footer className={styles.footer}>
      <div className={`container ${styles.footerContainer}`}>
        <p className={styles.copyright}>
          © {currentYear} Samkarya | Examify Platform. All Rights Reserved.
        </p>
        
        <nav className={styles.footerNav}>
          <Link to="/about" className={styles.footerLink}>About Us</Link>
          <span className={styles.divider}>|</span>
          <Link to="/contact" className={styles.footerLink}>Contact</Link>
          <span className={styles.divider}>|</span>
          <Link to="/terms-of-service" className={styles.footerLink}>Terms of Service</Link>
          <span className={styles.divider}>|</span>
          <Link to="/privacy-policy" className={styles.footerLink}>Privacy Policy</Link>
          <span className={styles.divider}>|</span>
          <Link to="/blog" className={styles.footerLink}>Blog</Link>
        </nav>
      </div>
    </footer>
  );
};

export default Footer;
```

---

## components\Header


### components\Header\Header.module.scss

```scss
// src/components/Header/Header.module.scss
@import '../../styles/variables';
@import '../../styles/mixins';

.header {
  background-color: $component-bg; // $white-color
  padding: map-get($spacers, 2) 0; // py-2 (8px top/bottom)
  border-bottom: $border-width solid $gray-200; // Use new border color
  box-shadow: $box-shadow-sm; // Use new subtle shadow
  position: sticky;
  top: 0;
  z-index: $zindex-sticky;
  width: 100%;
}

.container { // Inherits global .container for padding and max-width
  display: flex;
  justify-content: space-between;
  align-items: center;
  position: relative; // For mobile menu context
}

.logo {
  font-size: $h4-font-size; // Approx 20px
  font-weight: $font-weight-bold; // Bolder logo
  color: $primary-color;
  text-decoration: none;
  transition: color $transition-fast;

  &:hover {
    text-decoration: none;
    color: darken($primary-color, 10%);
  }
}

.beta {
  font-size: $font-size-base * 0.65; // Slightly smaller
  color: $text-muted;
  font-weight: $font-weight-normal; // Normal weight
  vertical-align: super;
  margin-left: map-get($spacers, 1); // 4px
  background-color: $gray-100; // Subtle background for beta tag
  padding: 2px 4px;
  border-radius: $border-radius-sm;
}

/* Mobile Menu Button */
.menuButton {
  display: block; // Will be hidden by media query for larger screens
  background: none;
  border: none;
  font-size: $h3-font-size * 0.9; // Icon size relative to h3
  color: $gray-700; // Slightly darker gray for better visibility
  cursor: pointer;
  padding: map-get($spacers, 2); // 8px padding
  line-height: 1;
  z-index: $zindex-modal + 1; // Ensure it's above mobile nav content
  transition: color $transition-fast, transform 0.2s ease-out;

  &:hover {
    color: $primary-color;
    transform: scale(1.1);
  }
  @include focus-outline($primary-color); // Uses new focus mixin

  @media (min-width: map-get($grid-breakpoints, lg)) { // Using 'lg' (992px) breakpoint
    display: none;
  }
}

/* Navigation */
.nav {
  display: flex;
  gap: map-get($spacers, 4); // 24px gap for desktop nav items
  align-items: center;

  @media (max-width: calc(map-get($grid-breakpoints, lg) - 1px)) { // Max width lg-1
    // Mobile navigation styles
    display: none; // Hidden by default, shown by .navMobileOpen
    &.navMobileOpen {
      display: flex;
      flex-direction: column;
      position: fixed;
      top: 0;
      left: 0;
      width: 80%; // Or a fixed width like 280px
      max-width: 300px;
      height: 100vh;
      background-color: $component-bg; // White background
      padding: map-get($spacers, 6) map-get($spacers, 4) map-get($spacers, 4); // Generous padding
      box-shadow: $box-shadow-lg; // More prominent shadow for mobile nav
      z-index: $zindex-modal; // Below menu button but above overlay
      transform: translateX(0);
      transition: transform 0.3s ease-in-out;
      overflow-y: auto;
      gap: 0; // Reset gap for vertical list
    }
    // Slide-out animation for hidden state
    &:not(.navMobileOpen) {
      transform: translateX(-105%);
      transition: transform 0.3s ease-in-out;
      pointer-events: none; // Important for elements off-screen
    }
  }
}

.navLink {
  color: $gray-700; // Use darker gray for text
  text-decoration: none;
  font-weight: $font-weight-medium;
  transition: color $transition-fast, border-color $transition-fast;
  padding: map-get($spacers, 2) 0; // py-2 for desktop
  position: relative; // For underline pseudo-element

  // Underline effect for desktop
  &::after {
    content: '';
    position: absolute;
    bottom: -2px; // Position underline slightly below text
    left: 0;
    width: 100%;
    height: 2px;
    background-color: $primary-color;
    transform: scaleX(0);
    transform-origin: center; // Underline grows from center
    transition: transform 0.25s ease-out;
  }

  &:hover,
  &.active { // .active class for current page
    color: $primary-color;
    text-decoration: none;
    &::after {
      transform: scaleX(1);
    }
  }
  @include focus-outline($primary-color, 1px); // Offset a bit for underline

  // Mobile-specific nav link styles
  @media (max-width: calc(map-get($grid-breakpoints, lg) - 1px)) {
    font-size: $font-size-base * 1.1; // Larger font for mobile
    padding: map-get($spacers, 3) map-get($spacers, 2); // py-3 px-2 for mobile
    border-bottom: 1px solid $gray-100; // Lighter separator
    width: 100%;
    display: flex; // For icon alignment if added later
    align-items: center;
    gap: map-get($spacers, 2);

    &::after { display: none; } // No underline effect on mobile

    &:hover,
    &.active {
      background-color: $gray-50; // Subtle background on hover/active
      color: $primary-color;
    }
    &:last-child {
      border-bottom: none;
    }
  }
}

/* Mobile-only buttons (that look like nav links) and auth actions in nav menu */
.mobileNavButton, // For buttons styled as nav links
.mobileOnlyActions {
  @media (min-width: map-get($grid-breakpoints, lg)) {
    display: none !important; // Ensure it's hidden on desktop
  }
}
.mobileNavButton { // Used for logout/login/register within mobile nav
  @extend .navLink; // Inherit navLink mobile styles
  background: none;
  border: none;
  cursor: pointer;
  text-align: left;
  width: 100%; // Full width like other links
}

.mobileOnlyActions {
  // Container for mobile-specific action links/buttons
  @media (max-width: calc(map-get($grid-breakpoints, lg) - 1px)) {
    display: flex;
    flex-direction: column;
    margin-top: map-get($spacers, 4); // Space above action group
    border-top: 1px solid $gray-200; // Separator line
    padding-top: map-get($spacers, 4); // Space below separator
    gap: 0; // Links will handle their own padding/border
  }
}

/* Desktop User Actions */
.userActions {
  display: flex;
  align-items: center;
  gap: map-get($spacers, 2); // 8px gap between action items

  @media (max-width: calc(map-get($grid-breakpoints, lg) - 1px)) {
    display: none; // Hide on mobile (actions are in .mobileOnlyActions)
  }
}

.username { // For "Profile" link text on desktop
  margin-left: map-get($spacers, 1);
  display: none; // Hidden by default, shown on larger breakpoints if needed

  @media (min-width: map-get($grid-breakpoints, md)) { // Show username from md upwards
    display: inline;
  }
}

// --- Revised Auth Button Styles ---
.authButton { // Base for desktop user action buttons (Profile link, Login, Register, Logout)
  // This will be extended by specific button types
  font-size: $font-size-base * 0.9;
  padding: map-get($spacers, 1) map-get($spacers, 2); // py-1 px-2 (4px 8px)
  display: inline-flex;
  align-items: center;
  gap: map-get($spacers, 1); // 4px gap for icon + text

  // Profile link styled as a subtle button
  &.profileLink {
    @include button-text-variant($gray-700, rgba($gray-700, 0.05), $primary-color);
    svg { font-size: $font-size-base * 1.25; } // Larger icon for profile
  }

  // Login button - Outline style
  &.login {
    @include button-variant(
      transparent,      // bg
      $gray-300,       // border
      $gray-700,       // text
      $gray-50,        // hover-bg
      $gray-400,       // hover-border
      $gray-800,       // hover-text
      $gray-100,       // active-bg
      $gray-500,       // active-border
      0.65,
      true              // is-outline
    );
  }

  // Register button - Solid primary style
  &.register {
    @include button-variant($primary-color, $primary-color, $white-color);
    // Optional: Add a bit more emphasis
    // box-shadow: $box-shadow-sm;
    // &:hover { box-shadow: $box-shadow-md; }
  }

  // Logout button - Subtle text style
  &.logout {
    @include button-text-variant($gray-500, rgba($danger-color, 0.08), $danger-color);
    svg { font-size: $font-size-base * 1.1; }
  }
}
// --- End Revised Auth Button Styles ---


.icon { // General icon styling if used inside .navLink or .authButton for mobile
  margin-right: map-get($spacers, 2); // Consistent spacing for icons in mobile nav
  // The authButton class itself now uses gap, so this might be less needed unless directly inside .navLink
}

/* Mobile Menu Overlay */
.menuOverlay {
  display: none;
  position: fixed;
  top: 0;
  left: 0;
  width: 100vw;
  height: 100vh;
  background-color: rgba($black-color, 0.4); // Slightly less dark overlay
  z-index: $zindex-modal - 1; // Below nav, above content
  opacity: 0;
  transition: opacity 0.3s ease-in-out;
  backdrop-filter: blur(2px); // Optional: blur background

  &.overlayVisible {
    display: block;
    opacity: 1;
  }

  @media (min-width: map-get($grid-breakpoints, lg)) {
    display: none !important; // Never show overlay on desktop
  }
}
```

---

### components\Header\Header.tsx

```typescript
import React, { useState } from 'react'; 
import { useAuth } from '../../contexts/AuthContext';
import styles from './Header.module.scss';
import { FaUserCircle, FaSignOutAlt, FaSignInAlt, FaUserPlus, FaBars } from 'react-icons/fa';
import { IconBaseProps } from 'react-icons';
import { Link } from 'react-router-dom';
import { toast } from 'react-toastify';

const Header: React.FC = () => {
  const { currentUser, logout, openLoginModal, openRegistrationModal } = useAuth();
  const [isMenuOpen, setIsMenuOpen] = useState(false);
  
  const toggleMenu = () => setIsMenuOpen(!isMenuOpen);

  const handleLogout = async () => {
    try {
      await logout();
      window.location.replace('https://bcaexamprep.web.app/');
    } catch (error) {
      toast.error("Logout failed. Please try again.");
    }
  };

  const handleLoginClick = () => {
    openLoginModal("Please log in to continue.");
  };

  const handleRegisterClick = () => {
    openRegistrationModal();
  };

  // Close menu when clicking a nav link (mobile UX improvement)
  const handleNavLinkClick = () => {
    if (isMenuOpen) {
      setIsMenuOpen(false);
    }
  };

  // Type-safe wrapper for icons
  const Icon = (IconComponent: React.ComponentType<IconBaseProps>, props: IconBaseProps) => {
    return <IconComponent {...props} />;
  };

  return (
    <header className={styles.header}>
      <div className={`${styles.container} container`}>
        <Link to="/" className={styles.logo}>
          Examify <span className={styles.beta}>Beta</span>
        </Link>
        
        {/* Mobile Menu Button */}
        <button 
          className={styles.menuButton} 
          onClick={toggleMenu}
          aria-expanded={isMenuOpen}
          aria-label="Toggle navigation menu"
        >
          {Icon(FaBars, { size: 24 })}
        </button>

        {/* Navigation Menu - with conditional classes for mobile */}
        <nav className={`${styles.nav} ${isMenuOpen ? styles.navMobileOpen : ''}`}>
          <Link to="/select-exam" className={styles.navLink} onClick={handleNavLinkClick}>Practice</Link>
          <Link to="/blog" className={styles.navLink} onClick={handleNavLinkClick}>Blog</Link>
          <Link to="/group-exam/dashboard" className={styles.navLink} title="My Hosted Sessions">Hosted Sessions</Link>
          {/* Show these items only in mobile menu */}
          <div className={styles.mobileOnlyActions}>
            {currentUser ? (
              <>
                <Link to="/profile" className={styles.navLink} onClick={handleNavLinkClick}>
                  {Icon(FaUserCircle, { size: 20, className: styles.icon })}
                  Profile
                </Link>
                
                <button onClick={handleLogout} className={`${styles.navLink} ${styles.mobileNavButton}`}>
                  {Icon(FaSignOutAlt, { size: 20, className: styles.icon })}
                  Logout
                </button>
              </>
            ) : (
              <>
                <button
                  onClick={handleLoginClick}
                  className={`${styles.navLink} ${styles.mobileNavButton}`}
                >
                  {Icon(FaSignInAlt, { size: 20, className: styles.icon })}
                  Login
                </button>
                <button
                  onClick={handleRegisterClick}
                  className={`${styles.navLink} ${styles.mobileNavButton}`}
                >
                  {Icon(FaUserPlus, { size: 20, className: styles.icon })}
                  Register
                </button>
              </>
            )}
          </div>
        </nav>

        {/* Desktop User Actions - visible only on desktop */}
        <div className={styles.userActions}>
          {currentUser ? (
            <>
              <Link to="/profile" className={styles.navLink} title="Profile & History">
                {Icon(FaUserCircle, { size: 22 })}
                <span className={styles.username}>Profile</span>
              </Link>
              <button onClick={handleLogout} className={styles.authButton} title="Logout">
                {Icon(FaSignOutAlt, { size: 20 })}
              </button>
            </>
          ) : (
            <>
              <button
                onClick={handleLoginClick}
                className={`${styles.authButton} ${styles.login}`}
                title="Login"
              >
                {Icon(FaSignInAlt, { size: 20, className: styles.icon })}
                {' Login'}
              </button>

              <button
                onClick={() => { handleRegisterClick(); handleNavLinkClick(); }}
                className={`${styles.authButton} ${styles.register}`}
                title="Register"
              >
                {Icon(FaUserPlus, { size: 20, className: styles.icon })}
                {' Register'}
              </button>
            </>
          )}
        </div>
      </div>
      
      {/* Overlay for mobile menu */}
      <div 
        className={`${styles.menuOverlay} ${isMenuOpen ? styles.overlayVisible : ''}`} 
        onClick={toggleMenu}
        aria-hidden="true"
      />
    </header>
  );
};

export default Header;
```

---

## components\Layout


### components\Layout\Layout.tsx

```typescript
// src/components/Layout/Layout.tsx
import React from 'react';
import { Outlet } from 'react-router-dom'; // Outlet renders the matched child route component
import Header from '../Header/Header';
import Footer from '../Footer/Footer';

const Layout: React.FC = () => {
  return (
    <div>
      <Header />
      <main>
         {/* Render the active page component here */}
        <Outlet />
      </main>
      <Footer />
    </div>
  );
};

export default Layout;
```

---

## components\Leaderboard


### components\Leaderboard\Leaderboard.module.scss

```scss
// src/components/Leaderboard/Leaderboard.module.scss
@import '../../styles/variables';
@import '../../styles/mixins';

.leaderboard {
  margin-top: map-get($spacers, 5); // mt-5 (increased margin)
  background-color: $component-bg; // $white-color
  border: 1px solid $gray-200; // Lighter border
  border-radius: $border-radius-lg; // 8px
  padding: map-get($spacers, 4) map-get($spacers, 5); // p-4 px-5
  box-shadow: $box-shadow-md; // Softer shadow

  h3 { // Leaderboard Title
    margin-top: 0;
    margin-bottom: map-get($spacers, 4); // mb-4
    font-size: $h4-font-size; // H4 size
    font-weight: $font-weight-semibold; // Bolder
    color: $primary-color; // Primary color for title
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: map-get($spacers, 2); // gap-2
    border-bottom: 1px solid $gray-200; // Lighter separator
    padding-bottom: map-get($spacers, 3); // pb-3
  }
}

// --- States: Loading, Error, Empty ---
.loadingState, .errorState, .emptyStateContainer { // Common container style for these states
  text-align: center;
  padding: map-get($spacers, 6) map-get($spacers, 3); // py-6 px-3
  color: $text-muted;
  border-radius: $border-radius; // Add radius if it's a distinct box
}

.loadingState { // Spinner + text
  font-style: normal;
  display: flex;
  align-items: center;
  justify-content: center;
  gap: map-get($spacers, 2);
  font-size: $font-size-base;
}

.errorState { // Error message
  color: $danger-color;
  font-weight: $font-weight-medium;
  font-size: $font-size-base;
  // Could use the ErrorMessage component's styling here too
  background-color: lighten($danger-color, 52%);
  border: 1px solid lighten($danger-color, 35%);
}

// Empty state styling (reusing from other components for consistency)
.emptyStateContainer {
  border: 1px dashed $gray-300;
  background-color: $gray-50;
  margin: map-get($spacers, 3) 0;
}
.emptyStateIcon {
  color: $primary-color;
  margin-bottom: map-get($spacers, 3);
  opacity: 0.6;
}
.emptyStateText {
  font-size: $font-size-base * 1.05;
  font-weight: $font-weight-medium;
  margin-bottom: map-get($spacers, 2);
  color: $gray-700;
}
.emptyStateSubtext {
  font-size: $font-size-base * 0.9;
  margin-bottom: 0;
  color: $gray-600;
}
// --- End States ---

.tableContainer {
  overflow-x: auto;
  // Optional: Add a subtle border if table is directly on card background
  // border: 1px solid $gray-200;
  // border-radius: $border-radius-sm;
}

table {
  width: 100%;
  border-collapse: separate; // Allows border-spacing and rounded corners on table
  border-spacing: 0;
  font-size: $font-size-base * 0.95; // Slightly larger base font for table

  th, td {
    padding: map-get($spacers, 3) map-get($spacers, 3); // p-3 for cells (16px)
    text-align: left;
    border-bottom: 1px solid $gray-200; // Lighter row separator
    vertical-align: middle;
  }

  th {
    font-weight: $font-weight-semibold; // Bolder header
    font-size: $font-size-base * 0.85; // Smaller header text
    color: $gray-600; // Muted header text
    background-color: $gray-50; // Very light gray for header row
    white-space: nowrap;
    position: relative; // For sort icon positioning
    // text-transform: uppercase; // Optional: if you prefer uppercase headers

    // Remove top border for first th row if tableContainer has a border
    &:first-child { border-top-left-radius: $border-radius-sm; } // If tableContainer has border
    &:last-child { border-top-right-radius: $border-radius-sm; }
  }

  th.sortableHeader { // Class applied in TSX if header is sortable
    cursor: pointer;
    user-select: none;
    transition: background-color $transition-fast, color $transition-fast;

    &:hover {
      background-color: $gray-100; // Subtle hover on header
      color: $gray-700;
    }
  }

  th.numericHeader { // Class for right-aligning numeric data headers
    text-align: right;
    padding-right: map-get($spacers, 4); // More padding for numeric columns
  }
}

// Sorting Icons
.sortIconDimmed, .sortIconActive {
  margin-left: map-get($spacers, 1); // ml-1
  vertical-align: middle;
  font-size: $font-size-base * 0.9; // Smaller icon
  transition: color $transition-fast, opacity $transition-fast;
}
.sortIconDimmed {
  color: $gray-400; // More visible than very faint
  opacity: 0.6;
}
.sortIconActive {
  color: $primary-color; // Active sort icon in primary color
}

tbody tr {
  transition: background-color $transition-fast;
  &:last-child td {
    border-bottom: none; // No border on the last row of the table
  }
  &:hover {
    background-color: $gray-50; // Very subtle row hover
  }

  &.currentUser { // Highlight for the current user's row
    background-color: lighten($primary-color, 58%); // Very light primary tint
    font-weight: $font-weight-semibold; // Bolder text for current user

    td:first-child { // Rank cell for current user
      color: $primary-color; // Primary color for rank number
    }
  }
}

td {
  color: $gray-700; // Standard text color for cells

  // Column-specific styling
  &:nth-child(1) { // Rank column (usually 1st)
    text-align: center;
    font-weight: $font-weight-bold; // Bold rank numbers
    min-width: 70px; // Ensure space for rank + icon
    color: $gray-600; // Default rank color
    padding-left: map-get($spacers, 2); // Less padding on left for centered rank
    padding-right: map-get($spacers, 2);
  }
  &:nth-child(2) { // Participant column (Name)
    display: flex;
    align-items: center;
    gap: map-get($spacers, 2); // gap-2 (8px)
    font-weight: $font-weight-medium; // Medium weight for names
  }
  &:nth-child(3), // Score column
  &:nth-child(4) { // Time Taken column (assuming they are numeric)
    text-align: right;
    font-family: $font-family-monospace;
    white-space: nowrap;
    color: $gray-800; // Darker text for numeric data
  }
}

.userIcon { // Icon next to participant name
  color: $gray-400; // Muted user icon
  font-size: $font-size-base * 1.3;
  flex-shrink: 0;
}

// Rank Icons (Trophy, Medal)
.rankIcon { // Base for rank icons
  font-size: $font-size-base * 1.1; // Adjust size as needed
  margin-right: map-get($spacers, 1); // Space between icon and number if shown
  vertical-align: middle;

  &.gold { color: #ffd700; } // Gold
  &.silver { color: #c0c0c0; } // Silver
  &.bronze { color: #cd7f32; } // Bronze
}
.rankNumber { // Actual rank number next to icon or by itself
  display: inline-block;
  // If icon present, number might be smaller or styled differently
}
.rankNumberHiddenMobile { // For desktop-only rank number if icon replaces it on mobile
  @include media-breakpoint-up(md) {
    display: inline-block;
    margin-left: map-get($spacers, 1);
  }
  display: none;
}

// Responsive Table - "Card" view on mobile
@media (max-width: calc(map-get($grid-breakpoints, md) - 1px)) {
  .tableContainer { border: none; border-radius: 0; } // No border on container for mobile
  table {
    border: none; // No table border
    thead { display: none; } // Hide table headers

    tr {
      display: block;
      margin-bottom: map-get($spacers, 3); // mb-3
      border: 1px solid $gray-200; // Card border
      border-radius: $border-radius; // Card radius (6px)
      padding: map-get($spacers, 3); // p-3
      background-color: $white-color; // Ensure card background
      box-shadow: $box-shadow-sm; // Add shadow to cards

      &.currentUser { // Current user card on mobile
        border-left: 4px solid $primary-color; // Accent left border
        background-color: lighten($primary-color, 59%);
      }
    }

    td {
      display: block;
      text-align: right; // Value on the right
      padding: map-get($spacers, 2) 0; // py-2, no horizontal padding here
      border-bottom: 1px dotted $gray-100; // Lighter dotted separator between fields
      font-size: $font-size-base * 0.9;

      &::before { // Data label
        content: attr(data-label);
        float: left; // Label on the left
        font-weight: $font-weight-semibold; // Bolder label
        margin-right: map-get($spacers, 2);
        // text-transform: uppercase; // No uppercase for softer look
        font-size: $font-size-base * 0.8;
        color: $text-muted;
        min-width: 90px; // Ensure label has space
        text-align: left;
      }

      &:last-child { border-bottom: none; padding-bottom: 0; }

      // Reset specific desktop styles for mobile card view
      &:nth-child(1) { text-align: right; min-width: auto; } // Rank value right
      &:nth-child(2) { display: block; .userIcon { display: inline-block; margin-right: map-get($spacers,1); } } // Name right, icon inline
      &:nth-child(3), &:nth-child(4) { font-family: $font-family-base; } // Use base font for score/time
    }
    // Ensure current user details are bold in card view too
    // &.currentUser td { font-weight: $font-weight-semibold; } // Redundant if already set on tr.currentUser
  }
  .rankNumberHiddenMobile { display: none !important; }
}

// Spinner class (reused from global App.scss)
// .spin-icon { ... }
```

---

### components\Leaderboard\Leaderboard.tsx

```typescript
// src/components/Leaderboard/Leaderboard.tsx
import React, { useState, useEffect, useMemo, useCallback } from 'react';
import styles from './Leaderboard.module.scss'; // Create this SCSS file next
import { getGroupExamParticipants } from '../../services/firestoreService';
import { ParticipantData } from '../../types';
import { FaMedal, FaTrophy, FaUserCircle, FaSort, FaSortUp, FaSortDown, FaUsersSlash } from 'react-icons/fa';
import { useAuth } from '../../contexts/AuthContext'; // To potentially highlight current user
import { formatDuration } from '../../utils/formatters'; // Added formatter import
import Spinner from '../Spinner/Spinner';

interface LeaderboardProps {
    sessionId: string;
}

// Extend ParticipantData to include timeTakenSeconds
interface ExtendedParticipantData extends ParticipantData {
    id: string; // Participant's UID
    timeTakenSeconds?: number; // Make this optional since it might not exist
}

// Define a type for processed participant data with rank
interface RankedParticipant extends ExtendedParticipantData {
    rank: number;
}

// Add sortable keys type
type SortableColumn = 'rank' | 'displayName' | 'score' | 'timeTakenSeconds';
type SortDirection = 'asc' | 'desc';

interface SortConfig {
    key: SortableColumn;
    direction: SortDirection;
}

const Leaderboard: React.FC<LeaderboardProps> = ({ sessionId }) => {
    const { currentUser } = useAuth();
    const [participants, setParticipants] = useState<ExtendedParticipantData[]>([]);
    const [isLoading, setIsLoading] = useState(true);
    const [error, setError] = useState<string | null>(null);
    
    // --- NEW State for Sorting ---
    const [sortConfig, setSortConfig] = useState<SortConfig>({ key: 'rank', direction: 'asc' }); // Default sort by rank ascending

    useEffect(() => {
        let isMounted = true;
        const fetchParticipants = async () => {
            if (!sessionId) return;
            setIsLoading(true);
            setError(null);
            try {
                const fetchedData = await getGroupExamParticipants(sessionId);
                if (isMounted) {
                    // Calculate timeTakenSeconds for each participant that has completed
                    const extendedData = fetchedData.map(p => {
                        const participantWithTime: ExtendedParticipantData = { ...p };
                        // Calculate time taken only if we have both timestamps
                        if (p.completionTimestamp && p.startedAt) {
                            const endTime = p.completionTimestamp.toDate().getTime();
                            const startTime = p.startedAt.toDate().getTime();
                            participantWithTime.timeTakenSeconds = (endTime - startTime) / 1000;
                        }
                        return participantWithTime;
                    });
                    setParticipants(extendedData);
                }
            } catch (err: any) {
                if (isMounted) {
                    setError(err.message || "Could not load leaderboard data.");
                    //console.error("Leaderboard fetch error:", err);
                }
            } finally {
                if (isMounted) setIsLoading(false);
            }
        };

        fetchParticipants();
        return () => { isMounted = false; }; // Cleanup
    }, [sessionId]); // Fetch when sessionId changes

    // --- UPDATED Processing and Sorting ---
    const rankedAndSortedParticipants = useMemo(() => {
        // Filter only completed participants with a valid score
        const completed = participants.filter(p =>
            p.status === 'completed' && typeof p.score === 'number'
        );

        // Initial sort for ranking (Score DESC, Time ASC) - needed to assign correct ranks
        completed.sort((a, b) => {
            if (b.score! !== a.score!) { 
                return b.score! - a.score!; 
            }
            // Tie-breaker using timeTakenSeconds if available
            const timeA = typeof a.timeTakenSeconds === 'number' ? a.timeTakenSeconds : Infinity;
            const timeB = typeof b.timeTakenSeconds === 'number' ? b.timeTakenSeconds : Infinity;
            if (timeA !== timeB) { 
                return timeA - timeB; 
            }
            // Further tie-breaker: earlier completion time is better
            const compA = a.completionTimestamp?.toDate()?.getTime() ?? Infinity;
            const compB = b.completionTimestamp?.toDate()?.getTime() ?? Infinity;
            return compA - compB;
        });

        // Assign Ranks (handle ties correctly - same score = same rank)
        let currentRank = 0;
        let lastScore = -Infinity; // Start lower than any possible score
        let participantsAtRank = 0; // How many tied at the *previous* rank
        let ranked = completed.map((p) => {
            if (p.score !== lastScore) {
                currentRank += (participantsAtRank + 1); // Jump rank by number of previous ties + 1
                lastScore = p.score!;
                participantsAtRank = 0; // Reset tie counter
            } else {
                participantsAtRank++; // Increment tie counter
            }

            return {
                ...p,
                rank: currentRank
            } as RankedParticipant;
        });

        // --- Apply Secondary Sort based on sortConfig state ---
        ranked.sort((a, b) => {
            let aValue: string | number | undefined;
            let bValue: string | number | undefined;

            // Handle different keys
            switch (sortConfig.key) {
                case 'displayName':
                    // Case-insensitive string sort for names
                    aValue = a.displayName?.toLowerCase() || '';
                    bValue = b.displayName?.toLowerCase() || '';
                    break;
                case 'timeTakenSeconds':
                    // Use Infinity for undefined/null to sort them last/first depending on direction
                    aValue = typeof a.timeTakenSeconds === 'number' ? a.timeTakenSeconds : (sortConfig.direction === 'asc' ? Infinity : -Infinity);
                    bValue = typeof b.timeTakenSeconds === 'number' ? b.timeTakenSeconds : (sortConfig.direction === 'asc' ? Infinity : -Infinity);
                    break;
                case 'score':
                    // Already number or nullish
                    aValue = a.score ?? (sortConfig.direction === 'asc' ? -Infinity : Infinity);
                    bValue = b.score ?? (sortConfig.direction === 'asc' ? -Infinity : Infinity);
                    break;
                case 'rank':
                default:
                    // Already number
                    aValue = a.rank;
                    bValue = b.rank;
                    break;
            }

            // Safe comparison that handles undefined/null
            if (aValue === undefined || bValue === undefined) {
                return 0;
            }
            
            // Comparison logic
            if (aValue < bValue) {
                return sortConfig.direction === 'asc' ? -1 : 1;
            }
            if (aValue > bValue) {
                return sortConfig.direction === 'asc' ? 1 : -1;
            }
            // If values are equal, maintain original relative order
            return 0;
        });

        return ranked;
    }, [participants, sortConfig]); // Re-run when participants OR sortConfig changes

    // --- NEW Sorting Request Handler ---
    const requestSort = useCallback((key: SortableColumn) => {
        let direction: SortDirection = 'asc';
        // If clicking the same key, toggle direction
        if (sortConfig.key === key && sortConfig.direction === 'asc') {
            direction = 'desc';
        }
        // Reset to ascending if clicking a new column
        // Or if clicking same key that was descending (toggles back to asc)
        setSortConfig({ key, direction });
    }, [sortConfig]); // Dependency on current sortConfig

    // --- Helper to get Sort Icon ---
    const getSortIcon = (columnKey: SortableColumn) => {
        if (sortConfig.key !== columnKey) {
            return <FaSort className={styles.sortIconDimmed}/>; // Default icon for non-active columns
        }
        return sortConfig.direction === 'asc'
            ? <FaSortUp className={styles.sortIconActive}/>
            : <FaSortDown className={styles.sortIconActive}/>;
    };

    // Render Logic
    if (isLoading) {
        return (
            <div className={styles.loadingState}>
                 <Spinner text="Loading Leaderboard..." size={20} />
            </div>
        );
    }

    if (error) {
        return <div className={styles.errorState}>Error: {error}</div>;
    }

    if (rankedAndSortedParticipants.length === 0) {
        return (
           <div className={`${styles.emptyStateContainer}`}>
               <FaUsersSlash size={36} className={styles.emptyStateIcon}/> {/* Or your preferred icon */}
               <p className={styles.emptyStateText}>Leaderboard Still Brewing!</p>
               <p className={styles.emptyStateSubtext}>No participants have completed the session yet, or results might be hidden until the session ends.</p>
           </div>
       );
    }

    return (
        <div className={styles.leaderboard}>
            <h3><FaTrophy /> Leaderboard</h3>
            <div className={styles.tableContainer}>
                <table>
                    <thead>
                        <tr>
                            <th onClick={() => requestSort('rank')} className={styles.sortableHeader}>
                                Rank {getSortIcon('rank')}
                            </th>
                            <th onClick={() => requestSort('displayName')} className={styles.sortableHeader}>
                                Participant {getSortIcon('displayName')}
                            </th>
                            <th onClick={() => requestSort('score')} className={`${styles.sortableHeader} ${styles.numericHeader}`}>
                                Score {getSortIcon('score')}
                            </th>
                            <th onClick={() => requestSort('timeTakenSeconds')} className={`${styles.sortableHeader} ${styles.numericHeader}`}>
                                Time Taken {getSortIcon('timeTakenSeconds')}
                            </th>
                        </tr>
                    </thead>
                    <tbody>
                        {rankedAndSortedParticipants.map((p) => (
                            <tr key={p.id} className={`${p.id === currentUser?.uid ? styles.currentUser : ''} ${p.rank <= 3 ? styles.topRank : ''}`}>
                                <td data-label="Rank">
                                    {p.rank === 1 && <FaTrophy className={`${styles.rankIcon} ${styles.gold}`} title="1st Place"/>}
                                    {p.rank === 2 && <FaMedal className={`${styles.rankIcon} ${styles.silver}`} title="2nd Place"/>}
                                    {p.rank === 3 && <FaMedal className={`${styles.rankIcon} ${styles.bronze}`} title="3rd Place"/>}
                                    {p.rank > 3 && <span className={styles.rankNumber}>{p.rank}</span>}
                                    {(p.rank === 1 || p.rank === 2 || p.rank === 3) && <span className={styles.rankNumberHiddenMobile}>{p.rank}</span> /* Show number beside icon on desktop */}
                                </td>
                                <td data-label="Participant">
                                    <FaUserCircle className={styles.userIcon} />
                                    {p.displayName || `User...${p.id.substring(p.id.length - 6)}`}
                                    {p.id === currentUser?.uid && ' (You)'}
                                </td>
                                <td data-label="Score">
                                    {p.score?.toFixed(1)} / {p.maxScore?.toFixed(1)}
                                    {/* Optional: Add Percentage */}
                                    {p.maxScore && p.score !== undefined && ` (${((p.score / p.maxScore) * 100).toFixed(1)}%)`}
                                </td>
                                <td data-label="Time Taken">
                                    {typeof p.timeTakenSeconds === 'number' 
                                        ? formatDuration(p.timeTakenSeconds)
                                        : '—'}
                                </td>
                            </tr>
                        ))}
                    </tbody>
                </table>
            </div>
        </div>
    );
};

export default Leaderboard;
```

---

## components\MarkdownRenderer


### components\MarkdownRenderer\MarkdownRenderer.tsx

```typescript
// src/components/MarkdownRenderer/MarkdownRenderer.tsx
import React, { useEffect, useState } from 'react'; // <-- Import React
import ReactMarkdown from 'react-markdown'; // <-- Import Options if needed elsewhere, otherwise remove
import remarkMath from 'remark-math';
import rehypeKatex from 'rehype-katex';
import { Prism as SyntaxHighlighter } from 'react-syntax-highlighter';
import { coy } from 'react-syntax-highlighter/dist/esm/styles/prism'; // Or your preferred theme

interface MarkdownRendererProps {
    children: string; // The markdown string to render
}

// --- Helper Component for Rendering Images with Error Handling ---
interface RenderedImageProps {
    src: string;
    alt?: string;
    [key: string]: any; // Allow other img props
}

// Base URL for resolving relative image paths from the questions repo
const GITHUB_QUESTIONS_REPO_RAW_BASE_URL = 'https://raw.githubusercontent.com/Samkarya/online-exam-questions/main/'; // Adjust branch if needed

const RenderedImage: React.FC<RenderedImageProps> = ({ src, alt, ...props }) => {
    const [imageError, setImageError] = useState(false);

    useEffect(() => {
        // Reset error state if the src changes
        setImageError(false);
    }, [src]);

    const handleError = () => {
        // Don't show console errors for expected 404s, maybe just a warning
        //console.warn(`Image failed to load: ${src}`);
        setImageError(true);
    };

    if (imageError || !src) {
        // Render fallback content if image failed to load or src is empty
        return (
            <span style={{
                display: 'inline-block',
                padding: '10px',
                border: '1px dashed #ccc',
                color: '#777',
                fontSize: '0.9em',
                fontStyle: 'italic',
                maxWidth: '100%', // Ensure fallback doesn't overflow
                wordBreak: 'break-word' // Handle long alt text
            }}>
                {alt ? `[Image: ${alt}]` : '[Image not found]'}
            </span>
        );
        // Alternatively, return null to hide it completely:
        // return null;
    }

    // Render the actual image if no error
    return (
        <img
            src={src}
            alt={alt || ''} // Good practice to have alt attribute even if empty
            onError={handleError}
            style={{
                maxWidth: '100%',
                height: 'auto',
                display: 'block', // Consistent block-level display
                margin: '1em auto' // Center images with margin
             }}
            {...props} // Pass down any other props like width, height from markdown
        />
    );
};

const MarkdownRenderer: React.FC<MarkdownRendererProps> = ({ children }) => {

    const transformImageUri = (uri: string): string => {
        if (!uri) return '';
        if (uri.startsWith('https://')) {
            return uri;
        } else if (uri.startsWith('http://')) {
            console.warn('Insecure HTTP image URL blocked:', uri);
            return '';
        } else if (!uri.includes(':')) {
            const cleanedUri = uri.startsWith('/') ? uri.substring(1) : uri;
            return `${GITHUB_QUESTIONS_REPO_RAW_BASE_URL}${cleanedUri}`;
        } else {
             console.warn('Unsupported image URI scheme:', uri);
             return '';
        }
    };

    return (
        <ReactMarkdown
            children={children}
            remarkPlugins={[remarkMath]}
            rehypePlugins={[rehypeKatex]}
            components={{
                // --- Use the new RenderedImage component ---
                img: ({ node, src, alt, ...props }) => {
                    const resolvedSrc = src ? transformImageUri(src) : '';
                    // Use the dedicated component for rendering + error handling
                    return <RenderedImage src={resolvedSrc} alt={alt} {...props} />;
                },
                // --- Code Block Highlighting Updated ---
                code({ node, className, children, ...props }) { // Removed 'inline' from destructuring
                    const match = /language-(\w+)/.exec(className || '');
                    // Condition simplified: if there's a language match, treat as block
                    return match ? (
                        <SyntaxHighlighter
                            children={String(children).replace(/\n$/, '')}
                            style={coy as any} // <-- Added 'as any' to bypass TS error
                            language={match[1]}
                            PreTag="div" // Use div for the wrapper, helps with styling
                            
                        />
                    ) : (
                        // Render inline code or code blocks without a language tag normally
                        <code className={className} {...props}>
                            {children}
                        </code>
                    );
                },
                // Optional: Add styling/handling for other elements like tables, etc.
                // table: ({node, ...props}) => <table style={{ borderCollapse: 'collapse', width: '100%' }} {...props} />,
                // th: ({node, ...props}) => <th style={{ border: '1px solid #ddd', padding: '8px', textAlign: 'left', backgroundColor: '#f2f2f2' }} {...props} />,
                // td: ({node, ...props}) => <td style={{ border: '1px solid #ddd', padding: '8px' }} {...props} />,
            }}
        />
    );
};

export default MarkdownRenderer;
```

---

## components\Modal


### components\Modal\ConfirmationModal.module.scss

```scss
// src/components/Modal/ConfirmationModal.module.scss
@import '../../styles/variables';
@import '../../styles/mixins';

.modalOverlay {
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background-color: rgba($gray-900, 0.5); // Softer overlay
  // backdrop-filter: blur(3px); // Optional: Frosted glass effect
  display: flex;
  justify-content: center;
  align-items: center;
  z-index: $zindex-modal;
  padding: map-get($spacers, 3); // p-3 for spacing around modal on small screens
  opacity: 0; // For fade-in animation
  visibility: hidden; // For animation
  transition: opacity 0.25s ease-out, visibility 0s 0.25s linear;
  overflow-y: auto;

  &.open { // Class to trigger open animation
    opacity: 1;
    visibility: visible;
    transition: opacity 0.25s ease-out, visibility 0s linear;
  }
}

// Keyframes can be in App.scss or here if specific to modals
// If keeping here, ensure no duplication
@keyframes modalFadeIn {
  from { opacity: 0; }
  to { opacity: 1; }
}

@keyframes modalSlideInUp {
  from { transform: translateY(20px) scale(0.98); opacity: 0; }
  to { transform: translateY(0) scale(1); opacity: 1; }
}

.modalContent {
  background-color: $component-bg; // $white-color
  border-radius: $border-radius-xl; // Softer, larger radius (12px)
  box-shadow: $box-shadow-xl;    // More prominent shadow for modals
  width: 100%;
  position: relative;
  display: flex;
  flex-direction: column;
  overflow: hidden; // Important for border-radius on children like header/footer
  max-height: 85vh;
  // Default is medium size
  max-width: 500px;

  &.sizeSM { max-width: 400px; }
  &.sizeMD { max-width: 500px; }
  &.sizeLG { max-width: 700px; } // Use 700px or 800px for large

  // Apply animation when overlay is open
  .modalOverlay.open & {
    animation: modalSlideInUp 0.3s ease-out forwards;
  }
}

.modalHeader {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: map-get($spacers, 3) map-get($spacers, 4); // p-3 px-4
  border-bottom: $border-width solid $gray-200; // Lighter border
  flex-shrink: 0;
}

.modalTitle {
  margin: 0;
  font-size: $h4-font-size; // ~20px
  font-weight: $font-weight-semibold;
  color: $gray-800; // Darker heading color
}

.closeButton {
  background: transparent;
  border: none;
  display: flex;
  align-items: center;
  justify-content: center;
  cursor: pointer;
  color: $gray-400; // Muted color for close icon
  width: 36px;  // Larger tap target
  height: 36px;
  border-radius: 50%;
  transition: background-color $transition-fast, color $transition-fast;
  font-size: $font-size-base * 1.2; // Control icon size here

  &:hover {
    background-color: $gray-100; // Subtle hover background
    color: $gray-700;
  }
  @include focus-outline($primary-color);
}

.modalBody {
  padding: map-get($spacers, 4); // p-4 (24px)
  //max-height: 70vh; // Adjust as needed
  overflow-y: auto;
  color: $text-color; // Ensure body text color is set
  flex-grow: 1;

  .customContentWrapper { // If custom ReactNode content is passed
    p {
      margin-bottom: map-get($spacers, 2);
      line-height: $line-height-base; // Ensure good line height
      &:last-child { margin-bottom: 0; }
    }
    ul, ol {
      margin-bottom: map-get($spacers, 3);
      padding-left: map-get($spacers, 4); // Ensure good list indentation
    }
    strong { font-weight: $font-weight-semibold; }
  }
}

.message { // For simple text message
  margin: 0;
  font-size: $font-size-base;
  line-height: 1.6;
  color: $text-color;
  white-space: pre-wrap; // Respect line breaks
}

.modalFooter {
  display: flex;
  justify-content: flex-end; // Align buttons to the right by default
  gap: map-get($spacers, 2);  // gap-2 (8px)
  padding: map-get($spacers, 3) map-get($spacers, 4); // p-3 px-4
  border-top: $border-width solid $gray-100; // Even lighter border for footer
  background-color: $gray-50; // Subtle background for footer
  flex-shrink: 0;

  .confirmInProgress {
    display: inline-flex;
    align-items: center;
    gap: map-get($spacers, 2);
    svg { vertical-align: middle; }
  }
}

// --- Updated Modal Button Styling ---
.modalButton { // Base for all buttons in modal footer
  padding: map-get($spacers, 2) map-get($spacers, 3); // py-2 px-3
  font-size: $font-size-base * 0.9; // Slightly smaller footer buttons
  min-width: 90px; // Slightly smaller min-width
  font-weight: $font-weight-medium;
}

.cancelButton {
  // Secondary/Outline button: Gray border and text, transparent BG
  @include button-variant(
    transparent,      // bg
    $gray-300,       // border
    $gray-700,       // text
    $gray-100,       // hover-bg
    $gray-400,       // hover-border
    $gray-800,       // hover-text
    $gray-200,       // active-bg
    $gray-500,       // active-border
    0.65,
    true              // is-outline
  );
  @extend .modalButton; // Apply base modal button sizing
}

.primaryButton {
  @include button-variant($primary-color);
  @extend .modalButton;
}

.dangerButton {
  @include button-variant($danger-color);
  @extend .modalButton;
}

.successButton {
  @include button-variant($success-color);
  @extend .modalButton;
}

.warningButton {
  // Warning buttons often need dark text for accessibility on yellow/amber
  @include button-variant($warning-color, $warning-color, $gray-800, darken($warning-color, 8%), darken($warning-color, 10%), $gray-900);
  @extend .modalButton;
}

// Responsive adjustments
@media (max-width: map-get($grid-breakpoints, sm)) {
  .modalContent {
    max-width: 100%;
    margin: map-get($spacers, 3); // Add margin around modal on very small screens
    max-height: calc(100vh - #{map-get($spacers, 3) * 2});
  }
  .modalFooter {
    flex-direction: column-reverse; // Stack buttons vertically on small screens
    .modalButton {
      width: 100%; // Make buttons full width
    }
  }
}
```

---

### components\Modal\ConfirmationModal.tsx

```typescript
// src/components/Modal/ConfirmationModal.tsx
import React, { useEffect, useRef } from 'react';
import { FaTimes } from 'react-icons/fa';
import styles from './ConfirmationModal.module.scss';

interface ConfirmationModalProps {
  isOpen: boolean;
  title: string;
  /** Simple text message (ignored if customContent is provided) */
  message?: string; // Make optional if customContent is primary
  /** React node for more complex content in the modal body */
  customContent?: React.ReactNode; // Renamed for clarity
  onConfirm: () => Promise<void> | void;
  onCancel: () => void;
  confirmText?: string;
  cancelText?: string;
  confirmButtonVariant?: 'primary' | 'danger' | 'success' | 'warning';
  size?: 'sm' | 'md' | 'lg';
  closeOnEsc?: boolean;
  closeOnOutsideClick?: boolean;
  hideCancel?: boolean;
  // Added for spinner integration if needed
}

const ConfirmationModal: React.FC<ConfirmationModalProps> = ({
  isOpen,
  title,
  message,
  customContent,
  onConfirm,
  onCancel,
  confirmText = 'Confirm',
  cancelText = 'Cancel',
  confirmButtonVariant = 'danger',
  size = 'md',
  closeOnEsc = true,
  closeOnOutsideClick = true,
  hideCancel = false,

}) => {
  const modalDialogRef = useRef<HTMLDivElement>(null); // Ref for dialog content
  const modalOverlayRef = useRef<HTMLDivElement>(null); // Ref for the overlay
  const confirmButtonRef = useRef<HTMLButtonElement>(null); // Ref for focus management

  useEffect(() => {
    // Handle animation classes for overlay
    if (modalOverlayRef.current) {
      if (isOpen) {
        modalOverlayRef.current.classList.add(styles.open);
      } else {
        // For smooth exit animation, you might need to delay removal
        // or handle animationend. For simple opacity/visibility, direct removal is okay.
        modalOverlayRef.current.classList.remove(styles.open);
      }
    }
    
    // Handle ESC key
    const handleEscKey = (event: KeyboardEvent) => {
      // Don't close if action is in progress
      if (isOpen && closeOnEsc &&  event.key === 'Escape') {
        onCancel();
      }
    };

    // Handle outside click
    const handleOutsideClick = (event: MouseEvent) => {
      // Don't close if action is in progress
      if (
        isOpen &&
        closeOnOutsideClick &&
        modalDialogRef.current &&
        !modalDialogRef.current.contains(event.target as Node)
      ) {
        onCancel();
      }
    };

    // Focus trap - keep focus within modal when open
    const handleTabKey = (event: KeyboardEvent) => {
      if (isOpen && event.key === 'Tab') {
        // Get all focusable elements in modal
        const focusableElements = modalDialogRef.current?.querySelectorAll(
          'button, [href], input, select, textarea, [tabindex]:not([tabindex="-1"])'
        );
        
        if (focusableElements && focusableElements.length > 0) {
          const firstElement = focusableElements[0] as HTMLElement;
          const lastElement = focusableElements[focusableElements.length - 1] as HTMLElement;
          
          // If shift+tab on first element, move to last element
          if (event.shiftKey && document.activeElement === firstElement) {
            lastElement.focus();
            event.preventDefault();
          } 
          // If tab on last element, move to first element
          else if (!event.shiftKey && document.activeElement === lastElement) {
            firstElement.focus();
            event.preventDefault();
          }
        }
      }
    };

    // Add event listeners
    document.addEventListener('keydown', handleEscKey);
    document.addEventListener('mousedown', handleOutsideClick);
    document.addEventListener('keydown', handleTabKey);
    
    // Focus confirm button (or first button) when modal opens
    if (isOpen && modalDialogRef.current) {
      // Prioritize focusing the confirm button if available
      const buttonToFocus = confirmButtonRef.current || modalDialogRef.current.querySelector('button:not([disabled])') as HTMLElement;
      if (buttonToFocus) setTimeout(() => buttonToFocus.focus(), 50);
    }

    // Prevent scrolling on body when modal is open
    if (isOpen) {
      document.body.style.overflow = 'hidden';
    }

    // Clean up
    return () => {
      document.removeEventListener('keydown', handleEscKey);
      document.removeEventListener('mousedown', handleOutsideClick);
      document.removeEventListener('keydown', handleTabKey);
      // Only reset body overflow if no other modal is potentially open
      if (!document.querySelector(`.${styles.modalOverlay}`)) {
        document.body.style.overflow = '';
      }
    };
    // Added isConfirming to dependencies for ESC/outside click logic
  }, [isOpen, onCancel, closeOnEsc, closeOnOutsideClick]);

  if (!isOpen) return null;

  return (
    <div 
      ref={modalOverlayRef}
      className={styles.modalOverlay}
    >
      <div 
        ref={modalDialogRef}
        className={`${styles.modalContent} ${styles[`size${size.toUpperCase()}`]}`}
        role="dialog"
        aria-modal="true"
        aria-labelledby="modal-title"
        aria-describedby={customContent ? undefined : "modal-message"} // Describe by message only if it exists
      >
        <div className={styles.modalHeader}>
          <h2 id="modal-title" className={styles.modalTitle}>{title}</h2>
          {/* Disable close button during confirm action */}
          <button 
            className={styles.closeButton} 
            onClick={onCancel}
            aria-label="Close modal"
            
          >
            <FaTimes />
          </button>
        </div>
        
        <div className={styles.modalBody}>
          {/* Prioritize customContent if provided */}
          {customContent ? (
            <div className={styles.customContentWrapper}>
              {customContent}
            </div>
          ) : message ? (
            // Render simple message (respects whitespace/newlines)
            <p id="modal-message" className={styles.message}>{message}</p>
          ) : null}
        </div>
        
        <div className={styles.modalFooter}>
          {!hideCancel && (
            // Disable cancel button during confirm action
            <button 
              onClick={onCancel}
              className={`${styles.modalButton} ${styles.cancelButton}`}
             
            >
              {cancelText}
            </button>
          )}
          {/* Updated confirm button with loading state */}
          <button 
            ref={confirmButtonRef}
            onClick={onConfirm}
            className={`${styles.modalButton} ${styles[`${confirmButtonVariant}Button`]}`}
            
          > 
          {confirmText}
          </button>
        </div>
      </div>
    </div>
  );
};

export default ConfirmationModal;
```

---

## components\MonitoringIndicator


### components\MonitoringIndicator\MonitoringIndicator.module.scss

```scss
// src/components/MonitoringIndicator/MonitoringIndicator.module.scss
@import '../../styles/variables';
@import '../../styles/mixins';

.indicator {
  // Position is now set by inline style from component state
  background-color: rgba($gray-800, 0.85); // Darker, more solid background
  color: $white-color;
  padding: map-get($spacers, 1) map-get($spacers, 2);
  border-radius: $border-radius; // Softer radius
  font-size: $font-size-base * 0.75;
  font-weight: $font-weight-medium;
  display: inline-flex;
  align-items: center;
  gap: map-get($spacers, 1);
  z-index: $zindex-tooltip + 5; // Even higher z-index
  box-shadow: $box-shadow-lg; // More prominent shadow to look "above" content
  backdrop-filter: blur(4px);
  transition: background-color $transition-fast, opacity $transition-fast, box-shadow $transition-fast;
  opacity: 0.9;
  cursor: grab; // Indicate it's draggable
  user-select: none; // Prevent text selection during drag

  &:hover {
    opacity: 1;
    box-shadow: $box-shadow-xl;
  }

  &.dragging { // Style while actively being dragged
    cursor: grabbing;
    opacity: 0.75; // Slightly more transparent while dragging
    box-shadow: $box-shadow-md; // Less shadow while moving
  }

  .icon {
    font-size: $font-size-base * 0.9;
  }
  
   &.unfocused {
     background-color: rgba($danger-color, 0.9);
   }
}

```

---

### components\MonitoringIndicator\MonitoringIndicator.tsx

```typescript
// src/components/MonitoringIndicator/MonitoringIndicator.tsx
import React, { useState, useRef, useEffect, CSSProperties } from 'react';
import { FaEye } from 'react-icons/fa';
import styles from './MonitoringIndicator.module.scss';

interface MonitoringIndicatorProps {
    isActive: boolean;
    isPageFocused: boolean;
    initialPosition?: { top?: string; right?: string; bottom?: string; left?: string }; // Optional initial position
}

const DRAG_AREA_CLASS = 'monitoring-indicator-drag-handle'; // Class for the draggable area

const MonitoringIndicator: React.FC<MonitoringIndicatorProps> = ({
    isActive,
    isPageFocused,
    initialPosition = { bottom: 'calc(env(safe-area-inset-bottom, 0px) + 80px)', right: '16px' } // Default initial pos (adjust 80px)
}) => {
    const [position, setPosition] = useState(initialPosition);
    const [isDragging, setIsDragging] = useState(false);
    const indicatorRef = useRef<HTMLDivElement>(null);
    const dragStartPosRef = useRef({ x: 0, y: 0 }); // Mouse position at drag start
    const elementStartPosRef = useRef({ x: 0, y: 0 }); // Element position at drag start

    const handleMouseDown = (e: React.MouseEvent<HTMLDivElement>) => {
        // Only allow dragging if the mousedown is on the indicator itself or a specific handle
        if (indicatorRef.current && (e.target === indicatorRef.current || (e.target as HTMLElement).classList.contains(DRAG_AREA_CLASS))) {
            e.preventDefault(); // Prevent text selection while dragging
            setIsDragging(true);
            dragStartPosRef.current = { x: e.clientX, y: e.clientY };

            const rect = indicatorRef.current.getBoundingClientRect();
            // Calculate initial position relative to viewport, preferring right/bottom
            const currentRight = window.innerWidth - rect.right;
            const currentBottom = window.innerHeight - rect.bottom;

            elementStartPosRef.current = { x: currentRight, y: currentBottom };

            // Add class for dragging styles (e.g., cursor)
            indicatorRef.current.classList.add(styles.dragging);
        }
    };

    useEffect(() => {
        const handleMouseMove = (e: MouseEvent) => {
            if (!isDragging || !indicatorRef.current) return;

            const dx = e.clientX - dragStartPosRef.current.x;
            const dy = e.clientY - dragStartPosRef.current.y;

            // Calculate new right and bottom based on drag
            let newRight = elementStartPosRef.current.x - dx;
            let newBottom = elementStartPosRef.current.y - dy;

            // --- Boundary Checks (important!) ---
            const rect = indicatorRef.current.getBoundingClientRect();
            const parentWidth = window.innerWidth; // Assuming viewport is parent
            const parentHeight = window.innerHeight;

            // Keep within right boundary (newRight >= 0)
            if (newRight < 0) newRight = 0;
            // Keep within left boundary (newRight + rect.width <= parentWidth)
            if (newRight + rect.width > parentWidth) newRight = parentWidth - rect.width;

            // Keep within bottom boundary (newBottom >= 0)
            if (newBottom < 0) newBottom = 0;
            // Keep within top boundary (newBottom + rect.height <= parentHeight)
            if (newBottom + rect.height > parentHeight) newBottom = parentHeight - rect.height;

            setPosition({
                right: `${newRight}px`,
                bottom: `${newBottom}px`,
                top: 'auto', // Ensure top/left are not conflicting
                left: 'auto'
            });
        };

        const handleMouseUp = () => {
            if (isDragging) {
                setIsDragging(false);
                if (indicatorRef.current) {
                    indicatorRef.current.classList.remove(styles.dragging);
                }
                // Optional: Save final position to localStorage if you want it to persist
                localStorage.setItem('monitoringIndicatorPosition', JSON.stringify(position));
            }
        };

        if (isDragging) {
            document.addEventListener('mousemove', handleMouseMove);
            document.addEventListener('mouseup', handleMouseUp);
        }

        return () => {
            document.removeEventListener('mousemove', handleMouseMove);
            document.removeEventListener('mouseup', handleMouseUp);
        };
    }, [isDragging, position]); // Only re-run if isDragging changes

    // Load position from localStorage on mount
    useEffect(() => {
        const savedPosition = localStorage.getItem('monitoringIndicatorPosition');
        if (savedPosition) {
            try {
                setPosition(JSON.parse(savedPosition));
            } catch (e) { console.error("Failed to parse saved indicator position", e); }
        }
    }, []);

    const indicatorStyle: CSSProperties = {
        position: 'fixed',
        ...position, // Apply dynamic position
        top: position.top === 'auto' ? undefined : position.top, // Only apply if not 'auto'
        left: position.left === 'auto' ? undefined : position.left,
        right: position.right === 'auto' ? undefined : position.right,
        bottom: position.bottom === 'auto' ? undefined : position.bottom,
    };

    // Render null if not active, but after all hooks are called
    if (!isActive) {
        return null;
    }

    return (
        <div
            ref={indicatorRef}
            className={`${styles.indicator} ${DRAG_AREA_CLASS} ${isPageFocused ? styles.focused : styles.unfocused}`}
            style={indicatorStyle}
            onMouseDown={handleMouseDown}
            title={isPageFocused ? "Monitoring Active. Drag to move." : "Window Lost Focus! Monitoring Active. Drag to move."}
        >
            <FaEye className={styles.icon} />
            <span className={styles.text}>Monitoring</span>
        </div>
    );
};

export default MonitoringIndicator;
```

---

## components\NavigationPalette


### components\NavigationPalette\NavigationPalette.module.scss

```scss
// src/components/NavigationPalette/NavigationPalette.module.scss
@import '../../styles/variables';
@import '../../styles/mixins';
@import '../../styles/palette-common'; // If using the common partial

.paletteWrapper {
  @extend %paletteWrapperBase; // If using common partial
  // Or copy styles from %paletteWrapperBase if not extending
  display: flex;
  flex-direction: column;
  height: 100%;
}

.title {
  @extend %paletteTitleBase;
  text-align: center;
  font-size: $font-size-base * 1.05;
  font-weight: $font-weight-semibold;
  margin-bottom: map-get($spacers, 3);
  color: $gray-700;
  flex-shrink: 0;
  padding-bottom: map-get($spacers, 2);
  border-bottom: 1px solid $gray-200;
}

.legend {
  @extend %legendBase;
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(110px, 1fr));
  gap: map-get($spacers, 1) map-get($spacers, 2);
  margin-bottom: map-get($spacers, 3);
  padding: map-get($spacers, 2);
  background-color: $gray-50;
  border: 1px solid $gray-200;
  border-radius: $border-radius;
  font-size: $font-size-base * 0.8;
  flex-shrink: 0;
  color: $gray-600;
}

.legendItem {
  @extend %legendItemBase;
  display: flex;
  align-items: center;
  gap: map-get($spacers, 2);
}

.legendColorBox {
  @extend %legendColorBoxBase;
  display: inline-block;
  width: 15px;
  height: 15px;
  border-radius: $border-radius-sm;
  border: 1px solid rgba($black-color, 0.15);
  flex-shrink: 0;
}

.paletteGrid {
  @extend %paletteGridBase;
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(40px, 1fr));
  gap: map-get($spacers, 2);
  overflow-y: auto;
  flex-grow: 1;
  padding: map-get($spacers, 1) 2px;
}

.paletteButton {
  @extend %paletteButtonBase;
  display: flex;
  justify-content: center;
  align-items: center;
  aspect-ratio: 1 / 1;
  border: 1px solid $gray-300;
  border-radius: $border-radius-sm;
  font-weight: $font-weight-semibold;
  font-size: $font-size-base * 0.9;
  cursor: pointer;
  transition: background-color $transition-fast, border-color $transition-fast, transform $transition-fast, box-shadow $transition-fast, color $transition-fast;
  background-color: $white-color;
  color: $gray-700;

  &:hover:not(:disabled):not(.current) {
    transform: scale(1.08);
    border-color: $primary-color;
    z-index: 1;
    box-shadow: $box-shadow-sm;
  }
  @include focus-outline($primary-color);

  &.disabled {
    cursor: not-allowed;
    opacity: 0.6;
    filter: grayscale(50%);
    background-color: $gray-100;
    border-color: $gray-200;
    color: $gray-400;
  }
}


// --- Navigation Status Styles ---
// These colors aim for clarity and accessibility.

// Answered
.answered, .legendColorBox.answered {
  background-color: lighten($success-color, 48%); // Lighter green
  border-color: $success-color;
  color: darken($success-color, 15%); // Dark green text
}

// Not Answered (but visited)
.notAnswered, .legendColorBox.notAnswered {
  background-color: lighten($warning-color, 48%); // Lighter amber/yellow
  border-color: $warning-color;
  color: darken($warning-color, 25%); // Darker text for amber
}

// Marked for Review
.markedForReview, .legendColorBox.markedForReview {
  background-color: lighten($info-color, 48%); // Lighter info blue
  border-color: $info-color;
  color: darken($info-color, 20%); // Darker info text
  // Optional: add a small dot or icon inside button using ::before or ::after if just color isn't enough
}

// Not Visited
.notVisited, .legendColorBox.notVisited {
  background-color: $gray-100; // Light gray for not visited
  border-color: $gray-300;    // Standard border
  color: $gray-500;           // Muted text
}

// Current Question Indicator (common for both palettes)
.current, .legendColorBox.current {
  border-width: 2px; // Thicker border
  border-color: $primary-color !important; // Strong primary color border, important to override status border
  box-shadow: 0 0 0 3px rgba($primary-color, 0.3), $box-shadow-sm; // Focus ring + base shadow
  transform: scale(1.1); // Slightly larger
  z-index: 2; // Ensure current is above others

  // Ensure text color contrasts with its own background if background changes due to status
  // e.g., if current and answered, it will have .answered bg.
  // color: $primary-color; // Or a specific color if background is predictable

  &.legendColorBox { // Style for legend's "current" indicator box
    background-color: transparent; // Or $primary-color if you want a solid fill
    // Keep border and shadow from above for consistency
    outline: 2px solid $primary-color; // Different visual for legend item
    outline-offset: -2px; // Inset outline
    box-shadow: none;
  }
}
```

---

### components\NavigationPalette\NavigationPalette.tsx

```typescript
// src/components/NavigationPalette/NavigationPalette.tsx
import React, { useCallback } from 'react';
import { useExam } from '../../contexts/ExamContext';
import { QuestionStatus } from '../../types'; 
import styles from './NavigationPalette.module.scss';

// Map status to CSS class names for styling
const getStatusClass = (status: QuestionStatus): string => {
    switch (status) {
        case 'answered':
            return styles.answered;
        case 'notAnswered':
            return styles.notAnswered;
        case 'markedForReview':
            return styles.markedForReview;
        case 'notVisited':
            return styles.notVisited;
        default:
            return styles.notVisited;
    }
};

// Props for the memoized button component
interface PaletteButtonProps {
    questionNumber: number;
    index: number;
    status: QuestionStatus;
    isCurrent: boolean;
    isExamActive: boolean;
    onQuestionSelect: (index: number) => void;
}

// Memoized palette button component
const PaletteButton = React.memo(({
    questionNumber,
    index,
    status,
    isCurrent,
    isExamActive,
    onQuestionSelect
}: PaletteButtonProps) => {
    const statusClass = getStatusClass(status);
    const handleClick = () => onQuestionSelect(index);

    return (
        <button
            onClick={handleClick}
            className={`
                ${styles.paletteButton}
                ${statusClass}
                ${isCurrent ? styles.current : ''}
                ${!isExamActive ? styles.disabled : ''}
            `}
            title={
                !isExamActive ? `Exam not active - Q ${questionNumber}` :
                `Question ${questionNumber} - ${status.replace(/([A-Z])/g, ' $1').trim()}`
            }
            disabled={!isExamActive}
        >
            {questionNumber}
        </button>
    );
});

// Ensure display name for debugging
PaletteButton.displayName = 'PaletteButton';

const NavigationPalette: React.FC = () => {
    const {
        questions,
        userAnswers,
        currentQuestionIndex,
        navigateToQuestion,
        examStatus
    } = useExam();

    const isExamActive = examStatus === 'active';

    // Memoize the question selection handler
    const handleQuestionSelect = useCallback((index: number) => {
        if (!isExamActive) return; // Prevent navigation if exam not active
        navigateToQuestion(index);
    }, [isExamActive, navigateToQuestion]);

    return (
        <div className={styles.paletteWrapper}>
            <h3 className={styles.title}>Question Palette</h3>

            {/* Legend */}
            <div className={styles.legend}>
                <div className={styles.legendItem}>
                    <span className={`${styles.legendColorBox} ${styles.answered}`}></span> Answered
                </div>
                <div className={styles.legendItem}>
                    <span className={`${styles.legendColorBox} ${styles.notAnswered}`}></span> Not Answered
                </div>
                <div className={styles.legendItem}>
                    <span className={`${styles.legendColorBox} ${styles.markedForReview}`}></span> Marked
                </div>
                <div className={styles.legendItem}>
                    <span className={`${styles.legendColorBox} ${styles.notVisited}`}></span> Not Visited
                </div>
                <div className={styles.legendItem}>
                    <span className={`${styles.legendColorBox} ${styles.current}`}></span> Current
                </div>
            </div>

            {/* Grid for Question Buttons */}
            <div className={styles.paletteGrid}>
                {questions.map((question, index) => {
                    const questionNumber = question.question_number;
                    const answerData = userAnswers[questionNumber];
                    const status = answerData ? answerData.status : 'notVisited';
                    const isCurrent = index === currentQuestionIndex;
                    
                    return (
                        <PaletteButton
                            key={questionNumber}
                            questionNumber={questionNumber}
                            index={index}
                            status={status}
                            isCurrent={isCurrent}
                            isExamActive={isExamActive}
                            onQuestionSelect={handleQuestionSelect}
                        />
                    );
                })}
            </div>
        </div>
    );
};

export default NavigationPalette;
```

---

## components\OfficialExamSelector


### components\OfficialExamSelector\OfficialExamSelector.module.scss

```scss
// src/components/OfficialExamSelector/OfficialExamSelector.module.scss
@import '../../styles/variables';
@import '../../styles/mixins';

.selectionStepContainer {
  padding: map-get($spacers, 2) 0; // py-2
  // transition: opacity 0.3s ease-in-out; // If animating step changes
}

.backButton {
  //@include button-text-variant($gray-600, rgba($gray-600, 0.05), $gray-700); // Subtle text button
  background-color: transparent;
  border: 1px solid $gray-300;
  color: $gray-700;

  &:hover {
    background-color: $gray-100;
  }
  font-size: $font-size-base * 0.9;
  padding: map-get($spacers, 1) map-get($spacers, 2); // py-1 px-2
  margin-bottom: map-get($spacers, 4); // mb-4
  gap: map-get($spacers, 1); // gap-1
  svg { font-size: $font-size-base * 0.9; } // Adjust icon size
}

.selectionStepTitle {
  font-size: $h5-font-size; // H5 for step titles
  font-weight: $font-weight-semibold; // Bolder
  color: $primary-color;
  text-align: left;
  margin-bottom: map-get($spacers, 4); // mb-4
  padding-bottom: map-get($spacers, 2); // pb-2
  border-bottom: 1px solid $gray-200; // Lighter separator
}

// --- Card Grid Common Styles ---
.examGrid {
  display: grid;
  gap: map-get($spacers, 3); // gap-3 (16px) for cards
}
// Specific grid column templates (keep as is, they define layout well)
.categoryGrid { grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); } // Wider category cards
.yearGrid { grid-template-columns: repeat(auto-fit, minmax(100px, 1fr)); } // Smaller years
.sessionGrid { grid-template-columns: repeat(auto-fit, minmax(120px, 1fr)); }
.paperGrid { grid-template-columns: repeat(auto-fit, minmax(240px, 1fr)); } // Papers in grid

.examCard { // Base style for all clickable selection cards
  background-color: $component-bg; // $white-color
  border: 1px solid $gray-200;    // Lighter border
  border-radius: $border-radius-lg; // 8px
  padding: map-get($spacers, 3);    // p-3 (16px)
  text-align: center;
  cursor: pointer;
  transition: transform $transition-fast, box-shadow $transition-medium, border-color $transition-fast, background-color $transition-fast;
  box-shadow: $box-shadow-sm;
  position: relative; // For check icon
  display: flex;
  flex-direction: column;
  justify-content: center;
  min-height: 70px; // Ensure some minimum height for consistency

  &:hover:not(:disabled):not(.selected) { // Hover only if not disabled or already selected
    transform: translateY(-3px);
    box-shadow: $box-shadow-md;
    border-color: $primary-color; // Highlight border on hover
    // background-color: $gray-50; // Optional: subtle background tint on hover
  }

  &.selected {
    border-color: $primary-color;
    border-width: 2px; // Thicker border for selected state
    background-color: lighten($primary-color, 58%); // Light primary tint
    box-shadow: 0 0 0 2px rgba($primary-color, 0.1), $box-shadow-sm; // Focus ring like effect + base shadow
    // transform: translateY(-1px); // Optional: slight lift
    color: darken($primary-color, 10%); // Darken text if on light primary bg

    .examTitle { color: darken($primary-color, 10%); } // Ensure title also changes
    .examDescription { color: darken($primary-color, 5%); }
  }

  &:disabled { // When this section is not active
    cursor: not-allowed;
    opacity: 0.6;
    background-color: $gray-100; // Lighter disabled background
    border-color: $gray-200;
    box-shadow: none;
    transform: none;
    &:hover { border-color: $gray-200; } // Prevent hover style on disabled
  }
  @include focus-outline($primary-color); // Standard focus outline
}

// --- Specific Card Type Adjustments ---
.categoryCard {
  padding: map-get($spacers, 4); // More padding for category cards
  min-height: 90px;
}
.yearCard {
  .examTitle { font-size: $h5-font-size; font-weight: $font-weight-semibold; } // Larger year text
}
.sessionCard {
  min-height: 60px; // Shorter session cards if they just show session name/number
}
.paperCard { // For individual papers when displayed in grid mode
  text-align: left; // Align text left for paper details
  justify-content: space-between; // Push title to top, meta to bottom
  padding: map-get($spacers, 3);
  min-height: 110px; // More height for paper details
}

.examTitle { // Title text inside cards
  font-size: $font-size-base;
  margin-bottom: map-get($spacers, 1); // mb-1
  color: $gray-800; // Darker text for titles
  font-weight: $font-weight-medium;
  @include truncate-text; // Handle long titles
}

.examDescription { // Description inside cards (e.g., "X configurations available")
  font-size: $font-size-base * 0.8; // Smaller description
  color: $text-muted;
  margin-bottom: 0;
}

.checkIcon { // Icon for selected card state
  color: $primary-color;
  position: absolute;
  top: map-get($spacers, 2);    // 8px from top
  right: map-get($spacers, 2);   // 8px from right
  font-size: $font-size-base * 1.25; // Larger check icon
  // Optional: background circle for more definition if needed
  // background-color: $white-color;
  // border-radius: 50%;
  // padding: 2px;
  // box-shadow: 0 1px 2px rgba($black-color, 0.15);
}

// Meta data for papers in grid view
.paperMetaGrid {
  display: flex;
  flex-wrap: wrap;
  gap: map-get($spacers, 1) map-get($spacers, 2); // row-gap col-gap
  font-size: $font-size-base * 0.75; // Smaller meta text
  color: $text-muted;
  margin-top: map-get($spacers, 2); // mt-2
  justify-content: flex-start;

  span { // Individual meta items (Date, Shift, etc.)
    background-color: $gray-100; // Light background for tags
    padding: 2px map-get($spacers, 1); // Small padding
    border-radius: $border-radius-sm; // Small radius for tags
    // border: 1px solid $gray-200; // Optional: subtle border for tags
    color: $gray-600; // Slightly darker text for tags
  }
}

// --- Paper Selection: Grid/List Toggle & Table View ---
.paperSelectionContainer { margin-top: map-get($spacers, 4); } // mt-4

.paperDisplayToggle { // Container for Grid/List view toggle buttons
  display: flex;
  justify-content: flex-end;
  align-items: center;
  gap: map-get($spacers, 2); // gap-2
  margin-bottom: map-get($spacers, 3); // mb-3

  span { font-size: $font-size-base * 0.85; color: $text-muted; }
  button { // Style for toggle icons (FaThLarge, FaTable)
    @include button-text-variant($gray-500, rgba($gray-500, 0.05), $gray-700); // Subtle text button
    padding: map-get($spacers, 1); // p-1, make it squarish for icons
    border: 1px solid transparent; // No border by default
    font-size: $font-size-base * 1.1; // Icon size

    &:hover:not(:disabled) {
      border-color: $gray-300; // Add border on hover
      background-color: $gray-100;
    }
    &:disabled { // Active state for selected view mode
      background-color: $primary-color;
      border-color: $primary-color;
      color: $white-color;
      cursor: default;
      &:hover { background-color: $primary-color; border-color: $primary-color; } // Keep active style on hover
    }
    @include focus-outline($primary-color);
  }
}

.paperTableContainer { overflow-x: auto; }
.paperTable { // Table styling (align with ProfilePage/Leaderboard tables)
  width: 100%;
  border-collapse: separate;
  border-spacing: 0;
  font-size: $font-size-base * 0.9;

  th, td {
    padding: map-get($spacers, 2) map-get($spacers, 3);
    text-align: left;
    border-bottom: 1px solid $gray-200;
    vertical-align: middle;
  }
  th {
    background-color: $gray-50;
    font-weight: $font-weight-semibold;
    color: $gray-600;
    white-space: nowrap;
    border-top: 1px solid $gray-200;
    &:first-child { border-top-left-radius: $border-radius-sm; }
    &:last-child { border-top-right-radius: $border-radius-sm; }
  }
  tbody tr {
    cursor: pointer;
    transition: background-color $transition-fast, border-left-color $transition-fast;
    border-left: 3px solid transparent; // For selected state highlight

    &:hover:not(.selectedRow) { // Hover only if not selected
      background-color: $gray-50;
    }
    &:last-child td { border-bottom: none; }
  }
  .selectedRow {
    background-color: lighten($primary-color, 58%) !important; // Ensure selection override
    border-left-color: $primary-color;
    td { font-weight: $font-weight-medium; color: darken($primary-color, 5%); }
  }
  td { color: $gray-700; }
  .selectHeader { text-align: center; }
  .selectCell { text-align: center; vertical-align: middle; }
  .selectButton { // "Select" button within table cell
    @include button-variant(
      transparent, $gray-300, $gray-700, $is-outline: true
    );
    padding: map-get($spacers, 1) map-get($spacers, 2); // py-1 px-2
    font-size: $font-size-base * 0.85;
    width: 90px; // Fixed width
    gap: map-get($spacers, 1);

    svg { color: $success-color; font-size: $font-size-base * 0.9; } // Icon size

    &:hover:not(:disabled):not(&[aria-pressed="true"]) {
      background-color: lighten($success-color, 55%);
      color: $success-color;
      border-color: $success-color;
    }
    &[aria-pressed="true"] { // When selected
      @include button-variant($success-color); // Solid success
      svg { color: $white-color; }
    }
  }

  // Responsive styles for table (using data-label)
  @media (max-width: map-get($grid-breakpoints, md)) {
    // (Copy responsive table styles from ProfilePage.module.scss or Leaderboard.module.scss)
    // For brevity, assuming you'll reuse those consistent styles.
    // Key aspects: thead hidden, tr becomes card, td stacks with ::before label.
    border: none;
    thead { display: none; }
    tr {
      display: block; margin-bottom: map-get($spacers, 3);
      border: 1px solid $gray-200; border-radius: $border-radius;
      padding: map-get($spacers, 3); background-color: $white-color; box-shadow: $box-shadow-sm;
    }
    td {
      display: block; text-align: right; padding: map-get($spacers, 2) 0;
      border-bottom: 1px dotted $gray-100; white-space: normal;
      &::before {
        content: attr(data-label); float: left; font-weight: $font-weight-semibold;
        margin-right: map-get($spacers, 2); font-size: $font-size-base * 0.8; color: $text-muted;
      }
      &:last-child { border-bottom: none; padding-bottom: 0;}
    }
    .selectedRow {
      border-left-width: 4px; // Thicker accent border for mobile selected card
    }
  }
}

// Message when no exams/years/papers found
.infoMessage {
  // Reuse ErrorMessage component or style consistently
  padding: map-get($spacers, 4);
  text-align: center;
  color: $text-muted;
  font-style: italic;
  border: 1px dashed $gray-300; // Dashed border for info
  border-radius: $border-radius;
  margin-top: map-get($spacers, 3); // mt-3
  background-color: $gray-50; // Light background
}
```

---

### components\OfficialExamSelector\OfficialExamSelector.tsx

```typescript
// src/components/OfficialExamSelector/OfficialExamSelector.tsx
import React, { useState, useMemo, useCallback } from 'react';
import { ExamConfig } from '../../types'; // Assuming types are correctly set up
import styles from './OfficialExamSelector.module.scss'; // Import the component's SCSS module
import { FaCheckCircle, FaArrowLeft, FaTable, FaThLarge } from 'react-icons/fa';

interface OfficialExamSelectorProps {
    availableExams: ExamConfig[];
    isDisabled: boolean; // Passed from parent to disable this whole section
    onExamSelected: (config: ExamConfig) => void;
    onSelectionCleared: () => void;
}

const OfficialExamSelector: React.FC<OfficialExamSelectorProps> = ({
    availableExams,
    isDisabled, // We might not need to use this directly inside if the parent handles overlay/disabling
    onExamSelected,
    onSelectionCleared,
}) => {

    // --- State for internal selection steps ---
    const [selectedCategory, setSelectedCategory] = useState<string | null>(null);
    const [selectedYear, setSelectedYear] = useState<number | null>(null);
    const [selectedSession, setSelectedSession] = useState<string | number | null>(null);
    // Final selected exam *within this component* before notifying parent
    const [localSelectedExamConfig, setLocalSelectedExamConfig] = useState<ExamConfig | null>(null);
    const [paperDisplayMode, setPaperDisplayMode] = useState<'grid' | 'list'>('grid');


    // --- Memoized data hooks ---
    const examCategories = useMemo(() => {
        const categories = new Set<string>(availableExams.map(exam => exam.category));
        return Array.from(categories).sort();
    }, [availableExams]);

    const availableYears = useMemo(() => {
        if (!selectedCategory) return [];
        const years = new Set<number>(
            availableExams
                .filter(exam => exam.category === selectedCategory)
                .map(exam => exam.year)
        );
        return Array.from(years).sort((a, b) => b - a); // Sort descending
    }, [availableExams, selectedCategory]);

    const availableSessions = useMemo(() => {
        if (!selectedCategory || !selectedYear) return [];
        const hasDefinedSession = availableExams.some(exam =>
            exam.category === selectedCategory && exam.year === selectedYear && exam.session != null
        );
        if (!hasDefinedSession) return [];
        const sessions = new Set<string | number>(
            availableExams
                .filter(exam => exam.category === selectedCategory && exam.year === selectedYear && exam.session != null)
                .map(exam => exam.session!)
        );
        return Array.from(sessions).sort((a, b) => String(a).localeCompare(String(b)));
    }, [availableExams, selectedCategory, selectedYear]);

    const finalPaperList = useMemo(() => {
        if (!selectedCategory || !selectedYear) return [];
        return availableExams.filter(exam =>
            exam.category === selectedCategory &&
            exam.year === selectedYear &&
            (availableSessions.length === 0 || exam.session === selectedSession) // Correctly filter by session only if applicable and selected
        ).sort((a, b) => { // Keep sorting logic
             const dateA = a.date ?? 'zzzz'; const dateB = b.date ?? 'zzzz';
             const dateCompare = dateA.localeCompare(dateB);
             if (dateCompare !== 0) return dateCompare;
             const shiftA = a.shift != null ? String(a.shift) : 'zzzz'; const shiftB = b.shift != null ? String(b.shift) : 'zzzz';
             const shiftCompare = shiftA.localeCompare(shiftB);
             if (shiftCompare !== 0) return shiftCompare;
             const paperTypeA = a.paperType ?? 'zzzz'; const paperTypeB = b.paperType ?? 'zzzz';
             return paperTypeA.localeCompare(paperTypeB);
         });
    }, [availableExams, selectedCategory, selectedYear, availableSessions, selectedSession]);


    // --- Handlers for internal steps ---
    const resetSelection = useCallback((level: 'category' | 'year' | 'session' = 'category') => {
        setLocalSelectedExamConfig(null); // Always reset final selection
        if (level === 'category') {
            setSelectedCategory(null);
            setSelectedYear(null);
            setSelectedSession(null);
            onSelectionCleared(); // Notify parent when fully reset
        } else if (level === 'year') {
            setSelectedYear(null);
            setSelectedSession(null);
            // Don't call onSelectionCleared here unless year is the final step sometimes?
        } else if (level === 'session') {
            setSelectedSession(null);
        }
    }, [onSelectionCleared]); // Include callback in dependencies

    const handleCategorySelect = useCallback((category: string) => {
        resetSelection('category'); // Ensure full reset
        setSelectedCategory(category);
        // Optional: logEvent here if desired, or handle logging in parent based on mode change
    }, [resetSelection]);

    const handleYearSelect = useCallback((year: number) => {
        resetSelection('year'); // Reset session and final paper
        setSelectedYear(year);
    }, [resetSelection]);

    const handleSessionSelect = useCallback((session: string | number | null) => {
        resetSelection('session'); // Reset final paper
        setSelectedSession(session);
    }, [resetSelection]);

    // This now sets local state AND calls the parent prop
    const handlePaperSelect = useCallback((examConfig: ExamConfig) => {
        setLocalSelectedExamConfig(examConfig);
        onExamSelected(examConfig); // Notify parent immediately
    }, [onExamSelected]);

    // Back Button Handlers
    const handleBackToCategories = useCallback(() => resetSelection('category'), [resetSelection]);
    const handleBackToYears = useCallback(() => resetSelection('year'), [resetSelection]);
    const handleBackToSessions = useCallback(() => resetSelection('session'), [resetSelection]);


    // --- Rendering logic for different steps ---

    // Step 4: Render Paper Selector (Final Step)
    const renderPaperSelector = () => {
        if (!selectedCategory || !selectedYear) return null; // Should not happen
        // Determine if loading state should be shown here (e.g., if availableExams is empty but loading?) - handled by parent mostly
        if (finalPaperList.length === 0) {
            // Check if session selection is the blocker
            if (availableSessions.length > 0 && selectedSession == null) {
                 return <p className={styles.infoMessage}>Please select a session above.</p>;
            }
            return <p className={styles.infoMessage}>No specific papers found matching your criteria for {selectedCategory} {selectedYear}{selectedSession ? ` (Session: ${selectedSession})` : ''}.</p>;
        }

        const showSessionColumn = finalPaperList.some(p => p.session != null);
        const showDateColumn = finalPaperList.some(p => p.date);
        const showShiftColumn = finalPaperList.some(p => p.shift != null);
        const showPaperTypeColumn = finalPaperList.some(p => p.paperType);

        return (
             <div className={styles.paperSelectionContainer}>
                <div className={styles.paperDisplayToggle}>
                     <span>View as:</span>
                     {/* Make buttons control local state */}
                     <button onClick={() => setPaperDisplayMode('grid')} className={paperDisplayMode === 'grid' ? styles.activeToggle : ''} disabled={paperDisplayMode === 'grid'} title="Grid View"><FaThLarge /></button>
                     <button onClick={() => setPaperDisplayMode('list')} className={paperDisplayMode === 'list' ? styles.activeToggle : ''} disabled={paperDisplayMode === 'list'} title="List View"><FaTable /></button>
                 </div>

                {paperDisplayMode === 'grid' ? (
                     <div className={styles.paperGrid}>
                        {finalPaperList.map((exam) => (
                             <button
                                key={exam.id}
                                className={`${styles.examCard} ${styles.paperCard} ${localSelectedExamConfig?.id === exam.id ? styles.selected : ''}`}
                                onClick={() => handlePaperSelect(exam)}
                             >
                                 <h4 className={styles.paperTitleInCard}>{exam.paperType || exam.title}</h4>
                                <div className={styles.paperMetaGrid}>
                                   {showDateColumn && exam.date && <span>{exam.date}</span>}
                                   {showShiftColumn && exam.shift != null && <span>Shift: {exam.shift}</span>}
                                   {showSessionColumn && exam.session != null && <span>Sess: {exam.session}</span>}
                                 </div>
                                {localSelectedExamConfig?.id === exam.id && <FaCheckCircle className={styles.checkIcon} />}
                            </button>
                         ))}
                     </div>
                 ) : ( // List View
                     <div className={styles.paperTableContainer}>
                        <table className={styles.paperTable}>
                             <thead>
                                <tr>
                                     <th>{showPaperTypeColumn ? 'Paper/Subject' : 'Title'}</th>
                                     {showDateColumn && <th>Date</th>}
                                     {showSessionColumn && <th>Session</th>}
                                     {showShiftColumn && <th>Shift</th>}
                                     <th className={styles.selectHeader}>Select</th>
                                </tr>
                            </thead>
                            <tbody>
                                {finalPaperList.map((exam) => (
                                    <tr
                                        key={exam.id}
                                        className={localSelectedExamConfig?.id === exam.id ? styles.selectedRow : ''}
                                        onClick={() => handlePaperSelect(exam)}
                                        tabIndex={0}
                                        onKeyPress={(e) => (e.key === 'Enter' || e.key === ' ') && handlePaperSelect(exam)}
                                    >
                                        <td data-label={showPaperTypeColumn ? 'Paper/Subject' : 'Title'}>{exam.paperType || exam.title}</td>
                                        {showDateColumn && <td data-label="Date">{exam.date || '-'}</td>}
                                        {showSessionColumn && <td data-label="Session">{exam.session != null ? exam.session : '-'}</td>}
                                        {showShiftColumn && <td data-label="Shift">{exam.shift != null ? exam.shift : '-'}</td>}
                                        <td data-label="Select" className={styles.selectCell}>
                                            <button
                                                className={styles.selectButton}
                                                onClick={(e) => { e.stopPropagation(); handlePaperSelect(exam); }}
                                                aria-label={`Select ${exam.paperType || exam.title}`}
                                                aria-pressed={localSelectedExamConfig?.id === exam.id}
                                            >
                                                {localSelectedExamConfig?.id === exam.id ? <FaCheckCircle /> : "Select"}
                                            </button>
                                        </td>
                                    </tr>
                                ))}
                            </tbody>
                         </table>
                     </div>
                 )}
            </div>
         );
    };


    // Determine which step to show
    const showPaperListStep = selectedCategory && selectedYear && (availableSessions.length === 0 || selectedSession != null);
    const showSessionStep = selectedCategory && selectedYear && availableSessions.length > 0 && selectedSession == null;
    const showYearStep = selectedCategory && !selectedYear;
    const showCategoryStep = !selectedCategory;


    // Render the steps conditionally
    return (
        <div className={styles.selectionStepContainer}>
            {/* Step 4: Paper List */}
            {showPaperListStep && (
                 <>
                    <button onClick={availableSessions.length > 0 ? handleBackToSessions : handleBackToYears} className={styles.backButton}>
                        <FaArrowLeft /> {availableSessions.length > 0 ? `Back to ${selectedYear} Sessions` : `Back to ${selectedCategory} Years`}
                    </button>
                    <h3 className={styles.selectionStepTitle}>
                        Select Specific Paper for {selectedCategory} {selectedYear}
                        {selectedSession != null ? ` (Session: ${selectedSession})` : ''}
                    </h3>
                     {renderPaperSelector()}
                 </>
             )}

            {/* Step 3: Sessions */}
            {showSessionStep && (
                <>
                    <button onClick={handleBackToYears} className={styles.backButton}>
                        <FaArrowLeft /> Back to {selectedCategory} Years
                    </button>
                    <h3 className={styles.selectionStepTitle}>Select Session for {selectedCategory} {selectedYear}</h3>
                    <div className={`${styles.examGrid} ${styles.sessionGrid}`}>
                        {availableSessions.map((session) => (
                            <button
                                key={String(session)}
                                className={`${styles.examCard} ${styles.sessionCard}`}
                                onClick={() => handleSessionSelect(session)}
                            >
                                <h4 className={styles.examTitle}>{session}</h4>
                            </button>
                        ))}
                    </div>
                </>
            )}

            {/* Step 2: Years */}
            {showYearStep && (
                <>
                    <button onClick={handleBackToCategories} className={styles.backButton}>
                        <FaArrowLeft /> Back to Exam Types
                    </button>
                    <h3 className={styles.selectionStepTitle}>Select Year for {selectedCategory}</h3>
                    {availableYears.length > 0 ? (
                        <div className={`${styles.examGrid} ${styles.yearGrid}`}>
                            {availableYears.map((year) => (
                                <button
                                    key={year}
                                    className={`${styles.examCard} ${styles.yearCard}`}
                                    onClick={() => handleYearSelect(year)}
                                >
                                    <h4 className={styles.examTitle}>{year}</h4>
                                </button>
                            ))}
                        </div>
                    ) : (
                        <p className={styles.infoMessage}>No years found for {selectedCategory}.</p>
                    )}
                </>
            )}

             {/* Step 1: Categories */}
             {showCategoryStep && (
                 <>
                     <h3 className={styles.selectionStepTitle}>Select Exam Type</h3>
                     {examCategories.length > 0 ? (
                         <div className={`${styles.examGrid} ${styles.categoryGrid}`}>
                             {examCategories.map((category) => {
                                 const count = availableExams.filter(e => e.category === category).length;
                                 return (
                                     <button
                                         key={category}
                                         className={`${styles.examCard} ${styles.categoryCard}`}
                                         onClick={() => handleCategorySelect(category)}
                                         disabled={isDisabled} // Disable button based on parent prop
                                     >
                                         <h4 className={styles.examTitle}>{category}</h4>
                                         {count > 0 &&
                                             <p className={styles.examDescription}>
                                                 {count} configuration(s) available
                                             </p>
                                         }
                                     </button>
                                 );
                             })}
                         </div>
                     ) : (
                         <p className={styles.infoMessage}>No official exams available at the moment.</p>
                     )}
                 </>
             )}
        </div>
    );
};

export default OfficialExamSelector;
```

---

## components\QuestionDisplay


### components\QuestionDisplay\QuestionDisplay.module.scss

```scss
// src/components/QuestionDisplay/QuestionDisplay.module.scss
@import '../../styles/variables';
@import '../../styles/mixins';

.questionDisplayWrapper {
  // No specific padding here if .questionArea on ExamPage handles it.
  // If this component is used elsewhere and needs self-contained padding:
  padding: map-get($spacers, 4);
  line-height: $line-height-base; // 1.6 for readability
  height: 100%; // Try to take full height of its container (.questionArea)
  display: flex;
  flex-direction: column;
}

.loadingOrError { // Style for when question data isn't ready
  padding: map-get($spacers, 5);
  text-align: center;
  color: $text-muted;
  font-style: italic;
  flex-grow: 1; // Center it vertically if wrapper is flex
  display: flex;
  align-items: center;
  justify-content: center;
}

.questionHeader {
  margin-bottom: map-get($spacers, 4); // mb-4 (24px)
  padding-bottom: map-get($spacers, 3); // pb-3 (16px)
  border-bottom: 1px solid $gray-200; // Lighter border
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap; // Allow wrapping if subject is long
  gap: map-get($spacers, 2); // Gap between number and subject
  flex-shrink: 0; // Prevent header from shrinking
}

.questionNumber {
  font-weight: $font-weight-semibold; // Bolder
  font-size: $font-size-base * 1.2; // Slightly larger (1.2rem / ~19px)
  color: $primary-color;
}

.subject { // Optional subject/topic tag
  font-size: $font-size-base * 0.85; // Smaller
  color: $gray-600;
  background-color: $gray-100; // Light background for tag
  padding: map-get($spacers, 1) map-get($spacers, 2); // py-1 px-2
  border-radius: $border-radius-pill; // Pill shape
  font-weight: $font-weight-medium;
}

.questionText {
  margin-bottom: map-get($spacers, 5); // mb-5 (32px), more space before options
  font-size: $font-size-base * 1.1; // Slightly larger question text (1.1rem / ~17.5px)
  color: $gray-800; // Darker text for questions
  line-height: 1.7; // More line height for complex questions
  flex-grow: 1;     // Allow text area to expand
  overflow-y:visible; // Scroll only this part if extremely long, but .questionArea scrolls usually
  padding-right: map-get($spacers, 2); // Small padding if scrollbar appears

  // Styles for content rendered by MarkdownRenderer
  p { // Paragraphs within question_text
    margin-bottom: map-get($spacers, 3); // Consistent paragraph spacing
    &:last-child { margin-bottom: 0; }
  }
  // Add more specific styles for ul, ol, blockquote, pre, code if needed
  // Ensure KaTeX math (`.katex`) and Prism code blocks are styled well.
  // These often come with their own stylesheets but can be overridden.
}

.optionsList {
  display: flex;
  flex-direction: column;
  gap: map-get($spacers, 2); // gap-2 (8px) between options
  flex-shrink: 0; // Prevent options list from shrinking
}

.optionItem {
  border: 1px solid $gray-300; // Standard border
  border-radius: $border-radius-lg; // Softer, larger radius (8px)
  transition: border-color $transition-fast, background-color $transition-fast, box-shadow $transition-fast;
  position: relative;
  background-color: $white-color; // Ensure background for shadow/hover

  &:hover:not(.disabled) {
    border-color: $primary-color;
    background-color: lighten($primary-color, 58%); // Very light primary tint on hover
    // box-shadow: $box-shadow-sm; // Subtle shadow on hover
  }

  &.selected {
    border-color: $primary-color;
    border-width: 2px; // Make border thicker for selected
    background-color: lighten($primary-color, 55%); // Light primary background
    box-shadow: $box-shadow-sm;

    .optionLabel {
      // font-weight: $font-weight-semibold; // Text within label can be bolder
      color: $primary-color; // Text color changes
    }
    .optionKey {
      background-color: $primary-color;
      color: $white-color;
      border-color: $primary-color;
    }
  }

  &.disabled { // When exam is not active
    opacity: 0.7;
    background-color: $gray-50; // Slightly off-white disabled background
    cursor: not-allowed;
    border-color: $gray-200; // Lighter border for disabled
    box-shadow: none;

    .optionLabel { cursor: not-allowed; }
    &:hover { background-color: $gray-50; } // No visual change on hover when disabled

    &.selected { // Selected but disabled state
      background-color: $gray-200; // More distinct disabled-selected background
      border-color: $gray-400;    // Muted border
      .optionKey {
        background-color: $gray-400;
        color: $white-color;
        border-color: $gray-400;
      }
      .optionLabel {
        color: $gray-600; // Muted text color
      }
    }
  }
}

.radioInput { // Visually hidden radio button (as before)
  position: absolute;
  opacity: 0;
  width: 0;
  height: 0;
  pointer-events: none;
}

.optionLabel { // The clickable label area
  display: flex;
  align-items: flex-start; // Align key to top of potentially multi-line option text
  padding: map-get($spacers, 3); // p-3 (16px), generous padding for tap target
  cursor: pointer;
  width: 100%;
  color: $text-color; // Default text color for option
  transition: color $transition-fast;
  border-radius: inherit; // Inherit radius from parent .optionItem
}

.optionKey { // The 'A', 'B', 'C' part
  display: inline-flex;
  justify-content: center;
  align-items: center;
  width: 28px;
  height: 28px;
  border-radius: 50%; // Circular key
  background-color: $gray-100; // Light background for key
  border: 1px solid $gray-300;
  margin-right: map-get($spacers, 3); // mr-3 (16px)
  font-weight: $font-weight-semibold; // Bolder key text
  font-size: $font-size-base * 0.9;
  color: $gray-700; // Darker text for key
  flex-shrink: 0;
  transition: background-color $transition-fast, color $transition-fast, border-color $transition-fast;
  margin-top: 2px; // Align better with first line of text if text wraps
}

.optionText {
  flex-grow: 1;
  line-height: 1.6; // Good line height for option text
  word-break: break-word;
  // Styles for content rendered by MarkdownRenderer within option text
  p {
    margin-bottom: map-get($spacers, 1); // Space between paragraphs in an option
    &:last-child { margin-bottom: 0; }
  }
  // Add styles for ul, ol, code, pre if they can appear in options
}
```

---

### components\QuestionDisplay\QuestionDisplay.tsx

```typescript
// src/components/QuestionDisplay/QuestionDisplay.tsx
import React from 'react';
import { useExam } from '../../contexts/ExamContext';
import { Question } from '../../types'; // Make sure Question type is imported
import styles from './QuestionDisplay.module.scss';
import MarkdownRenderer from '../MarkdownRenderer/MarkdownRenderer';

interface QuestionDisplayProps {
    // Props could be added later if needed, but context is primary data source now
}

const QuestionDisplay: React.FC<QuestionDisplayProps> = () => {
    const {
        questions,
        currentQuestionIndex,
        userAnswers,
        selectAnswer, // Function to update the answer in context
        examStatus
    } = useExam();

    const isExamActive = examStatus === 'active';
    const currentQuestion: Question | undefined = questions[currentQuestionIndex];

    if (!currentQuestion) {
        return <div className={styles.loadingOrError}>Loading question...</div>;
    }

    const questionNumber = currentQuestion.question_number;
    const currentSelection = userAnswers[questionNumber]?.selectedOption;

    const handleOptionChange = (event: React.ChangeEvent<HTMLInputElement>) => {
        if (!isExamActive) return;
        selectAnswer(questionNumber, event.target.value);
    };

    return (
        <div className={styles.questionDisplayWrapper}>
            <div className={styles.questionHeader}>
                <span className={styles.questionNumber}>Question No. {questionNumber}</span>
                {/* MODIFIED: Display Subject and Topic */}
                {(currentQuestion.subject || currentQuestion.topic) && (
                    <span className={styles.subject}>
                        {currentQuestion.subject}
                        {currentQuestion.subject && currentQuestion.topic ? ' - ' : ''}
                        {currentQuestion.topic}
                    </span>
                )}
            </div>

            <div className={styles.questionText}><MarkdownRenderer>{currentQuestion.question_text}</MarkdownRenderer></div>

            <div className={styles.optionsList}>
                {Object.entries(currentQuestion.options).map(([key, text]) => (
                    <div
                        key={key}
                        className={`${styles.optionItem} ${currentSelection === key ? styles.selected : ''} ${!isExamActive ? styles.disabled : ''}`}
                    >
                        <input
                            type="radio"
                            id={`q${questionNumber}_opt${key}`}
                            name={`question_${questionNumber}`}
                            value={key}
                            checked={currentSelection === key}
                            onChange={handleOptionChange}
                            className={styles.radioInput}
                            disabled={!isExamActive}
                        />
                        <label htmlFor={`q${questionNumber}_opt${key}`} className={styles.optionLabel}>
                            <span className={styles.optionKey}>{key.toUpperCase()}</span>
                            <span className={styles.optionText}><MarkdownRenderer>{text}</MarkdownRenderer></span>
                        </label>
                    </div>
                ))}
            </div>
        </div>
    );
};

export default QuestionDisplay;
```

---

## components\RegistrationModal


### components\RegistrationModal\RegistrationModal.module.scss

```scss
// src/components/RegistrationModal/RegistrationModal.module.scss (Examify)
@import '../../styles/variables'; 
@import '../../styles/mixins';   

.modalOverlay {
  position: fixed;
  top: 0; left: 0; right: 0; bottom: 0;
  background-color: rgba($black-color, 0.7); // Slightly darker overlay for focus
  display: flex;
  align-items: center;
  justify-content: center;
  z-index: $zindex-modal + 10; 
  padding: map-get($spacers, 2);
  opacity: 0;
  visibility: hidden;
  transition: opacity 0.3s ease-out, visibility 0s 0.3s linear;

  &.open {
    opacity: 1;
    visibility: visible;
    transition: opacity 0.3s ease-out, visibility 0s linear;
  }
}

.modalContent {
  background-color: transparent; // Make modal content itself transparent
  border-radius: $border-radius-xl; // Keep radius for iframe if iframe has bg
  box-shadow: $box-shadow-xl;    
  width: 100%;
  max-width: 480px; // Max width of MSP form. Adjust if MSP form is wider.
  position: relative;
  display: flex;
  flex-direction: column;
    height: 75vh; // Fixed height or a percentage of viewport
    max-height: 650px; // Max pixel height
    min-height: 500px; // Min pixel height to ensure form is usable
  
  .modalOverlay.open & { 
     animation: modalSlideInUp 0.35s ease-out forwards; 
  }
}

@keyframes modalSlideInUp { 
  from { transform: translateY(30px) scale(0.95); opacity: 0; }
  to { transform: translateY(0) scale(1); opacity: 1; }
}

.iframeLoader { 
  display: flex;
  align-items: center;
  justify-content: center;
  padding: map-get($spacers, 6) 0; 
  min-height: 300px; 
    position: absolute; // To overlay iframe if it's initially visible
    top: 0; left: 0; right: 0; bottom: 0;
    background-color: $component-bg; // Match modal desired background if any
    z-index: 2; // Above iframe while loading
    border-radius: inherit; // Inherit modal content's border radius
}

.iframeContainer { 
  flex-grow: 1; 
    height: 100%; // Make iframe container take full height of modalContent
  border: none;
  overflow: hidden; 
  position: relative; 
    background-color: $component-bg; // If modalContent is transparent, this gives iframe a bg
  border-radius: inherit; // Inherit modal content's border radius
    z-index: 1; // Below loader

  iframe {
    width: 100%;
    height: 100%;
    border: none;
    display: block; 
     border-radius: inherit; // Make iframe itself rounded
  }
}
```

---

### components\RegistrationModal\RegistrationModal.tsx

```typescript
// src/components/RegistrationModal/RegistrationModal.tsx (Examify)
import React, { useEffect, useRef, useState } from 'react';
import styles from './RegistrationModal.module.scss';
import Spinner from '../Spinner/Spinner'; 

interface RegistrationModalProps {
    isOpen: boolean;
    onClose: () => void; 
    onRegistrationSuccess: (data: { email?: string; uid?: string; displayName?: string; returnTo?: string }) => void; 
    initialReturnToPath?: string; 
}

const MY_SERVICES_PORTAL_EMBED_REGISTER_URL = 'https://bcaexamprep.web.app/embed/register'; // Adjust to your MSP dev URL

const RegistrationModal: React.FC<RegistrationModalProps> = ({
    isOpen,
    onClose,
    onRegistrationSuccess,
    initialReturnToPath = '/select-exam', 
}) => {
    const iframeRef = useRef<HTMLIFrameElement>(null);
    const [isLoadingIframe, setIsLoadingIframe] = useState(true);
    const modalOverlayRef = useRef<HTMLDivElement>(null);
   const [iframeKey, setIframeKey] = useState(0); // New state for iframe key

    const examifyReturnUrl = `${window.location.origin}${initialReturnToPath}`;
    const iframeSrc = `${MY_SERVICES_PORTAL_EMBED_REGISTER_URL}?returnTo=${encodeURIComponent(examifyReturnUrl)}`;

    useEffect(() => {
        if (modalOverlayRef.current) {
            if (isOpen) {
                modalOverlayRef.current.classList.add(styles.open);
                setIsLoadingIframe(true); 
               setIframeKey(prevKey => prevKey + 1); // Increment key to force iframe remount
            } else {
                modalOverlayRef.current.classList.remove(styles.open);
            }
        }
    }, [isOpen]);
    
    useEffect(() => {
        const handleMessage = (event: MessageEvent) => {
            const mspOrigin = new URL(MY_SERVICES_PORTAL_EMBED_REGISTER_URL).origin;
            if (event.origin !== mspOrigin) {
                console.warn(`[Examify RegistrationModal] Ignoring message from unexpected origin: ${event.origin}. Expected: ${mspOrigin}`);
                return;
            }

            if (event.data && event.data.type === 'mspRegistrationSuccess') {
                onRegistrationSuccess({ 
                    email: event.data.email,
                    uid: event.data.uid, 
                    displayName: event.data.displayName,
                    returnTo: event.data.returnTo 
                });
            }
        };
        if (isOpen) { window.addEventListener('message', handleMessage); }
        return () => { window.removeEventListener('message', handleMessage); };
    }, [isOpen, onRegistrationSuccess]);

    const handleIframeLoad = () => { 
        // console.log("[Examify RegistrationModal] iframe loaded."); // Debug log
        setIsLoadingIframe(false); 
    };
    if (!isOpen) { 
        return null; 
    }

    return (
        <div className={`${styles.modalOverlay} ${isOpen ? styles.open : ''}`} onClick={onClose}>
            <div className={styles.modalContent} onClick={(e) => e.stopPropagation()}>
                {/* No Examify-side title, subtitle, close button, or footer */}
                {isLoadingIframe && (
                    <div className={styles.iframeLoader}>
                        <Spinner text="Loading secure registration form..." size="2em"/>
                    </div>
                )}
                <div className={styles.iframeContainer} style={{ visibility: isLoadingIframe ? 'hidden' : 'visible' }}>
                    <iframe
                       key={iframeKey} // Add key prop here
                        ref={iframeRef}
                        src={iframeSrc}
                        title="MyServices Portal Registration" 
                        onLoad={handleIframeLoad}
                        allowFullScreen={false} 
                    />
                </div>
            </div>
        </div>
    );
};

export default RegistrationModal;
```

---

## components\ReviewPalette


### components\ReviewPalette\ReviewPalette.module.scss

```scss
// src/components/ReviewPalette/ReviewPalette.module.scss
@import '../../styles/variables';
@import '../../styles/mixins';
@import '../../styles/palette-common'; // If using the common partial

.paletteWrapper {
  @extend %paletteWrapperBase;
  display: flex;
  flex-direction: column;
  height: 100%;
}

.title {
  @extend %paletteTitleBase;
  text-align: center;
  font-size: $font-size-base * 1.05;
  font-weight: $font-weight-semibold;
  margin-bottom: map-get($spacers, 3);
  color: $gray-700;
  flex-shrink: 0;
  padding-bottom: map-get($spacers, 2);
  border-bottom: 1px solid $gray-200;
}

.legend {
  @extend %legendBase;
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(110px, 1fr));
  gap: map-get($spacers, 1) map-get($spacers, 2);
  margin-bottom: map-get($spacers, 3);
  padding: map-get($spacers, 2);
  background-color: $gray-50;
  border: 1px solid $gray-200;
  border-radius: $border-radius;
  font-size: $font-size-base * 0.8;
  flex-shrink: 0;
  color: $gray-600;
}

.legendItem {
  @extend %legendItemBase;
  display: flex;
  align-items: center;
  gap: map-get($spacers, 2);
}

.legendColorBox {
  @extend %legendColorBoxBase;
  display: inline-block;
  width: 15px;
  height: 15px;
  border-radius: $border-radius-sm;
  border: 1px solid rgba($black-color, 0.15);
  flex-shrink: 0;
}

.paletteGrid {
  @extend %paletteGridBase;
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(40px, 1fr));
  gap: map-get($spacers, 2);
  overflow-y: auto;
  flex-grow: 1;
  padding: map-get($spacers, 1) 2px;
}

.paletteButton {
  @extend %paletteButtonBase;
  display: flex;
  justify-content: center;
  align-items: center;
  aspect-ratio: 1 / 1;
  border: 1px solid $gray-300;
  border-radius: $border-radius-sm;
  font-weight: $font-weight-semibold;
  font-size: $font-size-base * 0.9;
  cursor: pointer;
  transition: background-color $transition-fast, border-color $transition-fast, transform $transition-fast, box-shadow $transition-fast, color $transition-fast;
  background-color: $white-color;
  color: $gray-700;

  &:hover:not(:disabled):not(.current) {
    transform: scale(1.08);
    border-color: $primary-color;
    z-index: 1;
    box-shadow: $box-shadow-sm;
  }
  @include focus-outline($primary-color);

  // ReviewPalette buttons are generally not disabled during interaction
  // &.disabled { ... } (can be removed if not applicable to ReviewPalette)
}

// --- Review Status Styles ---
.correct, .legendColorBox.correct {
  background-color: lighten($success-color, 50%); // Even lighter green for review
  border-color: $success-color;
  color: darken($success-color, 20%);
}

.incorrect, .legendColorBox.incorrect {
  background-color: lighten($danger-color, 52%); // Even lighter red
  border-color: $danger-color;
  color: darken($danger-color, 20%);
}

.unattempted, .legendColorBox.unattempted {
  background-color: $gray-200; // Slightly darker gray for unattempted in review
  border-color: $gray-400;
  color: $gray-700;
}

// Optional: If you want to show 'Marked' status distinctly in ReviewPalette
.marked, .legendColorBox.marked { // Same as NavigationPalette's marked
  background-color: lighten($info-color, 48%);
  border-color: $info-color;
  color: darken($info-color, 20%);
}

// Current question indicator (inherits from NavigationPalette's .current style logic)
.current, .legendColorBox.current {
  border-width: 2px;
  border-color: $primary-color !important;
  box-shadow: 0 0 0 3px rgba($primary-color, 0.3), $box-shadow-sm;
  transform: scale(1.1);
  z-index: 2;

  &.legendColorBox {
    background-color: transparent;
    outline: 2px solid $primary-color;
    outline-offset: -2px;
    box-shadow: none;
  }
}
```

---

### components\ReviewPalette\ReviewPalette.tsx

```typescript
// src/components/ReviewPalette/ReviewPalette.tsx
import React from 'react';
import { Question, UserAnswer } from '../../types';
import styles from './ReviewPalette.module.scss'; // Create this SCSS file

interface ReviewPaletteProps {
    questions: Question[];
    userAnswers: UserAnswer;
    currentReviewIndex: number;
    onNavigate: (index: number) => void;
}

// Define review-specific statuses
type ReviewStatus = 'correct' | 'incorrect' | 'unattempted' | 'marked'; // Add 'marked' if you store/infer this

const getReviewStatus = (question: Question, userAnswerData: UserAnswer[number] | undefined): ReviewStatus => {
     const userAnswer = userAnswerData?.selectedOption;
     const correctAnswer = question.correct_answer;
     // Infer marked status if stored (e.g., userAnswerData?.wasMarked) or based on status during exam
     // const isMarked = userAnswerData?.status === 'markedForReview'; // Example

     if (userAnswer === null || userAnswer === undefined) {
        // if (isMarked) return 'marked'; // Handle marked but unattempted
        return 'unattempted';
     }
     if (userAnswer.toLowerCase() === correctAnswer.toLowerCase()) {
         // if (isMarked) return 'marked'; // Handle marked and correct? Maybe just show as correct.
         return 'correct';
     }
     // if (isMarked) return 'marked'; // Handle marked and incorrect? Maybe just show as incorrect.
     return 'incorrect';
};

const getStatusClass = (status: ReviewStatus): string => {
    switch (status) {
        case 'correct': return styles.correct;
        case 'incorrect': return styles.incorrect;
        case 'unattempted': return styles.unattempted;
        case 'marked': return styles.marked; // Example
        default: return styles.unattempted;
    }
};

const ReviewPalette: React.FC<ReviewPaletteProps> = ({
    questions,
    userAnswers,
    currentReviewIndex,
    onNavigate
}) => {
    return (
        <div className={styles.paletteWrapper}>
            <h3 className={styles.title}>Review Palette</h3>
            {/* Optional: Add a small legend for review colors */}
             <div className={styles.legend}>
                 <div className={styles.legendItem}><span className={`${styles.legendColorBox} ${styles.correct}`}></span> Correct</div>
                 <div className={styles.legendItem}><span className={`${styles.legendColorBox} ${styles.incorrect}`}></span> Incorrect</div>
                 <div className={styles.legendItem}><span className={`${styles.legendColorBox} ${styles.unattempted}`}></span> Unattempted</div>
                 {/* Add marked if applicable */}
                 <div className={styles.legendItem}><span className={`${styles.legendColorBox} ${styles.current}`}></span> Current</div>
             </div>

            <div className={styles.paletteGrid}>
                {questions.map((question, index) => {
                    const questionNumber = question.question_number;
                    const answerData = userAnswers[questionNumber];
                    const status = getReviewStatus(question, answerData);
                    const statusClass = getStatusClass(status);
                    const isCurrent = index === currentReviewIndex;

                    return (
                        <button
                            key={questionNumber}
                            onClick={() => onNavigate(index)}
                            className={`
                                ${styles.paletteButton}
                                ReviewPalette.tsx      ${statusClass}
                                ${isCurrent ? styles.current : ''}
                            `}
                            title={`Q${questionNumber} - ${status}`}
                        >
                            {questionNumber}
                        </button>
                    );
                })}
            </div>
        </div>
    );
};

export default ReviewPalette;
```

---

## components\ReviewQuestionDisplay


### components\ReviewQuestionDisplay\ReviewQuestionDisplay.module.scss

```scss
// src/components/ReviewQuestionDisplay/ReviewQuestionDisplay.module.scss
@import '../../styles/variables';
@import '../../styles/mixins';

.reviewQuestionWrapper {
  // Padding is now handled by .questionPanel in ReviewPage.module.scss
  // border: 1px solid $gray-200; // Border also handled by .questionPanel
  // background-color: $component-bg; // Handled by .questionPanel
  // border-radius: $border-radius-lg; // Handled by .questionPanel
  // box-shadow: $box-shadow-sm; // Handled by .questionPanel
  margin-bottom: 0; // No margin if it's the only content in .questionPanel
}

.questionHeader {
  margin-bottom: map-get($spacers, 4); // mb-4
  padding-bottom: map-get($spacers, 3); // pb-3
  border-bottom: 1px solid $gray-200; // Lighter border
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap;
  gap: map-get($spacers, 3); // gap-3
}
.headerActionsContainer {
  display: flex;
  align-items: center; // Vertically align items within this container
  gap: map-get($spacers, 3); // Gap between time spent and AI actions
  margin-left: auto; // Pushes this container to the right in the main flex header
  flex-shrink: 0; // Prevent this container from shrinking
}

.headerActions { 
  flex-shrink: 0; 
  // No changes here if it's just a placeholder for children props
}

.questionNumber { // (Keep existing refined style)
  font-weight: $font-weight-semibold;
  font-size: $font-size-base * 1.2;
  color: $primary-color;
}
.subject {
  font-size: $font-size-base * 0.85;
  color: $gray-600;
  background-color: $gray-100;
  padding: map-get($spacers, 1) map-get($spacers, 2);
  border-radius: $border-radius-pill;
  font-weight: $font-weight-medium;
  margin-left: map-get($spacers, 2); // Add some margin if it follows another tag
  display: inline-flex; // To align icon with text if any
  align-items: center;
}

// NEW or MODIFIED: Difficulty Tag Specifics
.difficultyTag {
  // Inherits some properties from .subject if used together, but can override
  margin-left: map-get($spacers, 2); // Space from previous element
  // Example: Different background color for difficulty
  &.Easy { // If you want to color code by difficulty
    background-color: lighten($success-color, 50%);
    color: darken($success-color, 15%);
    border: 1px solid lighten($success-color, 30%);
  }
  &.Medium {
    background-color: lighten($warning-color, 45%);
    color: darken($warning-color, 20%);
    border: 1px solid lighten($warning-color, 25%);
  }
  &.Hard {
    background-color: lighten($danger-color, 48%);
    color: darken($danger-color, 15%);
    border: 1px solid lighten($danger-color, 30%);
  }
  background-color: lighten($info-color, 45%); // Example: Light blue for difficulty
  color: darken($info-color, 15%);
  border: 1px solid lighten($info-color, 30%);
  padding: map-get($spacers, 1) map-get($spacers, 2);
  border-radius: $border-radius-sm; // Maybe less pill-like than subject/topic
}
.timeSpentDisplay { // (Keep existing refined style)
  font-size: $font-size-base * 0.85;
  color: $text-muted;
  font-weight: $font-weight-medium;
  background-color: $gray-100;
  padding: map-get($spacers, 1) map-get($spacers, 2);
  border-radius: $border-radius-sm;
  border: 1px solid $gray-200;
  display: inline-flex;
  align-items: center;
  gap: map-get($spacers, 1);
  svg.timeIcon { color: $secondary-color; } // Ensure icon has class or target svg
}

.questionText { // (Keep existing refined style from QuestionDisplay)
  margin-bottom: map-get($spacers, 5);
  font-size: $font-size-base * 1.1;
  color: $gray-800;
  line-height: 1.7;
  // Markdown styles within this: p, ul, ol, blockquote, pre, code
}
.optionsList { // (Keep existing refined style from QuestionDisplay)
  display: flex;
  flex-direction: column;
  gap: map-get($spacers, 2); // gap-2
}

// --- Option Item Styling for Review ---
.optionItem {
  border: 1px solid $gray-300;
  border-radius: $border-radius-lg; // Softer radius
  padding: map-get($spacers, 3); // p-3
  display: flex;
  align-items: flex-start; // Align key to top of multi-line text
  gap: map-get($spacers, 3); // gap-3
  position: relative;
  background-color: $white-color;
  opacity: 0.75; // Default slight dim for non-user-selected, non-correct options
  transition: background-color $transition-fast, border-color $transition-fast, opacity $transition-fast;

  &.correctUnselected, // The actual correct answer, user didn't pick it
  &.userCorrect,     // User picked the correct answer
  &.userIncorrect {  // User picked this, but it's wrong
    opacity: 1; // Make these fully opaque
  }
}

.optionKey { // (Keep refined style from QuestionDisplay)
  display: inline-flex;
  justify-content: center;
  align-items: center;
  width: 28px;
  height: 28px;
  border-radius: 50%;
  background-color: $gray-100;
  border: 1px solid $gray-300;
  font-weight: $font-weight-semibold;
  font-size: $font-size-base * 0.9;
  color: $gray-700;
  flex-shrink: 0;
  transition: background-color $transition-fast, color $transition-fast, border-color $transition-fast;
  margin-top: 1px; // Slight adjustment for alignment
}
.optionText { // (Keep refined style from QuestionDisplay)
  flex-grow: 1;
  line-height: 1.6;
  word-break: break-word;
  text-decoration: none; // Ensure no accidental underline from parent links
  color: $text-color; // Default option text color
  // Markdown styles within this
}

// --- Review-specific option visual cues ---
.icon { // Checkmark or X icon
  position: absolute;
  right: map-get($spacers, 3); // Position to the right
  top: 50%;
  transform: translateY(-50%);
  font-size: $font-size-base * 1.3; // Icon size
}
.correctIcon { color: $success-color; }
.incorrectIcon { color: $danger-color; }

// Correct answer (user did NOT select this one)
.correctUnselected {
  border-color: $success-color;
  background-color: lighten($success-color, 55%); // Very light green
  .optionKey {
    border-color: $success-color;
    background-color: $white-color; // Keep key background light
    color: $success-color; // Key text in green
  }
  .optionText { color: darken($success-color, 10%); } // Darker green text
}

// User selected THIS and it IS CORRECT
.userCorrect {
  border-color: $success-color;
  border-width: 2px; // Thicker border for emphasis
  background-color: lighten($success-color, 50%); // Light green
  .optionKey {
    background-color: $success-color;
    color: $white-color;
    border-color: $success-color;
  }
  .optionText { color: darken($success-color, 15%); }
}

// User selected THIS, but it IS INCORRECT
.userIncorrect {
  border-color: $danger-color;
  border-width: 1px; // Normal border, but red
  background-color: lighten($danger-color, 50%); // Light red
  .optionKey {
    background-color: $danger-color;
    color: $white-color;
    border-color: $danger-color;
  }
  .optionText {
    color: darken($danger-color, 15%);
    text-decoration: line-through; // Strike through incorrect selected text
    text-decoration-color: rgba($danger-color, 0.7);
    text-decoration-thickness: 1.5px;
  }
}

// --- Explanation Section ---
.explanation {
  margin-top: map-get($spacers, 5); // mt-5, more space above
  padding: map-get($spacers, 4);    // p-4
  background-color: $gray-50;       // Light gray background
  border-left: 4px solid $info-color; // Accent border (info color)
  border-radius: $border-radius;    // Standard radius
  // box-shadow: $box-shadow-sm;    // Optional subtle shadow

  h4 { // "Explanation:" title
    margin-top: 0;
    margin-bottom: map-get($spacers, 2); // mb-2
    font-weight: $font-weight-semibold;
    color: $info-color; // Title in info color
    font-size: $font-size-base * 1.1;
  }
  // MarkdownRenderer output within explanation
  div > p, // Target paragraphs rendered by MarkdownRenderer
  div > ul,
  div > ol {
    font-size: $font-size-base * 0.95; // Slightly smaller explanation text
    line-height: 1.7;
    color: $gray-700; // Dark gray text
    white-space: pre-wrap; // Respect formatting from Markdown
    margin-bottom: map-get($spacers, 2); // Space between paragraphs in explanation
    &:last-child { margin-bottom: 0; }
  }
}
```

---

### components\ReviewQuestionDisplay\ReviewQuestionDisplay.tsx

```typescript
// src/components/ReviewQuestionDisplay/ReviewQuestionDisplay.tsx
import React from 'react';
import { Question, UserAnswer } from '../../types';
import styles from './ReviewQuestionDisplay.module.scss';
import { FaCheck, FaTimes, FaClock, FaStarHalfAlt } from 'react-icons/fa'; // Added FaStarHalfAlt for difficulty
import { formatDuration } from '../../utils/formatters';
import MarkdownRenderer from '../MarkdownRenderer/MarkdownRenderer';

interface ReviewQuestionDisplayProps {
    question: Question;
    userAnswerData: UserAnswer[number] | undefined;
    showTimeSpent: boolean;
    children?: React.ReactNode;
}

const ReviewQuestionDisplay: React.FC<ReviewQuestionDisplayProps> = ({ question, userAnswerData, showTimeSpent, children }) => {
    const questionNumber = question.question_number;
    const userAnswer = userAnswerData?.selectedOption;
    const correctAnswer = question.correct_answer;
    const timeSpent = userAnswerData?.timeSpentSeconds;

    return (
        <div className={styles.reviewQuestionWrapper}>
            <div className={styles.questionHeader}>
                {/* Left side of header: Question Number, Subject, Topic, Difficulty */}
                <div>
                    <span className={styles.questionNumber}>Question No. {questionNumber}</span>
                    {(question.subject || question.topic) && (
                        <span className={styles.subject}>
                            {question.subject}
                            {question.subject && question.topic ? ' - ' : ''}
                            {question.topic}
                        </span>
                    )}
                    {/* MODIFIED: Display Difficulty */}
                    {question.difficulty && (
                       <span className={`${styles.subject} ${styles.difficultyTag} ${question.difficulty ? styles[question.difficulty] : ''}`}> {/* Re-use subject style or create specific difficultyTag style */}
                            <FaStarHalfAlt style={{ marginRight: '4px', verticalAlign: 'middle', fontSize: '0.9em' }} />
                            {question.difficulty}
                        </span>
                    )}
                </div>

                <div className={styles.headerActionsContainer}>
                    {showTimeSpent && timeSpent !== undefined && timeSpent >= 0 && (
                        <span className={styles.timeSpentDisplay} title="Time spent on this question during the attempt">
                            <FaClock className={styles.timeIcon} /> {formatDuration(timeSpent)}
                        </span>
                    )}
                    {children && <div className={styles.headerActions}>{children}</div>}
                </div>
            </div>

            <div className={styles.questionText}><MarkdownRenderer>{question.question_text}</MarkdownRenderer></div>

            <div className={styles.optionsList}>
                {Object.entries(question.options).map(([key, text]) => {
                    const isCorrect = key.toLowerCase() === correctAnswer.toLowerCase();
                    const isUserSelected = key === userAnswer;
                    let optionClass = styles.optionItem;

                    if (isUserSelected && isCorrect) {
                        optionClass += ` ${styles.userCorrect}`;
                    } else if (isUserSelected && !isCorrect) {
                        optionClass += ` ${styles.userIncorrect}`;
                    } else if (isCorrect) {
                        optionClass += ` ${styles.correctUnselected}`;
                    }

                    return (
                        <div key={key} className={optionClass}>
                            <span className={styles.optionKey}>{key.toUpperCase()}</span>
                            <span className={styles.optionText}><MarkdownRenderer>{text}</MarkdownRenderer></span>
                            {isCorrect && <FaCheck className={`${styles.icon} ${styles.correctIcon}`} title="Correct Answer"/>}
                            {isUserSelected && !isCorrect && <FaTimes className={`${styles.icon} ${styles.incorrectIcon}`} title="Your Incorrect Answer"/>}
                        </div>
                    );
                })}
            </div>

            {question.explanation && (
                <div className={styles.explanation}>
                    <h4>Explanation:</h4>
                    <MarkdownRenderer>{question.explanation}</MarkdownRenderer>
                </div>
            )}
        </div>
    );
};

export default ReviewQuestionDisplay;
```

---

## components\SessionMonitor


### components\SessionMonitor\SessionMonitor.module.scss

```scss
// src/components/SessionMonitor/SessionMonitor.module.scss
@import '../../styles/variables';
@import '../../styles/mixins';

.sessionMonitor {
    margin-top: $spacer * 1.5;
    padding-top: $spacer * 1.5;
    border-top: 1px solid $border-color; // Separator within modal/expanded view

    h4 {
        margin-top: 0;
        margin-bottom: $spacer;
        font-size: $font-size-base * 0.8;
        color: $text-muted;
        font-weight: $font-weight-normal;
        text-align: center;
        color: $dark-color;
    }
}

.monitorLoading, .monitorError, .noParticipants {
    text-align: center;
    padding: $spacer * 1.5 0;
    color: $text-muted;
    font-style: italic;
}
.monitorLoading { font-style: normal; display: flex; align-items: center; justify-content: center; gap: $spacer * 0.5;}
.monitorError { color: $danger-color; font-weight: 500; font-style: normal;}

.participantList {
    list-style: none;
    padding: 0;
    margin: 0 0 $spacer 0;
    max-height: 300px; // Adjust max height for modal/inline view
    overflow-y: auto;
    border: 1px solid lighten($border-color, 5%);
    border-radius: $border-radius-sm;
    background-color: $white-color;

    li {
        padding: $spacer * 0.6 $spacer; // Slightly less padding
        border-bottom: 1px dotted lighten($border-color, 5%);
        display: flex;
        justify-content: space-between;
        flex-direction: column; // Stack primary info and monitoring summary
        align-items: stretch; // Make children take full width
        gap: map-get($spacers, 1);
        font-size: $font-size-base * 0.95;

        &:last-child { border-bottom: none; }

         span:first-child { // Name/icon span
             display: flex;
             align-items: center;
             gap: $spacer * 0.6;
         }

         //&.isCurrentUserHost {
            // Style if needed, though host isn't usually a participant
            // background-color: lighten($info-color, 50%);
        // }
    }
}

.statusIcon {
    font-size: $font-size-base * 0.9;
    flex-shrink: 0;
    // Status colors
    &.joined { color: $secondary-color; }
    &.started { color: $info-color; }
    &.completed { color: $success-color; }
}
.participantPrimaryInfo { // New wrapper for name + status
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 100%;
}

.participantMonitoringSummary {
    font-size: $font-size-base * 0.8;
    color: $text-muted;
    padding: map-get($spacers, 1) 0 map-get($spacers, 1) map-get($spacers, 5); // Indent summary
    border-top: 1px dotted $gray-200; // Separator if desired
    margin-top: map-get($spacers, 1);
    background-color: $gray-50; // Slight background for summary area
    border-radius: $border-radius-sm;
}

.eventSummary {
    display: flex;
    flex-wrap: wrap;
    gap: map-get($spacers, 1) map-get($spacers, 2); // Gap between summary items
}
.summaryItem {
    display: inline-flex;
    align-items: center;
    gap: map-get($spacers, 1);
    background-color: lighten($warning-color, 45%);
    padding: 2px map-get($spacers, 1);
    border-radius: $border-radius-sm;
    color: darken($warning-color, 20%);
    font-weight: $font-weight-medium;
}
.flagIcon {
    color: $warning-color;
    font-size: $font-size-base * 0.85;
}
.noFlags {
    color: $gray-400;
    font-style: italic;
}

.participantStatus {
    font-size: $font-size-base * 0.85;
    color: $text-muted;
    font-style: italic;
    font-weight: 500;
    min-width: 90px;
    text-align: right;
    text-transform: capitalize;
    white-space: nowrap;

    &.joined { color: $text-muted; }
    &.started { color: $info-color; }
    &.completed { color: $success-color; }
}

.participantCount {
    margin-top: $spacer;
    text-align: right;
    font-weight: 500;
    color: $text-muted;
    font-size: $font-size-base * 0.9;
}

```

---

### components\SessionMonitor\SessionMonitor.tsx

```typescript
// src/components/SessionMonitor/SessionMonitor.tsx
import React, { useState, useEffect, useCallback } from 'react'; // Removed Fragment, added useCallback
import styles from './SessionMonitor.module.scss';
import { db } from '../../services/firebase';
import { collection, query, onSnapshot, orderBy } from 'firebase/firestore';
import { ParticipantData, GroupExam, MonitoringEvent } from '../../types';
import { useAuth } from '../../contexts/AuthContext';
import {  FaUserCheck, FaExclamationTriangle } from 'react-icons/fa';
import { getParticipantMonitoringEvents } from '../../services/firestoreService';
import Spinner from '../Spinner/Spinner';
// import { formatTimestamp } from '../../utils/formatters'; // Not used directly in this component

interface SessionMonitorProps {
    sessionId: string;
    sessionDetails: GroupExam | null;
    showMonitoringDetails?: boolean;
}

const SessionMonitor: React.FC<SessionMonitorProps> = ({ sessionId, sessionDetails, showMonitoringDetails = false }) => {
    const { currentUser } = useAuth();
    const [participants, setParticipants] = useState<(ParticipantData & { id: string })[]>([]);
    const [isLoadingParticipants, setIsLoadingParticipants] = useState(true); // Renamed for clarity
    const [error, setError] = useState<string | null>(null);

    const [monitoringEvents, setMonitoringEvents] = useState<{ [participantId: string]: MonitoringEvent[] | 'error' | 'loading' | 'no_events' }>({});
    // No need for a separate isLoadingParticipantEvents string state. We can infer loading from the monitoringEvents[p.id] value.

    // Fetch Participants (existing logic)
    useEffect(() => {
        if (!sessionId) {
            setError("Session ID missing for monitor.");
            setIsLoadingParticipants(false);
            return;
        }
        setIsLoadingParticipants(true);
        setError(null);
        const participantsRef = collection(db, `groupExams/${sessionId}/participants`);
        const q = query(participantsRef, orderBy("joinedAt", "asc"));
        const unsubscribe = onSnapshot(q, (querySnapshot) => {
            const fetchedParticipants: (ParticipantData & { id: string })[] = [];
            querySnapshot.forEach((doc) => fetchedParticipants.push({ id: doc.id, ...(doc.data() as ParticipantData) }));
            setParticipants(fetchedParticipants);
            setIsLoadingParticipants(false);
            setError(null);
        }, (err) => {
           //console.error("Error listening to participants in SessionMonitor:", err);
            setError(err.message || "Could not load participant list.");
            setIsLoadingParticipants(false);
        });
        return () => unsubscribe();
    }, [sessionId]);

    // Fetch Monitoring Events for each participant
    const fetchEventsForParticipant = useCallback(async (participantId: string) => {
        // Don't re-fetch if already loaded, errored, or explicitly 'no_events' unless forced
        if (monitoringEvents[participantId] && monitoringEvents[participantId] !== 'loading') {
            // If data is already there (array), or errored, or explicitly no_events, don't refetch unless desired
            ////console.log(`Events for ${participantId} already processed:`, monitoringEvents[participantId]);
            // return;
        }

        setMonitoringEvents(prev => ({ ...prev, [participantId]: 'loading' }));
        try {
            const events = await getParticipantMonitoringEvents(sessionId, participantId);
            setMonitoringEvents(prev => ({
                ...prev,
                [participantId]: events.length > 0 ? events : 'no_events'
            }));
        } catch (err) {
           //console.error(`Failed to load monitoring events for ${participantId}`, err);
            setMonitoringEvents(prev => ({ ...prev, [participantId]: 'error' }));
        }
    }, [sessionId, monitoringEvents]); // monitoringEvents is included to avoid stale closures but be careful with it.

    useEffect(() => {
        if (showMonitoringDetails && sessionDetails?.monitoringEnabled && participants.length > 0) {
            participants.forEach(p => {
                // Trigger fetch only if not already loading, loaded, or errored for this participant
                if (!monitoringEvents[p.id] || monitoringEvents[p.id] === undefined) { // Only fetch if state is initial/undefined
                    fetchEventsForParticipant(p.id);
                }
            });
        } else if (!showMonitoringDetails) {
            // Optional: Clear events when details are hidden
            // setMonitoringEvents({});
        }
    }, [
        showMonitoringDetails,
        sessionDetails?.monitoringEnabled,
        participants, // This will trigger when participants list changes
        fetchEventsForParticipant, // This is stable due to useCallback
        monitoringEvents // This dependency ensures re-check if events for SOME participant change.
                         // This could be optimized if participants list is stable after initial load.
    ]);


    const summarizeEvents = useCallback((participantId: string): React.ReactNode => {
        const eventState = monitoringEvents[participantId];

        if (eventState === 'loading' || eventState === undefined) { // Check for undefined (not yet processed) too
            return <Spinner size="0.8em" text="Loading flags..." />;
        }
        if (eventState === 'error') {
            return <span className={styles.errorFlags}>Error loading flags</span>;
        }
        if (eventState === 'no_events' || !Array.isArray(eventState) || eventState.length === 0) {
            return <span className={styles.noFlags}>No flags</span>;
        }

        // eventState is now an array of MonitoringEvent
        const eventsArray = eventState as MonitoringEvent[];

        const focusLossCount = eventsArray.filter(e => e.type === 'focus_lost' || e.type === 'focus_lost_on_unmount' || e.type === 'navigation_away').length;
        const copyAttemptCount = eventsArray.filter(e => e.type === 'copy_attempt_blocked').length;
        const pasteAttemptCount = eventsArray.filter(e => e.type === 'paste_attempt_blocked').length;
        const restrictedKeyCount = eventsArray.filter(e => e.type === 'restricted_key_logged').length;

        const summaries: string[] = [];
        if (focusLossCount > 0) summaries.push(`${focusLossCount} Focus Loss`);
        if (copyAttemptCount > 0) summaries.push(`${copyAttemptCount} Copy`);
        if (pasteAttemptCount > 0) summaries.push(`${pasteAttemptCount} Paste`);
        if (restrictedKeyCount > 0) summaries.push(`${restrictedKeyCount} Key`);

        if (summaries.length === 0) return <span className={styles.noFlags}>No notable flags</span>;

        return (
            <div className={styles.eventSummary}>
                {summaries.map((s, i) => (
                    <span key={i} className={styles.summaryItem} title="Detailed logs available in CSV (if enabled) or future UI updates.">
                        <FaExclamationTriangle className={styles.flagIcon}/> {s}
                        {i < summaries.length - 1 ? ", " : ""} {/* Add comma correctly */}
                    </span>
                ))}
            </div>
        );
    }, [monitoringEvents]); // summarizeEvents depends on monitoringEvents


    if (isLoadingParticipants) {
        return <div className={styles.monitorLoading}><Spinner text="Loading participants..." /></div>;
    }
    if (error) {
        return <div className={styles.monitorError}>Error: {error}</div>;
    }

    return (
        <div className={styles.sessionMonitor}>
            <h4>
                Real-time Participant Status
                {showMonitoringDetails && sessionDetails?.monitoringEnabled && (
                    <small> (Monitoring Active)</small>
                )}
            </h4>
            {participants.length === 0 ? (
                <p className={styles.noParticipants}>No participants have joined yet.</p>
            ) : (
                <ul className={styles.participantList}>
                    {participants.map(p => (
                        <li key={p.id} className={p.id === currentUser?.uid ? styles.isCurrentUserHost : ''}>
                            <div className={styles.participantPrimaryInfo}>
                                <span>
                                    <FaUserCheck className={`${styles.statusIcon} ${styles[p.status]}`} />
                                    {p.displayName || `User...${p.id.substring(p.id.length - 6)}`}
                                </span>
                                <span className={`${styles.participantStatus} ${styles[p.status]}`}>
                                    {p.status}
                                    {p.status === 'completed' && p.score !== undefined && ` (${p.score?.toFixed(1)} / ${p.maxScore?.toFixed(1)})`}
                                </span>
                            </div>
                            {showMonitoringDetails && sessionDetails?.monitoringEnabled && (
                                <div className={styles.participantMonitoringSummary}>
                                    {summarizeEvents(p.id)}
                                </div>
                            )}
                        </li>
                    ))}
                </ul>
            )}
            <div className={styles.participantCount}>Total Joined: {participants.length}</div>
        </div>
    );
};

export default SessionMonitor;
```

---

## components\Spinner


### components\Spinner\Spinner.module.scss

```scss
// src/components/Spinner/Spinner.module.scss
@import '../../styles/variables'; // If needing variables like primary color

.spinnerContainer {
    display: inline-flex; // Display inline by default, can be overridden
    align-items: center;
    gap: $spacer * 0.5; // Space between spinner icon and text
    color: inherit; // Inherit color by default
    vertical-align: middle; // Align well with surrounding text
}

// .spin-icon is already defined globally in App.scss, no need to repeat keyframes
// Just ensure it targets FaSpinner correctly if needed, but the global one should work.

.spinnerText {
    // Add specific styling for the text if needed
    font-weight: 500;
}

// Optional: Define variant colors if implemented in the component
// .primary { color: $primary-color; }
// .secondary { color: $secondary-color; }
// .light { color: $light-color; } // Use on dark backgrounds

// Screen reader only class (add if not globally defined)
// .sr-only { ... }
```

---

### components\Spinner\Spinner.tsx

```typescript
// src/components/Spinner/Spinner.tsx
import React from 'react';
import { FaSpinner } from 'react-icons/fa';
import styles from './Spinner.module.scss'; // We'll create this SCSS module

interface SpinnerProps {
    /** Optional: Adjust spinner size (defaults to 1em) */
    size?: number | string;
    /** Optional: Text to display next to the spinner */
    text?: string;
    /** Optional: Additional CSS class names */
    className?: string;
    /** Optional: Style variant (e.g., for different colors) - TBD if needed */
    // variant?: 'primary' | 'secondary' | 'light';
    /** Optional: For accessibility, describing the loading region */
    'aria-label'?: string;
}

const Spinner: React.FC<SpinnerProps> = ({
    size = '1em', // Default size
    text,
    className = '',
    'aria-label': ariaLabel = 'Loading...', // Default accessible label
    // variant = 'primary', // Default variant if implementing color options
}) => {
    // Combine classes: component base class, global spin animation, optional custom class
    const spinnerClasses = `${styles.spinnerContainer} ${className}`;
    // const iconClasses = `spin-icon ${styles[variant] || ''}`; // Combine global animation class + potential variant class
    const iconClasses = `spin-icon`; // Use global .spin-icon from App.scss

    return (
        <span className={spinnerClasses} role="status" aria-live="polite">
            <FaSpinner className={iconClasses} size={size} aria-hidden="true" />
            {text && <span className={styles.spinnerText} aria-label={ariaLabel}>{text}</span>}
            {!text && <span className="sr-only">{ariaLabel}</span>} {/* Screen reader only text if no visual text */}
        </span>
    );
};

// Helper class for screen reader only text
// Can be defined globally or here if needed
// .sr-only {
//   position: absolute;
//   width: 1px;
//   height: 1px;
//   padding: 0;
//   margin: -1px;
//   overflow: hidden;
//   clip: rect(0, 0, 0, 0);
//   white-space: nowrap;
//   border-width: 0;
// }

export default Spinner;
```

---

## components\SubmitExamButton


### components\SubmitExamButton\SubmitExamButton.module.scss

```scss
// src/components/SubmitExamButton/SubmitExamButton.module.scss
@import '../../styles/variables';
@import '../../styles/mixins';

.submitButton {
  @include button-variant($danger-color); // Solid danger (red) button
  width: 100%; // Take full width of its container (.submitArea)
  padding: map-get($spacers, 3); // p-3 (16px), generous padding
  font-size: $font-size-base * 1.05; // Slightly larger text
  font-weight: $font-weight-semibold; // Bolder
  gap: map-get($spacers, 2); // gap-2 for icon/spinner and text

  // Disabled state is handled by the button-variant mixin
  // &:disabled { ... }

  .icon {
    font-size: $font-size-base * 1.2;
  }
}

// Spinner animation and .spinner class are global from App.scss
// No need for modal styles here as it uses the ConfirmationModal component

// --- Styles for the content passed to ConfirmationModal (if needed) ---
// Example: If confirmationContent in SubmitExamButton.tsx needs specific styling
// .confirmationSummary {
//   text-align: left;
//   font-size: $font-size-base * 0.9;
//   ul {
//     list-style: none;
//     padding-left: map-get($spacers, 2);
//     margin-bottom: map-get($spacers, 3);
//     li { margin-bottom: map-get($spacers, 1); }
//   }
//   strong { font-weight: $font-weight-semibold; }
//   .finalWarning {
//     margin-top: map-get($spacers, 3);
//     font-weight: $font-weight-semibold;
//     color: $danger-color;
//   }
// }
```

---

### components\SubmitExamButton\SubmitExamButton.tsx

```typescript
// src/components/SubmitExamButton/SubmitExamButton.tsx
import React, { useState } from 'react';
import { useExam } from '../../contexts/ExamContext';
import styles from './SubmitExamButton.module.scss';
import { FaCheckCircle } from 'react-icons/fa'; 
import { toast } from 'react-toastify';
import ConfirmationModal from '../Modal/ConfirmationModal';
import Spinner from '../Spinner/Spinner';

const SubmitExamButton: React.FC = () => {
    const { submitExam, examStatus, questions, userAnswers } = useExam();
    const [isConfirming, setIsConfirming] = useState(false);

    const isExamActive = examStatus === 'active';
    const isSubmitting = examStatus === 'submitting';

    // --- Calculate Summary for Confirmation ---
    let answeredCount = 0;
    let notAnsweredCount = 0; // Includes marked but not answered
    let markedCount = 0;
    let notVisitedCount = 0;

    Object.values(userAnswers).forEach(ans => {
        switch(ans.status) {
            case 'answered':
                answeredCount++;
                break;
            case 'notAnswered':
                notAnsweredCount++;
                break;
            case 'markedForReview':
                markedCount++;
                // Also count as not answered if no option selected
                if (!ans.selectedOption) {
                    notAnsweredCount++;
                } else {
                    // Optional: could count as 'answered' in summary if selected
                    answeredCount++;
                }
                break;
            case 'notVisited':
                notVisitedCount++;
                break;
        }
    });
    
    // Recalculate notAnswered based on total to avoid double counting marked+answered
    const totalQuestionsCount = questions.length;
    notVisitedCount = totalQuestionsCount - answeredCount - notAnsweredCount;
    // Ensure counts add up correctly, adjusting notAnswered if needed (especially if marked+answered logic changes)
    notAnsweredCount = totalQuestionsCount - answeredCount - notVisitedCount;


    const confirmationContent = (
        <div className={styles.confirmationSummary}> {/* Apply a new class */}
          <p><strong>Summary of your attempt:</strong></p>
                  <ul style={{ listStyle: 'none', paddingLeft: '10px', marginBottom: '1rem' }}>
                      <li> Answered: {answeredCount}</li>
                      <li> Not Answered: {notAnsweredCount}</li>
                      <li> Marked for Review: {markedCount}</li>
                      <li> Not Visited: {notVisitedCount}</li>
                      <li style={{ borderTop: '1px solid #eee', paddingTop: '5px', marginTop: '5px' }}>
                         <strong>Total: {totalQuestionsCount}</strong>
                      </li>
                  </ul>
                  <p className={styles.finalWarning}> {/* Use variable if possible */}
                      Once submitted, you cannot return to the exam. Are you sure you want to proceed?
                  </p>
              </div>
           );
    const handleSubmitClick = () => {
        if (!isExamActive) return;
        setIsConfirming(true); // Open confirmation dialog
    };

    const handleConfirmSubmit = async () => {
        setIsConfirming(false);
        if (!isExamActive) return; // Re-check just in case
        try {
            await submitExam();
            // Navigation should happen inside submitExam context function
        } catch (error) {
            toast.error("Submission failed. Please check your internet connection and try again.");
            //console.error("Submission failed:", error);
            // Maybe show an error message to the user here
            // The context state might also hold an error
        }
    };

    const handleCancelSubmit = () => {
        setIsConfirming(false);
    };

    return (
        <>
            <button
                onClick={handleSubmitClick}
                disabled={!isExamActive || isSubmitting} // Disable if not active or already submitting
                className={styles.submitButton}
                title={
                                   isSubmitting ? "Submission in progress..." :
                                   !isExamActive ? "Exam is not currently active" :
                                   "Submit the exam and view results"
                               }
            >
                {isSubmitting ? (
                    <>
                         <Spinner size="1.1em" /> Submitting... {/* Adjusted size slightly */}
                    </>
                ) : (
                    <>
                        <FaCheckCircle className={styles.icon} /> Submit Exam
                    </>
                )}
            </button>

            {/* Replace the inline modal with our new ConfirmationModal component */}
            <ConfirmationModal
                isOpen={isConfirming}
                title="Submit Exam"
                customContent={confirmationContent}
                onConfirm={handleConfirmSubmit}
                onCancel={handleCancelSubmit}
                confirmText="Yes, Submit Now"
                cancelText="No, Continue Exam"
                confirmButtonVariant="danger"
                size="md"
                
            />
        </>
    );
};

export default SubmitExamButton;
```

---

### constants.ts

```typescript
// Exam Defaults
export const DEFAULT_EXAM_TIME_LIMIT_MINS = 120;
export const DEFAULT_MARKS_PER_CORRECT = 4; // Default positive marks
export const DEFAULT_ENABLE_NEGATIVE_MARKING = true; // Default enable state
export const DEFAULT_NEGATIVE_MARKS_PER_INCORRECT = 1; // Default negative value (will be subtracted)
export const DEFAULT_TRACK_QUESTION_TIME = true;
```

---

## contexts


### contexts\AuthContext.tsx

```typescript
// src/contexts/AuthContext.tsx
import React, { createContext, useContext, useEffect, useState, useMemo, useRef, useCallback, ReactNode } from 'react';
import { User as FirebaseUser } from 'firebase/auth';
import { doc, onSnapshot, Timestamp } from 'firebase/firestore';
import { FirebaseError } from 'firebase/app';
import { logEvent } from 'firebase/analytics';
import {
    loginUser as firebaseLoginUser,
    onAuthUserStateChanged,
    auth,
    logoutUser as firebaseLogoutUser,
    db,
    analytics
} from '../services/firebase';
import { AuthContextType, UserData } from '../types';
import Spinner from '../components/Spinner/Spinner';
import RegistrationModal from '../components/RegistrationModal/RegistrationModal';
import { toast } from 'react-toastify';

// Update AuthContextType definition
export interface ExtendedAuthContextType extends AuthContextType {
  isLoginModalOpen: boolean;
  loginModalMessage: string | null;
  openLoginModal: (message: string, returnTo?: string) => void;
  closeLoginModal: () => void;
  isRegistrationModalOpen: boolean;
  registrationModalReturnToPath: string | null; // Store the path Examify wants user back to
  openRegistrationModal: (returnToPath?: string) => void;
  closeRegistrationModal: () => void;
}

const DELETION_GRACE_PERIOD_MS = 5 * 1000;

export const AuthContext = createContext<ExtendedAuthContextType>({
  currentUser: null,
  userData: null,
  isLoading: true,
  login: async () => {},
  logout: async () => {},
  isLoginModalOpen: false,
  loginModalMessage: null,
  openLoginModal: () => {},
  closeLoginModal: () => {},
  isRegistrationModalOpen: false,
  registrationModalReturnToPath: null,
  openRegistrationModal: () => {},
  closeRegistrationModal: () => {},
});

interface AuthProviderProps {
    children: ReactNode;
}

export const AuthProvider: React.FC<AuthProviderProps> = ({ children }) => {
    const [currentUser, setCurrentUser] = useState<FirebaseUser | null>(null);
    const [userData, setUserData] = useState<UserData | null>(null);
    const [isLoading, setIsLoading] = useState<boolean>(true);
    
    // Modal state
    const [isLoginModalOpen, setIsLoginModalOpen] = useState<boolean>(false);
    const [loginModalMessage, setLoginModalMessage] = useState<string | null>(null);

    const [loginReturnToPath, setLoginReturnToPath] = useState<string | null>(null);
    const [isRegistrationModalOpen, setIsRegistrationModalOpen] = useState<boolean>(false);
    const [registrationModalReturnToPath, setRegistrationModalReturnToPath] = useState<string | null>(null);

    const userDocListenerUnsubscribe = useRef<(() => void) | null>(null);
    const gracePeriodTimerRef = useRef<NodeJS.Timeout | null>(null);
    const prevPerkLevelRef = useRef<string | null>(null);
    const prevPerkExpiryRef = useRef<Timestamp | Date | null>(null);

    // Modal Control Functions
    const openLoginModal = useCallback((message: string, returnTo?: string) => {
        logEvent(analytics, 'login_modal_opened');
        setLoginModalMessage(message);
        setLoginReturnToPath(returnTo || null);
        setIsLoginModalOpen(true);
    }, []);

    const closeLoginModal = useCallback(() => {
        setIsLoginModalOpen(false);
        setLoginModalMessage(null);
        setLoginReturnToPath(null);
    }, []);

const openRegistrationModal = useCallback((returnToPath: string = '/select-exam') => {
        logEvent(analytics, 'registration_modal_opened', { return_to_path: returnToPath });
        setRegistrationModalReturnToPath(returnToPath);
        setIsRegistrationModalOpen(true);
    }, []);

    const closeRegistrationModal = useCallback(() => {
        setIsRegistrationModalOpen(false);
        setRegistrationModalReturnToPath(null);
    }, []);

    const handleRegistrationSuccess = useCallback((data: { email?: string; returnTo?: string }) => {
        closeRegistrationModal();
        toast.success(
            <div>
                <h4>Registration Successful!</h4>
                <p>Your MyServices Portal account has been created. Please log in to Examify now.</p>
            </div>, 
            { autoClose: 5000 }
        );
        // Open login modal, passing the original returnTo path if available from MSP postMessage
        // The `data.returnTo` here is the full URL Examify initially sent to MSP.
        // We need to extract the path part for Examify's internal routing after login.
        let examifyPathFromMspReturnTo = '/select-exam'; // Default
        if (data.returnTo) {
            try {
                const url = new URL(data.returnTo);
                if (url.origin === window.location.origin) { // Ensure it's for Examify
                    examifyPathFromMspReturnTo = url.pathname + url.search + url.hash;
                }
            } catch (e) { console.warn("Could not parse returnTo from MSP:", data.returnTo); }
        }
        openLoginModal("Please log in with your new MyServices Portal credentials.", examifyPathFromMspReturnTo);
    }, [closeRegistrationModal, openLoginModal]);

    useEffect(() => {
        //console.log("[AuthContext] Setting up auth state listener.");
 
         if (gracePeriodTimerRef.current) {
             clearTimeout(gracePeriodTimerRef.current);
             gracePeriodTimerRef.current = null;
         }
 
         const unsubscribeAuth = onAuthUserStateChanged(async (user) => {
 
            //console.log("[AuthContext] Auth listener triggered. Firebase User:", user ? user.uid : 'null');
 
             if (userDocListenerUnsubscribe.current) {
                //console.log("[AuthContext] Unsubscribing previous user document listener.");
                 userDocListenerUnsubscribe.current();
                 userDocListenerUnsubscribe.current = null;
             }
 
             if (gracePeriodTimerRef.current) {
                 clearTimeout(gracePeriodTimerRef.current);
                 gracePeriodTimerRef.current = null;
             }
              // Reset prevPerkLevelRef if user changes or logs out
              if (!user || (currentUser && currentUser.uid !== user.uid)) {
                 prevPerkLevelRef.current = null;
                 prevPerkExpiryRef.current = null;
             }
 
             if (user) {
                //console.log(`[AuthContext] User ${user.uid} logged in. Setting up Firestore listener.`);
                 const userDocRef = doc(db, 'users', user.uid);
 
                 userDocListenerUnsubscribe.current = onSnapshot(userDocRef, (docSnap) => {
                    //console.log(`[AuthContext] Firestore snapshot received for user ${user.uid}. Exists: ${docSnap.exists()}`);
                     if (docSnap.exists()) {
                         const data = docSnap.data();
                         const fetchedData: UserData = {
                             uid: user.uid,
                             email: data.email ?? user.email ?? '', // Fallback to auth email
                             username: data.username ?? '',
                             displayName: data.displayName ?? user.displayName ?? '', // Fallback
                             services: data.services ?? [],
                             status: data.status ?? 'active',
                             // Ensure Timestamp conversion for all date fields
                             createdAt: data.createdAt instanceof Timestamp ? data.createdAt.toDate() : (data.createdAt ? new Date(data.createdAt) : null),
                             updatedAt: data.updatedAt instanceof Timestamp ? data.updatedAt.toDate() : (data.updatedAt ? new Date(data.updatedAt) : null),
                             deletedAt: data.deletedAt instanceof Timestamp ? data.deletedAt.toDate() : (data.deletedAt ? new Date(data.deletedAt) : null),
                             perkLevel: data.perkLevel ?? 'free',
                             perkExpiry: data.perkExpiry instanceof Timestamp ? data.perkExpiry.toDate() : (data.perkExpiry ? new Date(data.perkExpiry) : null),
                             currentBillingCycle: data.currentBillingCycle ?? null,
                         };
                        //console.log(`[AuthContext] User data fetched/updated for ${user.uid}:`, fetchedData);
 
                         let accessDeniedReason: string | null = null;
 
                         if (fetchedData.status === 'suspended') {
                             accessDeniedReason = "This account has been suspended.";
                         } else if (fetchedData.status === 'deleted') {
                             const now = new Date().getTime();
                             const deletedAtTime = fetchedData.deletedAt instanceof Timestamp 
                             ? fetchedData.deletedAt.toDate().getTime() 
                             : (fetchedData.deletedAt ? fetchedData.deletedAt.getTime() : 0);
 
 
                             if (deletedAtTime > 0 && (now - deletedAtTime < DELETION_GRACE_PERIOD_MS)) {
                                //console.log(`[AuthContext] User ${user.uid} 'deleted' but WITHIN grace period.`);
                                 setCurrentUser(user);
                                 setUserData(fetchedData);
                                 prevPerkLevelRef.current = fetchedData.perkLevel; // Set initial prevPerkLevel
                                 
                                 // Close login modal if it's open on successful auth
                                 closeLoginModal();
 
                                 // Handle login return path navigation
                                 if (loginReturnToPath) {
                                     const navigateTo = loginReturnToPath;
                                     setLoginReturnToPath(null); // Clear it after use
                                     //console.log(`[AuthContext] Login successful (grace period), intended return to path: ${navigateTo}`);
                                     
                                     // Use setTimeout to ensure state updates have settled
                                     setTimeout(() => {
                                         // If you have access to navigate function from react-router-dom:
                                         // navigate(navigateTo);
                                         
                                         // Or if using window.location (less preferred for SPA):
                                         // window.location.href = navigateTo;
                                         
                                         // For now, just logging - replace with actual navigation
                                         console.log(`[AuthContext] Should navigate to: ${navigateTo}`);
                                     }, 100);
                                 }
 
                                 if (gracePeriodTimerRef.current) clearTimeout(gracePeriodTimerRef.current);
                                 gracePeriodTimerRef.current = setTimeout(() => {
                                    //console.log(`[AuthContext] Grace period ended for ${user.uid}. Forcing logout.`);
                                     toast.error("Account deletion grace period expired. Access revoked.", { autoClose: 10000 });
                                     setCurrentUser(null);
                                     setUserData(null);
                                     prevPerkLevelRef.current = null;
                                     if (auth.currentUser?.uid === user.uid) {
                                         firebaseLogoutUser().catch(err =>console.error("Error during grace period forced logout:", err));
                                     }
                                 }, DELETION_GRACE_PERIOD_MS - (now - deletedAtTime) + 200); // Ensure a positive delay
                             } else {
                                 accessDeniedReason = "This account has been deleted. Access revoked.";
                             }
                         }
 
                         if (accessDeniedReason) {
                            //console.log(`[AuthContext] Access DENIED for ${user.uid}: ${accessDeniedReason}`);
                             toast.error(accessDeniedReason, { autoClose: 10000 });
                             setCurrentUser(null);
                             setUserData(null);
                             prevPerkLevelRef.current = null;
                             prevPerkExpiryRef.current = null;
                             if (auth.currentUser?.uid === user.uid) { // Check if it's still the same user
                                 firebaseLogoutUser().catch(err => console.error("[AuthContext] Error during forced logout (status denied):", err));
                             }
                         } else if (fetchedData.status === 'active' || (fetchedData.status === 'deleted' /* and within grace*/)) {
                            //console.log(`[AuthContext] Setting state for user ${user.uid} (status: ${fetchedData.status})`);
 
                             const now = new Date();
                             const currentPerkLevel = fetchedData.perkLevel;
                             const currentPerkExpiry = fetchedData.perkExpiry;
                             const isActuallyExpired = currentPerkExpiry && currentPerkExpiry < now;
                             
                             // Determine the effective perk level after considering expiry
                             const effectivePerkLevel = (isActuallyExpired || currentPerkLevel === 'free') ? 'free' : currentPerkLevel;
 
                             // Compare with previous *effective* perk level
                             const previousEffectivePerkLevel = (prevPerkExpiryRef.current && prevPerkExpiryRef.current < now) ? 'free' : prevPerkLevelRef.current;
 
                             // Only show toast if there was a previous state to compare against (not first load for this user session)
                             // And if the *effective* perk level has changed
                             if (previousEffectivePerkLevel !== null && effectivePerkLevel !== previousEffectivePerkLevel) {
                                //console.log(`[AuthContext] Effective perk level changed: ${previousEffectivePerkLevel} -> ${effectivePerkLevel}`);
                                 let toastMessage = "";
                                 let toastType: "success" | "info" | "warning" | "error" = "info";
 
                                 if (isActuallyExpired && previousEffectivePerkLevel !== 'free') {
                                     toastMessage = `Your '${previousEffectivePerkLevel}' subscription has expired. You're now on the Free plan.`;
                                     toastType = "warning";
                                 } else if (effectivePerkLevel === 'free' && previousEffectivePerkLevel !== 'free') {
                                     toastMessage = "Your premium subscription has ended. You're now on the Free plan.";
                                     toastType = "info";
                                 } else if (effectivePerkLevel !== 'free' && previousEffectivePerkLevel === 'free') {
                                     toastMessage = `Thank you for subscribing! You now have ${effectivePerkLevel} access.`;
                                     toastType = "success";
                                 } else if (effectivePerkLevel !== 'free') { // Change between paid tiers
                                     toastMessage = `Your subscription has changed to ${effectivePerkLevel}.`;
                                     toastType = "info";
                                 }
 
                                 if (toastMessage) {
                                     toast[toastType](toastMessage, { autoClose: 8000 });
                                 }
                             }
                             setCurrentUser(user);
                             setUserData(fetchedData);
                             
                             // Close login modal if it's open on successful auth
                             closeLoginModal();
                             
                             // Handle login return path navigation for active users
                             if (loginReturnToPath) {
                                 const navigateTo = loginReturnToPath;
                                 setLoginReturnToPath(null); // Clear it after use
                                 //console.log(`[AuthContext] Login successful, intended return to path: ${navigateTo}`);
                                 
                                 // Use setTimeout to ensure state updates have settled
                                 setTimeout(() => {
                                     // If you have access to navigate function from react-router-dom:
                                     // navigate(navigateTo);
                                     
                                     // Or if using window.location (less preferred for SPA):
                                     // window.location.href = navigateTo;
                                     
                                     // For now, just logging - replace with actual navigation
                                     console.log(`[AuthContext] Should navigate to: ${navigateTo}`);
                                 }, 100);
                             }
                             
                             prevPerkLevelRef.current = currentPerkLevel; // Store raw perk level
                             prevPerkExpiryRef.current = currentPerkExpiry; // Store raw expiry
                         }
                     } else {
                        //console.warn(`[AuthContext] User ${user.uid} found in Auth, but NO data in Firestore! Logging out.`);
                         toast.error("Your account data could not be loaded. This might be a temporary issue or an account setup problem. Please contact support if this persists.", { autoClose: 10000 });
                         setCurrentUser(null);
                         setUserData(null);
                         prevPerkLevelRef.current = null;
                         prevPerkExpiryRef.current = null;
                         if (auth.currentUser?.uid === user.uid) {
                              firebaseLogoutUser().catch(err =>console.error("[AuthContext] Error during forced logout (no Firestore doc):", err));
                         }
                     }
                     setIsLoading(prev => (prev ? false : prev));
                 }, (error) => {
                    //console.error(`[AuthContext] Error listening to user document (${user.uid}):`, error);
                     toast.error("There was an issue loading your user details. Please try refreshing the page. If the problem continues, contact support.");
                     setCurrentUser(null);
                     setUserData(null);
                     prevPerkLevelRef.current = null;
                     prevPerkExpiryRef.current = null;
                     if (auth.currentUser?.uid === user.uid) {
                         firebaseLogoutUser().catch(err =>console.error("[AuthContext] Error during forced logout (listener error):", err));
                     }
                     setIsLoading(false);
                 });
             } else {
                //console.log("[AuthContext] No Firebase user detected. Setting state to null.");
                 setCurrentUser(null);
                 setUserData(null);
                 prevPerkLevelRef.current = null;
                 prevPerkExpiryRef.current = null;
                 setIsLoading(false);
             }
         });
 
         return () => {
            //console.log("[AuthContext] Cleaning up auth state listener.");
             unsubscribeAuth();
             if (userDocListenerUnsubscribe.current) {
                //console.log("[AuthContext] Cleaning up active user document listener.");
                 userDocListenerUnsubscribe.current();
             }
             if (gracePeriodTimerRef.current) {
                 clearTimeout(gracePeriodTimerRef.current);
             }
             prevPerkLevelRef.current = null;
             prevPerkExpiryRef.current = null;
         };
         // eslint-disable-next-line
     }, [closeLoginModal, loginReturnToPath, setLoginReturnToPath]); // Add loginReturnToPath and setLoginReturnToPath to dependencies

    const login = useMemo(() => async (email: string, password: string) => {
        try {
            await firebaseLoginUser(email, password);
            logEvent(analytics, 'login', { method: 'Email/Password' });
            // Listener will handle state updates and closing modal
        } catch (error: any) {
           //console.error("[AuthContext][Login] Raw Error:", error);
            let userFriendlyMessage = 'Login failed. Please check connection or try again later.';
            if (error instanceof FirebaseError || (error && error.code)) {
                switch (error.code) {
                    case 'auth/user-not-found':
                    case 'auth/wrong-password':
                    case 'auth/invalid-credential':
                        userFriendlyMessage = 'Incorrect email or password.'; break;
                    case 'auth/too-many-requests':
                        userFriendlyMessage = 'Too many attempts. Access temporarily blocked.'; break;
                        default: userFriendlyMessage = `An unexpected error occurred during login. Please try again. (Code: ${error.code})`;
                }
            } else if (error.message?.includes("account has been suspended") || error.message?.includes("account has been deleted")) {
                userFriendlyMessage = error.message; // Pass through specific messages
            }
            logEvent(analytics, 'login_failed', {
                method: 'Email/Password',
                error_message: userFriendlyMessage.substring(0, 100)
            });
            
            throw new Error(userFriendlyMessage);
        }
    }, []);

    const logout = useMemo(() => async () => {
        try {
            const userId = currentUser?.uid; // Get user ID before logging out
            
            if (gracePeriodTimerRef.current) {
                clearTimeout(gracePeriodTimerRef.current);
                gracePeriodTimerRef.current = null;
            }
            
            await firebaseLogoutUser();
            
            if (userId) {
                logEvent(analytics, 'logout', { user_id_truncated: userId.substring(0, 8) });
            }
            
            closeLoginModal();
            // Listener will handle state updates
        } catch (error: any) {
            logEvent(analytics, 'logout_failed');
            toast.error(`Logout failed. Please check your connection and try again.`);
            throw error;
        }
    }, [currentUser, closeLoginModal]);

    const value: ExtendedAuthContextType = useMemo(() => ({
        currentUser,
        userData,
        isLoading,
        login,
        logout,
        // Modal values/functions
        isLoginModalOpen,
        loginModalMessage,
        openLoginModal,
        closeLoginModal,
        isRegistrationModalOpen,
        registrationModalReturnToPath,
        openRegistrationModal,
        closeRegistrationModal,
    }), [
        currentUser, 
        userData, 
        isLoading, 
        login,
        logout,
        isLoginModalOpen,
        loginModalMessage,
        openLoginModal,
        closeLoginModal,
        isRegistrationModalOpen, 
        registrationModalReturnToPath, 
        openRegistrationModal, 
        closeRegistrationModal
    ]);

    if (isLoading && !currentUser) { // Show full page spinner only on initial load and no user
        return (
            <div style={{ display: 'flex', justifyContent: 'center', alignItems: 'center', height: '100vh', width: '100vw', position: 'fixed', top: 0, left: 0, backgroundColor: 'rgba(255,255,255,0.8)', zIndex: 9999 }}>
                <Spinner size="3em" text="Initializing session..." />
            </div>
        );
    }

    return (
        <AuthContext.Provider value={value}>
            {children}
            {/* Render RegistrationModal globally so it can be opened from anywhere */}
            <RegistrationModal 
                isOpen={isRegistrationModalOpen}
                onClose={closeRegistrationModal}
                onRegistrationSuccess={handleRegistrationSuccess}
                initialReturnToPath={registrationModalReturnToPath || '/select-exam'}
            />
        </AuthContext.Provider>
    );
};

// Custom hook to use the context
export const useAuth = (): ExtendedAuthContextType => {
    const context = useContext(AuthContext);
    if (context === undefined) {
        throw new Error('useAuth must be used within an AuthProvider');
    }
    return context;
}; 
```

---

### contexts\ExamContext.tsx

```typescript
// src/contexts/ExamContext.tsx
import React, { createContext, useState, useContext, useCallback, useEffect} from 'react';
import { useNavigate } from 'react-router-dom';
import { Question, ExamSettings, UserAnswer, AttemptResult, QuestionStatus, GroupExam } from '../types'; // Added GroupExam type
import { saveAttemptResult, getGroupExam, completeParticipantAttempt, startParticipantAttempt, getAllUserAttempts} from '../services/firestoreService'; // Added new service functions
import { useAuth } from './AuthContext';
import { analytics } from '../services/firebase'; 
import { logEvent } from 'firebase/analytics';
import { toast } from 'react-toastify';
import { DEFAULT_MARKS_PER_CORRECT, DEFAULT_NEGATIVE_MARKS_PER_INCORRECT } from '../constants';

import { useUserPerks } from '../hooks/useUserPerks';
// --- Define Context State and Actions ---

type ExamStatus = 'submitting' | 'idle' | 'loading' | 'ready' | 'active' | 'paused' | 'finished' | 'loading_group_session'; // Added 'loading_group_session'

interface ExamContextState {
    examStatus: ExamStatus;
    questions: Question[];
    examSettings: ExamSettings | null;
    currentQuestionIndex: number;
    userAnswers: UserAnswer;
    startTime: number | null; // Timestamp ms when exam started
    endTime: number | null; // Timestamp ms when exam ended or submitted
    elapsedTime: number; // Seconds elapsed so far
    remainingTime: number | null; // Seconds remaining (if timed)
    examIdentifier: string | null; // e.g., "nimcet_2023" or "user_upload_..."
    examTitle: string | null;
    examPath: string | null; // Added path for GitHub repo
    isUserUploaded: boolean;
    error: string | null;
    groupSessionId: string | null; // NEW: Track if currently in a group session
    groupSessionDetails: GroupExam | null; // NEW: Store fetched group session details
    originalQuestionJsonString: string | null;
}

interface ExamContextActions {
    loadExam: (
        identifier: string, 
        type: 'official' | 'user', 
        sourceData: File | string, 
        title: string, 
        path: string | null
    ) => Promise<void>;
    startExam: (settings: ExamSettings) => void;
    loadAndStartGroupExam: (sessionId: string) => Promise<void>; // NEW: For group sessions
    selectAnswer: (questionNumber: number, selectedOption: string | null) => void;
    toggleMarkForReview: (questionNumber: number) => void;
    updateQuestionTime: (questionNumber: number, timeSpentIncrement: number) => void;
    navigateToQuestion: (index: number) => void;
    nextQuestion: () => void;
    previousQuestion: () => void;
    submitExam: () => Promise<void>; // Make async for saving results
    clearExamState: () => void;
    // pauseExam: () => void; // Optional
    // resumeExam: () => void; // Optional
}

type ExamContextType = ExamContextState & ExamContextActions;

// --- Default State ---
const initialExamState: ExamContextState = {
    examStatus: 'idle',
    questions: [],
    examSettings: null,
    currentQuestionIndex: 0,
    userAnswers: {},
    startTime: null,
    endTime: null,
    elapsedTime: 0,
    remainingTime: null,
    examIdentifier: null,
    examTitle: null,
    examPath: null, // Initialize path as null
    isUserUploaded: false,
    error: null,
    groupSessionId: null, 
    groupSessionDetails: null, 
    originalQuestionJsonString: null,
};

// --- Create Context ---
const ExamContext = createContext<ExamContextType | undefined>(undefined);

// --- Create Provider ---
export const ExamProvider: React.FC<{ children: React.ReactNode }> = ({ children }) => {
    const [state, setState] = useState<ExamContextState>(initialExamState);
    const { currentUser } = useAuth(); // Get current user for saving results (added userData)
    const { limits: perkLimits, isLoadingPerks, perksEnabledGlobally , features: perkFeatures} = useUserPerks();
    const navigate = useNavigate();
    const timerIntervalRef = React.useRef<NodeJS.Timeout | null>(null);
    const QUESTIONS_REPO_BASE_URL = 'https://raw.githubusercontent.com/Samkarya/online-exam-questions/refs/heads/main/'; // Replace with your repo

    // --- Utility: Stop Timer ---
    const stopTimer = useCallback(() => {
        if (timerIntervalRef.current) {
            clearInterval(timerIntervalRef.current);
            timerIntervalRef.current = null;
        }
    }, []);

    // --- Utility: Reset State ---
    const clearExamState = useCallback(() => {
        //console.log("clearExamState called, stopping timer."); // Add log
        stopTimer(); // Call stopTimer FIRST
        setState(initialExamState); // Then reset state
    }, [stopTimer]); // Dependency needed

    // --- Load Exam Data ---
    const loadExam = useCallback(async (
        identifier: string, 
        type: 'official' | 'user', 
        sourceData: File | string,
        title: string,
        path: string | null
    ) => {
        clearExamState(); // Clear previous state before loading new exam
        setState(prevState => ({ 
            ...initialExamState, 
            examStatus: 'loading', 
            error: null, 
            examIdentifier: identifier, 
            isUserUploaded: type === 'user', 
            examTitle: title, 
            examPath: path 
        }));

        try {
            let questionsData: Question[];
            let jsonText: string;
            let tempOriginalJsonString: string | null = null;

            if (type === 'official' && typeof sourceData === 'string') {
                // Fetch official JSON from GitHub repo
                const fetchUrl = `${QUESTIONS_REPO_BASE_URL}/${sourceData}`;
                const response = await fetch(fetchUrl);
                if (!response.ok) {
                    throw new Error(`Failed to fetch question paper: ${response.statusText} (URL: ${fetchUrl})`);
                }
                jsonText = await response.text();

            } else if (type === 'user') {
                // Handle both File and string for user uploads
                if (sourceData instanceof File) {
                    jsonText = await sourceData.text();
                } else if (typeof sourceData === 'string') {
                    jsonText = sourceData;
                    tempOriginalJsonString = jsonText;
                } else {
                     throw new Error("Invalid source data type for user exam.");
                }
            } else {
                throw new Error("Invalid loadExam parameters.");
            }
            // Parse the obtained JSON text
            questionsData = JSON.parse(jsonText);

            // Initialize userAnswers state based on loaded questions
            const initialAnswers: UserAnswer = {};
            questionsData.forEach((q, index) => {
                // Ensure questions have unique numbers or use index as fallback key
                const qNum = q.question_number ?? (index + 1);
                initialAnswers[qNum] = {
                    selectedOption: null,
                    status: 'notVisited',
                    timeSpentSeconds: 0,
                };
            });

            setState(prevState => ({
                ...prevState,
                questions: questionsData,
                userAnswers: initialAnswers,
                examStatus: 'ready', // Ready to configure and start
                error: null,
                originalQuestionJsonString: prevState.isUserUploaded ? tempOriginalJsonString : null,
            }));

        } catch (err: any) {
             let userFriendlyError = "An unexpected error occurred while loading the exam.";
             if (err.message?.includes("Failed to fetch question paper")) {
                 userFriendlyError = "Could not fetch the selected question paper. It might be unavailable or there's a network issue.";
             } else if (err.message?.includes("parse") || err.message?.includes("JSON")) {
                 userFriendlyError = "The exam file seems to be corrupted or not in the correct JSON format.";
             } else if (err.message) {
                 // Keep some part of original message if it's not too technical
                 userFriendlyError = `Failed to load exam: ${err.message.substring(0, 100)}${err.message.length > 100 ? '...' : ''}`;
             }
                    setState(prevState => ({ 
                        ...prevState, 
                        examStatus: 'idle', 
                 error: userFriendlyError
                    }));
                }
    }, [clearExamState, QUESTIONS_REPO_BASE_URL]);

    // --- Start Exam ---
    const startExam = useCallback((settings: ExamSettings) => {
        stopTimer(); // Ensure no previous timer is running
        if (state.questions.length === 0) {
            toast.error("Cannot start exam: No questions loaded.");
            return;
        }

        const now = Date.now();
        const initialRemaining = settings.timeLimitMinutes ? settings.timeLimitMinutes * 60 : null;

        // Mark the first question as notAnswered (since it's now visited)
        const firstQNum = state.questions[0]?.question_number ?? 1;
        const updatedAnswers = {
            ...state.userAnswers,
            [firstQNum]: {
                ...state.userAnswers[firstQNum],
                status: state.userAnswers[firstQNum]?.status === 'notVisited' ? 'notAnswered' : state.userAnswers[firstQNum]?.status // Don't overwrite if already answered/marked
            }
        };

        setState(prevState => ({
            ...prevState,
            examSettings: settings,
            startTime: now,
            elapsedTime: 0,
            remainingTime: initialRemaining,
            currentQuestionIndex: 0,
            examStatus: 'active',
            userAnswers: updatedAnswers, // Update status of first question
            endTime: null, // Reset end time
            error: null, // Clear previous errors
        }));

        logEvent(analytics, 'exam_start', { // <-- Track exam start
            exam_identifier: state.examIdentifier?.substring(0, 100),
            exam_title: state.examTitle?.substring(0, 100),
            question_count: state.questions.length,
            time_limit_minutes: settings.timeLimitMinutes ?? -1, // Use -1 for no limit
            negative_marking: settings.negativeMarkingEnabled
        });

        // Start the timer
        timerIntervalRef.current = setInterval(() => {
            setState(currentExamState => {
                if (currentExamState.examStatus !== 'active' || !currentExamState.startTime) {
                    stopTimer();
                    return currentExamState;
                }

                const elapsed = Math.floor((Date.now() - currentExamState.startTime) / 1000);
                let remaining: number | null = null;

                if (currentExamState.examSettings?.timeLimitMinutes) {
                    remaining = (currentExamState.examSettings.timeLimitMinutes * 60) - elapsed;
                    if (remaining <= 0) {
                        remaining = 0;
                        // Auto-submit when time is up
                        // Need to call submitExam logic carefully to avoid infinite loops/state issues
                        // Using a flag or checking remaining time in the submit function might be better
                        // For now, just update state. Auto-submit will be triggered in UI or effect.
                    }
                }

                // Update time spent on current question if tracking enabled
                let currentUserAnswers = currentExamState.userAnswers;
                if (currentExamState.examSettings?.trackQuestionTime) {
                    const currentQ = currentExamState.questions[currentExamState.currentQuestionIndex];
                    if (currentQ) {
                        const qNum = currentQ.question_number ?? (currentExamState.currentQuestionIndex + 1);
                        const currentAnswerData = currentUserAnswers[qNum];
                        if(currentAnswerData) {
                            // Increment time by 1 second (interval tick)
                            const newTimeSpent = (currentAnswerData.timeSpentSeconds || 0) + 1;
                            currentUserAnswers = {
                                ...currentUserAnswers,
                                [qNum]: { ...currentAnswerData, timeSpentSeconds: newTimeSpent }
                            };
                        }
                    }
                }

                return {
                    ...currentExamState,
                    elapsedTime: elapsed,
                    remainingTime: remaining,
                    userAnswers: currentUserAnswers
                };
            });
        }, 1000);

    }, [state.questions, state.userAnswers, stopTimer, state.examIdentifier, state.examTitle]); // Include dependencies

    // --- NEW: Load and Start Group Exam ---
    const loadAndStartGroupExam = useCallback(async (sessionId: string) => {
        if (!currentUser) {
            throw new Error("User not authenticated.");
        }
        clearExamState(); // Ensure clean state
        setState(prevState => ({ ...initialExamState, examStatus: 'loading_group_session', groupSessionId: sessionId }));

        try {
            // 1. Fetch Group Exam Session Details
            const groupExamDetails = await getGroupExam(sessionId);
            if (!groupExamDetails) {
                throw new Error("Group session not found.");
            }
            // Add status checks if needed (e.g., !groupExamDetails.status === 'pending')

            // 2. Fetch or Parse Question Data based on source type
            let questionsData: Question[];
            let examTitle = groupExamDetails.sessionName; // Use session name as default title
            let isUserUploaded = groupExamDetails.examSourceType === 'custom_json';
            let examPath: string | null = null; // Store path only for official exams

            if (groupExamDetails.examSourceType === 'custom_json' && groupExamDetails.questionJsonString) {
                questionsData = JSON.parse(groupExamDetails.questionJsonString);
            } else if (groupExamDetails.examSourceType === 'official' && groupExamDetails.examSourcePath && groupExamDetails.examSourceId) {
                const fetchUrl = `${QUESTIONS_REPO_BASE_URL}/${groupExamDetails.examSourcePath}`;
                const response = await fetch(fetchUrl);
                if (!response.ok) {
                    throw new Error(`Failed to fetch official questions: ${response.statusText}`);
                }
                questionsData = await response.json();
                // Optionally fetch the full official config to get the precise title? Less critical here.
                examTitle = groupExamDetails.sessionName; // Or potentially fetch config title
                examPath = groupExamDetails.examSourcePath; // Save the path
            } else {
                throw new Error("Invalid or missing question source data in group session.");
            }

            if (!Array.isArray(questionsData) || questionsData.length === 0) {
                throw new Error("Failed to load valid questions for the session.");
            }

            // 3. Prepare Initial Answers State
            const initialAnswers: UserAnswer = {};
            questionsData.forEach((q, index) => {
                const qNum = q.question_number ?? (index + 1);
                initialAnswers[qNum] = { selectedOption: null, status: 'notVisited', timeSpentSeconds: 0 };
            });

            // 4. Define Exam Settings based on Group Session
            const settings: ExamSettings = {
                timeLimitMinutes: groupExamDetails.timeLimitMinutes,
                // Defaults for Phase 1, make configurable later if needed in GroupExam doc
                negativeMarkingEnabled: true, // Or fetch from groupExamDetails if added
                marksPerCorrect: 4,          // Or fetch from groupExamDetails if added
                negativeMarksPerIncorrect: 1,// Or fetch from groupExamDetails if added
                trackQuestionTime: true,     // Or fetch from groupExamDetails if added
            };

            // 5. Set State and Start Timer (similar to startExam)
            const now = Date.now();
            const initialRemaining = settings.timeLimitMinutes ? settings.timeLimitMinutes * 60 : null;
            const firstQNum = questionsData[0]?.question_number ?? 1;
            const updatedAnswers = {
                ...initialAnswers,
                [firstQNum]: { ...initialAnswers[firstQNum], status: 'notAnswered' as QuestionStatus }
            };

            setState(prevState => ({
                ...prevState,
                examStatus: 'active',
                questions: questionsData,
                userAnswers: updatedAnswers,
                examSettings: settings,
                startTime: now,
                elapsedTime: 0,
                remainingTime: initialRemaining,
                currentQuestionIndex: 0,
                groupSessionDetails: groupExamDetails, // Store group details
                groupSessionId: sessionId,
                examIdentifier: `group_${sessionId}`, // Use a distinct identifier
                examTitle: examTitle,
                isUserUploaded: isUserUploaded,
                examPath: examPath, // Store path if official
                endTime: null,
                error: null,
            }));

            // --- NEW: Call startParticipantAttempt AFTER state is set to active ---
            try {
                //console.log(`Marking participant ${currentUser.uid} as started for session ${sessionId}`);
                await startParticipantAttempt(sessionId, currentUser.uid);
                logEvent(analytics, 'group_session_participant_started', { session_id: sessionId });
            } catch (startError: any) {
                // Log the error but don't necessarily stop the exam for the user
                //console.error("Failed to mark participant as started in Firestore:", startError);
                toast.warn("Could not update start status online, but exam will proceed locally.");
            }
            // --- END NEW ---

            logEvent(analytics, 'group_session_exam_start', {
                session_id: sessionId,
                question_count: questionsData.length,
                time_limit_minutes: settings.timeLimitMinutes ?? -1
            });

            // Start timer (copy interval logic from startExam)
            timerIntervalRef.current = setInterval(() => {
                setState(currentExamState => {
                    if (currentExamState.examStatus !== 'active' || !currentExamState.startTime) {
                        stopTimer();
                        return currentExamState;
                    }
                    
                    const elapsed = Math.floor((Date.now() - currentExamState.startTime) / 1000);
                    let remaining: number | null = null;
                    
                    if (currentExamState.examSettings?.timeLimitMinutes) {
                        remaining = (currentExamState.examSettings.timeLimitMinutes * 60) - elapsed;
                        if (remaining <= 0) remaining = 0;
                    }
                    
                    // Track question time if enabled
                    let currentUserAnswers = currentExamState.userAnswers;
                    if (currentExamState.examSettings?.trackQuestionTime) {
                        const currentQ = currentExamState.questions[currentExamState.currentQuestionIndex];
                        if (currentQ) {
                            const qNum = currentQ.question_number ?? (currentExamState.currentQuestionIndex + 1);
                            const currentAnswerData = currentUserAnswers[qNum];
                            if(currentAnswerData) {
                                const newTimeSpent = (currentAnswerData.timeSpentSeconds || 0) + 1;
                                currentUserAnswers = {
                                    ...currentUserAnswers,
                                    [qNum]: { ...currentAnswerData, timeSpentSeconds: newTimeSpent }
                                };
                            }
                        }
                    }
                    
                    return { 
                        ...currentExamState, 
                        elapsedTime: elapsed, 
                        remainingTime: remaining, 
                        userAnswers: currentUserAnswers 
                    };
                });
            }, 1000);

        } catch (err: any) {
           //console.error("Failed to load or start group exam:", err);
     let userFriendlyError = "An unexpected error occurred while trying to start the group session.";
     if (err.message?.includes("Group session not found")) {
         userFriendlyError = "The group session ID is invalid or the session no longer exists.";
     } else if (err.message?.includes("fetch official questions")) {
         userFriendlyError = "Could not load the questions for this group session. The source might be unavailable.";
     } else if (err.message?.includes("Invalid or missing question source data")) {
         userFriendlyError = "The question source for this group session is not configured correctly by the host.";
     } else if (err.message?.includes("Failed to load valid questions")) {
         userFriendlyError = "The questions for this session are invalid or empty.";
     } else if (err.message) {
         userFriendlyError = `Failed to start group session: ${err.message.substring(0, 100)}${err.message.length > 100 ? '...' : ''}`;
     }
            setState(prevState => ({
                ...initialExamState,
                examStatus: 'idle',
         error: userFriendlyError
            }));
            navigate('/select-exam', { replace: true });
        }
    }, [clearExamState, currentUser, navigate, stopTimer, QUESTIONS_REPO_BASE_URL]); // Add dependencies

    // --- Answer Actions ---
    const selectAnswer = useCallback((questionNumber: number, selectedOption: string | null) => {
        setState(prevState => {
            if (prevState.examStatus !== 'active') return prevState;
            const currentStatus = prevState.userAnswers[questionNumber]?.status;
            let newStatus: QuestionStatus = selectedOption ? 'answered' : 'notAnswered';
            // Keep 'markedForReview' if it was marked, even when answering/clearing
            if (currentStatus === 'markedForReview' && !selectedOption) {
                newStatus = 'markedForReview'; // Keep mark if clearing answer
            } else if (currentStatus === 'markedForReview' && selectedOption) {
                newStatus = 'answered'; // Overwrite mark if answering (common behavior, can be adjusted)
                // Or: newStatus = 'markedAndAnswered'; // If you want a distinct state
            }

            return {
                ...prevState,
                userAnswers: {
                    ...prevState.userAnswers,
                    [questionNumber]: {
                        ...prevState.userAnswers[questionNumber],
                        selectedOption: selectedOption,
                        status: newStatus,
                    },
                },
            };
        });
    }, []);

    const toggleMarkForReview = useCallback((questionNumber: number) => {
        setState(prevState => {
            if (prevState.examStatus !== 'active') return prevState;
            const currentStatus = prevState.userAnswers[questionNumber]?.status;
            let newStatus: QuestionStatus;

            if (currentStatus === 'markedForReview') {
                newStatus = prevState.userAnswers[questionNumber]?.selectedOption ? 'answered' : 'notAnswered';
            } else if (currentStatus === 'answered') {
                // Decide if marking an answered question keeps it answered or changes status
                newStatus = 'markedForReview'; // Or a combined state like 'answeredAndMarked'
            }
            else {
                newStatus = 'markedForReview';
            }

            return {
                ...prevState,
                userAnswers: {
                    ...prevState.userAnswers,
                    [questionNumber]: {
                        ...prevState.userAnswers[questionNumber],
                        status: newStatus,
                    },
                },
            };
        });
    }, []);

    // This might be redundant if the timer effect handles it, but useful if tracking needs manual triggers
    const updateQuestionTime = useCallback((questionNumber: number, timeSpentIncrement: number) => {
        setState(prevState => {
            if (prevState.examStatus !== 'active' || !prevState.examSettings?.trackQuestionTime) return prevState;
            const currentAnswerData = prevState.userAnswers[questionNumber];
            if (!currentAnswerData) return prevState;

            return {
                ...prevState,
                userAnswers: {
                    ...prevState.userAnswers,
                    [questionNumber]: {
                        ...currentAnswerData,
                        timeSpentSeconds: (currentAnswerData.timeSpentSeconds || 0) + timeSpentIncrement
                    }
                }
            }
        })
    }, []);

    // --- Navigation Actions ---
    const navigateToQuestion = useCallback((index: number) => {
        setState(prevState => {
            if (prevState.examStatus !== 'active' || index < 0 || index >= prevState.questions.length) {
                return prevState;
            }
            // Update status of the target question if it's 'notVisited'
            const targetQNum = prevState.questions[index]?.question_number ?? (index + 1);
            let updatedAnswers = prevState.userAnswers;
            if (updatedAnswers[targetQNum]?.status === 'notVisited') {
                updatedAnswers = {
                    ...updatedAnswers,
                    [targetQNum]: { ...updatedAnswers[targetQNum], status: 'notAnswered' }
                };
            }

            return { ...prevState, currentQuestionIndex: index, userAnswers: updatedAnswers };
        });
    }, []);

    const nextQuestion = useCallback(() => {
        navigateToQuestion(state.currentQuestionIndex + 1);
    }, [state.currentQuestionIndex, navigateToQuestion]);

    const previousQuestion = useCallback(() => {
        navigateToQuestion(state.currentQuestionIndex - 1);
    }, [state.currentQuestionIndex, navigateToQuestion]);

    // --- MODIFIED: Submit Exam ---
    const submitExam = useCallback(async () => {
        if (state.examStatus !== 'active' || isLoadingPerks) {
            if (state.examStatus === 'active' && isLoadingPerks) {
                toast.info("Perk information is still loading. Please wait a moment and try submitting again.");
            }
            stopTimer();
            return;
        }
        stopTimer();
        const isGroupSession = !!state.groupSessionId;
        const submissionTime = Date.now();
        setState(prevState => ({ ...prevState, examStatus: 'submitting' }));
        // --- Calculate Results ---
        let score = 0;
        let correctCount = 0;
        let incorrectCount = 0;
        let unattemptedCount = 0;
    
        const settingsToUse: ExamSettings | null = isGroupSession && state.groupSessionDetails
            ? {
                // Extract settings from groupSessionDetails, providing defaults if needed
                timeLimitMinutes: state.groupSessionDetails.timeLimitMinutes ?? null,
                // Use group marking scheme or fall back to context/constants defaults
                marksPerCorrect: state.groupSessionDetails.marksPerCorrect ?? DEFAULT_MARKS_PER_CORRECT,
                negativeMarkingEnabled: state.groupSessionDetails.negativeMarkingEnabled ?? true, // Default to true if undefined? Or follow context default? Let's default true for group.
                negativeMarksPerIncorrect: state.groupSessionDetails.negativeMarksPerIncorrect ?? DEFAULT_NEGATIVE_MARKS_PER_INCORRECT,
                // trackQuestionTime might not be configurable per group session yet, use context setting
                trackQuestionTime: state.examSettings?.trackQuestionTime ?? true, // Default to true if main settings missing
            }
            : state.examSettings; // Fallback to individual exam settings

        if (!settingsToUse) { // Check if we have ANY settings
            //console.error("Cannot calculate score: Exam settings missing.");
             setState(prevState => ({ ...prevState, examStatus: 'finished', error: "Settings missing, cannot score." }));
            // Maybe display a generic error message on results page?
             navigate(`/results/error_${Date.now()}`, { state: { resultData: { /* minimal error data */ } }, replace: true }); // Navigate to an error state?
            return;
        }

        Object.entries(state.userAnswers).forEach(([qNumStr, answerData]) => {
            const qNum = parseInt(qNumStr, 10);
            const question = state.questions.find(q => q.question_number === qNum);

            if (!question || !question.correct_answer) return; // Skip if question or answer missing

            if (answerData.selectedOption === null || ['notVisited', 'notAnswered'].includes(answerData.status)) {
                unattemptedCount++;
            } else if (answerData.status === 'markedForReview' && !answerData.selectedOption) {
                // Marked but no answer selected
                unattemptedCount++;
            } else if (answerData.selectedOption.toLowerCase() === question.correct_answer.toLowerCase()) {
                correctCount++;
                score += settingsToUse.marksPerCorrect;
            } else {
                incorrectCount++;
                if (settingsToUse.negativeMarkingEnabled) {
                    score -= settingsToUse.negativeMarksPerIncorrect;
                }
            }
        });

        const finalElapsedTime = state.startTime ? Math.floor((submissionTime - state.startTime) / 1000) : state.elapsedTime;
        const maxScore = state.questions.length * settingsToUse.marksPerCorrect;

        const resultData: Omit<AttemptResult, 'userId' | 'id' | 'questionJsonString'> = {
            examIdentifier: state.examIdentifier!,
            examTitle: state.examTitle!,
            examPath: state.examPath,
            isUserUploaded: state.isUserUploaded,
            //attemptTimestamp: Timestamp.fromDate(new Date(submissionTime)),
            score,
            maxScore,
            correctCount,
            incorrectCount,
            unattemptedCount,
            totalQuestions: state.questions.length,
            userAnswers: state.userAnswers,
            timeTakenSeconds: finalElapsedTime,
            settingsUsed: settingsToUse,
            ...(isGroupSession && { groupSessionId: state.groupSessionId! }) // Conditionally add groupSessionId
        };
        let resultDataWithOptionalJson: Partial<AttemptResult> = { ...resultData }; // Use Partial for the full type

        if (state.isUserUploaded && perksEnabledGlobally && perkFeatures.canReviewCustomUploads && state.originalQuestionJsonString) {
            resultDataWithOptionalJson.questionJsonString = state.originalQuestionJsonString;
           //console.log("[ExamContext] Will save questionJsonString for custom upload review.");
        } else if (state.isUserUploaded && (!perksEnabledGlobally || !perkFeatures.canReviewCustomUploads)) {
           //console.log("[ExamContext] User uploaded exam, but perk for review not active. Not saving questionJsonString.");
        }

        let attemptId: string | null = null;
        let canSaveAttempt = true;
        if (currentUser && perksEnabledGlobally) { // Only check limit if perks system is on
            const attemptLimit = perkLimits.examAttempts; // null for unlimited
            if (attemptLimit !== null) { // If there is a limit
                try {
                    const userAttempts = await getAllUserAttempts(currentUser.uid);
                    if (userAttempts.length >= attemptLimit) {
                        canSaveAttempt = false;
                        toast.warn(`Attempt history limit (${attemptLimit}) reached for your current tier. This result will be shown locally but not saved to your history.`, { autoClose: 8000 });
                        logEvent(analytics, 'exam_submit_limit_reached', { exam_identifier: state.examIdentifier, user_tier: perksEnabledGlobally ? perkLimits.examAttempts : 'unknown' });
                    }
                } catch (e) {
                   //console.error("Failed to check attempt history count before saving:", e);
                    // Proceed with saving if count check fails, to not block user
                }
            }
        }
        // *** END NEW ***
        // --- Save Results to Firestore (if logged in) ---
        if (currentUser  && canSaveAttempt) {
            try {
                // 1. Save the attempt to the user's personal history
                const dataToSave: AttemptResult = {
                    ...resultDataWithOptionalJson, // This now might include questionJsonString
                    userId: currentUser.uid,
                    id: '', // Firestore generates ID
                } as AttemptResult; 

                attemptId = await saveAttemptResult(dataToSave);

                // 2. If it was a group session, update the participant record
                if (isGroupSession) {
                    try{
                        await completeParticipantAttempt(state.groupSessionId!, currentUser.uid, score, maxScore);
                        logEvent(analytics, 'group_session_participant_completed', { 
                            session_id: state.groupSessionId, 
                            score: score, 
                            max_score: maxScore 
                        });
                    } catch (participantCompleteError: any) {
                       //console.warn(`Could not update participant completion status (may already be completed): ${participantCompleteError.message}`);
                    }
                }
                
                logEvent(analytics, 'exam_submit', { 
                    exam_identifier: state.examIdentifier?.substring(0, 100),
                    exam_title: state.examTitle?.substring(0, 100),
                    score: score,
                    max_score: maxScore,
                    time_taken_seconds: finalElapsedTime,
                    correct_count: correctCount,
                    incorrect_count: incorrectCount,
                    unattempted_count: unattemptedCount,
                    total_questions: state.questions.length,
                    is_group: isGroupSession
                });
                
            } catch (saveError: any) {
                //console.error("Failed to save attempt result or update participant:", saveError);
                toast.error("Failed to save results online. Your results are shown locally.");
                setState(prevState => ({ ...prevState, error: "Failed to save results online." }));
                // Generate a temporary ID for local navigation if needed
                attemptId = `local_${Date.now()}`;
            }
        } else {
            if (currentUser && !canSaveAttempt) {
                // Already handled by toast warning above
            } else if (!currentUser) {
                toast.warn("Not logged in. Results shown locally, not saved.");
            }
            attemptId = `local_${Date.now()}`;
            logEvent(analytics, 'exam_submit', { exam_identifier: state.examIdentifier, score, max_score: maxScore, time_taken_seconds: finalElapsedTime, is_group: isGroupSession, saved_to_history: false });
        }

        setState(prevState => ({
            ...prevState,
            endTime: submissionTime,
            elapsedTime: finalElapsedTime, // Lock final time
            examStatus: 'finished',
        }));

        // Navigate to results page
        if (attemptId) {
            const displayData: AttemptResult & { id: string; questionJsonString?: string } = {
                ...(resultDataWithOptionalJson as AttemptResult),
                // Include userAnswers in the object passed via state
                userAnswers: state.userAnswers,
                userId: currentUser?.uid || 'local',
                id: attemptId,
                ...(resultDataWithOptionalJson.questionJsonString && { questionJsonString: resultDataWithOptionalJson.questionJsonString })
        };
            navigate(`/results/${attemptId}`, { state: { resultData: displayData }, replace: true }); // Pass resultData for immediate display
        } else {
            const localDisplayData = { ...resultData, userAnswers: state.userAnswers, id: `local_${Date.now()}`, userId: 'local' };
            navigate(`/results/local_${Date.now()}`, { state: { resultData: localDisplayData }, replace: true });
        }
// eslint-disable-next-line
    }, [state, currentUser, navigate, stopTimer, perkLimits, perksEnabledGlobally]); // Add dependencies

    // Effect to handle auto-submission when time runs out
    useEffect(() => {
        if (state.examStatus === 'active' && state.remainingTime !== null && state.remainingTime <= 0) {
            //console.log("Time expired. Auto-submitting...");
            logEvent(analytics, 'exam_auto_submit_time_expired'); // <-- Track auto-submit
            stopTimer(); // Stop timer immediately
            // Call submit exam (ensure this function itself doesn't cause re-renders that trigger this effect again)
            submitExam().catch(err => {
               //console.error("Auto-submit failed:", err);
                // Handle auto-submit failure, maybe set an error state
            });
        }
    }, [state.remainingTime, state.examStatus, stopTimer, submitExam]); // Add submitExam to dependency array

    // --- Provide Context Value ---
    const contextValue: ExamContextType = {
        ...state,
        loadExam,
        startExam,
        loadAndStartGroupExam, // NEW
        selectAnswer,
        toggleMarkForReview,
        updateQuestionTime,
        navigateToQuestion,
        nextQuestion,
        previousQuestion,
        submitExam,
        clearExamState,
    };

    // Cleanup timer on unmount
    useEffect(() => {
        return () => {
            stopTimer();
        };
    }, [stopTimer]);

    return <ExamContext.Provider value={contextValue}>{children}</ExamContext.Provider>;
};

// --- Custom Hook to use Context ---
export const useExam = (): ExamContextType => {
    const context = useContext(ExamContext);
    if (context === undefined) {
        throw new Error('useExam must be used within an ExamProvider');
    }
    return context;
};
```

---

## hooks


### hooks\useAntiCheatMonitor.ts

```typescript
// src/hooks/useAntiCheatMonitor.ts
import { useEffect, useRef, useCallback, useState } from 'react';
import { useLocation } from 'react-router-dom'; // To detect if user navigates away from exam
import { logAntiCheatEvent } from '../services/firestoreService'; // We'll create this
import { analytics } from '../services/firebase'; // For local analytics logging
import { logEvent as logFirebaseEvent } from 'firebase/analytics'; // Firebase analytics
import { toast } from 'react-toastify'; // Optional: for dev feedback or one-time warnings

interface MonitorConfig {
    focusTracking: boolean;
    copyPastePrevention: boolean;
    restrictedKeyLogging: boolean;
}

export const useAntiCheatMonitor = (
    isActive: boolean, // Is the exam session currently active for this user?
    sessionId: string | null,
    participantId: string | null,
    config: MonitorConfig | null // Configuration of which measures are active
) => {
    const [isPageFocused, setIsPageFocused] = useState(true); // For UI feedback if needed
    const timeLostFocusRef = useRef<number | null>(null);
    const location = useLocation();
    const originalPathnameRef = useRef<string>(location.pathname);

    // --- Event Logging Helper ---
    const logEvent = useCallback(async (eventType: string, eventDetails: object = {}) => {
        if (!isActive || !sessionId || !participantId || !config) return;

        // Log to Firebase Analytics (client-side, for trends)
        logFirebaseEvent(analytics, `ac_${eventType}`, { // Prefix with 'ac_' for anti-cheat
            session_id_short: sessionId.substring(0, 8), // Avoid logging full sensitive IDs
            ...eventDetails
        });

        // Log to Firestore for host review
        try {
            await logAntiCheatEvent(sessionId, participantId, {
                type: eventType,
                path: location.pathname, // Log current path for context
                ...eventDetails
            });
        } catch (error) {
           //console.warn(`[AntiCheatMonitor] Failed to log event type '${eventType}' to Firestore:`, error);
            // Don't disrupt user experience for logging failures
        }
    }, [isActive, sessionId, participantId, config, location.pathname]);


    // --- Focus Tracking ---
    useEffect(() => {
        if (!isActive || !config?.focusTracking || !sessionId || !participantId) {
            // Ensure focus state is reset if monitoring becomes inactive
            setIsPageFocused(true);
            timeLostFocusRef.current = null;
            return;
        }

        const handleVisibilityChange = () => {
            const isHidden = document.hidden;
            setIsPageFocused(!isHidden);

            if (isHidden) {
                timeLostFocusRef.current = Date.now();
                logEvent('focus_lost', { reason: 'visibility_hidden' });
                 toast.warn("Focus lost! Please return to the exam window.", { toastId: "focusLostToast" }); // Optional
            } else if (timeLostFocusRef.current) {
                const durationMs = Date.now() - timeLostFocusRef.current;
                logEvent('focus_regained', { reason: 'visibility_visible', durationMs });
                timeLostFocusRef.current = null;
                toast.dismiss("focusLostToast");
            }
        };

        const handleBlur = () => {
            // Only trigger blur if focus isn't already lost due to visibility change
            if (isPageFocused && document.hasFocus() && !document.hidden) {
                 setIsPageFocused(false);
                 timeLostFocusRef.current = Date.now();
                 logEvent('focus_lost', { reason: 'window_blur' });
                 toast.warn("Window lost focus! Please return to the exam.", { toastId: "focusLostToast" });
            }
        };

        const handleFocus = () => {
            if (!isPageFocused) { // Check if it was previously blurred by this mechanism
                setIsPageFocused(true);
                if (timeLostFocusRef.current) {
                    const durationMs = Date.now() - timeLostFocusRef.current;
                    logEvent('focus_regained', { reason: 'window_focus', durationMs });
                    timeLostFocusRef.current = null;
                    toast.dismiss("focusLostToast");
                } else {
                     // Regained focus without a recorded blur from this window, might be initial focus
                     logEvent('focus_regained', { reason: 'window_focus_initial_or_untracked_blur' });
                }
            }
        };
        
        // Store original pathname when monitoring starts
        originalPathnameRef.current = location.pathname;


        document.addEventListener('visibilitychange', handleVisibilityChange);
        window.addEventListener('blur', handleBlur);
        window.addEventListener('focus', handleFocus);

        return () => {
            document.removeEventListener('visibilitychange', handleVisibilityChange);
            window.removeEventListener('blur', handleBlur);
            window.removeEventListener('focus', handleFocus);
            // If focus was lost when unmounting, log final duration
            if (timeLostFocusRef.current) {
                const durationMs = Date.now() - timeLostFocusRef.current;
                logEvent('focus_lost_on_unmount', { durationMs });
            }
            toast.dismiss("focusLostToast");
        };
        // eslint-disable-next-line
    }, [isActive, config?.focusTracking, logEvent, sessionId, participantId, isPageFocused]); // Added isPageFocused to deps

    // Effect to detect navigation away from the exam page
    useEffect(() => {
        if (!isActive || !config?.focusTracking || !sessionId || !participantId) return;

        if (location.pathname !== originalPathnameRef.current) {
            logEvent('navigation_away', {
                from: originalPathnameRef.current,
                to: location.pathname
            });
            // Potentially show a persistent warning or inform host, this is a stronger signal than tab switch
            // For now, just logging.
            // Update originalPathnameRef if user is allowed to navigate within exam parts and then return
            // For simple single-page exams, any change is "navigation away".
            // If exam has internal routes, this needs more complex logic.
        }
    }, [location.pathname, isActive, config?.focusTracking, logEvent, sessionId, participantId]);


    // --- Copy/Paste Prevention ---
    useEffect(() => {
        if (!isActive || !config?.copyPastePrevention || !sessionId || !participantId) return;

        const handleCopy = (e: ClipboardEvent) => {
            e.preventDefault();
            logEvent('copy_attempt_blocked');
            toast.warn("Copying content is restricted during this exam.", { toastId: "copyRestrictionToast" });
        };
        const handlePaste = (e: ClipboardEvent) => {
            e.preventDefault();
            logEvent('paste_attempt_blocked');
            toast.warn("Pasting content is restricted during this exam.", { toastId: "pasteRestrictionToast" });
        };

        document.addEventListener('copy', handleCopy);
        document.addEventListener('paste', handlePaste);
        // Consider also contextmenu (right-click) for copy/paste
        const handleContextMenu = (e: MouseEvent) => e.preventDefault();
        document.addEventListener('contextmenu', handleContextMenu);

        return () => {
            document.removeEventListener('copy', handleCopy);
            document.removeEventListener('paste',handlePaste);
            document.removeEventListener('contextmenu', handleContextMenu);
            toast.dismiss("copyRestrictionToast");
            toast.dismiss("pasteRestrictionToast");
        };
    }, [isActive, config?.copyPastePrevention, logEvent, sessionId, participantId]);

    // --- Restricted Key Logging ---
    useEffect(() => {
        if (!isActive || !config?.restrictedKeyLogging || !sessionId || !participantId) return;

        const handleKeyDown = (e: KeyboardEvent) => {
            let keyDetail = '';
            let isRestricted = false;

            if (e.key === 'PrintScreen' || e.key === 'Snapshot') {
                keyDetail = 'PrintScreen';
                isRestricted = true;
                // e.preventDefault(); // Very hard to reliably prevent PrintScreen
            } else if ((e.ctrlKey || e.metaKey) && e.key.toLowerCase() === 'p') {
                keyDetail = (e.ctrlKey ? 'Ctrl' : 'Cmd') + '+P (Print)';
                isRestricted = true;
                e.preventDefault(); // Can prevent default print dialog
            } else if ((e.ctrlKey || e.metaKey) && e.key.toLowerCase() === 's') {
                keyDetail = (e.ctrlKey ? 'Ctrl' : 'Cmd') + '+S (Save Page)';
                isRestricted = true;
                e.preventDefault();
            }
            // Add more keys/combos as needed (e.g., F12 for DevTools, though this is also hard to block fully)

            if (isRestricted) {
                logEvent('restricted_key_logged', { keyDetail });
                if (keyDetail.includes("Print")) {
                     toast.warn(`Attempt to use ${keyDetail} logged.`, {toastId: "keyLoggedToast"});
                } else {
                     toast.error(`${keyDetail} is disabled during this exam.`, {toastId: "keyDisabledToast"});
                }
            }
        };

        window.addEventListener('keydown', handleKeyDown);
        return () => {
            window.removeEventListener('keydown', handleKeyDown);
            toast.dismiss("keyLoggedToast");
            toast.dismiss("keyDisabledToast");
        };
    }, [isActive, config?.restrictedKeyLogging, logEvent, sessionId, participantId]);

    return { isPageFocused }; // Hook can return state if UI needs to react (e.g., show focus indicator)
};
```

---

### hooks\useExamConfig.ts

```typescript
// src/hooks/useExamConfig.ts
import { useState, useEffect } from 'react';
import { ExamConfig, CONFIG_URL } from '../types';

export const useExamConfig = () => {
  const [availableExams, setAvailableExams] = useState<ExamConfig[]>([]);
  const [isLoadingConfig, setIsLoadingConfig] = useState(true);
  const [configError, setConfigError] = useState<string | null>(null);

  useEffect(() => {
    const fetchConfig = async () => {
      setIsLoadingConfig(true);
      setConfigError(null);
      try {
        const response = await fetch(CONFIG_URL);
        if (!response.ok) throw new Error(`Failed to fetch exam config (${response.status})`);
        let data;
        try { 
          data = await response.json(); 
        } catch (jsonError) { 
          throw new Error("Failed to parse config file - is it valid JSON?"); 
        }
        
        if (!Array.isArray(data)) throw new Error("Invalid config format: Expected an array.");
        if (data.some(item => !item.id || !item.category || !item.year || !item.title || !item.path)) {
         //console.warn("Some exam config items are missing required fields (id, category, year, title, path).");
        }
        setAvailableExams(data as ExamConfig[]);
      } catch (err: any) {
        //console.error("Error fetching or parsing exam config:", err);
        setConfigError(err.message || "Could not load exam list.");
        setAvailableExams([]);
      } finally {
        setIsLoadingConfig(false);
      }
    };
    
    fetchConfig();
  }, []);

  return { availableExams, isLoadingConfig, configError };
};
```

---

### hooks\useUserPerks.ts

```typescript
// src/hooks/useUserPerks.ts
import { useState, useEffect, useMemo } from 'react';
import { useAuth } from '../contexts/AuthContext';
import { getTierConfigs, getGlobalSettings } from '../services/configService';
import { TierConfig} from '../types';

// Default "Free" Tier structure if nothing is fetched or user's tier is not found
const FALLBACK_FREE_TIER: TierConfig = {
    id: 'free',
    name: 'Free Plan',
    pricingOptions: [{billingCycle: 'monthly', priceINR: 0, durationMonths: 1, displaySuffix: ''}],
    description: 'Get started with essential practice tools.',
    features: [
        "Practice with official & custom JSON exams",
        "Basic performance summary",
        "Host 1 group session",
        "Limited attempt history (5 attempts)",
        "Community support"
    ],
    limits: {
        examAttempts: 5,
        hostedSessions: 1,
    }
};

// Define the tier hierarchy for feature inheritance
const TIER_HIERARCHY: Array<TierConfig['id']> = ['free', 'basic', 'pro', 'elite'];

export interface ResolvedPerkLimits {
    examAttempts: number | null;
    hostedSessions: number | null;
    //maxParticipantsPerSession: number | null;
}

export interface ResolvedPerkFeatures {
    canReviewCustomUploads: boolean;
    canDownloadParticipantCsv: boolean;
    canEnableExamMonitoring: boolean; // Basic monitoring
    canEnableAdvancedMonitoring: boolean; // For GeoLocationLocking (Elite tier)
    adFreeExperience: boolean;
    prioritySupport: boolean;
}

interface UserPerksResult {
    currentTier: TierConfig;
    limits: ResolvedPerkLimits;
    features: ResolvedPerkFeatures;
    isLoadingPerks: boolean;
    activePerkLevel: string;
    hasActivePerk: boolean;
    perksEnabledGlobally: boolean;
}

export const useUserPerks = (): UserPerksResult => {
    const { userData, isLoading: isAuthLoading } = useAuth();
    const [allTiersFromDB, setAllTiersFromDB] = useState<TierConfig[]>([]);
    const [isConfigLoading, setIsConfigLoading] = useState<boolean>(true);
    const [perksEnabledGlobally, setPerksEnabledGlobally] = useState<boolean>(true);

    useEffect(() => {
        const fetchCoreConfigs = async () => {
            setIsConfigLoading(true);
            try {
                const [tiers, globalSettings] = await Promise.all([
                    getTierConfigs(),
                    getGlobalSettings(),
                ]);
                setAllTiersFromDB(tiers);
                setPerksEnabledGlobally(globalSettings?.features?.perksEnabled ?? true);

            } catch (error) {
               //console.error("Error fetching initial perk configurations:", error);
            } finally {
                setIsConfigLoading(false);
            }
        };
        fetchCoreConfigs();
    }, []);

    const { currentTier, activePerkLevel, hasActivePerk } = useMemo(() => {
        if (isAuthLoading || isConfigLoading) {
            return { currentTier: FALLBACK_FREE_TIER, activePerkLevel: 'free', hasActivePerk: false };
        }

        if (!perksEnabledGlobally || !userData || !userData.perkLevel || userData.status !== 'active') {
            return { currentTier: FALLBACK_FREE_TIER, activePerkLevel: 'free', hasActivePerk: false };
        }

        const now = new Date();
        const perkIsExpired = userData.perkExpiry && userData.perkExpiry < now;

        if (perkIsExpired) {
            return { currentTier: FALLBACK_FREE_TIER, activePerkLevel: 'free', hasActivePerk: false };
        }

        const foundTierInDB = allTiersFromDB.find(tier => tier.id === userData.perkLevel);

        if (foundTierInDB) {
            return {
                currentTier: foundTierInDB,
                activePerkLevel: foundTierInDB.id,
                hasActivePerk: foundTierInDB.id !== 'free',
            };
        } else {
           //console.warn(`[useUserPerks] Perk level '${userData.perkLevel}' for user ${userData.uid} not found in loaded DB configurations. Defaulting to free tier rules.`);
            return { currentTier: FALLBACK_FREE_TIER, activePerkLevel: 'free', hasActivePerk: false };
        }
    }, [userData, allTiersFromDB, perksEnabledGlobally, isAuthLoading, isConfigLoading]);

    const limits = useMemo((): ResolvedPerkLimits => {
        const getResolvedLimit = (
            limitKey: keyof TierConfig['limits'],
            ultimateFallback: number | null
        ): number | null => {
            if (currentTier.limits && typeof currentTier.limits[limitKey] !== 'undefined') {
                return currentTier.limits[limitKey];
            }
            if (FALLBACK_FREE_TIER.limits && typeof FALLBACK_FREE_TIER.limits[limitKey] !== 'undefined') {
                return FALLBACK_FREE_TIER.limits[limitKey];
            }
            return ultimateFallback;
        };
        return {
            examAttempts: getResolvedLimit('examAttempts', 5),
            hostedSessions: getResolvedLimit('hostedSessions', 1),
        };
    }, [currentTier]);

    const features = useMemo((): ResolvedPerkFeatures => {
        /**
         * Checks if a feature is available in the specified tier or any lower tier it inherits from
         * @param featureKey Partial feature name/description to search for
         * @param tierIdToCheck Current tier ID to check
         * @returns Boolean indicating if the feature is available
         */
        const isFeatureAvailableInTierOrLower = (
            featureKey: string,
            tierIdToCheck: TierConfig['id']
        ): boolean => {
            // Find the current tier's position in the hierarchy
            const tierIndex = TIER_HIERARCHY.indexOf(tierIdToCheck);
            if (tierIndex === -1) return false; // Invalid tier ID
            
            // Check the current tier and all tiers below it in the hierarchy
            // We start from the current tier and work our way down
            for (let i = tierIndex; i >= 0; i--) {
                const currentTierIdInLoop = TIER_HIERARCHY[i];
                const tierData = allTiersFromDB.find(t => t.id === currentTierIdInLoop);
                
                if (tierData) {
                    const lowerFeatureKey = featureKey.toLowerCase();
                    if (tierData.features.some(f => f.toLowerCase().includes(lowerFeatureKey))) {
                        return true;
                    }
                }
            }
            
            // If not found in any tier, check the fallback free tier as last resort
            if (tierIdToCheck !== 'free') {
                const lowerFeatureKey = featureKey.toLowerCase();
                return FALLBACK_FREE_TIER.features.some(f => 
                    f.toLowerCase().includes(lowerFeatureKey)
                );
            }
            
            return false;
        };

        return {
            canReviewCustomUploads: isFeatureAvailableInTierOrLower('review your custom uploaded exams', currentTier.id),
            canDownloadParticipantCsv: isFeatureAvailableInTierOrLower('download group session participant results (csv)', currentTier.id),
            canEnableExamMonitoring: isFeatureAvailableInTierOrLower('enable basic anti-cheating monitoring', currentTier.id),
            canEnableAdvancedMonitoring: isFeatureAvailableInTierOrLower('advanced anti-cheating monitoring', currentTier.id),
            adFreeExperience: isFeatureAvailableInTierOrLower('ad-free experience', currentTier.id),
            prioritySupport: isFeatureAvailableInTierOrLower('priority support', currentTier.id),
        };
    }, [currentTier, allTiersFromDB]);

    return {
        currentTier,
        limits,
        features,
        isLoadingPerks: isAuthLoading || isConfigLoading,
        activePerkLevel,
        hasActivePerk,
        perksEnabledGlobally,
    };
};
```

---

### index.tsx

```typescript
import React from 'react';
import ReactDOM from 'react-dom/client';
import App from './App';

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

## pages


## pages\AntiCheatingSandboxPage


### pages\AntiCheatingSandboxPage\AntiCheatingSandboxPage.module.scss

```scss
// src/pages/AntiCheatingSandboxPage/AntiCheatingSandboxPage.module.scss
@import '../../styles/variables';
@import '../../styles/mixins';

.sandboxPage {
    padding: $spacer * 2;
    max-width: 900px; // Allow slightly wider for sandbox
    margin: $spacer auto;

    h1 {
        text-align: center;
        color: $primary-color;
        margin-bottom: $spacer * 0.75;
        display: flex;
        align-items: center;
        justify-content: center;
        gap: $spacer * 0.5;
    }
}

.pageDescription {
    text-align: center;
    color: $text-muted;
    margin-bottom: $spacer * 2.5;
    font-size: $font-size-base * 1.05;
    line-height: 1.6;
}

.sandboxSection {
    background-color: $component-bg;
    border: 1px solid $border-color;
    border-radius: $border-radius-lg;
    padding: $spacer * 1.5 $spacer * 2;
    margin-bottom: $spacer * 2;
    box-shadow: $box-shadow-sm;

    h2 {
        font-size: $h4-font-size;
        color: $dark-color;
        margin-top: 0;
        margin-bottom: $spacer * 1.5;
        font-weight: 600;
        padding-bottom: $spacer * 0.75;
        border-bottom: 1px solid $border-color;
    }
}

.settingBlock {
    margin-bottom: $spacer * 2;
    padding-bottom: $spacer * 1.5;
    border-bottom: 1px dotted lighten($border-color, 5%);

    &:last-of-type {
        margin-bottom: 0;
        padding-bottom: 0;
        border-bottom: none;
    }
}

.settingTitle {
    font-size: $font-size-base * 1.1;
    font-weight: 500;
    color: darken($primary-color, 10%);
    margin-bottom: $spacer;
}

.settingDescription {
    font-size: $font-size-base * 0.9;
    color: $text-muted;
    margin-bottom: $spacer * 1.25;
}

.checkboxLabel {
    display: flex;
    align-items: center;
    gap: $spacer * 0.6;
    cursor: pointer;
    font-size: $font-size-base;

    input[type="checkbox"] {
        width: 1.1em;
        height: 1.1em;
        cursor: pointer;
         accent-color: $primary-color; // Style checkbox color modernly
    }
}

.locationConfig {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
    gap: $spacer $spacer * 1.5;
    margin-bottom: $spacer * 1.5;

    label {
        display: block;
        font-size: $font-size-base * 0.85;
        font-weight: 500;
        margin-bottom: $spacer * 0.3;
        color: $text-muted;
    }

    input {
        width: 100%;
        padding: $spacer * 0.6 $spacer * 0.8;
        border: 1px solid $border-color;
        border-radius: $border-radius-sm;
        font-size: $font-size-base;

        &:focus {
            outline: none;
            border-color: $primary-color;
            box-shadow: 0 0 0 2px rgba($primary-color, 0.2);
        }
    }
}

.checkButton {
    @include button-variant($info-color, $info-color);
    font-size: $font-size-base * 0.9;
    padding: $spacer * 0.5 $spacer;
    display: inline-flex;
    align-items: center;
    gap: $spacer * 0.5;

    svg { font-size: $font-size-base; }
    &:disabled { opacity: 0.6; cursor: not-allowed; }
}

.geoStatus {
    margin-top: $spacer;
    font-size: $font-size-base * 0.9;
    font-weight: 500;

    .error { color: $danger-color; }
    .success { color: $success-color; }
    .warning { color: $warning-color; }
    .info { color: $text-muted; }
}

.startAction, .endAction {
    margin-top: $spacer * 2;
    text-align: center;
}

.startButton, .endButton {
    padding: $spacer * 0.8 $spacer * 2;
    font-size: $font-size-base * 1.05;
    font-weight: 500;

    &:disabled {
         @include button-variant(lighten($secondary-color, 20%), $secondary-color); // More distinct disabled
         color: $text-muted;
         cursor: not-allowed;
         opacity: 0.8;
         &:hover {
            // Prevent hover styles on disabled
            background-color: lighten($secondary-color, 20%);
         }
    }
}

.startButton {
    @include button-variant($success-color, $success-color);
}
.endButton {
    @include button-variant($primary-color, $primary-color);
}

// --- Exam Simulation Area ---
.examArea {
     border-top: 4px solid $primary-color; // Indicate active exam area
}
.examHeader {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: $spacer * 1.5;
    h2 { margin-bottom: 0; padding-bottom: 0; border-bottom: none; }
}

.focusIndicator {
    font-weight: 500;
    padding: $spacer * 0.25 $spacer * 0.75;
    border-radius: $border-radius;
    font-size: $font-size-base * 0.9;
    display: inline-flex;
    align-items: center;
    gap: $spacer * 0.5;
    border: 1px solid transparent;

    &.focusActive {
        background-color: lighten($success-color, 50%);
        color: darken($success-color, 15%);
         border-color: lighten($success-color, 30%);
    }
    &.focusLost {
        background-color: lighten($danger-color, 45%);
        color: darken($danger-color, 15%);
         border-color: lighten($danger-color, 30%);
    }
    svg { font-size: $font-size-base; }
}

.examContent {
    // Styling for the sample content area
     padding: $spacer;
     border: 1px dashed $border-color;
     border-radius: $border-radius;
     background-color: lighten($light-color, 3%);
     min-height: 150px; // Ensure some space

    h3 { margin-top: 0; font-size: $h5-font-size; margin-bottom: $spacer; }
    p { margin-bottom: $spacer * 0.5; }
     ul { margin-left: $spacer * 1.5; }
}

.sampleTextArea {
    width: 100%;
    padding: $spacer * 0.5;
    border: 1px solid $border-color;
    border-radius: $border-radius-sm;
    font-family: monospace;
    min-height: 60px;
    margin-top: $spacer;
    resize: none; // Prevent user resizing
    background-color: $white-color;
}

// --- Log Area ---
.logGrid {
    display: grid;
    grid-template-columns: 1fr;
    gap: $spacer * 1.5;

    @include media-breakpoint-up(md) {
         grid-template-columns: 1fr 1fr;
    }
}

.logBlock {
    background-color: lighten($light-color, 4%);
    padding: $spacer;
    border-radius: $border-radius;
    border: 1px solid lighten($border-color, 5%);

    &.fullWidth {
        @include media-breakpoint-up(md) {
             grid-column: 1 / -1; // Span both columns
        }
    }
}

.logTitle {
    font-weight: 600;
    font-size: $font-size-base;
    margin-bottom: $spacer * 0.75;
    color: $dark-color;
}

.logBlock p {
    font-size: $font-size-base * 0.9;
    margin-bottom: $spacer * 0.25;
    color: $text-muted;
    strong { color: $text-color; }
}

.noLogs {
    font-style: italic;
    color: $text-muted;
}

.logList {
    list-style: none;
    padding: 0;
    margin: 0;
    max-height: 150px; // Limit height
    overflow-y: auto;
    font-family: monospace;
    font-size: $font-size-base * 0.85;
    line-height: 1.4;

    li {
        padding: $spacer * 0.25 0;
        border-bottom: 1px dotted lighten($border-color, 8%);
        color: darken($text-muted, 5%);
        &:last-child { border-bottom: none; }
    }
}
.defenseLayerToggle {
    display: flex;
    align-items: center;
    gap: map-get($spacers, 3);
    padding: map-get($spacers, 3) map-get($spacers, 2);
    border-bottom: 1px solid $gray-100;
    &:last-of-type { border-bottom: none; }
  
    svg { color: $primary-color; font-size: $font-size-base * 1.3; }
    label { flex-grow: 1; font-weight: $font-weight-medium; color: $gray-700; }
    input[type="checkbox"] { // Basic toggle switch style (can be more complex with pseudo-elements)
      appearance: none;
      width: 40px; height: 20px;
      background-color: $gray-300;
      border-radius: $border-radius-pill;
      position: relative;
      cursor: pointer;
      transition: background-color $transition-fast;
      &:checked { background-color: $success-color; }
      &::before {
        content: ''; position: absolute;
        width: 16px; height: 16px;
        border-radius: 50%;
        background-color: $white-color;
        top: 2px; left: 2px;
        transition: transform 0.2s ease-in-out;
      }
      &:checked::before { transform: translateX(20px); }
    }
  }
  .locationConfigBox { /* Style if needed, similar to a form subsection */
      margin-top: map-get($spacers, 3);
      padding: map-get($spacers, 3);
      background-color: $gray-50;
      border-radius: $border-radius;
  }
  
  
  // --- Challenge Zone ---
  .challengeZone { border-top-color: $warning-color; /* Example accent */ }
  .challengeHeader {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: map-get($spacers, 4);
    h2 { border: none; padding: 0; margin: 0; color: $warning-color; }
  }
  .integrityScoreDisplay {
    font-size: $font-size-base * 1.1;
    font-weight: $font-weight-semibold;
    background-color: $gray-100;
    padding: map-get($spacers, 1) map-get($spacers, 3);
    border-radius: $border-radius;
    strong { color: $primary-color; font-size: $font-size-base * 1.3; }
  }
  // .focusIndicator styles are already good from before.
  
  .objectivesList {
    margin-bottom: map-get($spacers, 4);
    h3 { font-size: $font-size-base * 1.1; color: $gray-700; margin-bottom: map-get($spacers, 2); }
    ul { list-style: none; padding: 0; }
    li {
      padding: map-get($spacers, 2);
      border: 1px solid $gray-200;
      border-radius: $border-radius-sm;
      margin-bottom: map-get($spacers, 2);
      display: flex;
      align-items: center;
      gap: map-get($spacers, 2);
      transition: background-color $transition-fast;
      &.objDetected { background-color: lighten($danger-color, 50%); border-left: 4px solid $danger-color; }
      &.objStealth { background-color: lighten($success-color, 50%); border-left: 4px solid $success-color; }
    }
    .objStatusIcon svg { font-size: $font-size-base * 1.2; }
    .objTagDetected, .objTagStealth {
      margin-left: auto;
      font-size: $font-size-base * 0.8;
      font-weight: $font-weight-semibold;
      padding: 2px map-get($spacers, 2);
      border-radius: $border-radius-pill;
    }
    .objTagDetected { background-color: $danger-color; color: $white-color; }
    .objTagStealth { background-color: $success-color; color: $white-color; }
  }
  
  .interactiveArea {
    margin-bottom: map-get($spacers, 4);
    h4 { font-size: $font-size-base; color: $gray-600; margin-bottom: map-get($spacers, 1); }
    textarea.secretDocument, input.suspiciousInput {
      width: 100%;
      padding: map-get($spacers, 2);
      border: 1px solid $gray-300;
      border-radius: $border-radius-sm;
      font-family: $font-family-monospace;
      background-color: $gray-50;
    }
    textarea.secretDocument { min-height: 80px; }
  }
  
  .detectionGrid { // Reuses existing .logGrid styles (flex/grid)
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: map-get($spacers, 3);
  }
  .logBlock { // Reuses existing .logBlock, can add more interactive styles
    transition: box-shadow $transition-fast, border-color $transition-fast;
    &.alertActive { // When a new alert fires in this category
      border-left: 4px solid $danger-color; // Or warning-color
      box-shadow: $box-shadow-md;
      animation: pulseAlertBorder 0.7s ease-out;
    }
  }
  @keyframes pulseAlertBorder {
    0% { border-left-color: $danger-color; }
    50% { border-left-color: lighten($danger-color, 20%); }
    100% { border-left-color: $danger-color; }
  }
  .geoStatusSuccess { color: $success-color; font-weight: $font-weight-medium; }
  .geoStatusFailure { color: $danger-color; font-weight: $font-weight-medium; }
  
  // --- Perk Info ---
  .perkInfoSection {
    margin-top: map-get($spacers, 5);
    padding: map-get($spacers, 4);
    text-align: center;
    background-color: lighten($primary-color, 58%);
    border-radius: $border-radius-lg;
    border: 1px solid lighten($primary-color, 45%);
    p {
      color: darken($primary-color, 15%);
      font-size: $font-size-base * 0.95;
      margin: 0;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: map-get($spacers, 1);
      svg { font-size: $font-size-base * 1.1; }
    }
    .learnMoreLink {
      font-weight: $font-weight-semibold;
      color: $primary-color;
      text-decoration: underline;
      margin-left: map-get($spacers, 1);
      &:hover { color: darken($primary-color, 10%); }
    }
  }
```

---

### pages\AntiCheatingSandboxPage\AntiCheatingSandboxPage.tsx

```typescript
// src/pages/AntiCheatingSandboxPage/AntiCheatingSandboxPage.tsx
import React, { useState, useEffect, useRef, useCallback } from 'react';
//import { useNavigate } from 'react-router-dom'; // Only used if redirecting elsewhere
import { analytics } from '../../services/firebase'; // Import analytics instance
import { logEvent } from 'firebase/analytics';
import { toast, ToastContainer } from 'react-toastify';
import 'react-toastify/dist/ReactToastify.css';
import { Link } from 'react-router-dom';
import styles from './AntiCheatingSandboxPage.module.scss'; // Import SCSS Module
import Spinner from '../../components/Spinner/Spinner'; // Import Spinner
import { 
  FaEye, 
  FaEyeSlash, 
  FaLocationArrow, 
  FaMapMarkerAlt, 
  FaShieldAlt, 
  FaPaste,
  FaKeyboard,
  FaUserSecret,
  FaTasks,
  FaBullseye,
  FaCheckCircle,
  FaPlayCircle,
  FaFileAlt,
  FaBroadcastTower,
  FaStar 
} from 'react-icons/fa';

const AntiCheatingSandboxPage: React.FC = () => {
  //const navigate = useNavigate();

  // --- Simulation State ---
  const [examStarted, setExamStarted] = useState<boolean>(false);

  // --- NEW State for Gamification ---
  const [challengeActive] = useState<boolean>(false);
  const [integrityScore, setIntegrityScore] = useState<number>(100);
  const [objectives, setObjectives] = useState([
    { id: 'focus', text: 'Try switching to another browser tab or window.', completed: false, detected: false },
    { id: 'copy', text: "Attempt to copy text from the 'Secret Document' below.", completed: false, detected: false },
    { id: 'paste', text: "Attempt to paste into the 'Suspicious Input Field'.", completed: false, detected: false },
    { id: 'print', text: 'Try to print this page (Ctrl+P or Cmd+P).', completed: false, detected: false },
    // Geolocation objective will be added conditionally
  ]);

  // --- State for toggling defense layers ---
  const [focusShieldActive, setFocusShieldActive] = useState<boolean>(true);
  const [clipboardLockdownActive, setClipboardLockdownActive] = useState<boolean>(true);
  const [keystrokeMonitorActive, setKeystrokeMonitorActive] = useState<boolean>(true);
  const [locationLockActive, setLocationLockActive] = useState<boolean>(false); // Default off

  // --- Anti-cheat States & Refs ---
  const [isFocused, setIsFocused] = useState<boolean>(true);
  const [focusLossCount, setFocusLossCount] = useState<number>(0);
  const timeLostFocus = useRef<number | null>(null);
  const totalFocusLostTime = useRef<number>(0);

  const [copyAttempts, setCopyAttempts] = useState<number>(0);
  const [pasteAttempts, setPasteAttempts] = useState<number>(0);

  const [restrictedKeyPresses, setRestrictedKeyPresses] = useState<string[]>([]);

  const [honorCodeChecked, setHonorCodeChecked] = useState<boolean>(false);

  const [geoPermission, setGeoPermission] = useState<PermissionState | 'prompt' | 'unsupported'>('prompt');
  const [isCheckingLocation, setIsCheckingLocation] = useState<boolean>(false);
  const [userLocation, setUserLocation] = useState<{ lat: number; lng: number } | null>(null);
  const [isUserInZone, setIsUserInZone] = useState<boolean | null>(null);
  const [distanceFromZone, setDistanceFromZone] = useState<number | null>(null);

  const [secretDocumentText] = useState("This is top-secret information about Examify's future. Agent, your mission is to protect it... or try to exfiltrate it!");
  const [suspiciousInput, setSuspiciousInput] = useState("");

  // --- Configurable Settings ---
  const [allowedLocation, setAllowedLocation] = useState<{ lat: number; lng: number }>({ lat: 37.7749, lng: -122.4194 }); // Default: SF
  const [allowedRadius, setAllowedRadius] = useState<number>(500); // Default: 500 meters

  // --- Helper Functions ---

  // Calculate distance (Haversine formula)
  const calculateDistance = (lat1: number, lon1: number, lat2: number, lon2: number): number => {
    const R = 6371e3; // Earth's radius in meters
    const φ1 = lat1 * Math.PI / 180;
    const φ2 = lat2 * Math.PI / 180;
    const Δφ = (lat2 - lat1) * Math.PI / 180;
    const Δλ = (lon2 - lon1) * Math.PI / 180;
    const a = Math.sin(Δφ / 2) * Math.sin(Δφ / 2) + Math.cos(φ1) * Math.cos(φ2) * Math.sin(Δλ / 2) * Math.sin(Δλ / 2);
    const c = 2 * Math.atan2(Math.sqrt(a), Math.sqrt(1 - a));
    return R * c; // Distance in meters
  };

  // --- Log and Score Events ---
  const logAndScoreEvent = (eventType: string, pointsDeducted: number, objectiveId?: string) => {
    logEvent(analytics, `sandbox_${eventType}`, { /* ...details... */ });

    if (objectiveId) {
      setObjectives(prev => prev.map(obj => obj.id === objectiveId ? { ...obj, detected: true, completed: true } : obj));
    }
    setIntegrityScore(prev => Math.max(0, prev - pointsDeducted));
  };

  // --- Event Handlers ---

  // Handle copy/paste
  const handleCopy = useCallback((e: ClipboardEvent) => {
    if (challengeActive && clipboardLockdownActive) {
      e.preventDefault(); // Prevent actual copy
      const attemptCount = copyAttempts + 1;
      setCopyAttempts(attemptCount);
      logAndScoreEvent('copy_attempt_blocked', 10, 'copy'); // Log, score, mark objective
      toast.error('CLIPBOARD LOCKDOWN: Copy attempt blocked & logged!');
    } else if (examStarted) {
      e.preventDefault(); // Prevent actual copy for traditional exam mode
      const attemptCount = copyAttempts + 1;
      setCopyAttempts(attemptCount);
      logEvent(analytics, 'sandbox_copy_attempt', { attempt_count: attemptCount });
      toast.error('Copying is disabled during the exam simulation!');
    }
  }, [challengeActive, clipboardLockdownActive, copyAttempts, examStarted]);

  const handlePaste = useCallback((e: ClipboardEvent) => {
    if (challengeActive && clipboardLockdownActive) {
      e.preventDefault(); // Prevent actual paste
      const attemptCount = pasteAttempts + 1;
      setPasteAttempts(attemptCount);
      logAndScoreEvent('paste_attempt_blocked', 10, 'paste'); // Log, score, mark objective
      toast.error('CLIPBOARD LOCKDOWN: Paste attempt blocked & logged!');
    } else if (examStarted) {
      e.preventDefault(); // Prevent actual paste
      const attemptCount = pasteAttempts + 1;
      setPasteAttempts(attemptCount);
      logEvent(analytics, 'sandbox_paste_attempt', { attempt_count: attemptCount });
      toast.error('Pasting is disabled during the exam simulation!');
    }
  }, [challengeActive, clipboardLockdownActive, pasteAttempts, examStarted]);


  // --- Effects ---

  // Focus tracking effect
  useEffect(() => {
    const handleVisibilityChange = () => {
      const isHidden = document.hidden;
      setIsFocused(!isHidden); // Update visual state

      if (!examStarted && !challengeActive) return; // Only track if exam/challenge is active

      if (isHidden) {
        // --- Focus Lost ---
        timeLostFocus.current = Date.now();
        const newCount = focusLossCount + 1;
        setFocusLossCount(newCount);
        
        if (challengeActive && focusShieldActive) {
          logAndScoreEvent('focus_lost', 5, 'focus'); // Less points first time, objective marked
          toast.warning(`FOCUS SHIELD ALERT: Focus lost (${newCount})! Integrity compromised.`);
        } else if (examStarted) {
          logEvent(analytics, 'sandbox_focus_lost', { count: newCount });
          toast.warning(`Focus lost (${newCount})! Stay on the exam page.`);
        }
      } else if (timeLostFocus.current) {
        // --- Focus Regained ---
        const timeAway = Date.now() - timeLostFocus.current;
        totalFocusLostTime.current += timeAway;
        timeLostFocus.current = null; // Reset timer
        
        if (challengeActive && focusShieldActive) {
          logEvent(analytics, 'sandbox_focus_regained', { time_away_ms: timeAway, total_time_away_ms: totalFocusLostTime.current });
          if (timeAway > 3000) { // Show stronger warning if away > 3s
            toast.error(`FOCUS SHIELD: Away for ${Math.round(timeAway / 1000)}s! Additional integrity impact.`);
            setIntegrityScore(prev => Math.max(0, prev - Math.min(15, Math.floor(timeAway / 1000)))); // More points for longer absence
          } else {
            toast.info("Focus Shield: Focus returned to exam.");
          }
        } else if (examStarted) {
          logEvent(analytics, 'sandbox_focus_regained', { time_away_ms: timeAway, total_time_away_ms: totalFocusLostTime.current });
          if (timeAway > 3000) { // Show stronger warning if away > 3s
            toast.error(`Returned after ${Math.round(timeAway / 1000)}s!`);
          } else {
            toast.info("Focus regained.");
          }
        }
      }
    };

    // Use blur/focus for window-level changes as well (fallback/complementary)
    const handleBlur = () => {
      if (document.hidden) return; // Ignore if already handled by visibilitychange
      setIsFocused(false);
      if (examStarted) {
        logEvent(analytics, 'sandbox_window_blur');
        // Don't necessarily increment focusLossCount here unless visibility didn't catch it
      } else if (challengeActive && focusShieldActive) {
        logEvent(analytics, 'sandbox_window_blur');
      }
    };
    
    const handleFocus = () => {
      if (!document.hidden) setIsFocused(true);
      if (examStarted) logEvent(analytics, 'sandbox_window_focus');
      else if (challengeActive) logEvent(analytics, 'sandbox_window_focus');
    };

    document.addEventListener('visibilitychange', handleVisibilityChange);
    window.addEventListener('blur', handleBlur);
    window.addEventListener('focus', handleFocus);

    return () => {
      document.removeEventListener('visibilitychange', handleVisibilityChange);
      window.removeEventListener('blur', handleBlur);
      window.removeEventListener('focus', handleFocus);
    };
  }, [examStarted, challengeActive, focusLossCount, focusShieldActive]); // Add challengeActive, focusShieldActive


  // Copy/Paste listener effect
  useEffect(() => {
    if (!examStarted && !challengeActive) return; // Only attach listeners when exam/challenge started

    document.addEventListener('copy', handleCopy);
    document.addEventListener('paste', handlePaste);

    return () => {
      document.removeEventListener('copy', handleCopy);
      document.removeEventListener('paste', handlePaste);
    };
  }, [examStarted, challengeActive, handleCopy, handlePaste]); // Re-attach if handlers change


  // Keystroke monitoring effect
  useEffect(() => {
    const handleKeyDown = (e: KeyboardEvent) => {
      if (!examStarted && !challengeActive) return;
      if (challengeActive && !keystrokeMonitorActive) return; // Skip if monitor not active

      let keyCombo = '';
      let shouldPreventDefault = false;

      // Detect specific key combinations
      if (e.key === 'PrintScreen' || e.key === 'Snapshot') { // Handle browser variations
        keyCombo = 'PrintScreen';
        shouldPreventDefault = true;
      } else if (e.ctrlKey && e.key.toLowerCase() === 'p') {
        keyCombo = 'Ctrl+P (Print)';
        shouldPreventDefault = true;
        
        // Mark print objective as completed if this is a challenge
        if (challengeActive) {
          logAndScoreEvent('print_attempt', 10, 'print');
        }
      } else if (e.metaKey && e.key.toLowerCase() === 'p') { // Cmd+P on Mac
        keyCombo = 'Cmd+P (Print)';
        shouldPreventDefault = true;
        
        // Mark print objective as completed if this is a challenge
        if (challengeActive) {
          logAndScoreEvent('print_attempt', 10, 'print');
        }
      } else if (e.ctrlKey && e.key.toLowerCase() === 'c') {
        keyCombo = 'Ctrl+C (Copy)';
        // Already handled by copy listener, maybe don't log/toast here? Or log differently?
        // logEvent(...);
      } else if (e.metaKey && e.key.toLowerCase() === 'c') { // Cmd+C
        keyCombo = 'Cmd+C (Copy)';
      } else if (e.ctrlKey && e.key.toLowerCase() === 'v') {
        keyCombo = 'Ctrl+V (Paste)';
        // Already handled by paste listener
      } else if (e.metaKey && e.key.toLowerCase() === 'v') { // Cmd+V
        keyCombo = 'Cmd+V (Paste)';
      }
      // Example: Detect Alt+Tab (tricky, often OS-level, might not work reliably)
      // else if (e.altKey && e.key === 'Tab') {
      //   keyCombo = 'Alt+Tab'; // Logging only, cannot prevent reliably
      // }

      if (keyCombo) {
        //console.log(`Restricted key press detected: ${keyCombo}`);
        setRestrictedKeyPresses(prev => [...prev, `${keyCombo} @ ${new Date().toLocaleTimeString()}`]);
        
        if (challengeActive) {
          logEvent(analytics, 'sandbox_restricted_key_press', { key_combo: keyCombo });
        } else {
          logEvent(analytics, 'sandbox_restricted_key_press', { key_combo: keyCombo });
        }

        if (shouldPreventDefault) {
          e.preventDefault();
          if (challengeActive) {
            toast.error(`KEYSTROKE MONITOR: ${keyCombo} attempt detected and blocked!`);
          } else {
            toast.error(`${keyCombo} is disabled during the exam simulation!`);
          }
        }
      }
    };

    window.addEventListener('keydown', handleKeyDown);
    return () => window.removeEventListener('keydown', handleKeyDown);
  }, [examStarted, challengeActive, keystrokeMonitorActive]);


  // Add Geolocation Objective if locationLockActive
  useEffect(() => {
    if (locationLockActive && !objectives.find(o => o.id === 'geo')) {
      setObjectives(prev => [...prev, { id: 'geo', text: "Ensure you are within the simulated 'Secure Exam Zone'.", completed: false, detected: false }]);
    } else if (!locationLockActive) {
      setObjectives(prev => prev.filter(o => o.id !== 'geo'));
    }
    // eslint-disable-next-line
  }, [locationLockActive]);

  // Update focus objective status
  useEffect(() => { 
    if (challengeActive && focusShieldActive && !isFocused) {
      // Mark objective as detected/completed after first focus loss
      if (focusLossCount > 0 && !objectives.find(o=>o.id==='focus')?.detected) {
        setObjectives(prev => prev.map(obj => obj.id === 'focus' ? { ...obj, detected: true, completed: true } : obj));
      }
    }
  }, [isFocused, focusLossCount, challengeActive, focusShieldActive, objectives]);


  // Geolocation logic
  const checkGeolocation = useCallback(() => {
    if (!('geolocation' in navigator)) {
      setGeoPermission('unsupported');
      toast.error('Geolocation is not supported by your browser.');
      return;
    }

    setIsCheckingLocation(true);
    setIsUserInZone(null);
    setDistanceFromZone(null);
    setUserLocation(null);

    navigator.geolocation.getCurrentPosition(
      (position) => {
        setGeoPermission('granted');
        const userPos = {
          lat: position.coords.latitude,
          lng: position.coords.longitude
        };
        setUserLocation(userPos);

        const distance = calculateDistance(
          userPos.lat, userPos.lng,
          allowedLocation.lat, allowedLocation.lng
        );
        setDistanceFromZone(distance);
        const isInZone = distance <= allowedRadius;
        setIsUserInZone(isInZone);

        logEvent(analytics, 'sandbox_location_check', {
          permission: 'granted',
          distance_m: Math.round(distance),
          radius_m: allowedRadius,
          in_zone: isInZone
        });

        if (!isInZone) {
          toast.error(`Location Check Failed: You are ~${Math.round(distance)}m away from the allowed zone (limit: ${allowedRadius}m).`);
          if (locationLockActive) {
            setObjectives(prev => prev.map(obj => obj.id === 'geo' ? { ...obj, completed: false, detected: true } : obj));
          }
        } else {
          toast.success('Location Check Passed: You are within the allowed zone.');
          if (locationLockActive) {
            setObjectives(prev => prev.map(obj => obj.id === 'geo' ? { ...obj, completed: true, detected: true } : obj));
          }
        }
        setIsCheckingLocation(false);
      },
      (error) => {
        setGeoPermission(error.code === error.PERMISSION_DENIED ? 'denied' : 'prompt'); // Update state based on error
        setUserLocation(null);
        setIsUserInZone(null);
        setDistanceFromZone(null);
        toast.error(`Geolocation Error: ${error.message}`);
        logEvent(analytics, 'sandbox_location_error', { error_code: error.code, error_message: error.message });
        
        if (locationLockActive) {
          setObjectives(prev => prev.map(obj => obj.id === 'geo' ? { ...obj, completed: false, detected: true } : obj));
        }
        
        setIsCheckingLocation(false);
      },
      { enableHighAccuracy: true, timeout: 10000, maximumAge: 0 } // Options
    );
  }, [allowedLocation, allowedRadius, locationLockActive]); // Dependencies

  // Check initial Geo permission state
  useEffect(() => {
    if ('permissions' in navigator) {
      navigator.permissions.query({ name: 'geolocation' }).then((permissionStatus) => {
        setGeoPermission(permissionStatus.state); // 'granted', 'prompt', 'denied'
        permissionStatus.onchange = () => {
          setGeoPermission(permissionStatus.state);
        };
      }).catch(() => {
        // Handle case where querying permissions isn't supported (fallback)
        if (!('geolocation' in navigator)) setGeoPermission('unsupported');
        else setGeoPermission('prompt'); // Assume prompt needed if query fails
      });
    } else {
      if (!('geolocation' in navigator)) setGeoPermission('unsupported');
      // Cannot check initial state without Permissions API, rely on checkGeolocation click
    }
  }, []);

  // --- Exam Simulation Control ---
  const startExam = () => {
    if (!honorCodeChecked) {
      toast.error('Please agree to the honor code first.');
      return;
    }
    // If location check hasn't passed successfully, prevent start
    if (geoPermission === 'prompt' || geoPermission === 'denied' || isCheckingLocation || isUserInZone === false) {
      toast.error('Please ensure location is verified and within the allowed zone before starting.');
      return;
    }
    logEvent(analytics, 'sandbox_exam_start');
    setExamStarted(true);
    // Reset logs for new session
    setFocusLossCount(0);
    setCopyAttempts(0);
    setPasteAttempts(0);
    setRestrictedKeyPresses([]);
    totalFocusLostTime.current = 0;
    timeLostFocus.current = null;

    toast.success('Exam Simulation Started!');
  };

  const endExam = () => {
    logEvent(analytics, 'sandbox_exam_end', {
      focus_losses: focusLossCount,
      total_focus_lost_ms: Math.round(totalFocusLostTime.current),
      copy_attempts: copyAttempts,
      paste_attempts: pasteAttempts,
      restricted_keys_count: restrictedKeyPresses.length
    });
    setExamStarted(false);
    toast.info('Exam Simulation Ended.');
  };

  // --- Challenge Mode Controls ---
  /*const startChallenge = () => {
    // Check location if location lock active
    if (locationLockActive && (geoPermission !== 'granted' || isUserInZone !== true)) {
      toast.error('Location Lock active! Please verify your position within the Secure Zone first.');
      // Mark geo objective as "failed to complete" if user tries to start
      if (!objectives.find(o=>o.id==='geo')?.detected) {
        setObjectives(prev => prev.map(obj => obj.id === 'geo' ? { ...obj, detected: true, completed: false } : obj));
      }
      return;
    }

    setChallengeActive(true);
    setIntegrityScore(100); // Reset score
    setObjectives(prev => prev.map(obj => ({ ...obj, completed: false, detected: false }))); // Reset objectives
    
    // Reset counters
    setFocusLossCount(0);
    setCopyAttempts(0);
    setPasteAttempts(0);
    setRestrictedKeyPresses([]);
    totalFocusLostTime.current = 0;
    timeLostFocus.current = null;
    
    toast.success("Challenge Active! Test the Integrity Shield!");
  };*/

  /*const endChallenge = () => {
    setChallengeActive(false);
    toast.info(
      <div>
        <h4>Challenge Debrief!</h4>
        <p>Integrity Score: {integrityScore}/100</p>
        <p>Focus Shields Breached: {focusLossCount} times</p>
        <p>Clipboard Extractions Attempted (Copy): {copyAttempts}</p>
        <p>Paste Attempts: {pasteAttempts}</p>
        <p>Restricted Key Presses: {restrictedKeyPresses.length}</p>
        <Link to="/pricing" className={styles.ctaLink}> {/* Fictional pricing page link /}
          Unlock these features for your exams!
        </Link>
      </div>,
      { autoClose: 10000 }
    );
  };*/

  //const canStartExam = honorCodeChecked && geoPermission === 'granted' && isUserInZone === true;
  // --- Render ---
  return (
    <div className={styles.sandboxPage}>
        <ToastContainer position="top-right" autoClose={3000} theme="colored" newestOnTop />

        <h1><FaUserSecret /> Integrity Shield: Sandbox Challenge</h1>
        <p className={styles.pageDescription}>
            Welcome, Agent! Your mission is to test Examify's defense layers. Activate shields, attempt 'rogue' actions, and see real-time detections. Can you outsmart the system?
        </p>

        {/* --- Configure Defense Layers (Visible when challenge not active) --- */}
        {!examStarted && (
            <section className={`${styles.sandboxSection} ${styles.defenseConfigSection}`}>
                <h2><FaShieldAlt /> Activate Defense Layers</h2>
                {/* Focus Shield */}
                <div className={styles.defenseLayerToggle}>
                    <FaEyeSlash />
                    <label htmlFor="focusShield">Focus Shield (Tab/Window Switch Detection)</label>
                    <input type="checkbox" id="focusShield" checked={focusShieldActive} onChange={e => setFocusShieldActive(e.target.checked)} />
                </div>
                {/* Clipboard Lockdown */}
                <div className={styles.defenseLayerToggle}>
                    <FaPaste />
                    <label htmlFor="clipboardLock">Clipboard Lockdown (Copy/Paste Prevention)</label>
                    <input type="checkbox" id="clipboardLock" checked={clipboardLockdownActive} onChange={e => setClipboardLockdownActive(e.target.checked)} />
                </div>
                {/* Keystroke Monitor */}
                <div className={styles.defenseLayerToggle}>
                    <FaKeyboard />
                    <label htmlFor="keyMonitor">Keystroke Monitor (Restricted Keys Logging)</label>
                    <input type="checkbox" id="keyMonitor" checked={keystrokeMonitorActive} onChange={e => setKeystrokeMonitorActive(e.target.checked)} />
                </div>
                {/* Location Lock */}
                <div className={styles.defenseLayerToggle}>
                    <FaMapMarkerAlt />
                    <label htmlFor="locationLock">Location Lock (Geolocation Restriction)</label>
                    <input type="checkbox" id="locationLock" checked={locationLockActive} onChange={e => setLocationLockActive(e.target.checked)} />
                </div>

                {locationLockActive && (
                    <div className={styles.locationConfigBox}>
                        <h4>Secure Zone Parameters:</h4>
                        <div className={styles.locationConfig}>
                             <div>
                                <label htmlFor="lat">Allowed Latitude:</label>
                                <input
                                    id="lat" type="number" value={allowedLocation.lat} step="0.0001"
                                    onChange={(e) => setAllowedLocation({...allowedLocation, lat: parseFloat(e.target.value) || 0})}
                                />
                             </div>
                            <div>
                                <label htmlFor="lng">Allowed Longitude:</label>
                                <input
                                    id="lng" type="number" value={allowedLocation.lng} step="0.0001"
                                    onChange={(e) => setAllowedLocation({...allowedLocation, lng: parseFloat(e.target.value) || 0})}
                                />
                            </div>
                            <div>
                                 <label htmlFor="radius">Allowed Radius (meters):</label>
                                 <input
                                    id="radius" type="number" value={allowedRadius} min="10" max="100000"
                                    onChange={(e) => setAllowedRadius(parseInt(e.target.value, 10) || 10)}
                                />
                            </div>
                        </div>
                        <button
                            onClick={checkGeolocation}
                            disabled={isCheckingLocation}
                            className={styles.checkButton}
                        >
                             {isCheckingLocation ? <Spinner size="1em" /> : <FaLocationArrow />}
                             Check My Location Now
                        </button>
                        {/* Display Geo Status */}
                        <div className={styles.geoStatus}>
                            <p>
                                Permission Status: {
                                    geoPermission === 'unsupported' ? <span className={styles.error}>Not Supported</span> :
                                    geoPermission === 'denied' ? <span className={styles.error}>Denied</span> :
                                    geoPermission === 'prompt' ? <span className={styles.warning}>Needs Permission</span> :
                                    <span className={styles.success}>Granted</span>
                                }
                            </p>
                            
                            {/* Display Current Location */}
                            {userLocation && (
                                <p className={styles.currentLocation}>
                                    <FaMapMarkerAlt /> Your Detected Location:
                                    <span className={styles.coords}>Lat: {userLocation.lat.toFixed(6)}, Lng: {userLocation.lng.toFixed(6)}</span>
                                    {distanceFromZone !== null && ` (~${Math.round(distanceFromZone)}m from target)`}
                                </p>
                            )}
                            
                            {/* Zone Status */}
                            {geoPermission === 'granted' && isUserInZone !== null && (
                                <p>
                                    Zone Status: {
                                        isUserInZone === true ? <span className={styles.success}>✓ In Allowed Zone</span> :
                                        isUserInZone === false ? <span className={styles.error}>✗ Out of Allowed Zone</span> :
                                        'Checking...'
                                    }
                                </p>
                            )}
                        </div>
                    </div>
                )}

                {/* Honor Code */}
                <div className={styles.settingBlock}>
                    <h3 className={styles.settingTitle}>Honor Code Agreement</h3>
                    <label className={styles.checkboxLabel} htmlFor="honorCode">
                         <input
                            type="checkbox"
                            id="honorCode"
                            checked={honorCodeChecked}
                            onChange={(e) => setHonorCodeChecked(e.target.checked)}
                         />
                         <span>I agree not to use unauthorized aids or attempt to circumvent security measures during the simulation.</span>
                    </label>
                </div>

                <div className={styles.startAction}>
                    <button 
                        onClick={startExam} 
                        disabled={!honorCodeChecked || (locationLockActive && (geoPermission !== 'granted' || isUserInZone !== true))}
                        className={styles.startButton}
                    >
                        <FaPlayCircle /> Start Challenge
                    </button>
                </div>
            </section>
        )}

        {/* --- Challenge Zone (Visible when active) --- */}
        {examStarted && (
            <>
                <section className={`${styles.sandboxSection} ${styles.challengeZone}`}>
                    <div className={styles.challengeHeader}>
                        <h2><FaTasks /> Challenge Zone - ACTIVE</h2>
                        <span className={styles.integrityScoreDisplay}>
                            Integrity Score: <strong>{integrityScore}</strong> / 100
                        </span>
                        {/* Focus Indicator (visual feedback) */}
                        <span className={`${styles.focusIndicator} ${isFocused ? styles.focusActive : styles.focusLost}`}>
                            {isFocused ? <><FaEye /> System Focused</> : <><FaEyeSlash /> Focus Lost!</>}
                        </span>
                    </div>

                    <div className={styles.objectivesList}>
                        <h3>Your Objectives:</h3>
                        <ul>
                            {objectives.map(obj => (
                                <li key={obj.id} className={obj.completed ? (obj.detected ? styles.objDetected : styles.objStealth) : ''}>
                                    <span className={styles.objStatusIcon}>
                                        {obj.completed ? (obj.detected ? <FaCheckCircle color="red"/> : <FaCheckCircle color="green"/>) : <FaBullseye/>}
                                    </span>
                                    {obj.text}
                                    {obj.detected && obj.completed && <span className={styles.objTagDetected}>Detected!</span>}
                                    {!obj.detected && obj.completed && <span className={styles.objTagStealth}>Stealth! (System Missed?)</span>}
                                </li>
                            ))}
                        </ul>
                    </div>

                    <div className={styles.interactiveArea}>
                        <h4><FaFileAlt /> Secret Document:</h4>
                        <textarea className={styles.secretDocument} value={secretDocumentText} readOnly />
                        <h4><FaKeyboard /> Suspicious Input Field:</h4>
                        <input type="text" className={styles.suspiciousInput} value={suspiciousInput} onChange={(e)=> setSuspiciousInput(e.target.value)} placeholder="Try pasting here..."/>
                    </div>

                    <div className={styles.endAction}>
                        <button onClick={endExam} className={styles.endButton}>
                            End Challenge & Debrief
                        </button>
                    </div>
                </section>

                {/* Detection Grid / System Alerts */}
                <section className={`${styles.sandboxSection} ${styles.detectionGridSection}`}>
                    <h2><FaBroadcastTower /> Detection Grid</h2>
                    <div className={styles.detectionGrid}>
                        {/* Panel for Focus Events */}
                        <div className={`${styles.logBlock} ${focusLossCount > 0 ? styles.alertActive : ''}`}>
                            <h4 className={styles.logTitle}><FaEyeSlash /> Focus Shield Alerts</h4>
                            <p>Focus Lost Count: <strong>{focusLossCount}</strong></p>
                            <p>Total Time Away: <strong>{Math.round(totalFocusLostTime.current / 1000)}s</strong></p>
                        </div>
                        {/* Panel for Clipboard Events */}
                        <div className={`${styles.logBlock} ${copyAttempts > 0 || pasteAttempts > 0 ? styles.alertActive : ''}`}>
                            <h4 className={styles.logTitle}><FaPaste /> Clipboard Lockdown Alerts</h4>
                            <p>Copy Attempts Blocked: <strong>{copyAttempts}</strong></p>
                            <p>Paste Attempts Blocked: <strong>{pasteAttempts}</strong></p>
                        </div>
                        {/* Panel for Keystroke Events */}
                        <div className={`${styles.logBlock} ${restrictedKeyPresses.length > 0 ? styles.alertActive : ''}`}>
                            <h4 className={styles.logTitle}><FaKeyboard /> Keystroke Monitor Alerts</h4>
                            {restrictedKeyPresses.length === 0 ? (
                                <p className={styles.noLogs}>No restricted keys logged.</p>
                            ) : (
                                <ul className={styles.logList}>
                                    {restrictedKeyPresses.slice(-5).map((event, index) => ( // Show last 5
                                        <li key={index}>{event}</li>
                                    ))}
                                    {restrictedKeyPresses.length > 5 && <li>...and {restrictedKeyPresses.length - 5} more.</li>}
                                </ul>
                            )}
                        </div>
                        {/* Panel for Geo Events (if active) */}
                        {locationLockActive && (
                             <div className={`${styles.logBlock} ${isUserInZone === false ? styles.alertActive : ''}`}>
                                <h4 className={styles.logTitle}><FaMapMarkerAlt /> Location Lock Status</h4>
                                <p>Secure Zone: <strong>Active</strong></p>
                                {isUserInZone === true && <p className={styles.geoStatusSuccess}>Status: You are INSIDE the Secure Zone.</p>}
                                {isUserInZone === false && <p className={styles.geoStatusFailure}>ALERT: You are OUTSIDE the Secure Zone!</p>}
                                {isCheckingLocation && <Spinner size="0.9em" text="Verifying zone..." />}
                            </div>
                        )}
                    </div>
                </section>
            </>
        )}
        {/* Link to learn more about perks, visible always or after challenge */}
        <div className={styles.perkInfoSection}>
            <p>
                <FaStar /> These Integrity Shield features demonstrate advanced monitoring capabilities available in Examify's premium tiers for Group Sessions.
                <Link to="/pricing" className={styles.learnMoreLink}>Learn More & Upgrade</Link> {/* Fictional pricing page */}
            </p>
        </div>
    </div>
  );
                        }
export default AntiCheatingSandboxPage;
```

---

## pages\BlogListPage


### pages\BlogListPage\BlogListPage.module.scss

```scss
@import '../../styles/variables';

.blogListPage {
     // Uses .container from global/base styles
    padding: $spacer * 2 0 $spacer * 3 0;

    h1 {
        font-size: $h2-font-size;
        color: $primary-color;
        text-align: center;
        margin-bottom: $spacer;
        font-weight: 600;
         display: flex;
         align-items: center;
         justify-content: center;
         gap: $spacer;
    }
     .blogSubtitle {
        text-align: center;
        font-size: $font-size-base * 1.1;
        color: $text-muted;
        margin-bottom: $spacer * 3;
        max-width: 700px;
         margin-left: auto;
         margin-right: auto;
     }

    //.postList {
        // Layout for the list of previews (e.g., single column)
    //}
     .errorMessage {
        color: $danger-color;
        text-align: center;
        font-weight: 500;
     }
}
```

---

### pages\BlogListPage\BlogListPage.tsx

```typescript
// src/pages/BlogListPage/BlogListPage.tsx
import React, { useState, useEffect } from 'react';
import { BlogPostMeta } from '../../types';
import BlogPostPreview from '../../components/BlogPostPreview/BlogPostPreview';
import listStyles from './BlogListPage.module.scss'; // Specific list styles
import { FaRss } from 'react-icons/fa';
import Spinner from '../../components/Spinner/Spinner';

// Import the index directly (or fetch if you prefer async loading)
// For direct import, ensure your build tool handles JSON imports
// If using Create React App, this usually works out of the box.
const CONTENT_REPO_BASE_URL = 'https://raw.githubusercontent.com/Samkarya/online-exam-questions/main/';

const BlogListPage: React.FC = () => {
    const [posts, setPosts] = useState<BlogPostMeta[]>([]);
    const [isLoading, setIsLoading] = useState<boolean>(true);
    const [error, setError] = useState<string | null>(null);

    useEffect(() => {
        document.title = 'Blog - Examify';

        const fetchPosts = async () => {
            setIsLoading(true);
            setError(null);
            try {
                // Fetch the index from the GitHub repo
                const response = await fetch(`${CONTENT_REPO_BASE_URL}blog/blog-index.json`);
                if (!response.ok) {
                   // Provide more specific error based on status
                   if (response.status === 404) {
                      throw new Error('Blog index file not found in repository.');
                   } else {
                      throw new Error(`Failed to fetch blog index (${response.status})`);
                   }
                }
                const data: BlogPostMeta[] = await response.json();
                // Sort posts by date descending
                data.sort((a, b) => new Date(b.date).getTime() - new Date(a.date).getTime());
                setPosts(data);
            } catch (err: any) {
                setError(err.message || 'Failed to fetch blog posts.');
                //console.error("Fetch error:", err);
            } finally {
                setIsLoading(false);
            }
        };

        fetchPosts();

    }, []);


    return (
        <div className={listStyles.blogListPage}>
             <div className="container">
                <h1><FaRss /> Examify Blog</h1>
                <p className={listStyles.blogSubtitle}>Tips, Guides, Updates, and Insights for Your Exam Preparation</p>

                {isLoading && <p className={listStyles.loadingMessage}><Spinner text="Loading posts..." /></p>}
                {error && <p className={listStyles.errorMessage}>{error}</p>}

                {!isLoading && !error && (
                    posts.length > 0 ? (
                        <div className={listStyles.postList}>
                            {posts.map(post => (
                                <BlogPostPreview key={post.slug} post={post} />
                            ))}
                        </div>
                    ) : (
                        // Show slightly different message if loading finished but no posts
                        !isLoading && <p>No blog posts found yet. Check back soon!</p>
                    )
                )}
            </div>
        </div>
    );
};

export default BlogListPage;
```

---

## pages\BlogPostPage


### pages\BlogPostPage\BlogPostPage.module.scss

```scss
@import '../../styles/variables';

// BlogPostPage inherits basic layout from StaticPages.module.scss via className prop

//.blogPostPage {
     // Add specific overrides or additions here
//}

.backLink {
     display: inline-flex;
     align-items: center;
     gap: $spacer * 0.5;
     margin-bottom: $spacer * 2;
     font-weight: 500;
     color: $link-color;
     text-decoration: none;
     &:hover {
         color: $link-hover-color;
         text-decoration: underline;
     }
}

.postHeader {
     margin-bottom: $spacer * 2.5;
     padding-bottom: $spacer * 1.5;
     border-bottom: 1px solid $border-color;

     h1 {
         text-align: left; // Override centered static page title
         font-size: $h1-font-size * 0.9; // Slightly smaller than H1 if needed
         margin-bottom: $spacer * 0.75;
         color: $dark-color;
     }
}
.postMeta {
    // Adjust spacing or alignment if needed from preview styles
    justify-content: flex-start; // Align left
    gap: $spacer * 1.5; // Increase gap
    margin-bottom: $spacer;
}
.postTags {
     justify-content: flex-start; // Align left
     margin-top: $spacer; // Add space above tags
}

.postContent {
     // Styles for the main content area rendered by MarkdownRenderer
     // Target elements rendered by markdown (p, h2, h3, ul, ol, blockquote, pre, code)
     // Use deep selectors if needed, but MarkdownRenderer structure is usually flat

     // Example styling within the content
     h2 {
         font-size: $h4-font-size; // Adjust heading sizes within post
         margin-top: $spacer * 2.5;
         margin-bottom: $spacer;
         border-bottom: none; // Remove border from headings inside content
         padding-bottom: 0;
     }
      h3 {
          font-size: $h5-font-size;
           margin-top: $spacer * 2;
         margin-bottom: $spacer * 0.75;
     }
     // Ensure nested lists have proper indentation
     ul ul, ol ol, ul ol, ol ul {
          margin-top: $spacer * 0.5;
          margin-bottom: $spacer * 0.75;
     }

     blockquote {
         border-left: 4px solid $border-color;
         padding-left: $spacer * 1.5;
         margin: $spacer * 1.5 $spacer * 0.5;
         color: $text-muted;
         font-style: italic;

         p:last-child { // Remove extra margin from last paragraph in quote
             margin-bottom: 0;
         }
     }

     // Ensure code blocks from MarkdownRenderer look good
     pre {
         background-color: lighten($dark-color, 5%) !important; // Override potential theme bg if needed
         padding: $spacer !important;
         border-radius: $border-radius-sm;
         margin: $spacer * 1.5 0;
         // Ensure font size/family are appropriate if not set by highlighter
     }
      // Inline code styling (redundant if set globally, but explicit here)
     code:not(pre > code) { // Target only inline code
          background-color: lighten($light-color, 3%);
          border: 1px solid $border-color;
          padding: 2px 5px;
          border-radius: $border-radius-sm;
          font-family: monospace;
          font-size: 90%;
     }
     img {
        display: block; // Make images block level
        margin: $spacer * 1.5 auto; // Center images with margin
        max-width: 100%; // Ensure images are responsive
         height: auto;
         border-radius: $border-radius; // Optional rounded corners
         box-shadow: 0 2px 8px rgba($black-color, 0.1); // Optional subtle shadow
     }
}

.errorMessage {
    color: $danger-color;
    font-weight: 500;
 }
```

---

### pages\BlogPostPage\BlogPostPage.tsx

```typescript
// src/pages/BlogPostPage/BlogPostPage.tsx
import React, { useState, useEffect } from 'react';
import { useParams, Link} from 'react-router-dom';
import { BlogPost, BlogPostMeta } from '../../types';
import MarkdownRenderer from '../../components/MarkdownRenderer/MarkdownRenderer'; // Your existing renderer
import pageStyles from './BlogPostPage.module.scss'; // Specific page styles
import metaStyles from '../../components/BlogPostPreview/BlogPostPreview.module.scss'; // Reuse meta styles
import staticPageStyles from '../StaticPages/StaticPages.module.scss'; // Reuse general static page styles
import { FaCalendarAlt, FaUser, FaTags, FaArrowLeft } from 'react-icons/fa';
import Spinner from '../../components/Spinner/Spinner';

const CONTENT_REPO_BASE_URL = 'https://raw.githubusercontent.com/Samkarya/online-exam-questions/main/'; 

const BlogPostPage: React.FC = () => {
    const { slug } = useParams<{ slug: string }>();
    const [post, setPost] = useState<BlogPost | null>(null);
    const [isLoading, setIsLoading] = useState<boolean>(true);
    const [error, setError] = useState<string | null>(null);

    useEffect(() => {
        const fetchPostData = async () => {
            setIsLoading(true);
            setError(null);
            setPost(null);

            if (!slug) {
                setError("Blog post identifier is missing.");
                setIsLoading(false);
                return;
            }

            try {
                // 1. Fetch the blog index first to get the metadata and file path
                const indexResponse = await fetch(`${CONTENT_REPO_BASE_URL}blog/blog-index.json`);
                if (!indexResponse.ok) {
                     throw new Error(`Failed to fetch blog index (${indexResponse.status})`);
                 }
                const blogIndex: BlogPostMeta[] = await indexResponse.json();
                const postMeta = blogIndex.find(p => p.slug === slug);

                if (!postMeta || !postMeta.mdFilePath) {
                    setError(`Blog post "${slug}" not found or is missing its file path in the index.`);
                    setIsLoading(false);
                    return;
                }

                // 2. Fetch the actual Markdown content using the path from the index
                const contentResponse = await fetch(`${CONTENT_REPO_BASE_URL}${postMeta.mdFilePath}`);
                if (!contentResponse.ok) {
                    throw new Error(`Failed to fetch blog content for "${slug}" (${contentResponse.status})`);
                }
                const fetchedContent = await contentResponse.text();

                // 3. Combine metadata and content
                setPost({ ...postMeta, content: fetchedContent });
                document.title = `${postMeta.title} - Examify Blog`;

            } catch (err: any) {
                //console.error(`Error loading blog post "${slug}":`, err);
                setError(err.message || `Could not load blog post "${slug}".`);
            } finally {
                setIsLoading(false);
            }
        };

        fetchPostData();

    }, [slug]);

    return (
        <div className={`${staticPageStyles.staticPage} ${pageStyles.blogPostPage}`}> {/* Combine styles */}
             <div className={staticPageStyles.container}>
                 <Link to="/blog" className={pageStyles.backLink}><FaArrowLeft /> Back to Blog List</Link>

                 {isLoading && <p className={pageStyles.loadingMessage}><Spinner text="Loading post..." /></p>}
                {error && <p className={pageStyles.errorMessage}>{error}</p>}

                {post && !isLoading && !error && (
                    <article>
                        <header className={pageStyles.postHeader}>
                            <h1>{post.title}</h1>
                            <div className={`${metaStyles.previewMeta} ${pageStyles.postMeta}`}> {/* Reuse meta styles */}
                                <span title="Published Date"><FaCalendarAlt /> {new Date(post.date).toLocaleDateString('en-US', { year: 'numeric', month: 'long', day: 'numeric' })}</span>
                                {post.author && <span title="Author"><FaUser /> {post.author}</span>}
                             </div>
                             {post.tags && post.tags.length > 0 && (
                                 <div className={`${metaStyles.previewTags} ${pageStyles.postTags}`}>
                                     <FaTags />
                                     {post.tags.map(tag => (
                                         <span key={tag} className={metaStyles.tag}>{tag}</span>
                                     ))}
                                 </div>
                            )}
                        </header>

                        <div className={pageStyles.postContent}>
                            {/* Render the fetched markdown content */}
                            <MarkdownRenderer>{post.content}</MarkdownRenderer>
                        </div>
                    </article>
                )}
            </div>
        </div>
    );
};

export default BlogPostPage;
```

---

## pages\ExamPage


### pages\ExamPage\ExamPage.module.scss

```scss
// src/pages/ExamPage/ExamPage.module.scss
@import '../../styles/variables';
@import '../../styles/mixins';

.statusMessage {
    padding: $spacer * 2;
    text-align: center;
    min-height: 300px; // Ensure it takes some space
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    gap: $spacer;
     button {
         // Basic button styling if needed
         padding: $spacer * 0.5 $spacer;
     }
}

.configSection {
    padding: $spacer * 2;
    max-width: 600px;
    margin: $spacer * 2 auto;
    background-color: $component-bg;
    border: 1px solid $border-color;
    border-radius: $border-radius-lg;
    box-shadow: 0 3px 8px rgba($black-color, 0.1);

    h2 {
        text-align: center;
        margin-bottom: $spacer * 1.5;
    }
     div { // Basic layout for labels/inputs
        margin-bottom: $spacer;
     }
     label {
        display: block; // Or flex
        margin-bottom: $spacer * 0.25;
         font-weight: 500;
     }
     input[type="number"], input[type="checkbox"] {
        margin-left: $spacer * 0.5; // Example spacing
         padding: $spacer * 0.4;
         border: 1px solid $border-color;
         border-radius: $border-radius;
     }
      input[type="checkbox"] {
         transform: scale(1.1); // Slightly larger checkbox
         margin-right: $spacer * 0.5;
      }
}

.startButton {
     @include button-variant($success-color, $success-color);
     display: block;
     width: 100%;
     padding: $spacer $spacer * 1.5;
     font-size: $font-size-base * 1.1;
     margin-top: $spacer * 1.5;
}


// --- Active Exam Layout ---
.examLayout {
    display: flex;
    flex-direction: column; // Mobile first
    gap: $spacer;
     padding-top: 0; // Reduce padding from main layout if needed

    @include media-breakpoint-up(lg) {
        flex-direction: row; // Side-by-side on larger screens
        height: 100vh; // Adjust based on header height & padding (Approximate)
        overflow: hidden; // Prevent scrolling of the main layout parts
    }
}

.leftPanel {
    flex-grow: 1; // Takes more space
    display: flex;
    flex-direction: column;
     background-color: $component-bg; // Optional background
     border: 1px solid $border-color; // Optional border
     border-radius: $border-radius; // Optional radius
     overflow-y: auto; // Allow scrolling within left panel if content overflows

    @include media-breakpoint-up(lg) {
         height: 100%; // Take full height of parent
         // overflow: hidden; // Don't allow left panel itself to scroll if Q area handles it
     }
}

.rightPanel {
     width: 100%; // Full width mobile
     display: flex;
     flex-direction: column;
     gap: $spacer;

    @include media-breakpoint-up(lg) {
        width: 300px; // Fixed width for sidebar on larger screens
        flex-shrink: 0; // Prevent shrinking
         height: 100%; // Full height
         overflow-y: auto; // Allow right panel to scroll if palette is long
    }
}

// --- Placeholder Area Styles ---
.questionArea {
    flex-grow: 1; // Takes available space in left panel
    padding: $spacer * 1.5;
     overflow-y: auto; // Scroll within question area if needed
}

.bottomControls {
    border-top: 1px solid $border-color;
    padding: $spacer;
    background-color: lighten($light-color, 2%);
     flex-shrink: 0; // Prevent shrinking
}

.timerArea {
     background-color: $component-bg;
     border: 1px solid $border-color;
     padding: $spacer;
     text-align: center;
      border-radius: $border-radius;
     flex-shrink: 0;
}

.paletteArea {
     background-color: $component-bg;
     border: 1px solid $border-color;
      border-radius: $border-radius;
     padding: $spacer;
     flex-grow: 1; // Take remaining space in right panel
     overflow-y: auto; // Allow palette itself to scroll
}
.submitArea {
     background-color: $component-bg;
     border: 1px solid $border-color;
     border-radius: $border-radius;
     padding: $spacer;
     text-align: center;
     flex-shrink: 0;
}
```

---

### pages\ExamPage\ExamPage.tsx

```typescript
// src/pages/ExamPage/ExamPage.tsx
import React, { useEffect } from 'react';
import { useParams, useNavigate } from 'react-router-dom';
import { useExam } from '../../contexts/ExamContext';
import styles from './ExamPage.module.scss';
import { ExamSettings } from '../../types';
import Spinner from '../../components/Spinner/Spinner';

import QuestionDisplay from '../../components/QuestionDisplay/QuestionDisplay';
import ExamTimer from '../../components/ExamTimer/ExamTimer';
import NavigationPalette from '../../components/NavigationPalette/NavigationPalette';
import ExamControls from '../../components/ExamControls/ExamControls';
import SubmitExamButton from '../../components/SubmitExamButton/SubmitExamButton';
import MonitoringIndicator from '../../components/MonitoringIndicator/MonitoringIndicator'; 
interface ExamPageProps {
    isGroupSession?: boolean;       // Optional: to know the context
    monitoringActive?: boolean;   // Is monitoring feature enabled for this exam?
    isCurrentlyFocused?: boolean; // Actual current focus state
}
const ExamPage: React.FC<ExamPageProps> = ({
    isGroupSession = false,
    monitoringActive = false,
    isCurrentlyFocused = true // Default to true, will be updated by prop
}) => {
    const { examIdentifier: urlIdentifier } = useParams<{ examIdentifier: string }>();
    const {
        examStatus,
        questions,
        currentQuestionIndex,
        error,
        //loadExam, // May need to reload if user navigates directly? Or rely on previous load.
        startExam, // To start the exam after configuration
        // clearExamState // To clean up on unmount or error
    } = useExam();
    const navigate = useNavigate();

     // State for exam configuration modal/step
     const [showConfig, setShowConfig] = React.useState(false);
     const [configuredSettings, setConfiguredSettings] = React.useState<ExamSettings | null>(null);


    useEffect(() => {
        // Redirect if accessed directly without loading state or if ID mismatch
        if (examStatus !== 'ready' && examStatus !== 'active' && examStatus !== 'loading' && examStatus !== 'submitting' && examStatus !== 'finished') {
           //console.warn("Exam state not ready or active. Redirecting.");
             // Optionally try to reload if urlIdentifier is present? Risky.
             // loadExam(decodeURIComponent(urlIdentifier!), ???, ???) -> Need type/source
             navigate('/select-exam', { replace: true, state: { message: 'Please select an exam first.' } });
             return;
        }

         // Once loaded ('ready'), show configuration options
         if (examStatus === 'ready') {
             setShowConfig(true);
             // Pre-fill default settings?
             setConfiguredSettings({
                timeLimitMinutes: 120, // Default example
                negativeMarkingEnabled: true,
                marksPerCorrect: 4, // Default example
                negativeMarksPerIncorrect: 1, // Default example
                trackQuestionTime: true
             });
         } else {
             setShowConfig(false);
         }

         // Cleanup on unmount only if exam finished/aborted? Careful not to clear during navigation
         // return () => {
         //    if(examStatus !== 'active' && examStatus !== 'paused') { // Example condition
         //       clearExamState();
         //    }
         // }

    }, [examStatus, navigate, urlIdentifier]); // Add dependencies


     const handleStartExam = () => {
         if (configuredSettings && examStatus === 'ready') {
             startExam(configuredSettings);
             setShowConfig(false);
         } else {
            //console.error("Cannot start: Settings not configured or exam not ready.");
         }
     };

    // --- Render logic ---
    if (examStatus === 'loading') {
        return <div className={styles.statusMessage}><Spinner text="Loading Exam Questions..." size={24} /></div>;
    }

    if (error) {
         return (
             <div className={styles.statusMessage}>
                 <h2>Error Loading Exam</h2>
                 <p>{error}</p>
                 <button onClick={() => navigate('/select-exam')}>Go Back</button>
             </div>
         );
    }

     if (showConfig && configuredSettings) {
         // *** Render Exam Configuration Modal/Section ***
         // This would be a separate component ideally
         return (
             <div className={styles.configSection}>
                 <h2>Configure Your Practice Session</h2>
                  {/* Form elements to modify configuredSettings state */}
                 <div>
                    <label>
                        Time Limit (minutes, 0 or empty for none):
                        <input type="number" min="0" value={configuredSettings.timeLimitMinutes ?? ''} onChange={e => setConfiguredSettings((prev: any) => ({...prev!, timeLimitMinutes: e.target.value ? parseInt(e.target.value) : null}))} />
                    </label>
                 </div>
                  <div>
                     <label>
                         Marks per Correct Answer:
                         <input type="number" min="0" step="0.1" value={configuredSettings.marksPerCorrect} onChange={e => setConfiguredSettings((prev: any) => ({...prev!, marksPerCorrect: parseFloat(e.target.value) || 0}))} />
                     </label>
                  </div>
                 <div>
                    <label>
                        Enable Negative Marking:
                        <input type="checkbox" checked={configuredSettings.negativeMarkingEnabled} onChange={e => setConfiguredSettings((prev: any) => ({...prev!, negativeMarkingEnabled: e.target.checked}))} />
                    </label>
                 </div>
                 {configuredSettings.negativeMarkingEnabled && (
                     <div>
                         <label>
                             Negative Marks per Incorrect Answer:
                             <input type="number" min="0" step="0.1" value={configuredSettings.negativeMarksPerIncorrect} onChange={e => setConfiguredSettings((prev: any) => ({...prev!, negativeMarksPerIncorrect: parseFloat(e.target.value) || 0}))} />
                         </label>
                     </div>
                 )}
                 <button onClick={handleStartExam} className={styles.startButton}>Start Exam</button>
             </div>
         );
     }


     if (examStatus !== 'active') {
        // ... handling for non-active states ...
        // Add handling for 'submitting' state if needed
        if (examStatus === 'submitting') {
            return <div className={styles.statusMessage}><Spinner text="Submitting your answers..." size={24}/></div>;
        }
        return <div className={styles.statusMessage}>Preparing exam interface...</div>;
    }

    // --- Main Exam Interface (when status is 'active') ---
    if (questions.length === 0) {
         return <div className={styles.statusMessage}>Error: No questions found for this exam.</div>; // Should have been caught earlier
    }

     const currentQuestion = questions[currentQuestionIndex];
      if (!currentQuestion) {
          return <div className={styles.statusMessage}>Error: Invalid question index.</div>;
      }


    return (
        <div className={styles.examLayout}>
            <div className={styles.leftPanel}>
                 {/* Placeholder for Question Area */}
                 <div className={styles.questionArea}>
                     <QuestionDisplay />
                 </div>

                  {/* Placeholder for Bottom Controls (Prev/Next/Mark/Clear) */}
                 <div className={styles.bottomControls}>
                     <ExamControls />
                 </div>
            </div>

            <div className={styles.rightPanel}>
                 {/* Placeholder for Timer */}
                 <div className={styles.timerArea}>
                     <ExamTimer />
                 </div>

                 {/* Placeholder for Question Palette */}
                 <div className={styles.paletteArea}>
                      <NavigationPalette />
                 </div>

                 {/* Placeholder for Submit Button */}
                 <div className={styles.submitArea}>
                 <SubmitExamButton />
                 </div>
            </div>
            {isGroupSession && monitoringActive && (
                <MonitoringIndicator
                    isActive={true} // It's active because monitoringActive is true
                    isPageFocused={isCurrentlyFocused}
                />
            )}
        </div>
    );
};

export default ExamPage;
```

---

## pages\ExamSelectionPage


### pages\ExamSelectionPage\ExamSelectionPage.module.scss

```scss
@import '../../styles/variables';
@import '../../styles/mixins';

.selectionPage {
    padding: $spacer * 2 0 $spacer * 3 0; // Generous vertical padding
    h1 {
        text-align: center;
        margin-bottom: $spacer * 0.75; // Reduced margin
        color: $primary-color;
        font-weight: 600;
    }
    .subtitle {
        text-align: center;
        color: $text-muted;
        margin-bottom: $spacer * 3; // More space before options
        font-size: $font-size-base * 1.1;
        max-width: 700px; // Keep readability
        margin-left: auto;
        margin-right: auto;
    }
}

.statusContainer {
    margin-bottom: $spacer * 1.5;
    min-height: 40px; // Reserve some space even when empty
    padding: 0 $spacer; // Horizontal padding for messages
}

// Common Status Message Styles
.statusMessage {
    padding: $spacer * 0.75 $spacer * 1.5; // Adjust padding
    text-align: center;
    font-size: $font-size-base;
    color: $text-muted;
    border-radius: $border-radius;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: $spacer * 0.5;

    &.infoMessage { // Distinct info style
        background-color: lighten($info-color, 45%);
        border: 1px solid lighten($info-color, 30%);
        color: darken($info-color, 15%);
    }
    &.errorMessage { // Distinct error style
        background-color: lighten($danger-color, 45%);
        border: 1px solid lighten($danger-color, 30%);
        color: darken($danger-color, 15%);
        font-weight: 500;
    }
}

// Three-column grid for the main options
.threeColumnGrid {
    display: grid;
    grid-template-columns: 1fr; // Mobile first - stacked
    gap: $spacer * 2.5;
    align-items: start;

    @include media-breakpoint-up(md) {
        grid-template-columns: 1fr auto 1fr; // Three columns layout
        gap: $spacer * 2;
    }
}

// Base styles for any section
.optionSection {
    background-color: $component-bg;
    border: 1px solid $border-color;
    border-radius: $border-radius-lg;
    padding: $spacer * 1.5 $spacer * 2;
    box-shadow: $box-shadow-sm;
    transition: opacity $transition-medium, filter $transition-medium, box-shadow $transition-medium;
    height: 100%; // Make sections equal height in grid row

    h2 {
        text-align: center;
        margin-top: 0;
        margin-bottom: $spacer; // Reduced margin
        font-weight: 500;
        font-size: $font-size-base * 1.3;
        color: $dark-color;
        padding-bottom: $spacer * 0.75;
        border-bottom: 1px solid $border-color;
        display: flex; // Center icon+text if icons added later
        align-items: center;
        justify-content: center;
        gap: $spacer * 0.5;
    }

    .sectionDescription {
        text-align: center;
        color: $text-muted;
        margin-bottom: $spacer * 1.5;
        font-size: $font-size-base * 0.95;
        line-height: 1.5;
    }

    // Specific visual identity for each section
    &.officialSection {
        border-top: 4px solid $primary-color; // Top border highlight
    }
    &.uploadSection {
        border-top: 4px solid $secondary-color; // Different color highlight
    }
}

// Styles for individual section
.individualSection {
    @extend .optionSection;
    border-top: 4px solid $primary-color;
    
    .sectionIcon {
        font-size: $font-size-base * 1.2;
        margin-right: $spacer * 0.5;
        color: $primary-color;
    }
}

// Styles for group section
.groupSection {
    @extend .optionSection;
    border-top: 4px solid $success-color;
    
    .sectionIcon {
        font-size: $font-size-base * 1.2;
        margin-right: $spacer * 0.5;
        color: $success-color;
    }
}

// Sub-section within main sections
.subSection {
    margin-top: $spacer * 1.5;
    padding: $spacer * 1.25;
    background-color: lighten($light-color, 2%);
    border-radius: $border-radius;
    border: 1px solid $border-color;
    
    h3 {
        font-size: $font-size-base * 1.1;
        margin-bottom: $spacer;
        color: $dark-color;
        font-weight: 500;
    }
}

// Divider styles
.divider {
    display: flex;
    align-items: center;
    text-align: center;
    font-weight: 500;
    color: $text-muted;
    margin: $spacer 0; // Mobile spacing

    &::before, &::after {
        content: '';
        flex-grow: 1;
        background: $border-color;
        height: 1px;
        margin: 0 $spacer;
    }

    @include media-breakpoint-up(md) {
        flex-direction: column;
        margin: 0; // Reset margin for grid layout
        width: 1px; // Vertical line width
        background-color: $border-color; // Make the divider itself the line
        min-height: 200px; // Give it some minimum height
        align-self: stretch; // Stretch to fill grid cell height
        justify-content: center;
        position: relative;

        &::before, &::after {
            content: none;
        }

        span {
            position: absolute;
            left: 50%;
            top: 50%;
            transform: translate(-50%, -50%);
            background-color: $body-bg;
            padding: $spacer * 0.25 $spacer * 0.5;
            font-size: $font-size-base * 0.9;
        }
    }
}

// Vertical divider specific styles
.dividerVertical {
    @extend .divider;
    
    @include media-breakpoint-up(md) {
        span { // Style the text within the vertical divider
            position: absolute;
            left: 50%;
            top: 50%;
            transform: translate(-50%, -50%);
            background-color: $body-bg; // Background to overlay the line
            padding: $spacer * 0.25 $spacer * 0.5;
            font-size: $font-size-base * 0.9;
            z-index: 1; // Ensure text is above the line
       }
    }
}

// Group action buttons
.groupButton {
    @include button-variant($success-color, $success-color);
    display: flex;
    align-items: center;
    justify-content: center;
    gap: $spacer * 0.5;
    padding: $spacer * 0.5 $spacer * 1.25;
    font-weight: 500;
    margin-bottom: $spacer;
    width: 100%;
    
    &:hover:not(:disabled) {
        transform: translateY(-2px);
        box-shadow: $box-shadow-sm;
    }
    
    &:disabled {
        opacity: 0.65;
        cursor: not-allowed;
    }
    
    i, svg {
        font-size: $font-size-base;
    }
}

// Container for group action buttons
.groupActions {
    display: flex;
    flex-direction: column;
    gap: $spacer * 1.5;
    margin-top: $spacer * 1.5;
    align-items: center;
    
    @include media-breakpoint-up(sm) {
        flex-direction: row;
        flex-wrap: wrap;
        
        .groupButton {
            flex: 1 0 calc(50% - #{$spacer});
            min-width: 140px;
        }
    }
}
.groupGraphicContainer {
    margin-top: $spacer; // Add significant space above the graphic
    text-align: center; // Center the image if it's inline-block or text
    padding: $spacer 0; // Add some vertical padding around it
    flex-grow: 1; // Allow this container to take remaining space
    display: flex; // Use flex to center content vertically/horizontally
    align-items: center;
    justify-content: center;
    // Optional: Add a subtle background or border if needed
    // background-color: lighten($light-color, 2%);
    // border-top: 1px dashed $border-color;
    // padding-top: $spacer * 2;
}
.groupGraphic {
    max-width: 100%; // Limit width relative to container
    height: auto; // Maintain aspect ratio
    //max-height: 350px; // Prevent graphic from becoming excessively large
    //opacity: 0.85; // Make it slightly subtle if desired
}

// Disabled section styling
.disabledSection {
    opacity: 0.65;
    filter: grayscale(50%);
    position: relative;
    pointer-events: none;

    &.individualSection { border-top-color: lighten($primary-color, 30%); }
    &.groupSection { border-top-color: lighten($success-color, 30%); }
    &.officialSection { border-top-color: lighten($primary-color, 30%); }
    &.uploadSection { border-top-color: lighten($secondary-color, 30%); }
}

.disabledOverlay {
    position: absolute;
    top: 0; left: 0; right: 0; bottom: 0;
    background-color: rgba($white-color, 0.3);
    z-index: 1;
    border-radius: inherit;
    pointer-events: none;
}

// Proceed section styles
.proceedSection {
    text-align: center;
    margin-top: $spacer * 3;
    padding: $spacer * 2;
    border-top: 1px solid $border-color;
    background-color: lighten($light-color, 3%);
    border-radius: 0 0 $border-radius-lg $border-radius-lg;
}

.proceedButton {
    @include button-variant($success-color, $success-color);
    padding: $spacer $spacer * 2.5;
    font-size: $font-size-base * 1.2;
    font-weight: 600;
    min-width: 250px;
    box-shadow: $box-shadow-sm;

    &:hover:not(:disabled) {
        box-shadow: $box-shadow-md;
        transform: translateY(-2px);
    }

    &:disabled {
        @include button-variant(lighten($success-color, 20%), lighten($success-color, 20%));
        cursor: not-allowed;
        opacity: 0.65;
        box-shadow: none;
        transform: none;
    }

    &.loginButton {
         @include button-variant($primary-color, $primary-color);
          &:disabled {
            @include button-variant(lighten($primary-color, 20%), lighten($primary-color, 20%));
          }
    }
}

// Style for info messages below proceed button
.proceedSection .infoMessage {
    margin-top: $spacer * 1.5;
    color: $text-muted;
    font-size: $font-size-base * 0.9;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: $spacer * 0.4;
    max-width: 500px;
    margin-left: auto;
    margin-right: auto;

    &.errorMessage {
        color: $danger-color;
        font-weight: 500;
        background-color: transparent;
        border: none;
    }
}

// Format example section
.formatExample {
    margin-top: $spacer * 3;
    padding: $spacer * 2;
    background-color: $dark-color;
    color: $light-color;
    border-radius: $border-radius;

    h3 {
        color: $white-color;
        text-align: center;
        margin-bottom: $spacer * 1.5;
        font-weight: 500;
    }

    p {
        color: lighten($light-color, 10%);
        text-align: center;
        margin-bottom: $spacer;
    }

    pre {
        background-color: lighten($dark-color, 7%);
        padding: $spacer * 1.5;
        border-radius: $border-radius-sm;
        overflow-x: auto;
        font-size: $font-size-base * 0.85;
        line-height: 1.5;
        box-shadow: inset 0 2px 4px rgba($black-color, 0.3);
        border: 1px solid lighten($dark-color, 15%);
    }

    code {
        font-family: SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;
        color: #f8f8f2;
    }
}
```

---

### pages\ExamSelectionPage\ExamSelectionPage.tsx

```typescript
// src/pages/ExamSelectionPage/ExamSelectionPage.tsx
import React, { useState, useEffect, useMemo, useCallback } from 'react';
import { useNavigate, useLocation, Link } from 'react-router-dom';
import styles from './ExamSelectionPage.module.scss';
import { FaInfoCircle, FaUsers, FaPlayCircle } from 'react-icons/fa';
import { useExam } from '../../contexts/ExamContext';
import { analytics } from '../../services/firebase';
import { logEvent } from 'firebase/analytics';
import { getAttemptsCount } from '../../services/firestoreService';
import { useAuth } from '../../contexts/AuthContext'; // Corrected path
import { toast } from 'react-toastify';
import Spinner from '../../components/Spinner/Spinner'; // Corrected path
// Corrected path

import { useExamConfig } from '../../hooks/useExamConfig'; // Corrected path
import OfficialExamSelector from '../../components/OfficialExamSelector/OfficialExamSelector'; // Corrected path
import CustomExamInput from '../../components/CustomExamInput/CustomExamInput'; // Corrected pat
import { ExamConfig } from '../../types';
import groupSessionGraphic from '../../assets/images/GroupSession.png'; // Corrected path

// Import useUserPerks from Examify's hooks
import { useUserPerks } from '../../hooks/useUserPerks'; // Corrected path
import ErrorMessage from '../../components/ErrorMessage/ErrorMessage'; 
const ExamSelectionPage: React.FC = () => {
    const [attemptCount, setAttemptCount] = useState<number | null>(null);
    const [isLoadingCount, setIsLoadingCount] = useState<boolean>(false); // Renamed for clarity
    const [countError, setCountError] = useState<string | null>(null);

    type SelectionMode = 'none' | 'official' | 'upload' | 'paste' | 'group';
    const [selectionMode, setSelectionMode] = useState<SelectionMode>('none');
    const [finalExamData, setFinalExamData] = useState<ExamConfig | File | string | null>(null);
    const [childValidationError, setChildValidationError] = useState<string | null>(null);

    const navigate = useNavigate();
    const location = useLocation();
    const message = location.state?.message;
    const { currentUser, openLoginModal } = useAuth();
    const { loadExam, examStatus, error: examError } = useExam();

    const { availableExams, isLoadingConfig, configError } = useExamConfig();
    // *** USE THE EXAMIFY useUserPerks HOOK ***
    const { limits: perkLimits, isLoadingPerks, currentTier, perksEnabledGlobally } = useUserPerks();

    useEffect(() => {
        const fetchCount = async () => {
            // *** MODIFIED: Check perksEnabledGlobally from useUserPerks ***
            if (currentUser && perksEnabledGlobally) {
                setIsLoadingCount(true);
                setCountError(null);
                try {
                    const count = await getAttemptsCount(currentUser.uid);
                    setAttemptCount(count);
                } catch (err: any) {
                    setCountError("Could not retrieve your attempt history count.");
                    setAttemptCount(null);
                } finally {
                    setIsLoadingCount(false);
                }
            } else {
                setAttemptCount(null);
                setIsLoadingCount(false);
                setCountError(null);
            }
        };
        // *** MODIFIED: Wait for isLoadingPerks to be false before fetching count ***
        if (!isLoadingPerks) {
            fetchCount();
        }
    }, [currentUser, isLoadingPerks, perksEnabledGlobally]); // Added perksEnabledGlobally

    // *** MODIFIED: Use perkLimits.examAttempts for attemptLimit ***
    const attemptLimit = perksEnabledGlobally && perkLimits.examAttempts !== null ? perkLimits.examAttempts : Infinity;

    const limitReached = useMemo(() => {
        if (!perksEnabledGlobally || isLoadingPerks || isLoadingCount || attemptCount === null) return false;
        return attemptLimit !== Infinity && attemptCount >= attemptLimit;
    }, [perksEnabledGlobally, isLoadingPerks, isLoadingCount, attemptCount, attemptLimit]);

    const canProceedIndividual = useMemo(() => { // Renamed from canProceed
        if (selectionMode === 'group') return false; // Explicitly false if group mode
        if (isLoadingPerks || isLoadingCount || limitReached || countError || isLoadingConfig || examStatus === 'loading' || examError || childValidationError) {
            return false;
        }
        return selectionMode !== 'none' && finalExamData !== null;
    }, [
        selectionMode, isLoadingPerks, isLoadingCount, limitReached, countError, isLoadingConfig,
        examStatus, examError, finalExamData, childValidationError
    ]);

    const handleProceedIndividual = useCallback(async () => {
        if (!currentUser) {
            openLoginModal("Please log in or sign up to start the practice session.");
            return;
        }
        // *** MODIFIED: Re-check isLoadingPerks, limitReached before proceeding ***
        if (isLoadingPerks || isLoadingCount || limitReached || countError) {
            if (limitReached) {
                toast.error(`Your attempt limit (${attemptLimit === Infinity ? 'Unlimited' : attemptLimit}) for the '${currentTier.name}' tier has been reached. Review your history or upgrade.`);
            } else {
                toast.warn("Still checking your limits or configuration. Please wait a moment.");
            }
            return;
        }
        if (examStatus === 'loading' || examError) {
             toast.error(examError || "Exam system is busy. Please try again shortly.");
             return;
        }

        let identifier: string | null = null;
        let type: 'official' | 'user' | null = null;
        let sourceData: File | string | null = null;
        let title: string | null = null;
        let pathForContext: string | null = null;

        if (selectionMode === 'official' && finalExamData && typeof finalExamData === 'object' && !(finalExamData instanceof File)) {
            const config = finalExamData as ExamConfig;
            identifier = config.id; type = 'official'; sourceData = config.path; title = config.title; pathForContext = config.path;
        } else if (selectionMode === 'upload' && finalExamData instanceof File) {
            const file = finalExamData;
            identifier = `user_upload_${file.name}_${Date.now()}`; type = 'user'; sourceData = file; title = file.name.replace('.json', ''); pathForContext = null;
        } else if (selectionMode === 'paste' && typeof finalExamData === 'string') {
            identifier = `user_paste_${Date.now()}`; type = 'user'; sourceData = finalExamData; title = "Pasted Custom Test"; pathForContext = null;
        }

        if (identifier && type && sourceData !== null && title) {
             logEvent(analytics, 'start_practice_session_intent', { exam_type: type, source_method: selectionMode, exam_identifier: identifier?.substring(0, 100) });
            try {
                await loadExam(identifier, type, sourceData, title, pathForContext);
                navigate(`/exam/${encodeURIComponent(identifier)}`);
            } catch (err) {
                 logEvent(analytics, 'load_exam_failed_on_proceed', { exam_type: type, source_method: selectionMode, exam_identifier: identifier?.substring(0, 100) });
                 toast.error(`Failed to load: ${examError || 'Please check selection and try again.'}`);
            }
        } else {
            toast.warn("Please ensure selection is complete and valid.");
            setSelectionMode('none'); setFinalExamData(null);
        }
        // eslint-disable-next-line
    }, [
        currentUser, isLoadingPerks, isLoadingCount, countError, attemptCount, limitReached, attemptLimit, currentTier.name, // Added attemptLimit, currentTier.name
        examStatus, examError, selectionMode, finalExamData, 
        loadExam, navigate, openLoginModal, perksEnabledGlobally
    ]);

    const handleStartGroupSession = () => {
        if (!currentUser) {
            openLoginModal("Please log in or sign up to start a group session."); return;
        }
        // *** MODIFIED: Check hostedSessions limit (isLoadingPerks handled implicitly in limitReachedGroup) ***
        const groupSessionLimitReached = perksEnabledGlobally && perkLimits.hostedSessions !== null && (hostedCount ?? 0) >= perkLimits.hostedSessions;
        if (groupSessionLimitReached) {
             toast.error(`Your limit for hosting group sessions (${perkLimits.hostedSessions}) on the '${currentTier.name}' tier has been reached.`); return;
        }
        logEvent(analytics, 'start_group_session_intent');
        navigate('/group-exam/setup');
    };
    
    const handleJoinGroupSession = () => {
        if (!currentUser) {
            openLoginModal("Please log in or sign up to join a group session."); return;
        }
        // *** MODIFIED: Joining uses individual attempt limit ***
        if (limitReached) {
            toast.error(`Your attempt limit (${attemptLimit === Infinity ? 'Unlimited' : attemptLimit}) for the '${currentTier.name}' tier has been reached.`); return;
        }
        logEvent(analytics, 'join_group_session_intent');
        navigate('/group-exam/join');
    };

    const handleOfficialExamSelected = useCallback((config: ExamConfig) => {
        setFinalExamData(config); setSelectionMode('official'); setChildValidationError(null);
    }, []);
    const handleCustomFileValidated = useCallback((file: File) => {
        setFinalExamData(file); setSelectionMode('upload'); setChildValidationError(null);
    }, []);
    const handleCustomPasteValidated = useCallback((jsonString: string) => {
        setFinalExamData(jsonString); setSelectionMode('paste'); setChildValidationError(null);
    }, []);
    const handleChildInputCleared = useCallback(() => {
        if (selectionMode !== 'group' && (selectionMode === 'official' || selectionMode === 'upload' || selectionMode === 'paste')) {
            setFinalExamData(null); setSelectionMode('none'); setChildValidationError(null);
        }
    }, [selectionMode]);
    const handleChildValidationError = useCallback((source: 'file' | 'paste', message: string) => {
        setChildValidationError(message); setFinalExamData(null);
        toast.error(`Validation Error (${source}): ${message}`);
    }, []);

    const renderStatusMessages = () => {
        // *** MODIFIED: Include isLoadingPerks in global loading checks ***
        if (isLoadingConfig || isLoadingPerks) return <ErrorMessage type="info" message={<Spinner text="Loading configurations..." />} textAlign="center" hideIcon />;
        if (currentUser && isLoadingCount && perksEnabledGlobally) return <ErrorMessage type="info" message={<Spinner text="Checking attempt history..." />} textAlign="center" hideIcon />;
        if (examStatus === 'loading') return <ErrorMessage type="info" message={<Spinner text="Preparing exam..." />} textAlign="center" hideIcon />;

        if (configError) return <ErrorMessage message={`Configuration Error: ${configError}`} textAlign="center" type="error" />;
        if (countError && perksEnabledGlobally) return <ErrorMessage message={`History Error: ${countError}`} textAlign="center" type="error" />;
        if (examError) return <ErrorMessage message={`Exam Initialization Error: ${examError}`} textAlign="center" type="error" />;
        if (childValidationError) return <ErrorMessage message={`Input Validation Error: ${childValidationError}`} textAlign="center" type="error" />;
        if (message) return <ErrorMessage type="info" message={message} textAlign="center" />;
        return null;
    };

    const [hostedCount] = useState<number | null>(null); // Placeholder, assuming actual count is fetched elsewhere or not critical for this page's group button enable/disable directly

    return (
        <div className={styles.selectionPage}>
            <h1>Select Your Practice Mode</h1>
            <p className={styles.subtitle}>Choose individual practice or start/join a group session.</p>

            <div className={styles.statusContainer}>
                {renderStatusMessages()}
            </div>

            <div className={`${styles.optionsContainer} ${styles.threeColumnGrid}`}>
                <section className={`${styles.optionSection} ${styles.individualSection} ${selectionMode === 'group' ? styles.disabledSection : ''}`}>
                     <h2><FaPlayCircle style={{ marginRight: '10px'}} /> Individual Practice</h2>
                     <p className={styles.sectionDescription}>Take official mocks or use your own JSON files for solo practice.</p>
                     
                     <div className={`${styles.subSection} ${styles.officialFlow} ${(selectionMode !== 'none' && selectionMode !== 'official') ? styles.disabledContent : ''}`}>
                        <h4>Official Mock Tests</h4>
                        <OfficialExamSelector
                            availableExams={availableExams}
                            isDisabled={(selectionMode !== 'none' && selectionMode !== 'official') || isLoadingConfig}
                            onExamSelected={handleOfficialExamSelected}
                            onSelectionCleared={handleChildInputCleared}
                            key={availableExams.length > 0 ? 'exams-loaded' : 'exams-loading'}
                        />
                     </div>
                     <div className={styles.dividerSmall}>OR</div>
                    <div className={`${styles.subSection} ${styles.customFlow} ${selectionMode === 'official' ? styles.disabledContent : ''}`}>
                        <h4>Custom Test (Upload or Paste)</h4>
                        <CustomExamInput
                            isDisabled={selectionMode === 'official' || isLoadingConfig}
                            onFileValidated={handleCustomFileValidated}
                            onPasteValidated={handleCustomPasteValidated}
                            onInputCleared={handleChildInputCleared}
                            onError={handleChildValidationError}
                            key={selectionMode}
                        />
                    </div>
                    <div className={styles.proceedSubSection}>
                        {!currentUser && (
                            <button onClick={() => openLoginModal("Please log in or sign up to continue")} className={`${styles.proceedButton} ${styles.loginButton}`}>
                                Login / Sign Up to Practice
                            </button>
                        )}
                        {currentUser && (
                            <button
                                onClick={handleProceedIndividual}
                                // *** MODIFIED: Include isLoadingPerks in disabled and title logic ***
                                disabled={!canProceedIndividual || examStatus === 'loading' || isLoadingCount || isLoadingPerks || selectionMode === 'group'}
                                className={styles.proceedButton}
                                title={
                                   isLoadingPerks || isLoadingCount ? "Checking limits..." :
                                   // *** MODIFIED: Use currentTier.name and attemptLimit ***
                                   limitReached ? `Your attempt limit (${attemptLimit === Infinity ? 'Unlimited' : attemptLimit}) for the '${currentTier.name}' tier has been reached. Review your history or upgrade for more attempts.` :
                                   selectionMode === 'group' ? 'Group session mode active. Use group buttons instead.' :
                                   examStatus === 'loading' ? 'Processing...' :
                                   !canProceedIndividual ? 'Please make a valid individual practice selection (Official, Upload, or Paste) and ensure it is error-free.' :
                                   'Start Individual Session'
                                }
                            >
                                {examStatus === 'loading' ? <><Spinner size="1em" /> Starting...</> : 'Start Individual Session'}
                            </button>
                        )}
                        {/* *** MODIFIED: Display limitReached message considering perks *** */}
                        {currentUser && perksEnabledGlobally && limitReached && !isLoadingPerks && !isLoadingCount &&
                           <ErrorMessage 
                               // *** MODIFIED: Use attemptLimit and currentTier.name ***
                               message={`Your attempt limit (${attemptLimit === Infinity ? 'Unlimited' : attemptLimit}) for the '${currentTier.name}' tier has been reached.`} 
                               type="warning"
                               actions={<Link to="/profile" style={{ textDecoration: 'underline', color: 'var(--warning-color, orange)' }}>Manage History</Link>}
                               textAlign="center"
                           />
                        }
                        {currentUser && !limitReached && !canProceedIndividual && selectionMode !== 'group' && !isLoadingConfig && !isLoadingCount && !isLoadingPerks && examStatus !== 'loading' && !renderStatusMessages() && (
                            <p className={styles.infoMessage}>
                                <FaInfoCircle /> Please make a valid selection (Official, Upload, or Paste).
                            </p>
                        )}
                    </div>
                    {selectionMode === 'group' && <div className={styles.disabledOverlay}></div>}
                </section>

                <div className={styles.dividerVertical}>OR</div>

                <section className={`${styles.optionSection} ${styles.groupSection} ${selectionMode !== 'none' && selectionMode !== 'group' ? styles.disabledSection : ''}`}>
                    <h2><FaUsers style={{ marginRight: '10px'}} /> Group Session</h2>
                    <p className={styles.sectionDescription}>Create a timed session for friends/students or join an existing one using a code.</p>
                    <div className={styles.groupActions}>
                        <button
                            onClick={handleStartGroupSession}
                            // *** MODIFIED: Include isLoadingPerks, currentTier.name, perkLimits.hostedSessions in disabled/title logic ***
                            disabled={(selectionMode !== 'none' && selectionMode !== 'group') || isLoadingPerks || isLoadingCount /* for hostedCount */}
                            className={styles.groupButton}
                            title={
                               isLoadingPerks || isLoadingCount ? "Loading perk info..." :
                               (selectionMode !== 'none' && selectionMode !== 'group') ? 'Individual practice mode selected. Clear selection to enable group actions.' :
                               (perksEnabledGlobally && perkLimits.hostedSessions !== null && (hostedCount ?? 0) >= perkLimits.hostedSessions) ? `Hosted session limit (${perkLimits.hostedSessions}) reached for your '${currentTier.name}' tier.` :
                               'Start a new timed session for others to join.'
                            }
                        >
                            Create New Group Session
                        </button>
                        <button
                            onClick={handleJoinGroupSession}
                             // *** MODIFIED: Include isLoadingPerks, limitReached, currentTier.name in disabled/title logic ***
                            disabled={(selectionMode !== 'none' && selectionMode !== 'group') || isLoadingPerks || isLoadingCount || limitReached}
                            className={styles.groupButton}
                            title={
                               isLoadingPerks || isLoadingCount ? "Loading perk info..." :
                               limitReached ? `Your individual attempt limit (${attemptLimit === Infinity ? 'Unlimited' : attemptLimit}) for the '${currentTier.name}' tier has been reached.` :
                               (selectionMode !== 'none' && selectionMode !== 'group') ? 'Individual practice mode selected. Clear selection to enable group actions.' :
                               'Join an existing session using its ID.'
                            }
                        >
                            Join Existing Session
                        </button>
                        <div className={styles.groupGraphicContainer}>
                        <img src={groupSessionGraphic} alt="Group collaboration" className={styles.groupGraphic} />
                    </div>
                    </div>
                    {(selectionMode !== 'none' && selectionMode !== 'group') && <div className={styles.disabledOverlay}></div>}
                </section>
            </div>

            <div id="json-format-example" className={styles.formatExample}>
                <h3>Example Custom JSON Format</h3>
                <p>Your file or pasted text should be an array `[]` containing question objects `{}`.</p>
                <pre><code className={styles.codeBlock}>{`[
  {
    "question_number": 1,                   // Required: Positive integer, unique & increasing
    "question_text": "What is 2 + 2?",      // Required: String (can include HTML)
    "options": {                            // Required: Object with key-value pairs
      "a": "3",
      "b": "4",                             // Option keys (a,b,c...) should be strings
      "c": "5",                             // Option values should be strings (can include HTML)
      "d": "6"
    },
    "correct_answer": "b",                  // Required: String, must match one of the option keys
    "subject": "Mathematics",               // Optional: String
    "topic": "Arithmetic",                  // Optional: String
    "explanation": "2 plus 2 equals 4.",    // Optional: String (can include HTML for formatting)
  },
  {
    "question_number": 2,
    "question_text": "What is the capital of France?",
    "options": { "a": "London", "b": "Paris", "c": "Berlin" },
    "correct_answer": "b",
    "subject": "Geography"                  // You can omit optional fields
  }
]`}</code></pre>
            </div>
        </div>
    );
};

export default ExamSelectionPage;
```

---

## pages\GroupExamDetailPage


### pages\GroupExamDetailPage\GroupExamDetailPage.module.scss

```scss
// src/pages/GroupExamDetailPage/GroupExamDetailPage.module.scss
@import '../../styles/variables';
@import '../../styles/mixins';

.detailPage {
    padding: map-get($spacers, 4) 0 map-get($spacers, 5);
    max-width: 1100px; // Wider for detail view
    margin: 0 auto;
}

.pageHeader {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: map-get($spacers, 4);
    padding-bottom: map-get($spacers, 3);
    border-bottom: 1px solid $border-color;

    h1 {
        font-size: $h3-font-size;
        color: $primary-color;
        margin: 0;
    }
}

.backLink {
    @include button-variant(transparent, $gray-400, $gray-700, $is-outline: true);
    font-size: $font-size-base * 0.9;
    padding: map-get($spacers, 1) map-get($spacers, 3);
    text-decoration: none;
    gap: map-get($spacers, 1);
    svg { font-size: $font-size-base * 0.9; }
}

.loadingContainer, .errorMessage { // Common style for full page states
    text-align: center;
    padding: map-get($spacers, 6) 0;
    font-size: $font-size-base * 1.1;
    color: $text-muted;
}
.errorMessage { color: $danger-color; font-weight: 500; }

.contentGrid {
    display: grid;
    grid-template-columns: 1fr; // Stack on mobile
    gap: map-get($spacers, 4);

    @include media-breakpoint-up(lg) {
        grid-template-columns: 1fr 1.2fr; // Example: Info | Participants+Actions
        // Or: grid-template-columns: 350px 1fr; // Fixed width for info
    }
}

.infoColumn, .participantsColumn {
    display: flex;
    flex-direction: column;
    gap: map-get($spacers, 4);
}

.detailSection {
    background-color: $component-bg;
    border: 1px solid $border-color;
    border-radius: $border-radius-lg;
    padding: map-get($spacers, 3) map-get($spacers, 4);
    box-shadow: $box-shadow-sm;

    h2 {
        font-size: $h5-font-size;
        color: $dark-color;
        margin-top: 0;
        margin-bottom: map-get($spacers, 3);
        font-weight: 600;
        padding-bottom: map-get($spacers, 2);
        border-bottom: 1px solid $gray-200;
        display: flex;
        align-items: center;
        gap: map-get($spacers, 2);
    }

    p {
        margin-bottom: map-get($spacers, 2);
        color: $text-color;
        font-size: $font-size-base * 0.95;
        line-height: 1.6;
        strong { font-weight: 600; color: $gray-700; }
        code {
            font-family: $font-family-monospace;
            background-color: $gray-100;
            padding: 2px 5px;
            border-radius: $border-radius-sm;
            font-size: $font-size-base * 0.9;
            color: $secondary-color;
        }
    }
}

.sessionIdCode {
    font-family: $font-family-monospace;
    font-size: $font-size-base * 1.1;
    font-weight: bold;
    background-color: $gray-100;
    padding: map-get($spacers, 1) map-get($spacers, 2);
    border-radius: $border-radius;
    border: 1px solid $gray-300;
    margin-right: map-get($spacers, 1);
    color: $primary-color;
}

.copyMiniButton { // For small copy buttons next to ID/Link
    @include button-text-variant($gray-500, $gray-100, $primary-color);
    padding: map-get($spacers, 1); // Small padding
    font-size: $font-size-base * 1.1; // Icon size
    line-height: 1;
    border: 1px solid $gray-300;
    border-radius: $border-radius-sm;
    margin-left: map-get($spacers, 1);

    &:hover { border-color: $primary-color; }
}

.shareLinkContainer { // Container for link input + copy button
    display: flex;
    align-items: center;
    gap: map-get($spacers, 1);
    margin-bottom: map-get($spacers, 2);
}
.shareLinkInput {
    flex-grow: 1;
    padding: map-get($spacers, 2);
    border: 1px solid $border-color;
    border-radius: $border-radius;
    font-size: $font-size-base * 0.9;
    background-color: $white-color;
    color: $link-color; // Make it look like a link
}

.webShareButton {
    @include button-variant($info-color);
    width: 100%;
    padding: map-get($spacers, 2) map-get($spacers, 3);
    gap: map-get($spacers, 2);
    font-size: $font-size-base;
}

.sessionStatusBadge { // Refined status badge
    font-weight: bold;
    padding: 3px map-get($spacers, 2);
    border-radius: $border-radius-pill;
    font-size: $font-size-base * 0.8;
    text-transform: uppercase;
    border: 1px solid;
    // Colors set by specific status classes
    &.statusPending { background-color: lighten($warning-color, 40%); color: darken($warning-color, 20%); border-color: lighten($warning-color, 20%); }
    &.statusActive { background-color: lighten($info-color, 40%); color: darken($info-color, 20%); border-color: lighten($info-color, 20%); }
    &.statusClosed { background-color: lighten($secondary-color, 40%); color: darken($secondary-color, 20%); border-color: lighten($secondary-color, 20%); }
}

.customJsonInfo { // Container for the new custom JSON section
    margin-top: map-get($spacers, 2);
    padding-top: map-get($spacers, 2);
    border-top: 1px dotted $gray-200;

    p {
        font-size: $font-size-base;
        color: $text-muted;
        margin-bottom: map-get($spacers, 1); // Tighter margin for info line
        strong { color: $dark-color; }
    }
}

.customJsonActions { // Container for Download/Copy buttons
    display: flex;
    gap: map-get($spacers, 2);
    margin-top: map-get($spacers, 1);
}

.jsonActionButton { // Style for Download/Copy JSON buttons
    @include button-variant(transparent, $secondary-color, $secondary-color, $is-outline: true);
    font-size: $font-size-base * 0.9;
    padding: map-get($spacers, 1) map-get($spacers, 2);
    gap: map-get($spacers, 1);

    svg { font-size: $font-size-base * 0.95; }

    &:hover:not(:disabled) {
        background-color: lighten($secondary-color, 45%);
    }
}

.actionsSection { // Container for Close/Delete/CSV buttons
    // No special styling if it inherits from .detailSection
    // Can add specific alignment or borders if needed.
    border-top: 3px solid $primary-color; // Accent top border
}

.actionsGrid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
    gap: map-get($spacers, 3);
}

.actionButton { // Common style for action buttons (Close, Delete, Download CSV)
    padding: map-get($spacers, 2) map-get($spacers, 3);
    font-size: $font-size-base;
    font-weight: 500;
    gap: map-get($spacers, 2);

    &.closeButton { @include button-variant($warning-color, $warning-color, $dark-color); }
    &.downloadButton { @include button-variant($success-color); 
        &.downloadLinkReady { text-decoration: none; color: $white-color; &:hover { color: $white-color;}}
    }
    &.deleteButton { @include button-variant($danger-color); }

    &:disabled { opacity: 0.6; cursor: not-allowed; }
}

.perkNotice { // For unavailable premium features
    font-size: $font-size-base * 0.8;
    color: $text-muted;
    margin-left: map-get($spacers, 1);
    font-style: italic;
}
.enabledText, .disabledText {
    font-weight: 500;
    display: inline-flex;
    align-items: center;
    gap: map-get($spacers, 1);
}
.enabledText { color: $success-color; }
.disabledText { color: $text-muted; }

.geoDetails {
    font-size: $font-size-base * 0.85;
    color: $gray-600;
    background-color: $gray-50;
    padding: map-get($spacers, 1) map-get($spacers, 2);
    border-radius: $border-radius-sm;
    margin-top: map-get($spacers, 1);
    border: 1px solid $gray-200;
}
```

---

### pages\GroupExamDetailPage\GroupExamDetailPage.tsx

```typescript
// src/pages/GroupExamDetailPage/GroupExamDetailPage.tsx
import React, { useState, useEffect, useMemo, useCallback } from 'react';
import { useParams, Link, useNavigate } from 'react-router-dom';
import styles from './GroupExamDetailPage.module.scss';
import { useAuth } from '../../contexts/AuthContext';
import { 
    getGroupExam, 
    updateGroupExamStatus, 
    deleteGroupExamDocument,
    getGroupExamParticipants,
    getParticipantMonitoringEvents,
} from '../../services/firestoreService';
import { GroupExam, MonitoringEvent, ParticipantData} from '../../types';
import { formatTimestamp, formatDuration } from '../../utils/formatters';
import { 
    FaArrowLeft, FaClipboard, FaClipboardCheck, FaShareAlt, FaListUl, 
FaEye, FaBan, FaTrashAlt, FaDownload, FaUserSecret, 
    FaMapMarkerAlt, 
    FaInfoCircle, 
    FaFileCode
} from 'react-icons/fa';
import { toast } from 'react-toastify';
import ConfirmationModal from '../../components/Modal/ConfirmationModal';
import { CSVLink } from 'react-csv';
import SessionMonitor from '../../components/SessionMonitor/SessionMonitor';
import Spinner from '../../components/Spinner/Spinner';
import { analytics } from '../../services/firebase';
import { logEvent } from 'firebase/analytics';
import { useUserPerks } from '../../hooks/useUserPerks';
import { Timestamp } from 'firebase/firestore'; // Import Timestamp


const GroupExamDetailPage: React.FC = () => {
    const { sessionId } = useParams<{ sessionId: string }>();
    const { currentUser, isLoading: isAuthLoading } = useAuth();
    const { features: perkFeatures, isLoadingPerks, currentTier } = useUserPerks();
    const navigate = useNavigate();

    const [sessionDetails, setSessionDetails] = useState<GroupExam | null>(null);
    
    const [isLoading, setIsLoading] = useState(true);
    const [error, setError] = useState<string | null>(null);
    const [actionInProgressId, setActionInProgressId] = useState<string | null>(null);

    const [showConfirmModal, setShowConfirmModal] = useState(false);
    const [modalConfig, setModalConfig] = useState<{
        title: string;
        message: React.ReactNode; 
        confirmText?: string;
        confirmButtonVariant?: 'primary' | 'danger' | 'success' | 'warning';
        onConfirm: () => void;
        isDanger?: boolean;
    } | null>(null);

    const [participantDataForCsv, setParticipantDataForCsv] = useState<{
        data: (ParticipantData & { id: string })[];
        monitoringEvents: { [participantId: string]: MonitoringEvent[] };
        isLoading: boolean;
    }>({ data: [], monitoringEvents: {}, isLoading: false });
    const [csvDownloadReady, setCsvDownloadReady] = useState(false);
    const [isPreparingCsv, setIsPreparingCsv] = useState(false);

    const [copiedId, setCopiedId] = useState(false);
    const [copiedLink, setCopiedLink] = useState(false);
    const [copiedJson, setCopiedJson] = useState(false);

    useEffect(() => {
        let isMounted = true;
        const fetchDetails = async () => {
            if (!sessionId || !currentUser) {
                if (isMounted) { setError("Session ID missing or user not authenticated."); setIsLoading(false); }
                return;
            }
            setIsLoading(true); setError(null);
            try {
                const session = await getGroupExam(sessionId);
                if (!isMounted) return;
                if (!session) throw new Error("Group session not found or you do not have access.");
                if (session.hostUid !== currentUser.uid) throw new Error("You are not the host of this session.");
                
                setSessionDetails(session);
                document.title = `Details: ${session.sessionName} - Examify`;

            } catch (err: any) {
                if (isMounted) {
                    setError(err.message || "Failed to load session details.");
                    toast.error(err.message || "Failed to load session details.");
                }
            } finally {
                if (isMounted) setIsLoading(false);
            }
        };

        if (!isAuthLoading && currentUser) {
            fetchDetails();
        } else if (!isAuthLoading && !currentUser) {
            navigate('/select-exam', { replace: true, state: { message: "Please log in." } });
        }
        return () => { isMounted = false; };
    }, [sessionId, currentUser, isAuthLoading, navigate]);

    const joinUrl = useMemo(() => {
        if (!sessionId) return null;
        const baseUrl = window.location.origin;
        return `${baseUrl}/group-exam/join?sessionId=${sessionId}`;
    }, [sessionId]);

    const shareText = useMemo(() => {
        return `Join my Examify group session "${sessionDetails?.sessionName || 'Unnamed Session'}"! Session ID: ${sessionId}`;
    }, [sessionDetails?.sessionName, sessionId]);

    const shareData = useMemo(() => ({
        title: `Join Examify Session: ${sessionDetails?.sessionName || 'Unnamed Session'}`,
        text: shareText,
        url: joinUrl || `https://examify.web.app`
    }), [sessionDetails?.sessionName, shareText, joinUrl]);

    const handleCopyToClipboard = (textToCopy: string | null, type: 'id' | 'link' | 'json') => {
        if (!textToCopy) {
            toast.error("Nothing to copy.");
            return;
        }
        navigator.clipboard.writeText(textToCopy)
            .then(() => {
                if (type === 'id') setCopiedId(true);
                else if (type === 'link') setCopiedLink(true);
                else if (type === 'json') setCopiedJson(true);

                toast.success(`${type === 'id' ? 'Session ID' : type === 'link' ? 'Join Link' : 'JSON Content'} copied!`);
                
                setTimeout(() => {
                    if (type === 'id') setCopiedId(false);
                    else if (type === 'link') setCopiedLink(false);
                    else if (type === 'json') setCopiedJson(false);
                }, 2500);
            })
            .catch(() => toast.error("Could not copy."));
    };

    const handleWebShare = async () => {
        if (navigator.share && joinUrl) {
            try {
                await navigator.share(shareData);
                toast.info("Shared successfully!");
            } catch (err: any) {
                if (err.name !== 'AbortError') toast.error(`Could not share: ${err.message}`);
            }
        } else {
            toast.warn("Web Share not supported. Link copied instead!");
            handleCopyToClipboard(joinUrl, 'link');
        }
    };
    
    const handleCloseSession = async () => {
        if (!sessionDetails || !sessionDetails.id || actionInProgressId === sessionDetails.id) return;
        setActionInProgressId(sessionDetails.id);
        setModalConfig({
            title: "Confirm Close Session",
            message: (
                <>
                    <p>Are you sure you want to close session <strong>"{sessionDetails.sessionName}"</strong>?</p>
                    <p>This will prevent new participants from joining. Ongoing attempts might finish, but results/review visibility could be affected based on settings.</p>
                </>
            ),
            confirmText: "Close Session",
            confirmButtonVariant: "warning",
            onConfirm: async () => {
                setShowConfirmModal(false);
                if (!sessionDetails?.id) return; // Guard again
                try {
                    await updateGroupExamStatus(sessionDetails.id, 'closed');
                    toast.success(`Session "${sessionDetails.sessionName}" closed.`);
                    setSessionDetails(prev => prev ? { ...prev, status: 'closed' } : null);
                    logEvent(analytics, 'group_session_closed_by_host', { session_id: sessionDetails.id });
                } catch (err: any) {
                    toast.error(`Failed to close session: ${err.message}`);
                } finally {
                    setActionInProgressId(null);
                }
            }
        });
        setShowConfirmModal(true);
    };

    const handleDeleteSession = async () => {
        if (!sessionDetails || !sessionDetails.id || actionInProgressId === sessionDetails.id || isPreparingCsv) return;
        setActionInProgressId(sessionDetails.id);
        setModalConfig({
            title: "Confirm Delete Session Configuration",
            message: (
                <>
                  <p>Delete session <strong>"{sessionDetails.sessionName}"</strong> (ID: {sessionDetails.id})?</p>
                  <p style={{color: 'var(--danger-color)', fontWeight: 'bold'}}>This action is IRREVERSIBLE.</p>
                  <p>It will remove the session configuration from your dashboard and prevent anyone from joining or accessing it further via its ID. Participant attempt results already saved to THEIR history will remain unless THEY delete them later.</p>
                </>
            ),
            confirmText: "Delete Permanently",
            confirmButtonVariant: "danger",
            isDanger: true,
            onConfirm: async () => {
                setShowConfirmModal(false);
                if (!sessionDetails?.id) return; // Guard again
                try {
                    await deleteGroupExamDocument(sessionDetails.id);
                    toast.success(`Session "${sessionDetails.sessionName}" configuration deleted.`);
                    logEvent(analytics, 'group_session_deleted_by_host', { session_id: sessionDetails.id });
                    navigate('/group-exam/dashboard', { replace: true }); 
                } catch (err: any) {
                    toast.error(`Failed to delete session: ${err.message}`);
                } finally {
                    setActionInProgressId(null);
                }
            }
        });
        setShowConfirmModal(true);
    };

    const closeConfirmationModal = () => {
        setShowConfirmModal(false);
        setActionInProgressId(null);
        setModalConfig(null);
    };
    
    const prepareCsvData = useCallback((
        participants: (ParticipantData & { id: string })[],
        _sessionDetails: GroupExam | null, // sessionDetails is now nullable
        allMonitoringEvents: { [participantId: string]: MonitoringEvent[] }
    ): Array<object> => {
        if (!participants || !_sessionDetails) return []; // Added null check for _sessionDetails
        const completed = participants.filter(p =>
            p.status === 'completed' && typeof p.score === 'number' && typeof p.maxScore === 'number'
        );
        if (completed.length === 0) return [];
    
        const participantsWithTimeTaken = completed.map(p => {
            const startTimeJS = p.startedAt instanceof Timestamp ? p.startedAt.toDate() : p.startedAt;
            const endTimeJS = p.completionTimestamp instanceof Timestamp ? p.completionTimestamp.toDate() : p.completionTimestamp;
            const timeTaken = (!startTimeJS || !endTimeJS) ? 0 : Math.floor((endTimeJS.getTime() - startTimeJS.getTime()) / 1000);
            return { ...p, timeTaken };
        });
            
        participantsWithTimeTaken.sort((a, b) => {
            if (a.score !== b.score) return (b.score || 0) - (a.score || 0);
            return (a.timeTaken || Infinity) - (b.timeTaken || Infinity);
        });
    
        let currentRank = 0;
        let lastScore = -Infinity;
        let participantsAtRank = 0;
        const rankedData = participantsWithTimeTaken.map((p) => {
            if (p.score !== lastScore) {
                currentRank += (participantsAtRank + 1);
                lastScore = p.score!;
                participantsAtRank = 0;
            } else {
                participantsAtRank++;
            }
            return { ...p, rank: currentRank };
        });
    
        return rankedData.map(p => {
            const participantEvents = allMonitoringEvents[p.id] || [];
            const focusLossCount = participantEvents.filter(e => 
                e.type === 'focus_lost' || e.type === 'focus_lost_on_unmount' || e.type === 'navigation_away'
            ).length;
            let totalFocusLostMs = 0;
            participantEvents.forEach(event => {
                if ((event.type === 'focus_regained' || event.type === 'focus_lost_on_unmount') && typeof event.durationMs === 'number') {
                    totalFocusLostMs += event.durationMs;
                }
            });
            const totalFocusLostFormatted = formatDuration(Math.round(totalFocusLostMs / 1000));
            const copyAttemptCount = participantEvents.filter(e => e.type === 'copy_attempt_blocked').length;
            const pasteAttemptCount = participantEvents.filter(e => e.type === 'paste_attempt_blocked').length;
            const restrictedKeyCount = participantEvents.filter(e => e.type === 'restricted_key_logged').length;
    
            const percentage = (p.maxScore && p.score !== undefined && p.maxScore > 0) ? ((p.score / p.maxScore) * 100).toFixed(2) : 'N/A';
    
            const joinedAtJS = p.joinedAt instanceof Timestamp ? p.joinedAt.toDate() : p.joinedAt;
            const startedAtJS = p.startedAt instanceof Timestamp ? p.startedAt.toDate() : p.startedAt;
            const completedAtJS = p.completionTimestamp instanceof Timestamp ? p.completionTimestamp.toDate() : p.completionTimestamp;

            return {
                rank: p.rank,
                displayName: p.displayName || `User...${p.id.substring(p.id.length-6)}`,
                participantId: p.id,
                status: p.status,
                score: p.score ?? '',
                maxScore: p.maxScore ?? '',
                percentage: percentage,
                timeTakenFormatted: formatDuration(p.timeTaken),
                focusLossCount: focusLossCount,
                totalFocusLostFormatted: totalFocusLostFormatted,
                copyAttemptCount: copyAttemptCount,
                pasteAttemptCount: pasteAttemptCount,
                restrictedKeyCount: restrictedKeyCount,
                joinedAtFormatted: formatTimestamp(joinedAtJS),
                startedAtFormatted: formatTimestamp(startedAtJS),
                completedAtFormatted: formatTimestamp(completedAtJS),
            };
        });
    }, []);

    const triggerCsvDataFetch = useCallback(async () => {
        if (!sessionDetails || !sessionDetails.id) return;
        setIsPreparingCsv(true);
        setCsvDownloadReady(false);
        setError(null);
        try {
            const participants = await getGroupExamParticipants(sessionDetails.id);
            let eventsForCsv: { [participantId: string]: MonitoringEvent[] } = {};

            if (sessionDetails.monitoringEnabled) {
                const eventPromises = participants.map(p => 
                    getParticipantMonitoringEvents(sessionDetails.id, p.id)
                        .then(events => ({ pid: p.id, events }))
                        .catch(() => ({ pid: p.id, events: [] })) 
                );
                const results = await Promise.all(eventPromises);
                results.forEach(r => { eventsForCsv[r.pid] = r.events; });
            }
            
            setParticipantDataForCsv({ data: participants, monitoringEvents: eventsForCsv, isLoading: false });
            setCsvDownloadReady(true);
            toast.info(`Participant data for "${sessionDetails.sessionName}" is ready. Click Download.`);
            logEvent(analytics, 'group_session_csv_data_prepared', { session_id: sessionDetails.id, participant_count: participants.length });
        } catch (err: any) {
            toast.error(`Failed to prepare data for CSV: ${err.message}`); 
            setError(`Failed to get data for CSV: ${err.message}`);
        } finally {
            setIsPreparingCsv(false);
        }
    }, [sessionDetails]);

    const csvHeaders = useMemo(() => [
        // ... (CSV headers remain the same)
        { label: "Rank", key: "rank" },
        { label: "Display Name", key: "displayName" },
        { label: "Participant ID", key: "participantId" },
        { label: "Status", key: "status" },
        { label: "Score", key: "score" },
        { label: "Max Score", key: "maxScore" },
        { label: "Percentage (%)", key: "percentage" },
        { label: "Attempt Time", key: "timeTakenFormatted" },
        { label: "Focus Loss Count", key: "focusLossCount" }, 
        { label: "Total Focus Lost Time", key: "totalFocusLostFormatted" },
        { label: "Copy Attempt Count", key: "copyAttemptCount" },
        { label: "Paste Attempt Count", key: "pasteAttemptCount" },
        { label: "Restricted Key Count", key: "restrictedKeyCount" },
        { label: "Joined At", key: "joinedAtFormatted" },
        { label: "Started At", key: "startedAtFormatted" },
        { label: "Completed At", key: "completedAtFormatted" },
    ], []);
    
    const formattedCsvData = useMemo(() => {
        if (!csvDownloadReady || !sessionDetails || participantDataForCsv.data.length === 0) return [];
        return prepareCsvData(participantDataForCsv.data, sessionDetails, participantDataForCsv.monitoringEvents);
    }, [csvDownloadReady, participantDataForCsv, sessionDetails, prepareCsvData]);


    if (isLoading || isAuthLoading || isLoadingPerks) {
        return <div className={styles.loadingContainer}><Spinner text="Loading session details..." size={24} /></div>;
    }
    if (error) {
        return (
            <div className={styles.detailPage}>
                <div className={styles.pageHeader}>
                    <h1>Error</h1>
                    <Link to="/group-exam/dashboard" className={styles.backLink}><FaArrowLeft /> Back to Dashboard</Link>
                </div>
                <p className={styles.errorMessage}>{error}</p>
            </div>
        );
    }
    if (!sessionDetails) {
        return (
            <div className={styles.detailPage}>
                 <div className={styles.pageHeader}>
                    <h1>Session Not Found</h1>
                    <Link to="/group-exam/dashboard" className={styles.backLink}><FaArrowLeft /> Back to Dashboard</Link>
                </div>
                <p className={styles.errorMessage}>The requested session could not be found or you may not have permission to view it.</p>
            </div>
        );
    }
    
    const { 
        sessionName, timeLimitMinutes, createdAt, status, examSourceType,
        startTime, endTime, resultVisibility, monitoringEnabled, geoRestriction,
        marksPerCorrect, negativeMarkingEnabled, negativeMarksPerIncorrect,
        examSourceId, examSourcePath, questionJsonString
    } = sessionDetails;

    const startTimeJS = startTime instanceof Timestamp ? startTime.toDate() : startTime;
    const endTimeJS = endTime instanceof Timestamp ? endTime.toDate() : endTime;
    const createdAtJS = createdAt instanceof Timestamp ? createdAt.toDate() : createdAt;

    const handleDownloadJson = () => {
            if (examSourceType === 'custom_json' && questionJsonString) {
                const blob = new Blob([questionJsonString], { type: 'application/json' });
                const url = URL.createObjectURL(blob);
                const a = document.createElement('a');
                a.href = url;
                a.download = `${sessionName.replace(/\s+/g, '_') || 'custom_exam'}_questions.json`;
                document.body.appendChild(a);
                a.click();
                document.body.removeChild(a);
                URL.revokeObjectURL(url);
                toast.success("Custom JSON downloaded!");
                logEvent(analytics, 'group_session_custom_json_downloaded', {session_id: sessionId});
            } else {
                toast.error("No custom JSON available to download for this session.");
            }
        };

        const renderQuestionSourceDetails = () => {
            if (examSourceType === 'official') {
                return (
                    <p>
                        <strong>Source:</strong> Official Exam
                        {examSourceId && <span> (ID: <code className={styles.codeInline}>{examSourceId}</code>)</span>}
                        {examSourcePath && <span> Path: <code className={styles.codeInline}>{examSourcePath}</code></span>}
                    </p>
                );
            } else if (examSourceType === 'custom_json') {
                let questionCount = 0;
                if (questionJsonString) {
                    try {
                        const parsed = JSON.parse(questionJsonString);
                        if (Array.isArray(parsed)) questionCount = parsed.length;
                    } catch { /* ignore parse error for count */ }
                }
                return (
                    <div className={styles.customJsonInfo}>
                        <p>
                            <strong>Source:</strong> Custom JSON 
                            {questionCount > 0 && ` (${questionCount} questions)`}
                        </p>
                        <div className={styles.customJsonActions}>
                            <button 
                                onClick={handleDownloadJson} 
                                disabled={!questionJsonString}
                                className={styles.jsonActionButton}
                                title="Download the custom JSON file for this session"
                            >
                                <FaDownload /> Download JSON
                            </button>
                            <button 
                                onClick={() => handleCopyToClipboard(questionJsonString || null, 'json')}
                                disabled={!questionJsonString || copiedJson}
                                className={styles.jsonActionButton}
                                title="Copy JSON content to clipboard"
                            >
                                {copiedJson ? <FaClipboardCheck /> : <FaClipboard />} Copy JSON
                            </button>
                        </div>
                    </div>
                );
            }
            return <p><strong>Source:</strong> Unknown</p>;
        };


    return (
        <div className={styles.detailPage}>
            <div className={styles.pageHeader}>
                <h1>Session: {sessionName}</h1>
                <Link to="/group-exam/dashboard" className={styles.backLink}><FaArrowLeft /> Back to Dashboard</Link>
            </div>

            <div className={styles.contentGrid}>
                <div className={styles.infoColumn}>
                    <section className={styles.detailSection}>
                        <h2><FaInfoCircle /> Session Information</h2>
                        <p><strong>ID:</strong> <code className={styles.sessionIdCode}>{sessionId}</code> 
                            <button onClick={() => handleCopyToClipboard(sessionId || null, 'id')} className={styles.copyMiniButton} title="Copy ID">
                                {copiedId ? <FaClipboardCheck /> : <FaClipboard />}
                            </button>
                        </p>
                        <p><strong>Status:</strong> <span className={`${styles.sessionStatusBadge} ${styles[`status${status.charAt(0).toUpperCase() + status.slice(1)}`]}`}>{status}</span></p>
                        <p><strong>Created:</strong> {formatTimestamp(createdAtJS)}</p>
                        <p><strong>Time Limit:</strong> {timeLimitMinutes ? `${timeLimitMinutes} minutes` : 'No time limit'}</p>
                        <p><strong>Scheduled Start:</strong> {startTime ? formatTimestamp(startTimeJS) : 'Anytime'}</p>
                        <p><strong>Entry Deadline:</strong> {endTime ? formatTimestamp(endTimeJS) : 'No deadline'}</p>
                        <p><strong>Result Visibility:</strong> {resultVisibility}</p>
                    </section>

                    <section className={styles.detailSection}>
                        <h2><FaShareAlt /> Share Session</h2>
                        <p><strong>Join Link:</strong></p>
                        <div className={styles.shareLinkContainer}>
                            <input type="text" value={joinUrl || ''} readOnly className={styles.shareLinkInput} />
                            <button onClick={() => handleCopyToClipboard(joinUrl, 'link')} className={styles.copyMiniButton} title="Copy Link">
                                {copiedLink ? <FaClipboardCheck /> : <FaClipboard />}
                            </button>
                        </div>
                        {typeof navigator.share === 'function' && (
                            <button onClick={handleWebShare} disabled={!joinUrl} className={styles.webShareButton}>
                                <FaShareAlt /> Share via...
                            </button>
                        )}
                    </section>
                    
                    <section className={styles.detailSection}>
                    <h2><FaFileCode /> Question Source</h2>
                        {renderQuestionSourceDetails()}
                    </section>
                </div>

                <div className={styles.participantsColumn}>
                     <section className={styles.detailSection}>
                        <h2><FaUserSecret /> Integrity Settings</h2>
                        <p><strong>Basic Monitoring:</strong> {monitoringEnabled ? 
                            <span className={styles.enabledText}><FaEye /> Enabled</span> : 
                            <span className={styles.disabledText}><FaEye style={{opacity:0.5}}/> Disabled</span>}
                            {!perkFeatures.canEnableExamMonitoring && !isLoadingPerks && 
                             <span className={styles.perkNotice}>(Requires {currentTier?.name === 'Free' ? 'Pro' : 'higher'} tier)</span>}
                        </p>
                        <p><strong>Geolocation Lock:</strong> {geoRestriction ? 
                            <span className={styles.enabledText}><FaMapMarkerAlt /> Enabled</span> : 
                            <span className={styles.disabledText}><FaMapMarkerAlt style={{opacity:0.5}}/> Disabled</span>}
                            {!perkFeatures.canEnableAdvancedMonitoring && !isLoadingPerks &&
                             <span className={styles.perkNotice}>(Requires Elite tier)</span>}
                        </p>
                        {geoRestriction && (
                            <div className={styles.geoDetails}>
                                Lat: {geoRestriction.latitude.toFixed(4)}, Lng: {geoRestriction.longitude.toFixed(4)}, Radius: {geoRestriction.radiusMeters}m
                            </div>
                        )}
                         <p><strong>Marking:</strong> Correct: +{marksPerCorrect ?? 'N/A'}, Incorrect: {negativeMarkingEnabled ? `-${negativeMarksPerIncorrect ?? 'N/A'}` : '0'}</p>
                    </section>
                    <section className={styles.detailSection}>
                        <h2><FaListUl /> Participants & Status</h2>
                        <SessionMonitor sessionId={sessionId!} sessionDetails={sessionDetails} showMonitoringDetails={true} />
                    </section>
                </div>
            </div>

            <section className={`${styles.detailSection} ${styles.actionsSection}`}>
                <h2>Session Actions</h2>
                <div className={styles.actionsGrid}>
                    <button
                        onClick={handleCloseSession}
                        disabled={actionInProgressId === sessionId || status === 'closed'}
                        className={`${styles.actionButton} ${styles.closeButton}`}
                    >
                        <FaBan /> {status === 'closed' ? 'Session Is Closed' : 'Close Session Now'}
                    </button>
                    
                    {isLoadingPerks ? <Spinner size="0.9em" text="Verifying perks..." /> : (
                        perkFeatures.canDownloadParticipantCsv ? (
                            (!csvDownloadReady || isPreparingCsv || participantDataForCsv.data.length === 0) ? (
                                <button
                                    onClick={triggerCsvDataFetch}
                                    className={`${styles.actionButton} ${styles.downloadButton}`}
                                    disabled={isPreparingCsv || isLoadingPerks || actionInProgressId === sessionId} 
                                    title="Prepare result data for CSV download"
                                >
                                    {isPreparingCsv ? 
                                        <Spinner size="0.9em" text="Preparing CSV..." /> : 
                                        <><FaDownload /> Prepare Results CSV</>
                                    }
                                </button>
                            ) : (
                                <CSVLink
                                    data={formattedCsvData}
                                    headers={csvHeaders}
                                    filename={`session_${sessionName.replace(/\s+/g, '_')}_results.csv`}
                                    className={`${styles.actionButton} ${styles.downloadButton} ${styles.downloadLinkReady}`}
                                    target="_blank"
                                    onClick={() => {
                                        toast.info(`Downloading CSV for ${sessionName}...`);
                                        setCsvDownloadReady(false); 
                                        logEvent(analytics, 'group_session_csv_downloaded', {session_id: sessionId});
                                    }}
                                >
                                    <FaDownload /> Download Prepared CSV
                                </CSVLink>
                            )
                        ) : (
                             <button
                                className={`${styles.actionButton} ${styles.downloadButton}`}
                                disabled
                                title={`CSV Download is available from Pro tier. (Your tier: ${currentTier?.name})`}
                            >
                                <FaDownload /> Prepare Results CSV (Pro+)
                            </button>
                        )
                    )}

                    <button
                        onClick={handleDeleteSession}
                        disabled={actionInProgressId === sessionId || isPreparingCsv}
                        className={`${styles.actionButton} ${styles.deleteButton}`}
                    >
                        <FaTrashAlt /> Delete Session Config
                    </button>
                </div>
            </section>

            {modalConfig && (
                <ConfirmationModal
                    isOpen={showConfirmModal}
                    title={modalConfig.title}
                    customContent={modalConfig.message} // Use customContent for ReactNode
                    onConfirm={modalConfig.onConfirm}
                    onCancel={closeConfirmationModal}
                    confirmText={modalConfig.confirmText}
                    confirmButtonVariant={modalConfig.confirmButtonVariant || (modalConfig.isDanger ? 'danger' : 'primary')}
                    size="md"
                />
            )}
        </div>
    );
};

export default GroupExamDetailPage;
```

---

## pages\GroupExamSessionPage


### pages\GroupExamSessionPage\GroupExamSessionPage.module.scss

```scss
// src/pages/GroupExamSessionPage/GroupExamSessionPage.module.scss
@import '../../styles/variables';
@import '../../styles/mixins';

// Container for loading/error messages before exam UI shows
.statusContainer, .statusContainerError {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    min-height: 60vh; // Take up significant screen space
    padding: $spacer * 2;
    text-align: center;
    gap: $spacer * 1.5;

    p {
        font-size: $font-size-base * 1.1;
        color: $text-muted;
    }
}

.statusContainerError {
     background-color: lighten($danger-color, 50%);
     border: 1px solid lighten($danger-color, 40%);
     border-radius: $border-radius-lg;
     max-width: 600px;
     margin: $spacer * 3 auto; // Center container
     padding: $spacer * 2.5;

     h2 {
        color: $danger-color;
        margin-top: 0;
        margin-bottom: $spacer * 0.5;
     }
      p {
         color: darken($danger-color, 10%);
     }
}

// Reuse action button style if needed
.actionButton {
     @include button-variant($secondary-color, $secondary-color);
     padding: $spacer * 0.7 $spacer * 1.5;
}


// Reusable spinner icon (if not global)
@keyframes spin {
  0% { transform: rotate(0deg); }
  100% { transform: rotate(360deg); }
}
.spin-icon {
  display: block; // Center easily
  margin: 0 auto $spacer auto;
  animation: spin 1.5s linear infinite; // Slightly slower spin
  color: $primary-color;
}
```

---

### pages\GroupExamSessionPage\GroupExamSessionPage.tsx

```typescript
// src/pages/GroupExamSessionPage/GroupExamSessionPage.tsx
import React, { useEffect, useState, useMemo} from 'react';
import { useParams, useNavigate } from 'react-router-dom';
import { useExam } from '../../contexts/ExamContext';
import ExamPage from '../ExamPage/ExamPage';
import styles from './GroupExamSessionPage.module.scss';
import Spinner from '../../components/Spinner/Spinner';
import { useAuth } from '../../contexts/AuthContext';
import { getParticipantStatus, getGroupExam } from '../../services/firestoreService';
import { toast } from 'react-toastify';
import { useAntiCheatMonitor } from '../../hooks/useAntiCheatMonitor';
import { GroupExam } from '../../types';

const GroupExamSessionPage: React.FC = () => {
    const { sessionId } = useParams<{ sessionId: string }>();
    const { examStatus, loadAndStartGroupExam, error: examError, clearExamState, examIdentifier } = useExam(); // Get examIdentifier
    const { currentUser, isLoading: isAuthLoading } = useAuth();
    const navigate = useNavigate();

    // State for loading checks
    const [isCheckingStatus, setIsCheckingStatus] = useState(true);
    const [accessError, setAccessError] = useState<string | null>(null);
    // State to track if loading has been initiated *for this specific sessionId* by *this component instance*
    const [currentSessionLoadInitiated, setCurrentSessionLoadInitiated] = useState(false);
    const [sessionDetailsForMonitor, setSessionDetailsForMonitor] = useState<GroupExam | null>(null);

    const monitorConfig = useMemo(() => {
        if (sessionDetailsForMonitor?.monitoringEnabled) {
            return {
                focusTracking: true,
                copyPastePrevention: true,
                restrictedKeyLogging: true,
            };
        }
        return null;
    }, [sessionDetailsForMonitor]);

    const { isPageFocused } = useAntiCheatMonitor( // isPageFocused can be used for UI if needed
        examStatus === 'active' && !!monitorConfig, // isActive for monitor
        sessionId || null,
        currentUser?.uid || null,
        monitorConfig
    );
    
    useEffect(() => {
        let isMounted = true;

        const checkStatusAndLoad = async () => {
            if (!currentUser || !sessionId) {
                if (isMounted) setIsCheckingStatus(false); // Stop checking if essential info is missing
                return;
            }

            // If exam context is already processing or finished for the *current target session*, let it be.
            // This prevents this page from interfering if it's, for example, remounted while ExamContext is submitting.
            const targetExamIdentifier = `group_${sessionId}`;
            if ((examStatus === 'submitting' || examStatus === 'finished') && examIdentifier === targetExamIdentifier) {
                //console.log(`[GroupExamSessionPage] ExamContext status is '${examStatus}' for current session '${targetExamIdentifier}'. No action needed from this page.`);
                if (isMounted) setIsCheckingStatus(false);
                return;
            }

            // If this page has already initiated the load for *this specific sessionId*,
            // and the context is now active or loading for it, don't re-initiate.
            if (currentSessionLoadInitiated &&
                (examStatus === 'active' || examStatus === 'loading_group_session') &&
                examIdentifier === targetExamIdentifier) {
                //console.log(`[GroupExamSessionPage] Load for session '${targetExamIdentifier}' already initiated by this page, and context is active/loading. Skipping.`);
                if (isMounted) setIsCheckingStatus(false);
                return;
            }

            //console.log(`[GroupExamSessionPage] Running checkStatusAndLoad. SessionId: ${sessionId}, Current ExamContext Status: ${examStatus}, examIdentifier: ${examIdentifier}, currentSessionLoadInitiated: ${currentSessionLoadInitiated}`);
            if(isMounted) setIsCheckingStatus(true);
            if(isMounted) setAccessError(null);
            // Not resetting currentSessionLoadInitiated here, only set it before calling loadAndStartGroupExam

            try {
                // Check Participant Status First
                //console.log("[GroupExamSessionPage] Checking participant status...");
                const participantData = await getParticipantStatus(sessionId, currentUser.uid);
                if (!isMounted) return;

                if (participantData?.status === 'completed') {
                    //console.log("[GroupExamSessionPage] Participant already completed. Navigating to profile.");
                    if (isMounted) {
                        setAccessError("You have already completed this group session.");
                        toast.info("You have already completed this session.");
                        navigate('/profile', { replace: true }); // Navigate away definitively
                    }
                    return; // Stop processing
                }
                //console.log("[GroupExamSessionPage] Participant status check passed (not completed).");

                // Fetch full session details to get monitoringEnabled config
                const fetchedGroupExamDetails = await getGroupExam(sessionId);
                if (!isMounted) return; // Check mount status again after async call
                if (fetchedGroupExamDetails) {
                    setSessionDetailsForMonitor(fetchedGroupExamDetails); // <-- SET DETAILS FOR MONITOR
                } else {
                    // If session details couldn't be fetched (e.g., session deleted by host)
                    setSessionDetailsForMonitor(null);
                    throw new Error("Group session details not found or could not be loaded.");
                }

                // Determine if we need to call loadAndStartGroupExam:
                // 1. Context is idle OR
                // 2. Context is finished (but for a DIFFERENT exam - checked by examIdentifier mismatch) OR
                // 3. Context is loading_group_session BUT for a different exam (unlikely, but safe check)
                // AND this page hasn't initiated the load for the current sessionId yet.
                const shouldInitiateLoad =
                    (
                        examStatus === 'idle' ||
                        (examStatus === 'finished' && examIdentifier !== targetExamIdentifier) ||
                        (examStatus === 'loading_group_session' && examIdentifier !== targetExamIdentifier)
                    ) && !currentSessionLoadInitiated;

                if (shouldInitiateLoad) {
                    //console.log(`[GroupExamSessionPage] Conditions met to call loadAndStartGroupExam for session ${sessionId}.`);
                    if (examStatus !== 'idle') { // If context wasn't idle, clear it first.
                        //console.log(`[GroupExamSessionPage] Clearing previous exam state (current status: ${examStatus}) before loading new group session.`);
                        clearExamState(); // This should reset examStatus to 'idle'
                        // Give a tick for state to update before proceeding with load
                        await new Promise(resolve => setTimeout(resolve, 0));
                        if (!isMounted) return;
                    }
                    if(isMounted) setCurrentSessionLoadInitiated(true); // Set flag *before* calling async func
                    await loadAndStartGroupExam(sessionId);
                    // loadAndStartGroupExam will change examStatus, triggering this useEffect again.
                    // The next run should be caught by the 'currentSessionLoadInitiated && (active/loading_group_session)' guard.
                } else {
                    //console.log(`[GroupExamSessionPage] Conditions not met to call loadAndStartGroupExam. examStatus: ${examStatus}, examIdentifier: ${examIdentifier}, currentSessionLoadInitiated: ${currentSessionLoadInitiated}`);
                    // If the exam is already active for the correct session, or loading for it, that's fine.
                    // If currentSessionLoadInitiated is true, but examStatus isn't active/loading_group_session for *this* session,
                    // it might indicate an error during the load. examError in context should reflect this.
                    if (currentSessionLoadInitiated && examStatus !== 'active' && examStatus !== 'loading_group_session' && examIdentifier === targetExamIdentifier) {
                        //console.warn(`[GroupExamSessionPage] Load was initiated for ${targetExamIdentifier}, but context status is ${examStatus}. This might indicate a load failure.`);
                    }
                }

            } catch (err: any) {
                if (isMounted) {
                    //console.error("[GroupExamSessionPage] Error in checkStatusAndLoad:", err);
                    setAccessError(err.message || "Could not load session.");
                    if (err.message?.includes("not found")) { // More specific error for navigation
                        navigate('/select-exam', { replace: true, state: { message: "Group session not found." } });
                    }
                    setCurrentSessionLoadInitiated(false); // Reset on error so retry might be possible if user navigates back or error is transient
                }
            } finally {
                if (isMounted) setIsCheckingStatus(false);
            }
        };

        if (!isAuthLoading && currentUser && sessionId) {
            checkStatusAndLoad();
        } else if (!isAuthLoading && !currentUser) {
            navigate('/select-exam', { replace: true, state: { message: "Please log in to join." } });
        }

        return () => { isMounted = false; };

    // Add examIdentifier and currentSessionLoadInitiated to ensure the effect correctly
    // re-evaluates when the context's active exam changes or when this page's load initiation status changes.
    }, [sessionId, currentUser, isAuthLoading, navigate, loadAndStartGroupExam, clearExamState, examStatus, examIdentifier, currentSessionLoadInitiated]);

    // Render Logic
    if (isAuthLoading || isCheckingStatus) {
        return (
            <div className={styles.statusContainer}>
                <Spinner size={30} />
                <p>Checking session status...</p>
            </div>
        );
    }

    if (accessError) {
        return (
            <div className={styles.statusContainerError}>
                <h2>Access Denied</h2>
                <p>{accessError}</p>
                <button onClick={() => navigate('/select-exam', { replace: true })} className={styles.actionButton}>
                    Back to Exam Selection
                </button>
            </div>
        );
    }

    // Check context status for loading AFTER initial checks are done
    // If this page initiated the load, and context is still loading the group session for this ID.
    const targetExamIdentifier = `group_${sessionId}`;
    if (examStatus === 'loading_group_session' && examIdentifier === targetExamIdentifier) {
        return (
            <div className={styles.statusContainer}>
                <Spinner size={30} />
                <p>Loading group exam session...</p>
            </div>
        );
    }

    // If there's a general exam error from context, and it matches this session, or if no session ID matches (generic error).
    if (examError && (examIdentifier === targetExamIdentifier || !examIdentifier)) {
        return (
            <div className={styles.statusContainerError}>
                <h2>Error Loading Session</h2>
                <p>{examError}</p>
                <button onClick={() => { clearExamState(); navigate('/select-exam'); }} className={styles.actionButton}>
                    Back to Exam Selection
                </button>
            </div>
        );
    }

    // If the exam is active and it's for the current sessionId.
    if (examStatus === 'active' && examIdentifier === targetExamIdentifier && sessionId) {
        return <ExamPage
            isGroupSession={true} // Add a prop to tell ExamPage it's a group session
            monitoringActive={!!monitorConfig} // Is monitoring generally on?
            isCurrentlyFocused={isPageFocused} // Current focus state
        />;
    }

    // Fallback if none of the above conditions are met (e.g., state mismatch or unexpected transition)
    // This might happen if the page is re-rendered after a context change that wasn't fully handled above.
    //console.log(`[GroupExamSessionPage] Rendering fallback. Context Status: ${examStatus}, Context ID: ${examIdentifier}, Page Session ID: ${sessionId}, Load Initiated Here: ${currentSessionLoadInitiated}`);
    return (
        <div className={styles.statusContainer}>
            <p>Verifying session state...</p>
            <button onClick={() => { clearExamState(); navigate(0); /* Refresh attempt */ }} className={styles.actionButton}>Retry Load</button>
        </div>
    );
};

export default GroupExamSessionPage;
```

---

## pages\GroupExamSetupPage


### pages\GroupExamSetupPage\GroupExamSetupPage.module.scss

```scss
// src/pages/GroupExamSetupPage/GroupExamSetupPage.module.scss
@import '../../styles/variables';
@import '../../styles/mixins';
@import 'react-datepicker/dist/react-datepicker.css'; // Keep this for DatePicker base styles

.setupPage {
  padding: map-get($spacers, 4) 0 map-get($spacers, 6); // py-4 my-6
  max-width: 800px;
  margin: 0 auto;

  h1 {
    text-align: center;
    margin-bottom: map-get($spacers, 5); // mb-5
    color: $primary-color;
    font-weight: $font-weight-semibold;
  }
}

.setupForm {
  background-color: $component-bg;
  padding: map-get($spacers, 4) map-get($spacers, 5); // p-4 px-5
  border: 1px solid $gray-200; // Lighter border
  border-radius: $border-radius-lg; // 8px
  box-shadow: $box-shadow-lg; // More prominent shadow
  display: flex;
  flex-direction: column;
  gap: map-get($spacers, 5); // Increased gap between form sections (32px)
}

.formSection {
  border-bottom: 1px solid $gray-100; // Very subtle separator
  padding-bottom: map-get($spacers, 4); // pb-4

  &:last-child {
    border-bottom: none;
    padding-bottom: 0;
  }

  h2 { // Section titles (e.g., "1. Session Details")
    font-size: $h4-font-size * 0.95; // Slightly smaller than H4
    color: $gray-700; // Dark gray for section titles
    margin-top: 0;
    margin-bottom: map-get($spacers, 4); // mb-4 (24px)
    font-weight: $font-weight-semibold;
    border-bottom: 1px solid $gray-200;
    padding-bottom: map-get($spacers, 2);
  }
}

.formGroup {
  margin-bottom: map-get($spacers, 4); // mb-4 (24px), consistent group spacing

  label {
    display: block;
    font-weight: $font-weight-medium;
    margin-bottom: map-get($spacers, 2); // mb-2 (8px)
    color: $gray-700;
    font-size: $font-size-base * 0.9; // Label font size
  }

  input[type="text"],
  input[type="number"],
  input[type="datetime-local"], // Apply base input styles
  select {                    // Apply base input styles to select
    width: 100%;
    padding: map-get($spacers, 2) map-get($spacers, 3); // py-2 px-3
    border: 1px solid $border-color;
    border-radius: $border-radius;
    font-size: $font-size-base;
    background-color: $white-color;
    color: $text-color;
    transition: border-color $transition-fast, box-shadow $transition-fast;

    &:focus {
      outline: none;
      border-color: $primary-color;
      box-shadow: 0 0 0 3px rgba($primary-color, 0.2);
    }
    &:disabled {
      background-color: $gray-100;
      opacity: 0.7;
      cursor: not-allowed;
    }
    &::placeholder { // Ensure placeholder style is consistent
        color: $text-muted;
        opacity: 1;
    }
  }
  // Specific styling for select arrow (from existing file, slightly adapted)
  select {
    appearance: none;
    background-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16'%3e%3cpath fill='none' stroke='#{$gray-500}' stroke-linecap='round' stroke-linejoin='round' stroke-width='2' d='m2 5 6 6 6-6'/%3e%3c/svg%3e"); // Use variable for stroke
    background-repeat: no-repeat;
    background-position: right #{map-get($spacers, 2)} center; // Adjust position
    background-size: 16px 12px; // Keep size
    padding-right: map-get($spacers, 5) !important; // Ensure space for arrow
  }
}

.timeInputs { // For Start/End Time
  display: grid;
  grid-template-columns: 1fr;
  gap: map-get($spacers, 3); // gap-3 for items within

  @include media-breakpoint-up(sm) {
    grid-template-columns: 1fr 1fr;
    gap: map-get($spacers, 4); // Increase gap for side-by-side
  }

  label { // Specific for date/time labels with icons
    display: flex;
    align-items: center;
    gap: map-get($spacers, 2);
    font-weight: $font-weight-medium;
    margin-bottom: map-get($spacers, 2);
    color: $gray-700;
    font-size: $font-size-base * 0.9;
    svg { color: $secondary-color; }
  }
}

// Styles for react-datepicker (wrapper and input)
.datePickerWrapper { width: 100%; }

// DatePicker Popper anTheme (optional, for better consistency)
.react-datepicker-popper { z-index: $zindex-dropdown + 5 !important; }
.react-datepicker {
  font-family: $font-family-base !important;
  border: 1px solid $gray-200 !important;
  border-radius: $border-radius-lg !important; // Softer radius
  box-shadow: $box-shadow-lg !important;
}
.react-datepicker__header {
  background-color: $gray-50 !important;
  border-bottom: 1px solid $gray-200 !important;
  border-top-left-radius: $border-radius-lg !important;
  border-top-right-radius: $border-radius-lg !important;
}
.react-datepicker__current-month,
.react-datepicker-time__header,
.react-datepicker__day-name {
  color: $gray-700 !important;
  font-weight: $font-weight-medium !important;
}
.react-datepicker__day--selected,
.react-datepicker__day--in-selecting-range,
.react-datepicker__day--in-range,
.react-datepicker__month-text--selected,
.react-datepicker__month-text--in-selecting-range,
.react-datepicker__month-text--in-range,
.react-datepicker__time-container .react-datepicker__time .react-datepicker__time-box ul.react-datepicker__time-list li.react-datepicker__time-list-item--selected {
  background-color: $primary-color !important;
  color: $white-color !important;
  font-weight: $font-weight-medium !important;
}
.react-datepicker__day:hover,
.react-datepicker__month-text:hover,
.react-datepicker__time-container .react-datepicker__time .react-datepicker__time-box ul.react-datepicker__time-list li.react-datepicker__time-list-item:hover {
  background-color: $gray-100 !important;
  color: $primary-color !important;
}
.react-datepicker__day--keyboard-selected { // Focus state for keyboard nav
  background-color: lighten($primary-color, 40%) !important;
  color: $primary-color !important;
}

.timeError { // Validation error specific to time inputs
  // Use global error message styling, but ensure it spans columns if in grid
  grid-column: 1 / -1; // If timeInputs is a grid itself
  text-align: center;
  // Apply general error message styles:
  background-color: lighten($red-500, 50%);
  border: 1px solid lighten($red-500, 30%);
  color: darken($red-500, 15%);
  border-radius: $border-radius;
  padding: map-get($spacers, 2) map-get($spacers, 3);
  font-size: $font-size-base * 0.9;
  line-height: 1.5;
  margin-top: map-get($spacers, 2); // Add some space if it's directly under inputs
}

.markingSchemeContainer {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(180px, 1fr)); // Responsive columns
  gap: map-get($spacers, 3) map-get($spacers, 4); // row-gap col-gap
  align-items: end; // Align baselines
  margin-top: map-get($spacers, 3);
  padding-top: map-get($spacers, 3);
  border-top: 1px dotted $gray-200;
}

.checkboxLabel { // For "Enable Negative Marking"
  display: flex;
  align-items: center;
  gap: map-get($spacers, 2); // gap-2 (8px)
  font-weight: $font-weight-medium;
  color: $gray-700; // Consistent label color
  cursor: pointer;
  font-size: $font-size-base * 0.9;
  // Align with bottom of input field in the same grid cell if paired
  // This can be tricky; using align-items: end on grid parent helps.
  // If direct sibling to an input, might need margin adjustment.
  margin-bottom: map-get($spacers, 1); // Allow space for hint below if needed
  &.disabledLabel { // Class to add when the whole feature is perk-locked
    color: $text-muted; // Muted text for the label
    cursor: not-allowed;
  }
}

.checkboxInput { // Style the checkbox itself
  height: 1.2em;
  width: 1.2em;
  cursor: pointer;
  accent-color: $primary-color; // Modern way to color checkbox
  border: 1px solid $border-color; // Fallback border
  border-radius: $border-radius-sm; // Slightly rounded square
  // Remove default appearance if fully custom styling is desired
  // -webkit-appearance: none;
  // appearance: none;
  // background-color: $white-color;
  // &:checked { background-color: $primary-color; /* ... add checkmark svg ... */ }
}
.geolocationInputs {
  margin-top: map-get($spacers, 3);
  padding-left: map-get($spacers, 4); // Indent geo inputs slightly
  border-left: 3px solid $gray-200; // Visual separator
  display: grid;
  grid-template-columns: 1fr; // Stack by default
  gap: map-get($spacers, 3);

  @include media-breakpoint-up(sm) {
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); // Responsive columns
  }
}
.hostLocationAction { // New container for the fetch button and its error
  // If geolocationInputs is a grid with more than 1 column, make this span all columns
  @include media-breakpoint-up(sm) { // Assuming .geolocationInputs becomes multi-column at sm
      grid-column: 1 / -1; // Span all columns
  }
  margin-top: map-get($spacers, 2); // Add some space above it
  text-align: left; // Or center if you prefer
}

.fetchLocationButton {
@include button-variant(
  transparent,      // bg
  $info-color,       // border
  $info-color,       // text
  lighten($info-color, 50%), // hover-bg
  $info-color,       // hover-border
  darken($info-color, 5%),   // hover-text
  lighten($info-color, 45%), // active-bg
  darken($info-color, 5%),   // active-border
  0.65,
  true              // is-outline
);
padding: map-get($spacers, 2) map-get($spacers, 3); // py-2 px-3
font-size: $font-size-base * 0.9;
// margin-bottom: map-get($spacers, 2); // If error is separate
display: inline-flex; // Keep it inline if preferred
align-items: center; // Align spinner/icon
gap: map-get($spacers, 2);
}

.inlineError { 
  padding: map-get($spacers, 1) map-get($spacers, 2) !important;
  margin-top: map-get($spacers, 2) !important; // Ensure space from button
  margin-bottom: 0 !important; // No extra bottom margin if it's the last element
  text-align: left !important; // Align with button usually
  font-size: $font-size-base * 0.85 !important;
  display: block; // To take width if needed
}
.inputHint {
  display: block;
  font-size: $font-size-base * 0.8; // Smaller hint text
  color: $text-muted; // Lighter color for hints
  margin-top: map-get($spacers, 1); // mt-1 (4px)
}

// --- Source Selection (Official / Custom Buttons) ---
.sourceTypeSelector {
  display: flex;
  gap: map-get($spacers, 2); // gap-2
  margin-bottom: map-get($spacers, 3); // mb-3

  button { // Style for "Official Exam" / "Custom JSON" toggles
    @include button-variant(
      transparent,      // bg
      $gray-300,       // border
      $gray-700,       // text
      $gray-50,        // hover-bg
      $gray-400,       // hover-border
      $gray-800,       // hover-text
      $gray-100,       // active-bg
      $gray-500,       // active-border
      0.65,
      true              // is-outline
    );
    flex-grow: 1;
    padding: map-get($spacers, 2) map-get($spacers, 3); // py-2 px-3
    font-weight: $font-weight-medium;

    &.active { // Active state for selected source type
      @include button-variant($primary-color); // Solid primary
      border-color: $primary-color; // Ensure border matches
      // color: $white-color; (handled by mixin)
      cursor: default;
    }
  }
}

.sourceInputArea { // Container for OfficialExamSelector or CustomExamInput
  border: 1px dashed $gray-200; // More subtle dashed border
  padding: map-get($spacers, 4); // p-4 (24px)
  border-radius: $border-radius; // Standard radius
  background-color: $gray-50; // Very light background for distinction
  min-height: 180px;
}

.selectSourcePrompt {
  text-align: center;
  color: $text-muted;
  font-style: italic;
  padding: map-get($spacers, 5) 0; // py-5
}

// --- Submission Area ---
.submissionArea {
  margin-top: map-get($spacers, 5); // mt-5
  text-align: center;
}

.createButton { // Button to create the session
  @include button-variant($success-color); // Solid success button
  padding: map-get($spacers, 3) map-get($spacers, 5); // py-3 px-5, large button
  font-size: $font-size-base * 1.1;
  font-weight: $font-weight-semibold; // Bolder
  min-width: 220px;
  // Disabled state handled by mixin
}

// Error message and Info message styles (reuse styles from CustomExamInput)
.errorMessage { // General form errors (not input-specific)
  // ... same as .errorMessage in CustomExamInput.module.scss ...
  background-color: lighten($red-500, 50%);
  border: 1px solid lighten($red-500, 30%);
  color: darken($red-500, 15%);
  border-radius: $border-radius;
  padding: map-get($spacers, 2) map-get($spacers, 3);
  margin-bottom: map-get($spacers, 3);
  text-align: left;
  font-size: $font-size-base * 0.9;
  display: block; // Make it block to take width or inline-block for centering
  width: 100%;    // Example: full width
  line-height: 1.5;
  svg {
    font-size: $font-size-base * 1.1;
    margin-right: map-get($spacers, 2);
    vertical-align: middle; // Better alignment with text
    margin-bottom: 2px;
  }
}

.infoMessage { // Info message below create button
  color: $text-muted;
  font-size: $font-size-base * 0.9;
  margin-top: map-get($spacers, 3); // mt-3
  display: inline-flex;
  align-items: center;
  gap: map-get($spacers, 1);
  svg { color: $secondary-color; } // Use secondary for info icon color

  // Error variant for info message (like limit reached)
  &.limitError { // Class to be added conditionally in TSX
    color: $danger-color;
    font-weight: $font-weight-medium;
    svg { color: $danger-color; }
  }
}
.locationPickerContainer {
  margin-top: map-get($spacers, 4); // mt-4
  border: 1px solid $gray-200;
  border-radius: $border-radius;
  position: relative; // For loading placeholder
}

.iframeHiddenInitially {
  visibility: hidden; // Hide it until it's ready to avoid flicker or showing unstyled content
}

.locationPickerIframe {
  width: 100%;
  height: 450px;
  border: none;
  display: block;
  visibility: visible; // Default to visible
}

.iframeLoadingPlaceholder {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%; // Cover the iframe area
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: rgba($white-color, 0.8);
  z-index: 1; // Above iframe until ready
  color: $text-muted;
  font-style: italic;
}
// Spin icon animation is global in App.scss
```

---

### pages\GroupExamSetupPage\GroupExamSetupPage.tsx

```typescript
// src/pages/GroupExamSetupPage/GroupExamSetupPage.tsx
import React, { useState, useCallback, useMemo, useEffect, useRef } from 'react';
import { useNavigate } from 'react-router-dom';
import { useAuth } from '../../contexts/AuthContext'; // Corrected path
import styles from './GroupExamSetupPage.module.scss';
import { createGroupExam, getHostedSessionsCount } from '../../services/firestoreService';
import { ExamConfig, GroupExam, ResultVisibility } from '../../types';
import OfficialExamSelector from '../../components/OfficialExamSelector/OfficialExamSelector'; // Corrected path
import CustomExamInput from '../../components/CustomExamInput/CustomExamInput'; // Corrected path
import { toast } from 'react-toastify';
import { FaInfoCircle, FaCalendarAlt, FaLock, FaMapMarkerAlt, FaEye } from 'react-icons/fa'; // Added FaEye for monitoring
import Spinner from '../../components/Spinner/Spinner'; // Corrected path
import { analytics } from '../../services/firebase';
import { logEvent } from 'firebase/analytics';
import { useExamConfig } from '../../hooks/useExamConfig'; // Corrected path
import DatePicker from 'react-datepicker';
import 'react-datepicker/dist/react-datepicker.css';
import { DEFAULT_MARKS_PER_CORRECT, DEFAULT_NEGATIVE_MARKS_PER_INCORRECT } from '../../constants'; // Corrected path

// Import useUserPerks from Examify's hooks
import { useUserPerks } from '../../hooks/useUserPerks'; // Corrected path

const LOCATION_PICKER_URL = "https://samkarya.github.io/PlugIn/LocationPicker/";

const GroupExamSetupPage: React.FC = () => {
    const navigate = useNavigate();
    const { currentUser, isLoading: isAuthLoading } = useAuth();
    const { availableExams, isLoadingConfig, configError } = useExamConfig();
    // *** USE THE EXAMIFY useUserPerks HOOK ***
    const { limits: perkLimits, features: perkFeatures, isLoadingPerks, currentTier } = useUserPerks();

    const [sessionName, setSessionName] = useState<string>('');
    const [timeLimitMinutes, setTimeLimitMinutes] = useState<number | null>(120);
    const [isSubmitting, setIsSubmitting] = useState<boolean>(false);
    const [setupError, setSetupError] = useState<string | null>(null);

    const [hostedCount, setHostedCount] = useState<number | null>(null);
    const [isLoadingCount, setIsLoadingCount] = useState<boolean>(true);
    const [countError, setCountError] = useState<string | null>(null);

    const [startTime, setStartTime] = useState<Date | null>(null);
    const [endTime, setEndTime] = useState<Date | null>(null);
    const [resultVisibility, setResultVisibility] = useState<ResultVisibility>('Self Only Immediate');
    const [marksPerCorrect, setMarksPerCorrect] = useState<number | string>(DEFAULT_MARKS_PER_CORRECT);
    const [negativeMarkingEnabled, setNegativeMarkingEnabled] = useState<boolean>(true);
    const [negativeMarksPerIncorrect, setNegativeMarksPerIncorrect] = useState<number | string>(DEFAULT_NEGATIVE_MARKS_PER_INCORRECT);
    
    // *** MODIFIED: Default monitoringEnabled based on perk ***
    // Initialize based on perk AFTER perks are loaded.
    // This initial value might be overridden by the useEffect below.
    const [monitoringEnabled, setMonitoringEnabled] = useState<boolean>(false);
    const [geoRestrictionEnabled, setGeoRestrictionEnabled] = useState<boolean>(false);

    const [geoLatitude, setGeoLatitude] = useState<string>('');
    const [geoLongitude, setGeoLongitude] = useState<string>('');
    const [geoRadius, setGeoRadius] = useState<string>('500');

    const [isFetchingHostLocation, setIsFetchingHostLocation] = useState<boolean>(false);
    const [hostLocationError, setHostLocationError] = useState<string | null>(null);

    type SourceMode = 'none' | 'official' | 'upload' | 'paste';
    const [sourceMode, setSourceMode] = useState<SourceMode>('none');
    const [selectedSourceData, setSelectedSourceData] = useState<ExamConfig | File | string | null>(null);
    const [childValidationError, setChildValidationError] = useState<string | null>(null);

    const iframeRef = useRef<HTMLIFrameElement>(null);
    const [isLocationPickerReady, setIsLocationPickerReady] = useState(false);

    // Set initial monitoring/geo states based on perks AFTER perks are loaded
    useEffect(() => {
        if (!isLoadingPerks) {
            setMonitoringEnabled(perkFeatures.canEnableExamMonitoring);
            setGeoRestrictionEnabled(perkFeatures.canEnableAdvancedMonitoring); // Example initial state
        }
    }, [isLoadingPerks, perkFeatures.canEnableExamMonitoring, perkFeatures.canEnableAdvancedMonitoring]);


    useEffect(() => {
        const handleIframeMessage = (event: MessageEvent) => {
            if (event.origin !== "https://samkarya.github.io") { return; }
            const { data: messageData } = event;
            if (messageData && messageData.type) {
                switch (messageData.type) {
                    case 'LOCATION_PICKER_UPDATE':
                        const { lat, lng, radius } = messageData.data;
                        setGeoLatitude(lat.toFixed(6));
                        setGeoLongitude(lng.toFixed(6));
                        setGeoRadius(String(radius));
                        break;
                    case 'LOCATION_PICKER_READY':
                        setIsLocationPickerReady(true);
                        if (geoLatitude && geoLongitude && geoRadius) {
                            sendLocationToPicker(parseFloat(geoLatitude), parseFloat(geoLongitude), parseInt(geoRadius, 10));
                        }
                        sendConfigurationToPicker({ autoSend: true, controlPanelVisible: true });
                        break;
                    default: break;
                }
            }
        };
        window.addEventListener('message', handleIframeMessage);
        return () => { window.removeEventListener('message', handleIframeMessage); };
        // eslint-disable-next-line
    }, []); // Empty: run once

    useEffect(() => {
        if (isLocationPickerReady && geoRestrictionEnabled && iframeRef.current && iframeRef.current.contentWindow) {
            iframeRef.current.contentWindow.postMessage({
                type: 'CONFIGURE_LOCATION_PICKER', data: { autoSend: true, controlPanelVisible: false }
            }, LOCATION_PICKER_URL);
            const latNum = parseFloat(geoLatitude);
            const lngNum = parseFloat(geoLongitude);
            const radNum = parseInt(geoRadius, 10);
            if (!isNaN(latNum) && !isNaN(lngNum) && !isNaN(radNum)) {
                 iframeRef.current.contentWindow.postMessage({
                    type: 'SET_LOCATION_PICKER', data: { lat: latNum, lng: lngNum, radius: radNum }
                }, LOCATION_PICKER_URL);
            }
        }
        // eslint-disable-next-line
    }, [isLocationPickerReady, geoRestrictionEnabled, geoLatitude, geoLongitude, geoRadius]);

    useEffect(() => {
        if (!geoRestrictionEnabled) { setIsLocationPickerReady(false); }
    }, [geoRestrictionEnabled]);
    
    const sendLocationToPicker = (lat?: number, lng?: number, radius?: number) => {
        if (iframeRef.current && iframeRef.current.contentWindow && isLocationPickerReady) {
            const dataToSend: any = {};
            if (lat !== undefined) dataToSend.lat = lat;
            if (lng !== undefined) dataToSend.lng = lng;
            if (radius !== undefined) dataToSend.radius = radius;
            if (Object.keys(dataToSend).length > 0) {
                iframeRef.current.contentWindow.postMessage({ type: 'SET_LOCATION_PICKER', data: dataToSend }, LOCATION_PICKER_URL);
            }
        }
    };
    const sendConfigurationToPicker = (config: { autoSend?: boolean; controlPanelVisible?: boolean }) => {
         if (iframeRef.current && iframeRef.current.contentWindow && isLocationPickerReady) {
             iframeRef.current.contentWindow.postMessage({ type: 'CONFIGURE_LOCATION_PICKER', data: config }, LOCATION_PICKER_URL);
         }
    };

    useEffect(() => { document.title = 'Create Group Session - Examify'; }, []);

    useEffect(() => {
        let isMounted = true;
        const fetchCount = async () => {
            if (currentUser) {
                setIsLoadingCount(true); setCountError(null);
                try {
                    const count = await getHostedSessionsCount(currentUser.uid);
                    if(isMounted) setHostedCount(count);
                } catch (err: any) {
                     if(isMounted) { setCountError("Could not check your current session count."); setHostedCount(null); }
                } finally {
                   if(isMounted) setIsLoadingCount(false);
                }
            } else {
                 if(isMounted) { setHostedCount(null); setIsLoadingCount(false); setCountError(null); }
            }
        };
        if (!isAuthLoading && currentUser && !isLoadingPerks) fetchCount(); // Fetch when auth and perks are ready
        return () => { isMounted = false; };
    }, [currentUser, isAuthLoading, isLoadingPerks]);

    // *** MODIFIED: Use perkLimits for sessionLimit ***
    const sessionLimit = perkLimits.hostedSessions === null ? Infinity : perkLimits.hostedSessions;
    const limitReached = useMemo(() => {
        if (isLoadingCount || isLoadingPerks || hostedCount === null) return false;
        return hostedCount >= sessionLimit;
    }, [hostedCount, sessionLimit, isLoadingCount, isLoadingPerks]);

    const timeValidationError = useMemo(() => {
        if (startTime && endTime && startTime.getTime() >= endTime.getTime()) {
            return "End Time must be after Start Time.";
        }
        return null;
    }, [startTime, endTime]);

    useEffect(() => {
        if (geoRestrictionEnabled && isLocationPickerReady) {
            const latNum = parseFloat(geoLatitude);
            const lngNum = parseFloat(geoLongitude);
            const radNum = parseInt(geoRadius, 10);
            if (!isNaN(latNum) && !isNaN(lngNum) && !isNaN(radNum) && radNum >=50 && radNum <=50000) {
                sendLocationToPicker(latNum, lngNum, radNum);
            }
        }
        // eslint-disable-next-line
    }, [geoLatitude, geoLongitude, geoRadius, geoRestrictionEnabled, isLocationPickerReady]);

    const fetchHostCurrentLocation = useCallback(() => {
         if (!('geolocation' in navigator)) { return; }
         setIsFetchingHostLocation(true); setHostLocationError(null);
         navigator.geolocation.getCurrentPosition(
             (position) => {
                 const { latitude, longitude } = position.coords;
                 setGeoLatitude(parseFloat(latitude.toFixed(6)).toString());
                setGeoLongitude(parseFloat(longitude.toFixed(6)).toString());
                if (!geoRadius || parseInt(geoRadius, 10) <= 0) { setGeoRadius('1000'); }
                toast.success("Current location fetched!");
                 setIsFetchingHostLocation(false);
             },
            (error) => {
                let msg = "Could not fetch current location.";
                if (error.code === error.PERMISSION_DENIED) msg = "Location permission denied.";
                toast.error(msg); setHostLocationError(msg); setIsFetchingHostLocation(false);
            },
            { enableHighAccuracy: true, timeout: 10000, maximumAge: 0 }
        );
    }, [geoRadius]);

    const geoSettingsValid = useMemo(() => {
        return !geoRestrictionEnabled ||
            (geoRestrictionEnabled &&
             geoLatitude.trim() !== '' && !isNaN(parseFloat(geoLatitude)) &&
             geoLongitude.trim() !== '' && !isNaN(parseFloat(geoLongitude)) &&
             geoRadius.trim() !== '' && !isNaN(parseInt(geoRadius)) &&
             parseInt(geoRadius) >= 50 && parseInt(geoRadius) <= 50000
            );
    }, [geoRestrictionEnabled, geoLatitude, geoLongitude, geoRadius]);

    const canCreateSession = useMemo(() => {
        const timeLimitValid = timeLimitMinutes === null || (typeof timeLimitMinutes === 'number' && timeLimitMinutes >= 1);
        const marksPerCorrectValid = (typeof marksPerCorrect === 'number' && marksPerCorrect >= 0) || (typeof marksPerCorrect === 'string' && parseFloat(marksPerCorrect) >= 0);
        const negativeMarksValid = !negativeMarkingEnabled || (typeof negativeMarksPerIncorrect === 'number' && negativeMarksPerIncorrect >= 0) || (typeof negativeMarksPerIncorrect === 'string' && parseFloat(negativeMarksPerIncorrect) >= 0);

        return !isSubmitting &&
               !isLoadingPerks && !isLoadingCount && !countError && !limitReached &&
               !!sessionName.trim() && sourceMode !== 'none' && !!selectedSourceData &&
               !childValidationError && !timeValidationError &&
               timeLimitValid && marksPerCorrectValid && negativeMarksValid && geoSettingsValid;
               // eslint-disable-next-line
    }, [
        sessionName, timeLimitMinutes, sourceMode, selectedSourceData, childValidationError, isSubmitting,
        timeValidationError, marksPerCorrect, negativeMarkingEnabled, negativeMarksPerIncorrect,
        isLoadingPerks, isLoadingCount, countError, limitReached, geoSettingsValid
    ]);

    const handleOfficialExamSelected = useCallback((config: ExamConfig) => {
        setSelectedSourceData(config); setSourceMode('official'); setChildValidationError(null);
    }, []);
    const handleCustomFileValidated = useCallback((file: File) => {
        setSelectedSourceData(file); setSourceMode('upload'); setChildValidationError(null);
    }, []);
    const handleCustomPasteValidated = useCallback((jsonString: string) => {
        setSelectedSourceData(jsonString); setSourceMode('paste'); setChildValidationError(null);
    }, []);
    const handleChildInputCleared = useCallback(() => {
        setSelectedSourceData(null); setChildValidationError(null);
        // eslint-disable-next-line
    }, []);
    const handleChildValidationError = useCallback((source: 'file' | 'paste', message: string) => {
        setChildValidationError(`Validation Error (${source}): ${message}`); setSelectedSourceData(null);
    }, []);
    const handleSourceTypeButtonClick = useCallback((newMode: SourceMode | 'custom') => {
        if (sourceMode === newMode || (newMode === 'custom' && (sourceMode === 'upload' || sourceMode === 'paste'))) return;
        if ((newMode === 'official' && (sourceMode === 'upload' || sourceMode === 'paste')) ||
            (newMode === 'custom' && sourceMode === 'official')) {
            setSelectedSourceData(null); setChildValidationError(null);
        }
        setSourceMode(newMode === 'custom' ? 'upload' : newMode as SourceMode);
    }, [sourceMode]);

    const handleCreateSession = async (event: React.FormEvent) => {
        event.preventDefault();
        // *** MODIFIED: Use isLoadingPerks in limitReached re-check ***
        if (isLoadingPerks || limitReached) {
            toast.error(`You have reached your limit of ${sessionLimit} hosted sessions for the ${currentTier?.name || 'Free'} tier.`);
            setIsSubmitting(false);
            return;
        }
        if (!canCreateSession || !currentUser || timeValidationError) {
            // Error messages based on specific validation failures
            if (timeValidationError) toast.error(timeValidationError);
            else if (!sessionName.trim()) toast.error("Please enter a Session Name.");
            else if (sourceMode === 'none' || !selectedSourceData) toast.error("Please select a valid Question Source.");
            else if (typeof marksPerCorrect !== 'number' && (typeof marksPerCorrect !== 'string' || parseFloat(marksPerCorrect) < 0)) toast.error("Valid positive Marks per Correct Answer required.");
            else if (negativeMarkingEnabled && (typeof negativeMarksPerIncorrect !== 'number' && (typeof negativeMarksPerIncorrect !== 'string' || parseFloat(negativeMarksPerIncorrect) < 0))) toast.error("Valid positive Negative Marks required.");
            else if (!geoSettingsValid) toast.error("Valid Geolocation settings required (Latitude, Longitude, Radius 50m-50km).");
            else toast.error("Please fix validation errors before creating.");
            return;
        }
        
        setIsSubmitting(true); setSetupError(null);
        let groupDataPayload: Partial<Omit<GroupExam, 'id' | 'createdAt' | 'status'>> & { hostUid: string; marksPerCorrect?: number; negativeMarkingEnabled?: boolean; negativeMarksPerIncorrect?: number;};
        let geoRestrictionValue = null;

        try {
           const finalTimeLimit = timeLimitMinutes === null ? null : Number(timeLimitMinutes);
           const finalMarksCorrect = Number(marksPerCorrect);
           const finalNegativeMarks = negativeMarkingEnabled ? Number(negativeMarksPerIncorrect) : 0;

           if (geoRestrictionEnabled) {
               if (geoSettingsValid) {
                   geoRestrictionValue = {
                       latitude: parseFloat(geoLatitude), longitude: parseFloat(geoLongitude), radiusMeters: parseInt(geoRadius, 10),
                   };
               } else {
                   toast.error("Invalid Geolocation settings."); setIsSubmitting(false); return;
               }
           }

           groupDataPayload = {
               hostUid: currentUser.uid, sessionName: sessionName.trim(), timeLimitMinutes: finalTimeLimit,
               startTime: startTime, endTime: endTime, resultVisibility: resultVisibility,
               marksPerCorrect: finalMarksCorrect, negativeMarkingEnabled: negativeMarkingEnabled,
               negativeMarksPerIncorrect: finalNegativeMarks, 
               monitoringEnabled: perkFeatures.canEnableExamMonitoring ? monitoringEnabled : false, // Respect perk
               geoRestriction: perkFeatures.canEnableAdvancedMonitoring ? geoRestrictionValue : null, // Respect perk
           };
            
            if (sourceMode === 'official' && selectedSourceData && typeof selectedSourceData === 'object' && !(selectedSourceData instanceof File)) {
                const config = selectedSourceData as ExamConfig;
                groupDataPayload = { ...groupDataPayload, examSourceType: 'official', examSourceId: config.id, examSourcePath: config.path, };
            } else if (sourceMode === 'upload' && selectedSourceData instanceof File) {
                const fileContent = await selectedSourceData.text();
                groupDataPayload = { ...groupDataPayload, examSourceType: 'custom_json', questionJsonString: fileContent, };
            } else if (sourceMode === 'paste' && typeof selectedSourceData === 'string') {
                groupDataPayload = { ...groupDataPayload, examSourceType: 'custom_json', questionJsonString: selectedSourceData, };
            } else {
                throw new Error("Invalid source data state for submission.");
            }
            
            const finalPayloadForFirestore = groupDataPayload as Omit<GroupExam, 'id' | 'createdAt' | 'status'> & { hostUid: string;};
            const newSessionId = await createGroupExam(finalPayloadForFirestore);
            toast.success(`Group session "${sessionName.trim()}" created!`);
            logEvent(analytics, 'group_session_created', { source_type: sourceMode, visibility: resultVisibility});
            navigate(`/group-exam/share/${newSessionId}`, { state: { sessionName: sessionName.trim() } });
        } catch (error: any) {
            setSetupError(error.message || "Failed to create session.");
            toast.error(error.message || "Failed to create session.");
        } finally {
            setIsSubmitting(false);
        }
    };

    // Combined loading for initial page setup
    const isPageLoading = isAuthLoading || isLoadingConfig || isLoadingPerks || isLoadingCount;


    return (
        <div className={styles.setupPage}>
            <h1>Create New Group Exam Session</h1>
            {isPageLoading ? <Spinner text="Loading setup options..." /> :
            <form onSubmit={handleCreateSession} className={styles.setupForm}>
                {/* Session Details Section */}
                <div className={styles.formSection}>
                    <h2>1. Session Details</h2>
                    {/* Session Name, Duration, Marking Scheme, Start/End Time, Result Visibility - existing inputs unchanged */}
                    <div className={styles.formGroup}>
                        <label htmlFor="sessionName">Session Name:</label>
                        <input type="text" id="sessionName" value={sessionName} onChange={(e) => setSessionName(e.target.value)} placeholder="e.g., Algebra Quiz, NIMCET Practice" maxLength={100} required disabled={isSubmitting} />
                    </div>
                    <div className={styles.formGroup}>
                        <label htmlFor="timeLimit">Exam Duration (minutes):</label>
                        <input type="number" id="timeLimit" value={timeLimitMinutes ?? ''} onChange={(e) => setTimeLimitMinutes(e.target.value === '' ? null : Math.max(1, parseInt(e.target.value, 10)))} placeholder="e.g., 60 (blank for none)" min="1" disabled={isSubmitting} />
                        <small className={styles.inputHint}>For each participant after they start. Leave blank for none.</small>
                    </div>

                    <div className={styles.markingSchemeContainer}>
                        {/* Marks per Correct, Negative Marking Enabled, Negative Marks - existing inputs unchanged */}
                        <div className={styles.formGroup}>
                            <label htmlFor="marksPerCorrect">Marks per Correct:</label>
                            <input type="number" id="marksPerCorrect" value={marksPerCorrect} onChange={(e) => setMarksPerCorrect(e.target.value === '' ? '' : parseFloat(e.target.value))} placeholder={`e.g., ${DEFAULT_MARKS_PER_CORRECT}`} min="0" step="0.1" required disabled={isSubmitting} />
                        </div>
                        <div className={styles.formGroup}>
                            <label htmlFor="negativeMarkingEnabled" className={styles.checkboxLabel}>
                                <input type="checkbox" id="negativeMarkingEnabled" checked={negativeMarkingEnabled} onChange={(e) => setNegativeMarkingEnabled(e.target.checked)} disabled={isSubmitting} className={styles.checkboxInput}/>
                                Enable Negative Marking
                            </label>
                        </div>
                        {negativeMarkingEnabled && (
                        <div className={styles.formGroup}>
                            <label htmlFor="negativeMarksPerIncorrect">Negative Marks:</label>
                            <input type="number" id="negativeMarksPerIncorrect" value={negativeMarksPerIncorrect} onChange={(e) => setNegativeMarksPerIncorrect(e.target.value === '' ? '' : parseFloat(e.target.value))} placeholder={`e.g., ${DEFAULT_NEGATIVE_MARKS_PER_INCORRECT}`} min="0" step="0.1" required={negativeMarkingEnabled} disabled={isSubmitting}/>
                            <small className={styles.inputHint}>Value to deduct (e.g., 1 for -1 mark).</small>
                        </div>
                        )}
                    </div>
                    <div className={`${styles.formGroup} ${styles.timeInputs}`}>
                        {/* Start Time, End Time DatePickers - existing inputs unchanged */}
                        <div>
                            <label htmlFor="startTime"><FaCalendarAlt /> Optional Start Time:</label>
                            <DatePicker selected={startTime} onChange={(date: Date | null) => setStartTime(date)} selectsStart startDate={startTime} endDate={endTime} minDate={new Date()} showTimeSelect timeFormat="HH:mm" timeIntervals={15} timeCaption="Time" dateFormat="MMMM d, yyyy h:mm aa" placeholderText="Session can start anytime" isClearable wrapperClassName={styles.datePickerWrapper} className={styles.datePickerInput} disabled={isSubmitting} id="startTime"/>
                            <small className={styles.inputHint}>When participants can start.</small>
                        </div>
                        <div>
                            <label htmlFor="endTime"><FaLock /> Optional Entry Deadline:</label>
                            <DatePicker selected={endTime} onChange={(date: Date | null) => setEndTime(date)} selectsEnd startDate={startTime} endDate={endTime} minDate={startTime || new Date()} showTimeSelect timeFormat="HH:mm" timeIntervals={15} timeCaption="Time" dateFormat="MMMM d, yyyy h:mm aa" placeholderText="No entry deadline" isClearable wrapperClassName={styles.datePickerWrapper} className={styles.datePickerInput} disabled={isSubmitting} id="endTime"/>
                            <small className={styles.inputHint}>Latest time to join/start.</small>
                        </div>
                    </div>
                    {timeValidationError && <p className={`${styles.errorMessage} ${styles.timeError}`}>{timeValidationError}</p>}
                    <div className={styles.formGroup}>
                         <label htmlFor="resultVisibility">Result Visibility:</label>
                         <select id="resultVisibility" value={resultVisibility} onChange={(e) => setResultVisibility(e.target.value as ResultVisibility)} disabled={isSubmitting}>
                             <option value="Self Only Immediate">Show My Results Immediately</option>
                             <option value="Self Only After End Time">Show My Results After Deadline</option>
                             <option value="Leaderboard After End Time">Show Leaderboard After Deadline</option>
                             <option value="Full Review After End Time">Allow Full Review After Deadline</option>
                         </select>
                         <small className={styles.inputHint}>Controls what participants see. Requires 'Entry Deadline' for timed visibility.</small>
                    </div>
                </div>

                <div className={styles.formSection}>
                    <h2>2. Question Source</h2>
                    {/* Source Type Selector, OfficialExamSelector, CustomExamInput - existing inputs unchanged */}
                    <div className={styles.sourceTypeSelector}>
                        <button type="button" onClick={() => handleSourceTypeButtonClick('official')} className={sourceMode === 'official' ? styles.active : ''} disabled={isSubmitting}>Official Exam</button>
                        <button type="button" onClick={() => handleSourceTypeButtonClick('custom')} className={(sourceMode === 'upload' || sourceMode === 'paste') ? styles.active : ''} disabled={isSubmitting}>Custom JSON</button>
                    </div>
                    <div className={styles.sourceInputArea}>
                        {sourceMode === 'official' && (
                            isLoadingConfig ? <Spinner text="Loading exam list..." /> :
                            configError ? <p className={styles.errorMessage}>{configError}</p> :
                            <OfficialExamSelector availableExams={availableExams} isDisabled={false} onExamSelected={handleOfficialExamSelected} onSelectionCleared={handleChildInputCleared} />
                        )}
                        {(sourceMode === 'upload' || sourceMode === 'paste') && (
                            <CustomExamInput isDisabled={false} onFileValidated={handleCustomFileValidated} onPasteValidated={handleCustomPasteValidated} onInputCleared={handleChildInputCleared} onError={handleChildValidationError}/>
                        )}
                        {sourceMode === 'none' && !isLoadingConfig && <p className={styles.selectSourcePrompt}>Please select a question source type.</p>}
                        {childValidationError && <p className={styles.errorMessage}>{childValidationError}</p>}
                    </div>
                </div>
                
                <div className={styles.formSection}>
                    <h2>3. Session Integrity (Optional)</h2>
                    <div className={styles.formGroup}>
                        {/* *** MODIFIED: Gated by perkFeatures.canEnableExamMonitoring *** */}
                        <label
                            htmlFor="monitoringEnabled"
                            className={`${styles.checkboxLabel} ${isLoadingPerks || !perkFeatures.canEnableExamMonitoring ? styles.disabledLabel : ''}`}
                            title={
                                isLoadingPerks ? "Loading feature availability..." :
                                !perkFeatures.canEnableExamMonitoring ? `Basic Anti-Cheating Monitoring is available for '${currentTier.name === 'free' ? 'paid tiers' : 'higher tiers'}'. (Your current tier: ${currentTier.name})` :
                                "Enable basic monitoring for tab focus, copy/paste, and restricted key presses."
                            }
                        >
                            <input
                                type="checkbox" id="monitoringEnabled"
                                checked={monitoringEnabled}
                                onChange={(e) => setMonitoringEnabled(e.target.checked)}
                                disabled={isSubmitting || isLoadingPerks || !perkFeatures.canEnableExamMonitoring}
                                className={styles.checkboxInput}
                            />
                            Enable Basic Anti-Cheating Monitoring <FaEye style={{marginLeft: '4px'}} />
                        </label>
                        <small className={styles.inputHint}>
                            Activates tab/window focus tracking, copy/paste restrictions, and logging of keys like PrintScreen.
                            {/* *** MODIFIED: Show premium hint if perk not available *** */}
                            {!isLoadingPerks && !perkFeatures.canEnableExamMonitoring && (
                                <span style={{ display: 'block', color: 'var(--warning-color, orange)', marginTop: '4px' }}>
                                    (Premium Feature - Requires Pro tier or higher)
                                </span>
                            )}
                        </small>
                    </div>
                </div>

                <div className={styles.formSection}>
                    <h2>4. Geolocation Restriction (Advanced)</h2>
                    <div className={styles.formGroup}>
                        {/* *** MODIFIED: Gated by perkFeatures.canEnableAdvancedMonitoring *** */}
                        <label
                            htmlFor="geoRestrictionEnabled"
                            className={`${styles.checkboxLabel} ${isLoadingPerks || !perkFeatures.canEnableAdvancedMonitoring ? styles.disabledLabel : ''}`}
                            title={
                                isLoadingPerks ? "Loading feature availability..." :
                                !perkFeatures.canEnableAdvancedMonitoring ? `Geolocation Restriction is available for the '${currentTier.name === 'free' || currentTier.name === 'Basic' || currentTier.name === 'Pro' ? 'Elite tier' : 'higher tiers'}'. (Your current tier: ${currentTier.name})` :
                                "Restrict exam access to participants within a geographic area."
                            }
                        >
                            <input
                                type="checkbox" id="geoRestrictionEnabled"
                                checked={geoRestrictionEnabled}
                                onChange={(e) => {
                                    setGeoRestrictionEnabled(e.target.checked);
                                    if (!e.target.checked) { setIsLocationPickerReady(false); setGeoLatitude(''); setGeoLongitude(''); setGeoRadius('500'); }
                                }}
                                disabled={isSubmitting || isLoadingPerks || !perkFeatures.canEnableAdvancedMonitoring}
                                className={styles.checkboxInput}
                            />
                            Restrict by Geographic Location <FaMapMarkerAlt style={{marginLeft: '4px'}} />
                        </label>
                        <small className={styles.inputHint}>
                            Participants must be within the specified radius of a central point to join. Optimized for smartphones.
                            {/* *** MODIFIED: Show premium hint if perk not available *** */}
                            {!isLoadingPerks && !perkFeatures.canEnableAdvancedMonitoring && (
                                <span style={{ display: 'block', color: 'var(--warning-color, orange)', marginTop: '4px' }}>
                                     (Premium Feature - Requires Elite tier)
                                </span>
                            )}
                        </small>
                    </div>
                    {/* GeoLocation Inputs (Latitude, Longitude, Radius), Iframe - existing inputs unchanged but only show if geoRestrictionEnabled */}
                    {geoRestrictionEnabled && perkFeatures.canEnableAdvancedMonitoring && (
                    <>
                        <div className={styles.geolocationInputs}>
                            <div className={styles.formGroup}>
                                <label htmlFor="geoLatitude">Center Latitude:</label>
                                <input type="number" id="geoLatitude" value={geoLatitude}
                                    onChange={(e) => setGeoLatitude(e.target.value)}
                                    placeholder="e.g., 34.0522" step="any" required={geoRestrictionEnabled} disabled={isSubmitting} />
                            </div>
                            <div className={styles.formGroup}>
                                <label htmlFor="geoLongitude">Center Longitude:</label>
                                <input type="number" id="geoLongitude" value={geoLongitude}
                                    onChange={(e) => setGeoLongitude(e.target.value)}
                                    placeholder="e.g., -118.2437" step="any" required={geoRestrictionEnabled} disabled={isSubmitting} />
                            </div>
                            <div className={styles.formGroup}>
                                <label htmlFor="geoRadius">Allowed Radius (meters):</label>
                                <input type="number" id="geoRadius" value={geoRadius}
                                    onChange={(e) => setGeoRadius(e.target.value)}
                                    placeholder="e.g., 1000" min="50" max="50000" step="50" required={geoRestrictionEnabled} disabled={isSubmitting} />
                                <small className={styles.inputHint}>Min: 50m, Max: 50km.</small>
                            </div>
                            <div className={styles.hostLocationAction}>
                                <button
                                    type="button"
                                    onClick={fetchHostCurrentLocation}
                                    disabled={isFetchingHostLocation || isSubmitting}
                                    className={styles.fetchLocationButton}
                                >
                                    {isFetchingHostLocation ? (
                                        <Spinner size="0.9em" />
                                    ) : (
                                        <FaMapMarkerAlt style={{ marginRight: '8px' }} />
                                    )}
                                    Use My Current Location
                                </button>
                                {hostLocationError && <p className={`${styles.errorMessage} ${styles.inlineError}`}>{hostLocationError}</p>}
                            </div>
                        </div>
                        <div className={styles.locationPickerContainer}>
                            <iframe ref={iframeRef} src={LOCATION_PICKER_URL} className={styles.locationPickerIframe} title="Location Picker Map" />
                            {!isLocationPickerReady && ( <div className={styles.iframeLoadingPlaceholder}><Spinner text="Initializing Map Tool..." /></div> )}
                        </div>
                    </>
                    )}
                </div>
                
                <div className={styles.submissionArea}>
                    {setupError && <p className={styles.errorMessage}>{setupError}</p>}
                    <button type="submit" disabled={!canCreateSession || isSubmitting} className={styles.createButton}>
                        {isSubmitting ? <Spinner size="1em" /> : 'Create Session'}
                    </button>
                    {/* *** MODIFIED: Update limitReached message *** */}
                    {limitReached && !isSubmitting && (
                        <p className={`${styles.infoMessage} ${styles.limitError}`}>
                            <FaInfoCircle /> You've reached the limit of {sessionLimit} active/pending hosted sessions for your current tier ({currentTier?.name || 'Free'}).
                        </p>
                    )}
                    {isLoadingPerks && <p className={styles.infoMessage}><Spinner size="0.9em"/> Checking session limits...</p>}
                    {!limitReached && !canCreateSession && !isSubmitting && !(isLoadingPerks || isLoadingCount) && !countError && (
                        <p className={`${styles.infoMessage}`}>
                            <FaInfoCircle /> Complete required fields and ensure selections are valid.
                        </p>
                    )}
                </div>
            </form>
            }
        </div>
    );
};

export default GroupExamSetupPage;
```

---

## pages\GroupExamSharePage


### pages\GroupExamSharePage\GroupExamSharePage.module.scss

```scss
// src/pages/GroupExamSharePage/GroupExamSharePage.module.scss
@import '../../styles/variables';
@import '../../styles/mixins';

.sharePage {
    padding: $spacer * 2 0 $spacer * 3 0;
    max-width: 700px; // Limit width
    margin: $spacer * 2 auto; // Add top margin and center

    h1 {
        text-align: center;
        margin-bottom: $spacer * 0.5;
        color: $success-color; // Use success color for confirmation
        display: flex;
        align-items: center;
        justify-content: center;
        gap: $spacer;
    }

    .sessionTitle {
        text-align: center;
        font-size: $font-size-base * 1.1;
        color: $text-muted;
        margin-bottom: $spacer * 2.5;
        span {
            font-weight: 600;
            color: $dark-color;
        }
    }
}

.shareBox {
    background-color: lighten($primary-color, 55%); // Light blue background
    border: 1px solid lighten($primary-color, 40%);
    padding: $spacer * 2;
    border-radius: $border-radius-lg;
    text-align: center;
    margin-bottom: $spacer * 2;

    h2 {
        margin-top: 0;
        margin-bottom: $spacer;
        font-size: $font-size-base * 1.2;
        font-weight: 600;
        color: darken($primary-color, 10%);
    }
}

.sessionIdContainer {
    display: flex;
    align-items: center;
    justify-content: center;
    background-color: $white-color;
    border: 1px solid $border-color;
    padding: $spacer * 0.75;
    border-radius: $border-radius;
    margin-bottom: $spacer * 0.5;
    box-shadow: inset 0 1px 3px rgba($black-color, 0.06);
}

.sessionId { // Base style for ID/URL text
    font-family: monospace;
    font-weight: 500; // Less bold than before maybe
    color: $dark-color;
    flex-grow: 1;
    margin-right: $spacer;
    word-break: break-all;
    text-align: left; // Align URL left
}

.urlDisplay { // Specific styles for the URL display
    font-size: $font-size-base * 0.95; // Slightly smaller for URL
    color: $link-color; // Make it look like a link
    letter-spacing: 0; // Normal spacing for URL
}

.shareDivider { // Style for 'OR' text divider
    text-align: center;
    color: $text-muted;
    font-weight: 500;
    margin: $spacer 0;
    font-size: $font-size-base * 0.9;
    text-transform: uppercase;
}


.shareButton { // Style for the Web Share button
    @include button-variant($info-color, $info-color); // Example: Use info color
    width: 100%; // Full width button
    max-width: 300px; // Max width
    margin: 0 auto $spacer * 1.5 auto; // Center and add margin below
    padding: $spacer * 0.7 $spacer * 1.5;
    font-size: $font-size-base;

    svg { margin-right: $spacer * 0.5; }

    &:disabled {
        opacity: 0.6;
        cursor: not-allowed;
    }
}

.shareInstructionsAlt { // Instructions for manual ID entry
    margin-top: $spacer * 1.5;
    font-size: $font-size-base * 0.9;
    color: darken($text-muted, 10%);
    margin-bottom: $spacer * 0.5;
}

.sessionIdDisplay { // Style for displaying the raw ID below share options
    font-family: monospace;
    font-size: $font-size-base * 1.4; // Larger raw ID display
    font-weight: bold;
    color: $dark-color;
    letter-spacing: 1px;
    background-color: lighten($light-color, 3%);
    padding: $spacer * 0.5 $spacer;
    border-radius: $border-radius-sm;
    border: 1px solid $border-color;
    display: inline-block; // Make it fit content
    margin-bottom: $spacer * 1.5;
}
.shareFallbackText {
    font-size: $font-size-base * 0.8;
    color: $text-muted;
    text-align: center;
    margin-top: -$spacer * 0.5; // Adjust spacing if needed
    margin-bottom: $spacer * 1.5;
}

.copyButton {
    @include button-variant(transparent, $secondary-color);
    color: $secondary-color;
    padding: $spacer * 0.5 $spacer;
    font-size: $font-size-base * 1.2; // Slightly larger icon
    line-height: 1; // Prevent extra height
    flex-shrink: 0;

    &:hover {
        background-color: $background-color-hover;
        color: $primary-color;
        border-color: $primary-color;
    }

    svg {
         display: block; // Remove potential spacing issues
    }
}

.shareInstructions {
    font-size: $font-size-base * 0.95;
    color: $text-muted;
    line-height: 1.6;
    margin-bottom: $spacer * 0.5; // Less margin below main instructions
}

.infoMessage {
    font-size: $font-size-base * 0.9;
    color: lighten($text-muted, 5%);
     background-color: rgba($primary-color, 0.1); // Subtle bg hint
     padding: $spacer * 0.5 $spacer;
     border-radius: $border-radius-sm;
     display: inline-flex;
     align-items: center;
     gap: $spacer * 0.5;
     margin-top: $spacer;
     svg { color: $primary-color; }
}

.participantSection {
    background-color: $component-bg;
    border: 1px solid $border-color;
    border-radius: $border-radius-lg;
    padding: $spacer * 1.5 $spacer * 2;
    margin-top: $spacer * 2; // Space above participant list
    box-shadow: $box-shadow-sm;


    h3 {
        margin-top: 0;
        margin-bottom: $spacer * 1.5;
        font-size: $font-size-base * 1.1;
        font-weight: 600;
        color: $dark-color;
        border-bottom: 1px solid $border-color;
        padding-bottom: $spacer * 0.75;
    }
}
.loadingState { // Style for initial loading
    text-align: center;
    padding: $spacer * 2 0;
    color: $text-muted;
    font-size: $font-size-base;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: $spacer * 0.5;
}

.noParticipants {
    color: $text-muted;
    font-style: italic;
    text-align: center;
     padding: $spacer 0;
}

.participantList {
    list-style: none;
    padding: 0;
    margin: 0 0 $spacer 0; // Remove bottom margin from ul directly
     max-height: 200px; // Limit height and make scrollable
     overflow-y: auto;

    li {
        padding: $spacer * 0.5 $spacer;
        border-bottom: 1px dotted lighten($border-color, 5%);
        display: flex; // Use flex for alignment
        justify-content: space-between; // Space out name and status
        align-items: center;
        font-size: $font-size-base;

        &:last-child {
            border-bottom: none;
        }
        span:first-child { // Target the name/icon span
            display: flex;
            align-items: center;
            gap: $spacer * 0.6; // Space between icon and name
        }
    }
}

.statusIcon {
    font-size: $font-size-base * 0.9; // Slightly smaller icon
    flex-shrink: 0;

    // Status colors for icons
    &.joined { color: $secondary-color; }
    &.started { color: $info-color; }
    &.completed { color: $success-color; }
}

.participantStatus {
    font-size: $font-size-base * 0.85;
    color: $text-muted;
    font-style: italic;
    margin-left: $spacer;
    font-weight: 500;
    min-width: 100px; // Give status space
    text-align: right;
    text-transform: capitalize; // Nicer display 'Joined', 'Completed'

     // Status colors for text (optional, use sparingly for readability)
     &.joined { color: $text-muted; }
     &.started { color: $info-color; }
     &.completed { color: $success-color; }

     // Mobile view adjustments if needed
     @media (max-width: map-get($grid-breakpoints, sm)) {
        min-width: 80px; // Less space on small screens
        font-size: $font-size-base * 0.8; // Smaller status text
     }
}

.participantCount {
    margin-top: $spacer;
    padding-top: $spacer;
    border-top: 1px solid $border-color;
    text-align: right;
    font-weight: 500;
    color: $text-muted;
    font-size: $font-size-base * 0.95;
}

.errorMessage { // Shared error style
    color: $danger-color;
    text-align: center;
    font-weight: 500;
     padding: $spacer 0;
}

.actions {
    margin-top: $spacer * 2.5;
    display: flex;
    justify-content: center;
    gap: $spacer * 1.5;
    flex-wrap: wrap;
}

.actionButton { // Reusable action button style
     @include button-variant($secondary-color, $secondary-color);
     padding: $spacer * 0.8 $spacer * 1.8;
     font-size: $font-size-base;
     font-weight: 500;
     text-decoration: none;
     min-width: 180px;

     &:hover {
         text-decoration: none;
     }
     &.primary {
        @include button-variant($primary-color, $primary-color);
     }
      &:disabled {
          opacity: 0.6;
          cursor: not-allowed;
      }
}

// Spinner animation (reuse if needed)
@keyframes spin {
  0% { transform: rotate(0deg); }
  100% { transform: rotate(360deg); }
}
.spin-icon {
  display: inline-block;
  animation: spin 1s linear infinite;
  margin-right: $spacer * 0.5;
  margin-bottom: -2px;
}

.emptyStateContainer { 
    padding: $spacer * 3 0;
    text-align: center;
    color: $text-muted;
    border: 1px dashed $border-color; // Optional dashed border
    border-radius: $border-radius;
    margin: $spacer 0; // Add some margin
    background-color: lighten($light-color, 3%); // Subtle background
}

.emptyStateIcon {
    color: $primary-color; // Or a muted color
    margin-bottom: $spacer;
    opacity: 0.7;
}

.emptyStateText {
    font-size: $font-size-base * 1.05;
    font-weight: 500;
    margin-bottom: $spacer * 0.5;
     color: darken($text-muted, 10%);
}

.emptyStateSubtext {
    font-size: $font-size-base * 0.9;
    margin-bottom: 0;
}
```

---

### pages\GroupExamSharePage\GroupExamSharePage.tsx

```typescript
// src/pages/GroupExamSharePage/GroupExamSharePage.tsx
import React, { useState, useEffect, useMemo } from 'react';
import { useParams, useLocation, Link } from 'react-router-dom';
import styles from './GroupExamSharePage.module.scss';
import { toast } from 'react-toastify';
import { FaClipboard, FaClipboardCheck, FaUsers, FaInfoCircle, FaUserCheck, FaUserClock, FaShareAlt } from 'react-icons/fa';
// Import Firestore listener capabilities
import { db } from '../../services/firebase'; // Direct db reference
import { collection, query, onSnapshot, orderBy } from 'firebase/firestore'; // Import necessary functions
import { useAuth } from '../../contexts/AuthContext';
import { ParticipantData } from '../../types';
import Spinner from '../../components/Spinner/Spinner';

const GroupExamSharePage: React.FC = () => {
    const { sessionId } = useParams<{ sessionId: string }>();
    const location = useLocation();
    const { currentUser } = useAuth();

    const sessionName = location.state?.sessionName || 'Group Session';

    const [copied, setCopied] = useState(false);
    const [participants, setParticipants] = useState<(ParticipantData & { id: string })[]>([]);
    // Separate loading state: initial load vs subsequent updates
    const [isInitialLoading, setIsInitialLoading] = useState(true);
    const [error, setError] = useState<string | null>(null);

    // --- Construct the full join URL ---
    const joinUrl = useMemo(() => {
        if (!sessionId) return null;
        // Ensure this base URL is correct for your deployed app
        const baseUrl = window.location.origin; // Gets 'https://yourapp.com' or 'http://localhost:3000'
        return `${baseUrl}/group-exam/join?sessionId=${sessionId}`;
    }, [sessionId]);

    // --- Generate share text ---
    const shareText = useMemo(() => {
         return `Join my Examify group session "${sessionName}"! Session ID: ${sessionId}`;
    }, [sessionName, sessionId]);

    const shareData = useMemo(() => ({
        title: `Join Examify Session: ${sessionName}`,
        text: shareText,
        url: joinUrl || `https://examify.web.app` // Fallback URL if joinUrl isn't ready
    }), [sessionName, shareText, joinUrl]);

    // --- Setup Real-time Listener ---
    useEffect(() => {
        if (!sessionId || !currentUser) {
            // Handle missing data or auth state
            setError("Session ID missing or user not authenticated.");
            setIsInitialLoading(false);
            return;
        }

        ///console.log(`Setting up listener for session: ${sessionId}`);
        setIsInitialLoading(true);
        setError(null);

        // Reference the participants subcollection
        const participantsRef = collection(db, `groupExams/${sessionId}/participants`);
        const q = query(participantsRef, orderBy("joinedAt", "asc")); // Order consistently

        // Subscribe to real-time updates
        const unsubscribe = onSnapshot(q, (querySnapshot) => {
            //console.log("Participant snapshot received:", querySnapshot.size);
            const fetchedParticipants: (ParticipantData & { id: string })[] = [];
            querySnapshot.forEach((doc) => {
                // Note: Timestamp fields might need conversion if directly used as Date objects elsewhere
                fetchedParticipants.push({
                    id: doc.id, // Participant UID is the ID
                    ...(doc.data() as ParticipantData) // Cast data from Firestore
                });
            });
            setParticipants(fetchedParticipants);
            setIsInitialLoading(false); // Mark initial load complete after first snapshot
            setError(null); // Clear previous errors on successful update
        }, (err) => {
            // Handle errors during listening
            //console.error("Error listening to participants:", err);
            setError(err.message || "Could not load real-time participant data.");
            setIsInitialLoading(false); // Stop loading on error
            // Optionally display a toast notification
            toast.error("Error getting participant updates.");
        });

        // Cleanup function: Unsubscribe when component unmounts or sessionId changes
        return () => {
            //console.log(`Unsubscribing listener for session: ${sessionId}`);
            unsubscribe();
        };

    }, [sessionId, currentUser]); // Rerun effect if sessionId or user changes

    // --- Copy to Clipboard Handler ---
    const handleCopyToClipboard = () => {
        // Copy the URL instead of just the ID
        if (!joinUrl) {
            toast.error("Could not generate join link.");
            return;
        };
        
        navigator.clipboard.writeText(joinUrl)
            .then(() => {
                setCopied(true);
                toast.success("Join link copied to clipboard!");
                setTimeout(() => setCopied(false), 2500);
            })
            .catch(err => {
                //console.error('Failed to copy link: ', err);
                toast.error("Could not copy link. Please copy it manually.");
            });
    };

    // --- Web Share API Handler ---
    const handleWebShare = async () => {
        if (navigator.share && joinUrl) {
            try {
                await navigator.share(shareData);
               //console.log('Content shared successfully');
                toast.info("Shared successfully!");
            } catch (err: any) {
                //console.error('Error sharing:', err);
                // Don't show error toast for user cancellations (AbortError)
                if (err.name !== 'AbortError') {
                   toast.error(`Could not share: ${err.message}`);
                }
            }
        } else {
            // Fallback if Web Share API is not supported - maybe just copy the link?
            toast.warn("Web Share not supported by your browser. Link copied instead!");
            handleCopyToClipboard(); // Copy link as fallback
        }
    };

    // --- Render Logic ---

    // Combined Loading State (Initial Load)
    const isLoading = isInitialLoading && !error; // Show loading only initially or if error occurred during loading

    return (
        <div className={styles.sharePage}>
            <h1><FaUsers /> Session Created!</h1>
            <p className={styles.sessionTitle}>Session Name: <span>{sessionName}</span></p>

            <div className={styles.shareBox}>
                <h2>Share with Participants:</h2>
                
                {/* Option 1: Display Join Link and Copy Button */}
                <p className={styles.shareInstructions}>Share this link:</p>
                <div className={styles.sessionIdContainer}>
                    <span className={`${styles.sessionId} ${styles.urlDisplay}`}>
                        {joinUrl || 'Generating link...'}
                    </span>
                    <button
                        onClick={handleCopyToClipboard}
                        disabled={!joinUrl || copied}
                        className={styles.copyButton}
                        title="Copy Join Link"
                    >
                        {copied ? <FaClipboardCheck /> : <FaClipboard />}
                    </button>
                </div>

                {/* Divider */}
                <div className={styles.shareDivider}>OR</div>

                {/* Option 2: Share using Web Share API */}
                {typeof navigator.share === 'function' ? (
                    <button
                        onClick={handleWebShare}
                        disabled={!joinUrl}
                        className={`${styles.actionButton} ${styles.shareButton}`}
                        title="Share Session Link via apps"
                    >
                        <FaShareAlt /> Share via...
                    </button>
                ) : (
                    <p className={styles.shareFallbackText}>(Web Share not available in this browser)</p>
                )}

                {/* Display Session ID Separately */}
                <p className={styles.shareInstructionsAlt}>Participants can also join manually using the ID:</p>
                <p className={styles.sessionIdDisplay}>{sessionId}</p>

                <p className={styles.infoMessage}>
                    <FaInfoCircle /> Participants need an Examify account to join. The exam starts for them immediately upon joining unless a specific start time is set.
                </p>
            </div>

            {/* Participant List Section */}
            <div className={styles.participantSection}>
                <h3>Participants Joined:</h3>
                {isLoading && <div className={styles.loadingState}><Spinner text="Loading initial participant list..." /></div>}
                {error && <p className={styles.errorMessage}>{error}</p>}

                {!isLoading && !error && participants.length === 0 && (
                   <div className={styles.emptyStateContainer}>
                       <FaUserClock size={24} className={styles.emptyStateIcon} />
                       <p className={styles.emptyStateText}>Waiting for participants...</p>
                       <p className={styles.emptyStateSubtext}>Share the Session ID above. Participants will appear here live as they join.</p>
                   </div>
                )}

                {!isLoading && !error && participants.length > 0 && (
                    <ul className={styles.participantList}>
                        {participants.map(p => (
                            <li key={p.id}>
                                <span>
                                    <FaUserCheck className={`${styles.statusIcon} ${styles[p.status]}`} />
                                    {p.displayName || `User...${p.id.substring(p.id.length - 6)}`}
                                </span>
                                <span className={`${styles.participantStatus} ${styles[p.status]}`}>
                                    {p.status}
                                    {p.status === 'completed' && p.score !== undefined && ` (${p.score?.toFixed(1)} / ${p.maxScore?.toFixed(1)})`}
                                </span>
                            </li>
                        ))}
                    </ul>
                )}
                <div className={styles.participantCount}>
                    Total Joined: {participants.length}
                </div>
            </div>

            {/* Action Buttons */}
            <div className={styles.actions}>
                <Link to="/group-exam/dashboard" className={`${styles.actionButton} ${styles.secondary}`}>Manage Sessions
                </Link>
                <Link to="/select-exam" className={`${styles.actionButton} ${styles.primary}`}>
                    Go Back to Exam Selection
                </Link>
            </div>
        </div>
    );
};

export default GroupExamSharePage;
```

---

## pages\GroupExamWaitingPage


### pages\GroupExamWaitingPage\GroupExamWaitingPage.module.scss

```scss
// src/pages/GroupExamWaitingPage/GroupExamWaitingPage.module.scss
@import '../../styles/variables';
@import '../../styles/mixins';

.waitingPage {
    padding: $spacer * 2 0 $spacer * 3 0;
    max-width: 650px; // Limit width
    margin: $spacer * 3 auto; // Add top margin and center

    h1 {
        text-align: center;
        margin-bottom: $spacer * 0.75;
        color: $primary-color;
        display: flex;
        align-items: center;
        justify-content: center;
        gap: $spacer * 0.75;
        font-size: $h2-font-size * 0.9; // Slightly smaller H1
    }

    .sessionTitle {
        text-align: center;
        font-size: $font-size-base * 1.1;
        color: $text-muted;
        margin-bottom: $spacer * 3;
        span {
            font-weight: 600;
            color: $dark-color;
        }
    }
}

.statusBox {
    background-color: $component-bg;
    padding: $spacer * 2 $spacer * 2.5;
    border: 1px solid $border-color;
    border-radius: $border-radius-lg;
    box-shadow: $box-shadow-md;
    text-align: center;
    min-height: 200px; // Ensure some height for loading/error
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    gap: $spacer * 1; // Gap between elements inside the box

    h2 {
        font-size: $font-size-base * 1.2;
        color: $text-muted;
        margin-top: 0;
        margin-bottom: $spacer * 0.5;
        font-weight: 500;
    }

    // Specific error styling
    &.errorBox {
        background-color: lighten($danger-color, 50%);
        border-color: lighten($danger-color, 40%);
        h2 { color: $danger-color; }
        p { color: darken($danger-color, 10%); }
    }
}

.startTimeDisplay {
    font-size: $font-size-base * 1.3;
    font-weight: 600;
    color: $dark-color;
    margin-bottom: $spacer * 1.5;
}

.countdown {
    font-size: $font-size-base * 1.1;
    color: $text-muted;
    span {
        font-weight: bold;
        font-size: $font-size-base * 1.4; // Larger countdown time
        color: $primary-color;
        margin-left: $spacer * 0.5;
        font-family: monospace; // Monospace for consistent timer width
        min-width: 100px; // Ensure some width
        display: inline-block;
    }
}
.monitoringReminder {
    font-size: $font-size-base * 0.85;
    color: $text-muted;
    background-color: lighten($warning-color, 48%);
    border: 1px solid lighten($warning-color, 35%);
    padding: map-get($spacers, 2);
    border-radius: $border-radius;
    text-align: center;
    margin-top: map-get($spacers, 3);
    display: inline-flex;
    align-items: center;
    gap: map-get($spacers, 2);
    svg { color: $warning-color; }
  }
// --- Notification Styles ---
.notificationButton {
    @include button-variant(lighten($info-color, 45%), lighten($info-color, 25%)); // Light info button
    color: darken($info-color, 15%);
    padding: $spacer * 0.5 $spacer * 1.2;
    font-size: $font-size-base * 0.9;
    font-weight: 500;
    border: 1px solid lighten($info-color, 30%);
    display: inline-flex;
    align-items: center;
    gap: $spacer * 0.5;
    margin-top: $spacer; // Space above button

    &:hover {
        background-color: lighten($info-color, 40%);
    }
    svg { font-size: $font-size-base; }
}

.notificationDenied {
    font-size: $font-size-base * 0.85;
    color: $text-muted;
    font-style: italic;
    margin-top: $spacer;
    background-color: lighten($warning-color, 45%);
    padding: $spacer * 0.3 $spacer * 0.8;
    border-radius: $border-radius-sm;
}

.startingNow {
    font-size: $font-size-base * 1.1;
    font-weight: 500;
    color: $success-color;
     display: inline-flex;
     align-items: center;
     gap: $spacer * 0.5;
}

.refreshButton {
    @include button-variant(transparent, $border-color);
    color: $text-muted;
    padding: $spacer * 0.5 $spacer * 1;
    font-size: $font-size-base * 0.9;
    margin-top: $spacer * 1.5; // Space above refresh button
     display: inline-flex;
     align-items: center;
     gap: $spacer * 0.5;

    &:hover {
         background-color: $background-color-hover;
         color: $primary-color;
         border-color: $primary-color;
    }
     svg { font-size: $font-size-base * 1; }
}


.infoMessage {
    margin-top: $spacer * 2;
    text-align: center;
    font-size: $font-size-base * 0.9;
    color: lighten($text-muted, 5%);
    background-color: lighten($info-color, 50%);
    padding: $spacer * 0.75 $spacer * 1.5;
    border-radius: $border-radius;
    display: inline-flex; // Use inline-flex for centering text/icon properly within block
    align-items: center;
    justify-content: center; // Center content if block
    gap: $spacer * 0.5;
     max-width: 90%;
     display: flex; // Use flex to allow centering within the page
     margin-left: auto;
     margin-right: auto;
    svg { color: $info-color; }
}

// Error button style (if using specific button in error state)
.actionButton {
     @include button-variant($secondary-color, $secondary-color);
     padding: $spacer * 0.7 $spacer * 1.5;
     margin-top: $spacer;
}


// Reusable spinner animation
@keyframes spin {
  0% { transform: rotate(0deg); }
  100% { transform: rotate(360deg); }
}
.spin-icon {
  display: inline-block;
  animation: spin 1.5s linear infinite;
  color: $primary-color; // Or adapt color based on context
}
```

---

### pages\GroupExamWaitingPage\GroupExamWaitingPage.tsx

```typescript
// src/pages/GroupExamWaitingPage/GroupExamWaitingPage.tsx
import React, { useState, useEffect, useCallback, useMemo, useRef } from 'react';
import { useParams, useNavigate } from 'react-router-dom';
import styles from './GroupExamWaitingPage.module.scss'; // Create this SCSS file next
import { getGroupExam } from '../../services/firestoreService';
import { GroupExam } from '../../types';
import { useAuth } from '../../contexts/AuthContext';
import { toast } from 'react-toastify';
import { FaClock, FaInfoCircle, FaRedo, FaBell, FaEye } from 'react-icons/fa';
import { formatTimestamp } from '../../utils/formatters'; // Reuse formatter
import Spinner from '../../components/Spinner/Spinner';

// Helper to calculate time difference
const calculateTimeRemaining = (targetTime: Date | null): number | null => {
    if (!targetTime) return null;
    const now = new Date().getTime();
    const target = targetTime.getTime();
    const diff = target - now; // Difference in milliseconds
    return diff > 0 ? Math.max(0, diff) : 0; // Return remaining ms or 0 if past
};

// Helper to format milliseconds into H:M:S or M:S etc.
const formatMilliseconds = (ms: number): string => {
    if (ms <= 0) return '0s';

    let seconds = Math.floor(ms / 1000);
    let minutes = Math.floor(seconds / 60);
    let hours = Math.floor(minutes / 60);

    seconds = seconds % 60;
    minutes = minutes % 60;

    let str = '';
    if (hours > 0) str += `${hours}h `;
    if (minutes > 0) str += `${minutes}m `;
    if (seconds >= 0) str += `${seconds}s`; // Always show seconds if minutes/hours are 0

    return str.trim();
};

const NOTIFICATION_THRESHOLD_MS = 60 * 1000; // Notify 1 minute before start
const NOTIFICATION_TITLE = "Exam Session Starting Soon!";

const GroupExamWaitingPage: React.FC = () => {
    const { sessionId } = useParams<{ sessionId: string }>();
    const navigate = useNavigate();
    const { currentUser, isLoading: isAuthLoading } = useAuth();

    const [groupExam, setGroupExam] = useState<GroupExam | null>(null);
    const [isLoading, setIsLoading] = useState(true);
    const [error, setError] = useState<string | null>(null);
    const [timeRemainingMs, setTimeRemainingMs] = useState<number | null>(null);
    const [notificationPermission, setNotificationPermission] = useState(Notification.permission);
    const notificationShownRef = useRef(false); // Ref to track if notification was already shown

    const startTimeDate = useMemo(() => {
        if (!groupExam?.startTime) return null;
        // Convert Firestore Timestamp (or potential Date from type change) to JS Date
        return groupExam.startTime instanceof Date
            ? groupExam.startTime
            : (groupExam.startTime as any)?.toDate ? (groupExam.startTime as any).toDate() : null;
    }, [groupExam]);

    // --- Request Notification Permission ---
    const requestNotificationPermission = useCallback(() => {
        if (!("Notification" in window)) {
            //console.warn("This browser does not support desktop notification");
            return;
        }
        // Don't ask if permission already granted or denied
        if (Notification.permission === 'granted' || Notification.permission === 'denied') {
            setNotificationPermission(Notification.permission); // Update state just in case
            return;
        }

        Notification.requestPermission().then((permission) => {
            //console.log("Notification permission:", permission);
            setNotificationPermission(permission); // Update state with user's choice
            if (permission === 'granted') {
                toast.success("Notifications enabled!");
            } else if (permission === 'denied') {
                toast.warn("Notifications blocked. You won't be reminded when the session starts.");
            }
        });
    }, []);

    // Ask for permission when component mounts if not already set
    useEffect(() => {
        if (notificationPermission === 'default') {
            // Maybe wait a second or two before asking?
            // setTimeout(requestNotificationPermission, 2000);
            // Or ask immediately:
            // requestNotificationPermission();
            // Let's add a button instead for better UX
        }
    }, [notificationPermission, requestNotificationPermission]);

    // Fetch Session Details
    const fetchSessionDetails = useCallback(async () => {
         if (!sessionId || !currentUser) {
             // This shouldn't happen if protected route is used, but handle anyway
             setError("Session ID missing or user not logged in.");
             setIsLoading(false);
             return;
         }
         setIsLoading(true);
         setError(null);
         try {
             const session = await getGroupExam(sessionId);
             if (!session) {
                 throw new Error("Session not found.");
             }
             // Crucially, check if it even HAS a start time
             if (!session.startTime) {
                 //console.log("Session has no start time, attempting to navigate directly.");
                 navigate(`/group-exam/session/${sessionId}`, { replace: true }); // Go straight to exam if no start time
                 return; // Stop processing here
             }

             setGroupExam(session);
         } catch (err: any) {
             setError(err.message || "Failed to load session details.");
             toast.error(err.message || "Failed to load session details.");
         } finally {
            // Don't set isLoading false here yet, wait for timer effect
         }
    }, [sessionId, currentUser, navigate]);

    // Effect to fetch data on mount
     useEffect(() => {
        if (!isAuthLoading && currentUser) {
             fetchSessionDetails();
        } else if (!isAuthLoading && !currentUser) {
            navigate('/select-exam', {replace: true, state: { message: "Please log in."}});
        }
    }, [sessionId, currentUser, isAuthLoading, fetchSessionDetails, navigate]);

    // Effect for Countdown Timer & Navigation Check with Notification
    useEffect(() => {
        if (!startTimeDate) {
            if (!isLoading) setIsLoading(false); // If no start time after load attempt, stop loading
            return; // No timer needed if no start time
        }

        const intervalId = setInterval(() => {
            const remaining = calculateTimeRemaining(startTimeDate);
            setTimeRemainingMs(remaining);
            setIsLoading(false); // Stop initial loading indicator once timer starts/checks

            if (remaining !== null) {
                // Check if notification should be shown
                if (remaining <= NOTIFICATION_THRESHOLD_MS && // Within threshold
                   remaining > 0 &&                     // Not past start time yet
                   !notificationShownRef.current &&     // Notification not shown yet
                   notificationPermission === 'granted') // Permission granted
                {
                    //console.log("Showing start notification");
                    try {
                       new Notification(NOTIFICATION_TITLE, {
                            body: `"${groupExam?.sessionName || 'Your Session'}" will begin in about ${formatMilliseconds(remaining)}.`,
                            icon: '/logo192.png' // Optional: Path to your app icon
                        });
                        notificationShownRef.current = true; // Mark as shown
                    } catch(err) {
                        //console.error("Error showing notification:", err);
                        // Prevent repeated attempts if showing fails
                        notificationShownRef.current = true;
                    }
                }

                // Check if start time reached for navigation
                if (remaining <= 0) {
                    clearInterval(intervalId); // Stop timer
                    //console.log("Start time reached, navigating to session...");
                    toast.info("Session starting!");
                    navigate(`/group-exam/session/${sessionId}`, { replace: true });
                }
            }
        }, 1000); // Update every second

        // Initial calculation
        const initialRemaining = calculateTimeRemaining(startTimeDate);
        setTimeRemainingMs(initialRemaining);
        setIsLoading(false);

        // Cleanup interval on component unmount or if startTime changes
        return () => clearInterval(intervalId);
// eslint-disable-next-line
    }, [startTimeDate, sessionId, navigate, notificationPermission, groupExam?.sessionName]); // Dependencies

    // --- Render Logic ---

    if (isLoading || isAuthLoading) {
        return (
            <div className={styles.waitingPage}>
                <div className={styles.statusBox}>
                <Spinner size={30} />
                    <p>Loading session information...</p>
                </div>
            </div>
        );
    }

    if (error) {
        return (
            <div className={styles.waitingPage}>
                 <div className={`${styles.statusBox} ${styles.errorBox}`}>
                     <h2>Error</h2>
                    <p>{error}</p>
                    <button onClick={() => navigate('/select-exam', { replace: true })} className={styles.actionButton}>
                         Back to Selection
                    </button>
                 </div>
            </div>
        );
    }

    if (!groupExam || !startTimeDate) {
         // Should generally be caught by error or loading states, but good fallback
         return (
            <div className={styles.waitingPage}>
                 <div className={styles.statusBox}>
                    <p>Session details are unavailable.</p>
                     <button onClick={() => navigate('/select-exam', { replace: true })} className={styles.actionButton}>
                          Back to Selection
                     </button>
                 </div>
            </div>
        );
    }

    // --- Main Waiting Display ---
    return (
        <div className={styles.waitingPage}>
            <h1><FaClock /> Waiting for Session to Start</h1>
            <p className={styles.sessionTitle}>Session: <span>{groupExam.sessionName}</span></p>

            <div className={styles.statusBox}>
                <h2>Scheduled Start Time:</h2>
                <p className={styles.startTimeDisplay}>{formatTimestamp(startTimeDate)}</p>

                {timeRemainingMs !== null && timeRemainingMs > 0 && (
                    <div className={styles.countdown}>
                         Starts in: <span>{formatMilliseconds(timeRemainingMs)}</span>
                    </div>
                )}

                {timeRemainingMs === 0 && (
                    <p className={styles.startingNow}><Spinner size="1em" /> Starting now...</p>
                )}
                {groupExam && groupExam.monitoringEnabled && (
    <p className={styles.monitoringReminder}>
        <FaEye /> Anti-cheating monitoring is active for this session.
    </p>
)}

                {/* --- Notification Permission Button --- */}
                {notificationPermission === 'default' && (
                    <button onClick={requestNotificationPermission} className={styles.notificationButton}>
                        <FaBell /> Enable Start Reminder
                    </button>
                )}
                {notificationPermission === 'denied' && (
                    <p className={styles.notificationDenied}>Notifications blocked by browser settings.</p>
                )}
                {/* --- End Notification --- */}

                <button onClick={fetchSessionDetails} className={styles.refreshButton} title="Check status again">
                    <FaRedo /> Refresh Status
                </button>
            </div>

            <p className={styles.infoMessage}>
                <FaInfoCircle /> The exam will load automatically when the start time is reached. Please keep this page open.
            </p>
        </div>
    );
};

export default GroupExamWaitingPage;
```

---

## pages\HomePage


### pages\HomePage\HomePage.module.scss

```scss
// src/pages/HomePage/HomePage.module.scss
@import '../../styles/variables';
@import '../../styles/mixins';

// --- General Page Styles ---
.homePage {
  width: 100%;
  overflow-x: hidden; // Keep this
}

// .container is global, no need to redefine unless for specific HomePage override

.section { // A base class for common section padding
  padding: map-get($spacers, 7) 0; // py-7 (48px) default section padding
  position: relative; // For pseudo-elements or absolute positioning within sections

  @include media-breakpoint-up(md) {
    padding: map-get($spacers, 8) 0; // py-8 (64px) on larger screens
  }
}

.sectionTitle {
  text-align: center;
  font-size: $h2-font-size; // Use H2 size
  color: $gray-800; // Darker title
  margin-bottom: map-get($spacers, 6); // mb-6 (40px) - more space below titles
  font-weight: $font-weight-bold; // Bolder titles
  position: relative;
  padding-bottom: map-get($spacers, 3); // pb-3 for underline space

  &::after { // Underline accent
    content: '';
    position: absolute;
    bottom: 0;
    left: 50%;
    transform: translateX(-50%);
    width: 70px; // Slightly narrower
    height: 4px;
    background-color: $primary-color;
    border-radius: $border-radius-pill; // Pill shape for underline
  }
}

// --- CTA Button (reused, ensure it's general enough or create specific variants) ---
.ctaButton { // Base CTA style (already refined, let's ensure consistency)
  @include button-variant($primary-color); // Defaults to solid primary
  padding: map-get($spacers, 3) map-get($spacers, 5); // py-3 px-5 (16px 32px)
  font-size: $font-size-base * 1.05; // Adjust as needed
  font-weight: $font-weight-semibold; // Bolder CTA text
  text-decoration: none;
  border-radius: $border-radius; // Standard radius, or $border-radius-lg for chunkier
  gap: map-get($spacers, 2);
  transition: transform 0.15s ease-out, box-shadow 0.2s ease-out, background-color $transition-fast, border-color $transition-fast; // Added bg/border transition
  box-shadow: $box-shadow-sm;

  &:hover:not(:disabled) {
    text-decoration: none;
    transform: translateY(-2px); // Subtle lift
    box-shadow: $box-shadow-md;
  }
  svg { margin-bottom: -2px; } // Fine-tune icon alignment
}

// --- Hero Section ---
.heroSection {
  @extend .section; // Use common section padding
  // New gradient: Subtle primary to a lighter shade or transparent
  background: linear-gradient(135deg, lighten($primary-color, 50%) 0%, $gray-50 70%); // Primary light to body bg
  color: $gray-800; // Dark text
  text-align: center;
  overflow: visible; // Remove overflow hidden if not using complex shapes cutting off content
  padding-bottom: map-get($spacers, 8) + 5rem; // Convert 80px to rem

  // Optional: smoother wave/curve using SVG or a pseudo-element if needed.
  // The clip-path approach can sometimes be jagged.
  // For simplicity, if after the existing clip-path, use the section bg color.
  // The existing ::after with clip-path is okay but might look dated.
  // Consider replacing with a subtle ::before gradient overlay or removing complex shape.
  // For now, let's assume body-bg is fine for the curve from App.scss if header/footer are outside this.
  &::after { // Assuming this creates the bottom curve into the next section
    content: '';
    position: absolute;
    bottom: 0;
    left: 0;
    width: 100%;
    height: 100px; // Height of the curve
    background-color: $body-bg; // Must match the next section's background
    // Example: simple curve. For complex waves, SVG is better.
    clip-path: ellipse(100% 70% at 50% 100%); // Creates an upward curve
  }
}

.heroHeadline {
  font-size: $h1-font-size * 1.1; // Adjust as per new $h1-font-size
  font-weight: $font-weight-bold; // Can go even bolder (e.g., 800)
  color: $gray-900; // Near black for max impact
  margin-bottom: map-get($spacers, 3); // mb-3
  line-height: 1.2; // Tighter line height for large headlines
  letter-spacing: -0.025em; // Slight negative tracking

  .highlight { color: $primary-color; }

  @include media-breakpoint-up(md) {
    font-size: $h1-font-size * 1.3; // Larger on desktop
  }
}

.heroSubheadline {
  font-size: $font-size-base * 1.15; // ~18px
  color: $gray-600; // Slightly darker muted text
  margin-bottom: map-get($spacers, 5); // mb-5, more space before CTAs
  max-width: 720px; // Limit width for readability
  margin-left: auto;
  margin-right: auto;
  line-height: 1.7;

  @include media-breakpoint-up(md) {
    font-size: $font-size-base * 1.25; // ~20px
  }
}

.heroCtaContainer {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  gap: map-get($spacers, 3); // gap-3
  margin-bottom: map-get($spacers, 4); // mb-4

  @include media-breakpoint-up(sm) {
    flex-direction: row;
    gap: map-get($spacers, 4);
  }
}

.primaryCta { // Specific primary CTA in hero
  @extend .ctaButton; // Inherits base
  // Already primary from .ctaButton, can add more emphasis
  font-size: $font-size-base * 1.15; // Larger
  padding: map-get($spacers, 3) map-get($spacers, 6); // py-3 px-6 (larger)
  box-shadow: 0 4px 14px 0 rgba($primary-color, 0.30); // Softer, more spread shadow
  &:hover:not(:disabled) {
    box-shadow: 0 6px 20px 0 rgba($primary-color, 0.35);
  }
}
.secondaryCta { // Specific secondary CTA in hero (outline style)
  @extend .ctaButton;
  @include button-variant(
    transparent,        // bg
    $primary-color,     // border (primary color for outline)
    $primary-color,     // text
    rgba($primary-color, 0.08), // hover-bg (light primary tint)
    $primary-color,     // hover-border
    $primary-color,     // hover-text (stays primary)
    rgba($primary-color, 0.12),// active-bg
    $primary-color,     // active-border
    0.65,
    true                // is-outline
  );
  box-shadow: none; // No shadow for outline CTA
  &:hover:not(:disabled) { box-shadow: none; }
}

.heroNote {
  margin-top: map-get($spacers, 4); // mt-4
  font-size: $font-size-base * 0.85;
  color: $gray-500;
}

// --- Steps Section ---
.stepsSection {
  @extend .section;
  background-color: $body-bg; // Or $gray-50
  z-index: 1; // Ensure it's above hero's ::after curve
}

.stepsGrid {
  display: grid;
  grid-template-columns: 1fr;
  gap: map-get($spacers, 6); // Larger gap between step cards

  @include media-breakpoint-up(md) {
    grid-template-columns: repeat(3, 1fr);
    gap: map-get($spacers, 5);
  }
}

.stepCard {
  text-align: center;
  padding: 0 map-get($spacers, 3); // px-3, number is outside
  position: relative;

  .stepNumber {
    position: absolute;
    top: -#{map-get($spacers, 4)}; // Position above, adjust based on number size
    left: 50%;
    transform: translateX(-50%);
    width: 44px; // Smaller number circle
    height: 44px;
    line-height: 44px;
    border-radius: 50%;
    background-color: $primary-color;
    color: $white-color;
    font-size: $h5-font-size; // Number font size
    font-weight: $font-weight-bold;
    box-shadow: $box-shadow-md; // Shadow for number
    z-index: 2;
    border: 2px solid $white-color; // White border around number for definition
  }

  .stepIcon {
    color: $primary-color;
    margin-top: map-get($spacers, 5); // mt-5, space below number circle
    margin-bottom: map-get($spacers, 3); // mb-3
  }

  h3 { // Step title
    font-size: $h5-font-size;
    font-weight: $font-weight-semibold;
    margin-bottom: map-get($spacers, 2);
    color: $gray-800;
  }

  p { // Step description
    font-size: $font-size-base * 0.9;
    color: $gray-600;
    line-height: 1.6;
  }
}

// --- Features Section ---
.featuresSection {
  @extend .section;
  background-color: $gray-100; // Slightly different background (light gray)
}

.featuresGrid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(300px, 1fr)); // Adjust minmax
  gap: map-get($spacers, 5); // gap-5
  align-items: stretch;
}

.featureCard {
  background-color: $component-bg; // $white-color
  border: 1px solid $gray-200; // Lighter border for cards
  border-radius: $border-radius-lg; // 8px
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: map-get($spacers, 5); // p-5 (32px)
  text-align: center;
  box-shadow: $box-shadow-sm;
  transition: transform 0.2s ease-in-out, box-shadow 0.2s ease-in-out;

  &:hover {
    transform: translateY(-4px); // More lift on hover
    box-shadow: $box-shadow-lg; // More prominent shadow
  }
}

.featureIconWrapper {
  color: $white-color;
  background-color: $primary-color;
  width: 60px; // Slightly smaller icon wrapper
  height: 60px;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  margin-bottom: map-get($spacers, 4); // mb-4
  flex-shrink: 0;
  box-shadow: 0 2px 4px rgba($primary-color, 0.3); // Shadow for icon wrapper

  svg { display: block; } // Icon size set in TSX (e.g., size={28})
}

.featureTitle {
  font-size: $h5-font-size; // Using H5 size for feature titles
  font-weight: $font-weight-semibold;
  color: $gray-800;
  margin-top: 0;
  margin-bottom: map-get($spacers, 2);
}

.featureDescription {
  font-size: $font-size-base * 0.9;
  color: $gray-600;
  line-height: 1.6;
  margin-bottom: 0;
  flex-grow: 1; // Allows description to push icon/title up if card height varies
}

// --- Use Case Section ---
.useCaseSection {
  @extend .section;
  background-color: $body-bg;
}

.useCaseGrid { // Same as features grid
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
  gap: map-get($spacers, 5);
}

.useCaseCard {
  text-align: center;
  background-color: $component-bg;
  padding: map-get($spacers, 5); // p-5
  border-radius: $border-radius-lg;
  border: 1px solid $gray-200;
  // Using top border as accent
  border-top: 4px solid $primary-color; // Accent border top
  box-shadow: $box-shadow-sm;
  transition: transform 0.2s ease-in-out, box-shadow 0.2s ease-in-out;

  &:hover {
    transform: translateY(-4px);
    box-shadow: $box-shadow-md;
  }

  .useCaseIcon {
    color: $primary-color;
    margin-bottom: map-get($spacers, 3);
  }
  h4 { // Use Case Title
    font-weight: $font-weight-semibold;
    margin-bottom: map-get($spacers, 2);
    font-size: $h5-font-size; // Consistent with feature titles
    color: $gray-800;
  }
  p { // Use Case Description
    font-size: $font-size-base * 0.9;
    color: $gray-600;
    line-height: 1.7;
    margin-bottom: 0;
  }
}

// --- Open Source Section ---
.openSourceSection {
  @extend .section;
  background: $gray-800; // Dark background
  color: $gray-200;    // Light text
  text-align: center;

  .sectionTitle { // Override default section title for dark background
    color: $white-color;
    &::after { background-color: $primary-color; }
  }
}

.openSourceIntro {
  max-width: 750px; // Limit width
  margin: 0 auto map-get($spacers, 5) auto; // mb-5
  color: $gray-300; // Lighter text
  font-size: $font-size-base * 1.05;
  line-height: 1.7;
}

.openSourceContent {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: map-get($spacers, 4); // gap-4
}

.githubButton { // CTA Button for GitHub
  @extend .ctaButton;
  // Make it a light outline button on dark background
  @include button-variant(
    transparent,        // bg
    $white-color,       // border (white border)
    $white-color,       // text (white text)
    rgba($white-color, 0.1), // hover-bg
    $white-color,       // hover-border
    $white-color,       // hover-text
    rgba($white-color, 0.15),// active-bg
    $white-color,       // active-border
    0.65,
    true                // is-outline
  );
  font-weight: $font-weight-semibold; // Bolder for GitHub button
}

.openSourceBenefits {
  color: $gray-300;
  display: flex;
  flex-direction: column;
  gap: map-get($spacers, 2); // gap-2
  align-items: center;
  margin-top: map-get($spacers, 3); // mt-3

  p {
    display: inline-flex;
    align-items: center;
    gap: map-get($spacers, 2); // gap-2
    margin-bottom: 0;
    font-size: $font-size-base * 0.95;
    svg {
      color: $success-color; // Green checkmarks
      flex-shrink: 0;
      font-size: $font-size-base * 1.1; // Slightly larger check
    }
  }

  @include media-breakpoint-up(sm) {
    flex-direction: row;
    justify-content: center;
    gap: map-get($spacers, 4);
  }
}
.ssoInfoText { // Example class, or integrate into existing subtitle style
  font-size: $font-size-base * 0.9;
  color: $gray-600;
  margin-top: map-get($spacers, 2);
  font-style: italic;
}

// --- Final CTA Section ---
.finalCtaSection {
  @extend .section;
  text-align: center;
  background-color: $gray-50; // Light background for final CTA

  .sectionTitle {
    color: $primary-color;
    margin-bottom: map-get($spacers, 3); // mb-3
    &::after { display: none; } // No underline for this title
  }
  p { // Subtext for final CTA
    color: $gray-600;
    margin-bottom: map-get($spacers, 5); // mb-5
    font-size: $font-size-base * 1.1; // Larger subtext
    max-width: 650px;
    margin-left: auto;
    margin-right: auto;
    line-height: 1.6;
  }
  .finalCta { // The button itself
    @extend .primaryCta; // Reuse hero's primary CTA style
  }
}
```

---

### pages\HomePage\HomePage.tsx

```typescript
// src/pages/HomePage/HomePage.tsx
import React, { useEffect } from 'react';
import { Link } from 'react-router-dom';
import styles from './HomePage.module.scss';
// Import more relevant/engaging icons
import {
    FaPlayCircle, FaUsers, FaClipboardList, FaChartLine,
    FaLaptopCode, FaUserCheck, FaShieldAlt, FaGithub, FaArrowRight,
    FaChalkboardTeacher, FaUserGraduate, FaSyncAlt,
    FaCheckDouble
} from 'react-icons/fa';
import { useAuth } from '../../contexts/AuthContext'; // To customize CTA later maybe

const GITHUB_REPO_URL = "https://github.com/Samkarya/online-exam-questions";

// Define benefit-focused features
const coreFeatures = [
    {
        icon: <FaLaptopCode size={30} />,
        title: "Realistic Exam Simulation",
        description: "Practice under pressure with timed tests, familiar navigation, and question palettes mimicking actual exam interfaces."
    },
    {
        icon: <FaClipboardList size={30} />,
        title: "Official & Custom Tests",
        description: "Prepare with official past papers transparently sourced via GitHub, or upload/paste your own JSON questions for targeted practice."
    },
    {
        icon: <FaChartLine size={30} />,
        title: "In-Depth Performance Analysis",
        description: "Instantly review your scores, see correct/incorrect answers (with explanations where available), and identify weak spots."
    },
    {
        icon: <FaUserCheck size={30} />,
        title: "Personalized Progress Tracking",
        description: "Log in to save your attempts, monitor your performance over time, and visualize your improvement journey on your profile."
    },
    {
        icon: <FaUsers size={30} />,
        title: "Collaborative Group Sessions",
        description: "Create timed sessions for study groups or classes, invite participants, and review collective performance (coming soon: leaderboards!)."
    },
    {
        icon: <FaShieldAlt size={30} />,
        title: "Transparent & Open Source",
        description: "Trust your practice material. Our official questions repository on GitHub is open for review and contributions."
    }
];


const HomePage: React.FC = () => {
    const { currentUser, openRegistrationModal } = useAuth(); // Get user status

     useEffect(() => {
         document.title = 'Examify - Realistic Exam Practice Platform'; // More descriptive title
     }, []);
     const handlePrimaryCtaClick = (event: React.MouseEvent<HTMLAnchorElement | HTMLButtonElement>) => {
        if (!currentUser) {
            event.preventDefault(); // Prevent default Link behavior if we handle redirect
            openRegistrationModal('/select-exam');
        }
        // If currentUser exists, the Link component will navigate to /select-exam
    };

    return (
        <div className={styles.homePage}>
            {/* === Hero Section === */}
            <section className={styles.heroSection}>
                <div className={styles.container}>
                     <h1 className={styles.heroHeadline}>
                        Stop Guessing. <span className={styles.highlight}>Start Mastering.</span>
                     </h1>
                     <h2 className={styles.heroSubheadline}>
                        The ultimate exam simulator for NIMCET, CUET, JEE & more. Practice realistically, analyze deeply, and conquer your entrance exams.
                        <br /><br />
 <strong style={{ fontSize: '0.95em' }}>Examify uses the <a href="https://bcaexamprep.web.app" target="_blank" rel="noopener noreferrer" style={{color: styles.primaryColor, fontWeight: 'bold'}}>MyServices Portal</a> for secure, unified account management. Register once, access all!</strong>
                     </h2>
                    <div className={styles.heroCtaContainer}>
                        <Link to="/select-exam" className={`${styles.ctaButton} ${styles.primaryCta}`}>
                            <FaPlayCircle /> Start Free Practice
                        </Link>
                         {/* Secondary CTA could be for group feature or registration */}
                         <Link to="/group-exam/setup" className={`${styles.ctaButton} ${styles.secondaryCta}`}>
                            <FaUsers /> Host Group Session
                        </Link>
                    </div>
                    <p className={styles.heroNote}>Free access. No credit card required.</p>
                </div>
            </section>

            {/* === "How It Works" / Simple Steps === */}
            <section className={styles.stepsSection}>
                 <div className={styles.container}>
                      <h2 className={styles.sectionTitle}>Get Exam Ready in 3 Simple Steps</h2>
                      <div className={styles.stepsGrid}>
                          <div className={styles.stepCard}>
                               <div className={styles.stepNumber}>1</div>
                               <FaClipboardList size={40} className={styles.stepIcon}/>
                               <h3>Choose or Upload</h3>
                               <p>Select official past papers or upload your custom JSON question sets.</p>
                          </div>
                           <div className={styles.stepCard}>
                                <div className={styles.stepNumber}>2</div>
                                <FaLaptopCode size={40} className={styles.stepIcon}/>
                                <h3>Simulate & Solve</h3>
                                <p>Take the test in a realistic, timed environment with familiar controls.</p>
                           </div>
                           <div className={styles.stepCard}>
                                <div className={styles.stepNumber}>3</div>
                                <FaChartLine size={40} className={styles.stepIcon}/>
                                <h3>Analyze & Improve</h3>
                                <p>Review detailed results, understand mistakes, and track your progress.</p>
                           </div>
                      </div>
                 </div>
            </section>


            {/* === Core Features/Benefits Section === */}
            <section className={styles.featuresSection}>
                <div className={styles.container}>
                    <h2 className={styles.sectionTitle}>Everything You Need to Succeed</h2>
                    <div className={styles.featuresGrid}>
                        {coreFeatures.map((feature, index) => (
                            <div key={index} className={styles.featureCard}>
                                <div className={styles.featureIconWrapper}>{feature.icon}</div>
                                <h3 className={styles.featureTitle}>{feature.title}</h3>
                                <p className={styles.featureDescription}>{feature.description}</p>
                            </div>
                        ))}
                    </div>
                </div>
            </section>

             {/* === Use Case / Who Is It For? Section === */}
             <section className={styles.useCaseSection}>
                 <div className={styles.container}>
                     <h2 className={styles.sectionTitle}>Built For Your Success</h2>
                      <div className={styles.useCaseGrid}>
                          <div className={styles.useCaseCard}>
                               <FaUserGraduate size={40} className={styles.useCaseIcon}/>
                               <h4>Individual Students</h4>
                               <p>Master concepts, improve speed, and track personal growth with targeted solo practice using official or custom tests.</p>
                          </div>
                           <div className={styles.useCaseCard}>
                                <FaUsers size={40} className={styles.useCaseIcon}/>
                                <h4>Study Groups</h4>
                                <p>Collaborate effectively by taking the same timed test together, then discuss results and problem areas.</p>
                           </div>
                           <div className={styles.useCaseCard}>
                                <FaChalkboardTeacher size={40} className={styles.useCaseIcon}/>
                                <h4>Educators & Tutors</h4>
                                <p>Quickly create and administer practice quizzes or mock tests for your students using custom JSON files.</p>
                           </div>
                      </div>
                 </div>
             </section>


            {/* === Open Source Section (Revised Emphasis) === */}
            <section className={styles.openSourceSection}>
                <div className={styles.container}>
                     <h2 className={styles.sectionTitle}>
                        <FaGithub style={{ marginRight: '10px', verticalAlign: 'middle' }}/> Transparent & Community-Powered
                     </h2>
                     <p className={styles.openSourceIntro}>
                        We believe in openness. Our official questions are hosted publicly on GitHub. This means you can verify sources, understand the format, and even contribute back to help fellow students!
                     </p>
                     <div className={styles.openSourceContent}>
                           {/* Link/Button prominent */}
                           <a href={GITHUB_REPO_URL} target="_blank" rel="noopener noreferrer" className={`${styles.ctaButton} ${styles.githubButton}`}>
                               <FaGithub /> Explore Question Repo & Contribute
                           </a>
                           <div className={styles.openSourceBenefits}>
                                <p><FaCheckDouble /> Verify question accuracy and origins.</p>
                                <p><FaUsers /> Join the community, add questions, or suggest improvements.</p>
                                <p><FaSyncAlt /> Benefit from continuous updates driven by users like you.</p>
                           </div>
                    </div>
                </div>
            </section>


             {/* === Final CTA Section === */}
             <section className={styles.finalCtaSection}>
                 <div className={styles.container}>
                     <h2 className={styles.sectionTitle}>Ready to Elevate Your Exam Prep?</h2>
                     <p>Transform your study routine with realistic practice and actionable insights. Sign up or start practicing for free today!</p>
                     {/* Show slightly different CTA if user is already logged in */}
                     {!currentUser ? (
                         <button 
                            onClick={(e) => handlePrimaryCtaClick(e as any)} // Reuses the same logic for consistency
                            className={`${styles.ctaButton} ${styles.primaryCta} ${styles.finalCta}`}>
                             Sign Up Now - It's Free! <FaArrowRight/>
                         </button>
                     ) : (
                         <Link to="/select-exam"
                             className={`${styles.ctaButton} ${styles.primaryCta} ${styles.finalCta}`}>
                             Go to Practice Dashboard <FaArrowRight/>
                         </Link>
                     )}

                 </div>
             </section>
        </div>
    );
};

export default HomePage;
```

---

## pages\HostDashboardPage


### pages\HostDashboardPage\HostDashboardPage.module.scss

```scss
// src/pages/HostDashboardPage/HostDashboardPage.module.scss
@import '../../styles/variables';
@import '../../styles/mixins';

.dashboardPage {
    padding: $spacer * 2 0 $spacer * 3 0;
    max-width: 1000px; // Wider for dashboard view
    margin: 0 auto;

    h1 {
        text-align: center;
        margin-bottom: $spacer * 2.5;
        color: $primary-color;
        display: flex;
        align-items: center;
        justify-content: center;
        gap: $spacer * 0.75;
    }
}

.actionsHeader {
    display: flex;
    flex-direction: column; // Stack vertically on small screens
    gap: $spacer; // Add gap between limit info and button on small screens
    align-items: stretch; // Make items stretch on small screens
    margin-bottom: $spacer * 1.5;
    padding-bottom: $spacer * 1.5;
    border-bottom: 1px solid $border-color;

    @include media-breakpoint-up(md) {
        flex-direction: row; // Side-by-side layout
        justify-content: space-between; // Pushes items to ends
        align-items: center; // Vertically align items
        gap: $spacer * 1.5;
    }
}
.limitInfo {
    display: flex;
    flex-direction: column;
    gap: $spacer * 0.3;
    width: 100%; // Full width on mobile

    @include media-breakpoint-up(md) {
        width: auto; // Auto width on larger screens
        min-width: 200px; // Ensure it has some space
        align-items: flex-start; // Align left near the title on larger screens
    }
    @include media-breakpoint-up(lg) { // Example adjustment for larger screens if needed
        min-width: 250px;
    }
}

.limitText {
    font-size: $font-size-base * 0.9;
    color: $text-muted;
    font-weight: 500;
    cursor: help; // Indicate tooltip presence
    display: inline-flex;
    align-items: center;
    gap: $spacer * 0.4;
    // Specific style for count error if needed
    &.countError {
        color: $danger-color;
        cursor: default;
    }
}

.infoIcon {
    font-size: $font-size-base * 0.95;
    color: $secondary-color;
    margin-bottom: -1px; // Fine-tune alignment
    &.countError {
        color: $danger-color;
    }
}

.limitProgressBar {
    width: 100%;
    height: 10px; // Adjust height as needed
    border-radius: $border-radius-lg; // Match container rounding
    overflow: hidden; // Ensure value doesn't overflow border radius
    border: 1px solid darken($border-color, 5%);
    background-color: lighten($light-color, 2%); // Track background


    // Webkit styling (Chrome, Safari, Edge)
    &::-webkit-progress-bar {
        background-color: lighten($light-color, 2%);
        border-radius: $border-radius-lg;
    }

    &::-webkit-progress-value {
        border-radius: $border-radius-lg; // Apply to value bar as well
        transition: background-color 0.3s ease-in-out; // Smooth color transition
    }

    // Firefox styling
    &::-moz-progress-bar {
        border-radius: $border-radius-lg;
        transition: background-color 0.3s ease-in-out;
    }

    // Apply color classes to the value bar
    &.progressBarGreen {
        &::-webkit-progress-value { background-color: $success-color; }
        &::-moz-progress-bar { background-color: $success-color; }
    }
    &.progressBarYellow {
        &::-webkit-progress-value { background-color: $warning-color; }
        &::-moz-progress-bar { background-color: $warning-color; }
    }
    &.progressBarRed {
        &::-webkit-progress-value { background-color: $danger-color; }
        &::-moz-progress-bar { background-color: $danger-color; }
    }
}

.createButton {
    @include button-variant($success-color, $success-color);
    padding: $spacer * 0.7 $spacer * 1.5;
    font-size: $font-size-base;
    font-weight: 500;
    text-decoration: none;
    display: inline-flex;
    align-items: center;
    gap: $spacer * 0.5;

    &.disabled {
        background-color: lighten($success-color, 25%);
        border-color: lighten($success-color, 15%);
        color: darken($success-color, 10%);
        opacity: 0.7;
        cursor: not-allowed;
        pointer-events: none; // Prevent click effects

        &:hover { // Override hover styles when disabled
            background-color: lighten($success-color, 25%);
            border-color: lighten($success-color, 15%);
            transform: none;
            box-shadow: none;
        }
    }
}

.loadingState, .emptyState {
    text-align: center;
    padding: $spacer * 3 0;
    color: $text-muted;
    font-size: $font-size-base * 1.05;
}

.errorMessage {
    color: $danger-color;
    background-color: lighten($danger-color, 48%);
    border: 1px solid lighten($danger-color, 35%);
    border-radius: $border-radius;
    padding: $spacer $spacer * 1.5;
    margin-bottom: $spacer * 1.5;
    text-align: center;
}

//.sessionListContainer {
    // Optional: Add a background or border if desired
//}

.sessionList {
    list-style: none;
    padding: 0;
    margin: 0;
}

.sessionItem {
    background-color: $component-bg;
    border: 1px solid $border-color;
    border-radius: $border-radius;
    padding: $spacer $spacer * 1.5;
    margin-bottom: $spacer;
    display: flex;
    flex-direction: column; // Stack info and actions on mobile
    gap: $spacer;
    box-shadow: $box-shadow-sm;
    transition: box-shadow $transition-fast;

    &:hover {
         box-shadow: $box-shadow-md;
    }

    @include media-breakpoint-up(md) {
        flex-direction: row; // Side by side on larger screens
        justify-content: space-between;
        align-items: center;
    }
}

.sessionInfo {
    display: flex;
    flex-direction: column; // Stack info items on mobile
    flex-wrap: wrap;
    gap: $spacer * 0.4;
    flex-grow: 1; // Allow info to take available space

    @include media-breakpoint-up(sm) {
        flex-direction: row; // Put info items inline on slightly larger screens
        align-items: baseline; // Align text nicely
        gap: $spacer * 1.5; // More space between items
    }
}

.sessionName {
    font-weight: 600;
    font-size: $font-size-base * 1.1;
    color: $dark-color;
     word-break: break-word; // Prevent long names breaking layout badly
}

.sessionDate {
    font-size: $font-size-base * 0.9;
    color: $text-muted;
    white-space: nowrap;
}

.sessionStatus {
    font-size: $font-size-base * 0.85;
    font-weight: bold;
    padding: $spacer * 0.2 $spacer * 0.6;
    border-radius: $border-radius-sm;
    text-transform: uppercase;
    display: inline-block; // Ensure padding/border applies correctly
     white-space: nowrap;
     border: 1px solid transparent; // Base border

     // Status colors
     &.statusPending { background-color: lighten($warning-color, 40%); color: darken($warning-color, 20%); border-color: lighten($warning-color, 20%); }
     &.statusActive { background-color: lighten($info-color, 40%); color: darken($info-color, 20%); border-color: lighten($info-color, 20%); }
     &.statusClosed { background-color: lighten($secondary-color, 40%); color: darken($secondary-color, 20%); border-color: lighten($secondary-color, 20%); }
     // Add more statuses later
}

.sessionTiming, .sessionVisibility {
    font-size: $font-size-base * 0.85;
    color: $text-muted;
    white-space: nowrap;
    display: inline-flex; // Align icon and text
    align-items: center;
    gap: $spacer * 0.4;
    flex-shrink: 0; // Prevent shrinking weirdly if wrapping

    svg {
        font-size: $font-size-base * 0.9; // Smaller icons for these details
         color: $secondary-color;
    }
}

.sessionActions {
    display: flex;
    gap: $spacer * 0.75;
    flex-shrink: 0; // Prevent actions shrinking too much
     align-self: flex-end; // Align buttons to end on mobile stacked view

     @include media-breakpoint-up(md) {
         align-self: center; // Vertically center actions in row view
     }
}

.actionButton {
    padding: $spacer * 0.5 $spacer;
    font-size: $font-size-base * 0.9;
    font-weight: 500;
    text-decoration: none;
    display: inline-flex;
    align-items: center;
    gap: $spacer * 0.4;

    &.viewButton { @include button-variant($info-color, $info-color); }
    &.manageButton { // Renaming from 'manage' to maybe 'close' if that's its only function?
        @include button-variant($warning-color, $warning-color, $dark-color); // Yellow/Orange for Close?
    }
    &.deleteButton { @include button-variant($danger-color, $danger-color); }
    &.downloadButton {
        @include button-variant($success-color, $success-color); // Green for download actions

       // Style for when it's a link but should look like a button
       &.downloadLinkReady {
           text-decoration: none; // Remove underline from link
           color: $white-color; // Ensure text color matches button
            &:hover {
                text-decoration: none;
                color: $white-color; // Keep color on hover
            }
       }
    }

    &:hover { text-decoration: none; }

    &:disabled {
        opacity: 0.5;
        cursor: not-allowed;
         filter: grayscale(50%);
    }
}

// Adjust info item spacing on larger views if needed
@include media-breakpoint-up(sm) {
    .sessionInfo {
        gap: $spacer $spacer * 1.5; // Add row/column gap for wrap
    }
}
@include media-breakpoint-up(lg) {
     .sessionInfo {
         gap: $spacer * 1.5; // Just horizontal gap again
         flex-wrap: nowrap; // Prevent wrapping on large screens
     }
    }

// Reusable spinner class if not global
.spin-icon {
  display: inline-block;
  animation: spin 1.5s linear infinite;
  margin-right: $spacer * 0.5;
}
@keyframes spin {
  0% { transform: rotate(0deg); }
  100% { transform: rotate(360deg); }
}
// --- Detail Modal Specific Styles ---
.detailModalContent {
    padding: $spacer * 0.5; // Add some padding inside modal body
}

.shareInfo {
    margin-bottom: $spacer * 1.5;
    padding-bottom: $spacer * 1.5;
    border-bottom: 1px solid $border-color;
    text-align: center;

    p {
        margin-bottom: $spacer;
        font-weight: 500;
        color: $text-muted;
    }
}

// Reuse styles from Share Page for consistency inside modal
.sessionIdContainer {
    display: flex;
    align-items: center;
    justify-content: center;
    background-color: $white-color;
    border: 1px solid $border-color;
    padding: $spacer * 0.75;
    border-radius: $border-radius;
    max-width: 400px; // Limit width inside modal
    margin: 0 auto; // Center it
    box-shadow: inset 0 1px 3px rgba($black-color, 0.06);
}
.sessionId {
    font-family: monospace;
    font-size: $font-size-base * 1.2; // Slightly smaller in modal?
    font-weight: bold;
    color: $dark-color;
    flex-grow: 1;
    margin-right: $spacer;
    letter-spacing: 1px;
    word-break: break-all;
}
// Add Copy button style if you include it here

.modalActions {
     margin-top: $spacer * 2;
     padding-top: $spacer * 1.5;
     border-top: 1px solid $border-color;
     display: flex;
     justify-content: flex-end; // Align actions right
     gap: $spacer;
}

.closeModalButton { // Specific style for close in detail modal
     @include button-variant(transparent, $secondary-color);
     color: $secondary-color;
}

.emptyStateContainer {
    padding: $spacer * 3 0;
    text-align: center;
    color: $text-muted;
    border: 1px dashed $border-color;
    border-radius: $border-radius;
    margin-top: $spacer * 2;
     background-color: lighten($light-color, 3%);

}
.emptyStateIcon {
    color: $primary-color; // Or a muted color
    margin-bottom: $spacer;
    opacity: 0.7;
}

.emptyStateText {
    font-size: $font-size-base * 1.05;
    font-weight: 500;
    margin-bottom: $spacer * 0.5;
     color: darken($text-muted, 10%);
}

.emptyStateSubtext {
    font-size: $font-size-base * 0.9;
    margin-bottom: 0;
}
```

---

### pages\HostDashboardPage\HostDashboardPage.tsx

```typescript
// src/pages/HostDashboardPage/HostDashboardPage.tsx
import React, { useState, useEffect, useMemo } from 'react';
import { Link, useNavigate } from 'react-router-dom';
import styles from './HostDashboardPage.module.scss';
import { useAuth } from '../../contexts/AuthContext';
import { 
    getHostedGroupExams, 
    getHostedSessionsCount,
} from '../../services/firestoreService';
import { GroupExam } from '../../types'; 
import { formatTimestamp } from '../../utils/formatters';
import { 
  FaPlusCircle, 
  FaListUl, 
  FaClock, 
  FaEye,
  FaChalkboardTeacher,
  FaInfoCircle
} from 'react-icons/fa';
import { toast } from 'react-toastify';
import Spinner from '../../components/Spinner/Spinner';
import ErrorMessage from '../../components/ErrorMessage/ErrorMessage';
import { useUserPerks } from '../../hooks/useUserPerks';

const HostDashboardPage: React.FC = () => {
    const { currentUser, isLoading: isAuthLoading } = useAuth();
    const { limits: perkLimits, isLoadingPerks, currentTier } = useUserPerks();
    const navigate = useNavigate();

    const [hostedSessions, setHostedSessions] = useState<GroupExam[]>([]);
    const [isLoadingSessions, setIsLoadingSessions] = useState(true);
    const [error, setError] = useState<string | null>(null);

    const [hostedCount, setHostedCount] = useState<number | null>(null);
    const [isLoadingCount, setIsLoadingCount] = useState<boolean>(true);
    const [countError, setCountError] = useState<string | null>(null);

    // Fetch Hosted Sessions (existing logic remains mostly the same)
    useEffect(() => {
        let isMounted = true;
        const fetchHosted = async () => {
            if (!currentUser) {
                if (isMounted) { setError("Please log in to view your dashboard."); setIsLoadingSessions(false); }
                return;
            }
            setIsLoadingSessions(true); setError(null);
            try {
                const sessions = await getHostedGroupExams(currentUser.uid);
                if (isMounted) setHostedSessions(sessions);
            } catch (err: any) {
                if (isMounted) {
                    setError(err.message || "Could not load your hosted sessions.");
                    toast.error(err.message || "Could not load your hosted sessions.");
                }
            } finally {
                if (isMounted) setIsLoadingSessions(false);
            }
        };
        if (!isAuthLoading && currentUser) fetchHosted();
        else if (!isAuthLoading && !currentUser) navigate('/select-exam', {replace: true, state: { message: "Please log in." }});
        return () => { isMounted = false; }
    }, [currentUser, isAuthLoading, navigate]);

    // Fetch Hosted Count (existing logic remains)
    useEffect(() => {
        let isMounted = true;
        const fetchCount = async () => {
            if (currentUser) {
                setIsLoadingCount(true); setCountError(null);
                try {
                    const count = await getHostedSessionsCount(currentUser.uid);
                    if(isMounted) setHostedCount(count);
                } catch (err: any) {
                     if(isMounted) { setCountError("Could not check session limit."); setHostedCount(null); }
                } finally {
                   if(isMounted) setIsLoadingCount(false);
                }
            } else {
                 if(isMounted) { setHostedCount(null); setIsLoadingCount(false); setCountError(null); }
            }
        };
        if (!isAuthLoading && currentUser && !isLoadingPerks) fetchCount();
        return () => { isMounted = false; };
    }, [currentUser, isAuthLoading, isLoadingPerks]);

    const getStatusClass = (status: GroupExam['status']) => {
        switch (status) {
            case 'pending': return styles.statusPending;
            case 'active': return styles.statusActive;
            case 'closed': return styles.statusClosed;
            default: return '';
        }
    };

    const sessionLimit = perkLimits.hostedSessions === null ? Infinity : perkLimits.hostedSessions;
    const getProgressBarClass = (count: number, limit: number): string => { /* ... (remains the same) ... */ 
        if (limit === Infinity || limit <= 0) return styles.progressBarGreen;
        const percentage = (count / limit) * 100;
        if (percentage >= 90) return styles.progressBarRed;
        if (percentage >= 70) return styles.progressBarYellow;
        return styles.progressBarGreen;
    };
    const limitReached = useMemo(() => {
        if (isLoadingCount || isLoadingPerks || hostedCount === null) return false;
        return hostedCount >= sessionLimit;
    }, [hostedCount, sessionLimit, isLoadingCount, isLoadingPerks]);
    
    const currentHostedCount = hostedCount ?? 0;
    const progressBarClass = isLoadingCount || isLoadingPerks ? styles.progressBarGreen : getProgressBarClass(currentHostedCount, sessionLimit);

    if (isAuthLoading) {
        return ( /* ... (Auth loading spinner remains the same) ... */ 
            <div className={styles.dashboardPage}>
                <h1><FaListUl /> My Hosted Sessions</h1>
                <div className={styles.loadingState}>
                    <Spinner text="Authenticating..." size={24} />
                </div>
            </div>
        );
    }

    return (
        <div className={styles.dashboardPage}>
            <h1><FaListUl /> My Hosted Sessions</h1>

            <div className={styles.actionsHeader}>
                {/* ... (Limit info and Create button JSX remain the same) ... */}
                <div className={styles.limitInfo}>
                    {(isLoadingCount || isLoadingPerks) && <Spinner size="0.9em" text="Checking limit..." />}
                    {countError && <span className={`${styles.limitText} ${styles.countError}`} title={countError}>Could not check session limit <FaInfoCircle className={styles.infoIcon} /></span>}
                    {!isLoadingCount && !isLoadingPerks && hostedCount !== null && (
                        <>
                            <span
                                className={styles.limitText}
                                title={
                                   `Your current tier ('${currentTier.name}') allows you to host ${sessionLimit === Infinity ? 'unlimited active/pending' : sessionLimit} session(s) concurrently.`
                               }
                            >
                                Hosted Limit: {currentHostedCount} / {sessionLimit === Infinity ? 'Unlimited' : sessionLimit}
                                <FaInfoCircle className={styles.infoIcon} />
                            </span>
                            {sessionLimit !== Infinity && (
                                <progress
                                    className={`${styles.limitProgressBar} ${progressBarClass}`}
                                    max={sessionLimit}
                                    value={currentHostedCount}
                                    title={`${currentHostedCount}/${sessionLimit} sessions used`}
                                ></progress>
                            )}
                        </>
                    )}
                </div>
                <Link
                    to="/group-exam/setup"
                    className={`${styles.createButton} ${limitReached || isLoadingPerks || isLoadingCount ? styles.disabled : ''}`}
                    onClick={(e) => { if (limitReached || isLoadingPerks || isLoadingCount) e.preventDefault(); }}
                    title={
                       isLoadingPerks || isLoadingCount ? "Checking session limits..." :
                       limitReached ? `Hosted session limit (${sessionLimit === Infinity ? 'Unlimited' : sessionLimit}) reached for your '${currentTier.name}' tier. Manage existing sessions or upgrade for more.` : 
                       "Create a new group session"
                   }
                    aria-disabled={limitReached || isLoadingPerks || isLoadingCount}
                >
                    <FaPlusCircle /> Create New Session
                </Link>
            </div>

            {(isLoadingSessions || isLoadingPerks) && !error && (
                <div className={styles.loadingState}>
                    <Spinner text="Loading sessions..." size={24} />
                </div>
            )}
            <ErrorMessage message={error && !countError ? error : null} textAlign="center" />

            {!error && !(isLoadingSessions || isLoadingPerks) && hostedSessions.length === 0 && (
                /* ... (Empty state JSX remains the same) ... */
                <div className={styles.emptyStateContainer}>
                    <FaChalkboardTeacher size={30} className={styles.emptyStateIcon} />
                    <p className={styles.emptyStateText}>You haven't created any group sessions yet.</p>
                    <p className={styles.emptyStateSubtext}>
                        {limitReached
                           ? `You've reached your session limit for the '${currentTier.name}' tier.`
                            : 'Click the button above to start your first session!'}
                    </p>
                </div>
            )}

            {!error && hostedSessions.length > 0 && (
                <div className={styles.sessionListContainer}>
                    <ul className={styles.sessionList}>
                        {hostedSessions.map(session => {
                            const startTimeFormatted = formatTimestamp(session.startTime instanceof Date ? session.startTime : session.startTime?.toDate());
                            const endTimeFormatted = formatTimestamp(session.endTime instanceof Date ? session.endTime : session.endTime?.toDate());
                            // const isActionLoading = actionInProgressId === session.id; // No longer needed here

                            return (
                                <li key={session.id} className={styles.sessionItem}>
                                    <div className={styles.sessionInfo}>
                                        <span className={styles.sessionName}>{session.sessionName}</span>
                                        {(startTimeFormatted !== 'N/A' || endTimeFormatted !== 'N/A') && (
                                            <span className={styles.sessionTiming} title={`Starts: ${startTimeFormatted} | Deadline: ${endTimeFormatted}`}>
                                                <FaClock /> {startTimeFormatted !== 'N/A' ? `Starts: ${startTimeFormatted}` : ''} {endTimeFormatted !== 'N/A' ? ` / Deadline: ${endTimeFormatted}` : ''}
                                            </span>
                                        )}
                                        <span className={styles.sessionVisibility} title={`Result Visibility: ${session.resultVisibility}`}>
                                            <FaEye /> {session.resultVisibility || 'Default'}
                                        </span>
                                        <span className={`${styles.sessionStatus} ${getStatusClass(session.status)}`}>
                                            {session.status}
                                        </span>
                                    </div>
                                    <div className={styles.sessionActions}>
                                        <Link
                                            to={`/group-exam/detail/${session.id}`}
                                            className={`${styles.actionButton} ${styles.viewButton}`}
                                            title="View Full Details, Participants & Actions"
                                        >
                                            <FaListUl /> Full Details
                                        </Link>
                                         {/* Removed Close/Delete buttons, they are now on Detail Page */}
                                    </div>
                                </li>
                            );
                        })}
                    </ul>
                </div>
            )}

            {/* Removed ConfirmationModal and DetailModal from here */}
        </div>
    );
};

export default HostDashboardPage;
```

---

## pages\JoinGroupExamPage


### pages\JoinGroupExamPage\JoinGroupExamPage.module.scss

```scss
// src/pages/JoinGroupExamPage/JoinGroupExamPage.module.scss
@import '../../styles/variables';
@import '../../styles/mixins';

.joinPage {
  padding: map-get($spacers, 5) 0 map-get($spacers, 6); // py-5 my-6
  max-width: 480px; // Slightly narrower for a single input form
  margin: map-get($spacers, 5) auto; // my-5 auto
  display: flex;
  flex-direction: column;
  align-items: center; // Center direct children

  h1 {
    text-align: center;
    margin-bottom: map-get($spacers, 3); // mb-3
    color: $primary-color;
    font-weight: $font-weight-semibold;
  }

  .instructions {
    text-align: center;
    color: $text-muted;
    margin-bottom: map-get($spacers, 5); // mb-5
    font-size: $font-size-base * 1.05;
    line-height: 1.6;
    max-width: 400px; // Limit width of instructions text
  }
}

.joinForm {
  width: 100%; // Form takes full width of .joinPage container
  background-color: $component-bg;
  padding: map-get($spacers, 5); // p-5 (32px)
  border: 1px solid $gray-200; // Lighter border
  border-radius: $border-radius-lg; // 8px
  box-shadow: $box-shadow-lg; // More prominent shadow
}

.formGroup {
  margin-bottom: map-get($spacers, 4); // mb-4 (24px)

  label {
    display: block;
    font-weight: $font-weight-medium;
    margin-bottom: map-get($spacers, 2); // mb-2 (8px)
    color: $gray-700;
    font-size: $font-size-base * 0.9;
  }

  input[type="text"] { // Style for Session ID input
    width: 100%;
    padding: map-get($spacers, 3); // p-3 (16px), larger padding
    border: 1px solid $border-color; // $gray-300
    border-radius: $border-radius;   // 6px
    font-size: $font-size-base * 1.15; // Larger text for ID input
    text-align: center;
    letter-spacing: 1.5px; // More spacing for ID
    font-family: $font-family-monospace; // Monospace for IDs often looks good
    text-transform: uppercase; // Convention for IDs
    background-color: $white-color;
    transition: border-color $transition-fast, box-shadow $transition-fast;

    &:focus {
      outline: none;
      border-color: $primary-color;
      box-shadow: 0 0 0 3px rgba($primary-color, 0.2);
    }
    &:disabled {
      background-color: $gray-100;
      opacity: 0.7;
      cursor: not-allowed;
    }
    &::placeholder {
        font-family: $font-family-base; // Placeholder can be normal font
        text-transform: none;
        letter-spacing: normal;
        font-size: $font-size-base; // Smaller placeholder
    }

    &.inputError { // For input-specific error state
      border-color: $danger-color;
      color: $danger-color; // Text color can also change on error
      &:focus {
        box-shadow: 0 0 0 3px rgba($danger-color, 0.2);
      }
    }
  }
}

.errorMessage { // For form-level error messages
  // Use styles consistent with global ErrorMessage component
  background-color: lighten($red-500, 50%);
  border: 1px solid lighten($red-500, 30%);
  color: darken($red-500, 15%);
  border-radius: $border-radius;
  padding: map-get($spacers, 2) map-get($spacers, 3);
  margin-bottom: map-get($spacers, 4); // mb-4
  text-align: center;
  font-size: $font-size-base * 0.9;
  line-height: 1.5;
}

.joinButton {
  @include button-variant($success-color); // Solid success button
  padding: map-get($spacers, 3) map-get($spacers, 4); // py-3 px-4, larger button
  font-size: $font-size-base * 1.05; // Slightly larger font
  font-weight: $font-weight-semibold; // Bolder
  width: 100%;
  gap: map-get($spacers, 2); // gap-2 (8px)

  // Disabled state handled by mixin
}
.geoStatusBox {
  margin-top: map-get($spacers, 3);
  padding: map-get($spacers, 3);
  border: 1px solid $gray-200;
  border-radius: $border-radius;
  background-color: $gray-50;
  text-align: center;

  p { // For geoCheckMessage
    margin: 0;
    line-height: 1.5;
    &.errorMessage { // If reusing error message class
      color: $danger-color;
      font-weight: $font-weight-medium;
    }
    &.infoMessage {
      color: $text-muted;
    }
  }
}
.marginTopLarge { // Utility for more margin if needed
  margin-top: map-get($spacers, 5) !important;
}
.errorMessageNoBg { // Simpler error text without the full box style
  color: $danger-color;
  font-weight: $font-weight-medium;
  margin-bottom: map-get($spacers, 2);
}
.retryGeoButton {
  @include button-variant(transparent, $primary-color, $primary-color, $is-outline: true);
  margin-top: map-get($spacers, 2);
  display: inline-flex;
  align-items: center;
  gap: map-get($spacers, 2);
}
.errorIcon { // If using an icon next to the error message
  color: $danger-color;
  margin-right: map-get($spacers, 2);
  font-size: $font-size-base * 1.2;
}

.inlineErrorMessage { // Used for error message within the consent modal
color: $danger-color;
font-size: $font-size-base * 0.9;
margin-top: map-get($spacers, 2);
font-weight: $font-weight-medium;
}
// Spin icon animation is global in App.scss
```

---

### pages\JoinGroupExamPage\JoinGroupExamPage.tsx

```typescript
// src/pages/JoinGroupExamPage/JoinGroupExamPage.tsx
import React, { useState,useEffect, useMemo } from 'react';
import { useNavigate, useLocation } from 'react-router-dom';
import { useAuth } from '../../contexts/AuthContext';
import styles from './JoinGroupExamPage.module.scss';
import { getGroupExam, addParticipantToGroupExam } from '../../services/firestoreService';
import { toast } from 'react-toastify';
import { FaSignInAlt, FaMapMarkerAlt } from 'react-icons/fa';
import { analytics } from '../../services/firebase';
import { logEvent } from 'firebase/analytics';
import Spinner from '../../components/Spinner/Spinner';
import { GroupExam } from '../../types';
import ConfirmationModal from '../../components/Modal/ConfirmationModal';

// Helper function to parse query parameters
function useQuery() {
    const { search } = useLocation();
    return React.useMemo(() => new URLSearchParams(search), [search]);
}

// Helper function to calculate distance between coordinates
const calculateDistance = (lat1: number, lon1: number, lat2: number, lon2: number): number => {
    const R = 6371e3; // Earth's radius in meters
    const φ1 = lat1 * Math.PI / 180;
    const φ2 = lat2 * Math.PI / 180;
    const Δφ = (lat2 - lat1) * Math.PI / 180;
    const Δλ = (lon2 - lon1) * Math.PI / 180;
    const a = Math.sin(Δφ / 2) * Math.sin(Δφ / 2) + Math.cos(φ1) * Math.cos(φ2) * Math.sin(Δλ / 2) * Math.sin(Δλ / 2);
    const c = 2 * Math.atan2(Math.sqrt(a), Math.sqrt(1 - a));
    return R * c; // Distance in meters
};

const JoinGroupExamPage: React.FC = () => {
    const navigate = useNavigate();
    const { currentUser, userData } = useAuth();
    const query = useQuery();

    const [sessionIdInput, setSessionIdInput] = useState<string>('');
    const [currentStep, setCurrentStep] = useState<'idle' | 'verifyingId' | 'consent' | 'checkingGeo' | 'joining'>('idle');
    const [processError, setProcessError] = useState<string | null>(null);
    const [sessionToJoinDetails, setSessionToJoinDetails] = useState<GroupExam | null>(null);

    // Pre-fill from URL on mount
    useEffect(() => {
        const sessionIdFromQuery = query.get('sessionId');
        if (sessionIdFromQuery) {
            setSessionIdInput(sessionIdFromQuery);
        }
    }, [query]);

    const handleSessionIdSubmit = async (event?: React.FormEvent) => {
        if (event) event.preventDefault();
        if (!currentUser) { 
            toast.error("Please log in to join."); 
            return; 
        }
        if (!sessionIdInput.trim()) { 
            toast.error("Please enter a Session ID."); 
            return; 
        }

        const trimmedSessionId = sessionIdInput.trim();
        setCurrentStep('verifyingId');
        setProcessError(null);
        setSessionToJoinDetails(null);

        try {
            const groupExam = await getGroupExam(trimmedSessionId);
            if (!groupExam) {
                throw new Error("Session ID not found or session is invalid.");
            }
            // Check if session is closed or past end time already before showing consent
            const now = new Date();
            const endTimeDate = groupExam.endTime instanceof Date ? groupExam.endTime : (groupExam.endTime as any)?.toDate?.();
            if (groupExam.status === 'closed' || (endTimeDate && now > endTimeDate)) {
                throw new Error("This session is closed or has already ended.");
            }

            setSessionToJoinDetails(groupExam);

            if (groupExam.monitoringEnabled || groupExam.geoRestriction) {
                setCurrentStep('consent');
            } else {
                // No monitoring or geo-restriction, proceed to join directly
                setCurrentStep('joining');
                await actuallyJoinSession(trimmedSessionId, groupExam);
            }
        } catch (error: any) {
            handleProcessError(error, trimmedSessionId);
            setCurrentStep('idle');
        }
    };

    const handleProcessError = (error: any, attemptedSessionId: string) => {
        let userMessage = "An error occurred. Please check the ID and try again.";
        if (error.code === 'permission-denied') {
            userMessage = "Could not join: Session might be closed, not started yet, past its deadline, or the ID is incorrect.";
        } else if (error.message) {
            // Check for specific known error messages from getGroupExam if needed
            if (error.message.includes("Session ID not found")) {
                userMessage = "Invalid Session ID. Please check and try again.";
            } else {
                userMessage = error.message;
            }
        }
        setProcessError(userMessage);
        toast.error(userMessage);
        logEvent(analytics, 'group_session_join_failed', {
            session_id: attemptedSessionId,
            error_msg: error.message?.substring(0, 100)
        });
    };

    const performGeoCheckAndJoin = async (sessionId: string, restriction: GroupExam['geoRestriction'], groupExam: GroupExam) => {
        setCurrentStep('checkingGeo');
        setProcessError(null);

        if (!restriction) { // Should not happen if called correctly, but good check
            setCurrentStep('joining');
            await actuallyJoinSession(sessionId, groupExam);
            return;
        }

        if (!('geolocation' in navigator)) {
            setProcessError("Geolocation is not supported by your browser. Cannot join this session.");
            toast.error("Geolocation not supported.");
            setCurrentStep('consent'); // Go back to consent step or idle
            return;
        }

        navigator.geolocation.getCurrentPosition(
            async (position) => {
                const userPos = { lat: position.coords.latitude, lng: position.coords.longitude };
                const distance = calculateDistance(userPos.lat, userPos.lng, restriction.latitude, restriction.longitude);
                const isInZone = distance <= restriction.radiusMeters;

                if (isInZone) {
                    toast.success(`Location verified within zone (~${Math.round(distance)}m from center).`);
                    logEvent(analytics, 'group_geo_check_success', { session_id: sessionId, distance });
                    setCurrentStep('joining');
                    await actuallyJoinSession(sessionId, groupExam);
                } else {
                    setProcessError(`Location outside allowed zone. You are ~${Math.round(distance)}m from the center (allowed: ${restriction.radiusMeters}m). Please move closer and try again.`);
                    toast.error(`Location outside allowed zone.`);
                    logEvent(analytics, 'group_geo_check_failed_location', { session_id: sessionId, distance });
                    setCurrentStep('consent'); // Allow user to retry or cancel from consent
                }
            },
            (error) => {
                let msg = "Could not verify location. Please ensure location services are enabled and permission is granted.";
                if (error.code === error.PERMISSION_DENIED) msg = "Location permission denied. Please grant permission to join.";
                setProcessError(msg);
                toast.error(msg);
                logEvent(analytics, 'group_geo_check_failed_permission', { session_id: sessionId, code: error.code });
                setCurrentStep('consent'); // Allow user to retry or cancel
            },
            { enableHighAccuracy: true, timeout: 15000, maximumAge: 0 }
        );
    };

    const actuallyJoinSession = async (sessionId: string, groupExamDetails: GroupExam) => {
        if (!currentUser) {
            toast.error("User not authenticated.");
            return;
        }
        
        try {
            await addParticipantToGroupExam(sessionId, currentUser.uid, userData?.displayName || undefined);
            toast.success(`Successfully joined session: "${groupExamDetails.sessionName || sessionId}"!`);
            logEvent(analytics, 'group_session_joined', { 
                session_id: sessionId, 
                monitoring_enabled: groupExamDetails.monitoringEnabled 
            });

            const startTimeDate = groupExamDetails.startTime instanceof Date ? 
                groupExamDetails.startTime : 
                (groupExamDetails.startTime as any)?.toDate?.();

            if (startTimeDate && new Date() < startTimeDate) {
                navigate(`/group-exam/wait/${sessionId}`);
            } else {
                navigate(`/group-exam/session/${sessionId}`);
            }
        } catch (error: any) {
            handleProcessError(error, sessionId);
            setCurrentStep('idle'); // Reset to idle on final join failure
        }
        // No finally setIsProcessing(false) here; navigation handles unmount
    };

    const handleConsentConfirmed = async () => {
        if (sessionToJoinDetails && sessionToJoinDetails.id) {
            if (sessionToJoinDetails.geoRestriction) {
                await performGeoCheckAndJoin(sessionToJoinDetails.id, sessionToJoinDetails.geoRestriction, sessionToJoinDetails);
            } else {
                setCurrentStep('joining');
                await actuallyJoinSession(sessionToJoinDetails.id, sessionToJoinDetails);
            }
        } else {
            setProcessError("Session details are missing. Please try again.");
            setCurrentStep('idle');
        }
    };

    const handleConsentCancelled = () => {
        setCurrentStep('idle');
        setSessionIdInput(''); // Clear input
        setSessionToJoinDetails(null);
        setProcessError(null);
        toast.info("Join process cancelled.");
    };

    const consentMessageContent = useMemo(() => {
        if (!sessionToJoinDetails || (!sessionToJoinDetails.monitoringEnabled && !sessionToJoinDetails.geoRestriction)) {
            return null;
        }

        let monitoringPoints: string[] = [];
        if (sessionToJoinDetails.monitoringEnabled) {
            monitoringPoints = [
                "Tracking if you switch browser tabs or windows.",
                "Restricting copy and paste functionality.",
                "Logging attempts to use certain keyboard shortcuts (e.g., PrintScreen)."
            ];
        }
        if (sessionToJoinDetails.geoRestriction) {
            monitoringPoints.push("Verifying your current geographic location to ensure you are within the designated exam area.");
        }

        return (
            <div style={{ textAlign: 'left', lineHeight: '1.6' }}>
                <p>The host of the session <strong>"{sessionToJoinDetails.sessionName}"</strong> has enabled the following integrity measures:</p>
                {monitoringPoints.length > 0 && (
                    <ul style={{ paddingLeft: '20px', margin: '0.5rem 0 1rem 0' }}>
                        {monitoringPoints.map((point, index) => <li key={index}>{point}</li>)}
                    </ul>
                )}
                <p>This information may be made available to the session host.</p>
                <p><strong>By clicking "Agree & Proceed", you consent to these measures for this exam session.</strong></p>
                {processError && currentStep === 'consent' && <p className={styles.inlineErrorMessage}>{processError}</p>}
            </div>
        );
    }, [sessionToJoinDetails, processError, currentStep]);

    const isLoading = currentStep === 'verifyingId' || currentStep === 'joining' || currentStep === 'checkingGeo';

    return (
        <div className={styles.joinPage}>
            <h1>Join Group Exam Session</h1>
            <p className={styles.instructions}>
                Enter the Session ID provided by the host or use the link they shared.
            </p>

            {(currentStep === 'idle' || (!sessionToJoinDetails && currentStep !== 'consent')) && (
                <form onSubmit={handleSessionIdSubmit} className={styles.joinForm}>
                    <div className={styles.formGroup}>
                        <label htmlFor="sessionId">Session ID:</label>
                        <input
                            type="text"
                            id="sessionId"
                            value={sessionIdInput}
                            onChange={(e) => { setSessionIdInput(e.target.value); setProcessError(null); }}
                            placeholder="Enter session ID"
                            required
                            disabled={isLoading} // isLoading covers verifyingId, checkingGeo, joining
                            className={processError && currentStep === 'idle' ? styles.inputError : ''}
                        />
                    </div>

                    {/* Display error specific to ID verification failures, when in idle step */}
                    {processError && currentStep === 'idle' && (
                        <p className={styles.errorMessage}>{processError}</p>
                    )}

                    <button type="submit" disabled={isLoading || !sessionIdInput.trim()} className={styles.joinButton}>
                        {currentStep === 'verifyingId' ? <Spinner size="1em" /> : <FaSignInAlt />}
                        {currentStep === 'verifyingId' ? 'Verifying...' : 'Verify Session ID'}
                    </button>
                </form>
            )}

            {sessionToJoinDetails && consentMessageContent && (
                <ConfirmationModal
                    isOpen={currentStep === 'consent'}
                    title="Session Integrity Measures"
                    customContent={consentMessageContent}
                    onConfirm={handleConsentConfirmed}
                    onCancel={handleConsentCancelled}
                    confirmText={currentStep === 'checkingGeo' ? "Checking Location..." : "Agree & Proceed"}
                    cancelText="Cancel"
                    confirmButtonVariant="success"
                    size="md"
                />
            )}

            {/* Displaying geo check status more prominently if it fails and returns to consent step */}
            {(currentStep === 'checkingGeo' || (currentStep === 'consent' && sessionToJoinDetails?.geoRestriction && processError?.toLowerCase().includes('location'))) &&
             sessionToJoinDetails?.geoRestriction && (
                <div className={`${styles.geoStatusBox} ${currentStep === 'consent' ? styles.marginTopLarge : ''}`}>
                    {currentStep === 'checkingGeo' && <Spinner text="Verifying your location..." />}
                    
                    {processError && currentStep === 'consent' && ( // Only show error and retry if consent is active and error is present
                        <>
                            <FaMapMarkerAlt className={styles.errorIcon} />
                            <p className={styles.errorMessageNoBg}>{processError}</p>
                            <button
                                type="button"
                                onClick={handleConsentConfirmed} // This will re-trigger performGeoCheckAndJoin
                                className={styles.retryGeoButton}
                            >
                                Retry Location Check
                            </button>
                        </>
                    )}
                </div>
            )}
        </div>
    );
};

export default JoinGroupExamPage;
```

---

## pages\NotFoundPage


### pages\NotFoundPage\NotFoundPage.module.scss

```scss
// src/pages/NotFoundPage/NotFoundPage.module.scss
@import '../../styles/variables';
@import '../../styles/mixins';

.notFoundContainer {
    padding: $spacer * 3 $spacer * 2; // Generous padding
    text-align: center;
    background-color: $component-bg; // Optional: slight background differentiation
    border-radius: $border-radius-lg;
    // border: 1px solid $border-color; // Optional subtle border
    box-shadow: $box-shadow-md; // Optional shadow
    max-width: 600px; // Limit width of the 404 box itself
    margin: $spacer * 2 auto; // Center the box vertically and horizontally within the static page container
}

.notFoundIcon {
    color: $primary-color; // Or secondary color
    margin-bottom: $spacer * 1.5;
    opacity: 0.8;
}

.notFoundTitle {
    font-size: $h2-font-size; // Or keep as H1 size
    color: $danger-color; // Use danger color for emphasis
    margin-bottom: $spacer;
    font-weight: 600;
}

.notFoundMessage {
    font-size: $font-size-base * 1.1;
    color: $text-muted;
    margin-bottom: $spacer * 1.5;
    line-height: 1.6;
}

.suggestionMessage {
    font-weight: 500;
    margin-bottom: $spacer * 2;
    color: darken($text-muted, 10%);
}

.actionsContainer {
    display: flex;
    flex-direction: column; // Stack buttons on mobile
    align-items: center;
    justify-content: center;
    gap: $spacer;

    @include media-breakpoint-up(sm) {
        flex-direction: row; // Buttons side-by-side on larger screens
        gap: $spacer * 1.5;
    }
}

.actionButton {
    // Use mixin for consistent button styling
    @include button-variant(transparent, $secondary-color); // Default is secondary outline
    color: $secondary-color;
    padding: $spacer * 0.7 $spacer * 1.8;
    font-weight: 500;
    text-decoration: none;
    display: inline-flex;
    align-items: center;
    gap: $spacer * 0.6;
    min-width: 180px; // Ensure decent button width
    justify-content: center; // Center content in button

    &:hover {
        text-decoration: none;
        color: $dark-color; // Example hover text color
        border-color: $dark-color; // Example hover border
        background-color: $background-color-hover;
    }

    // Primary action styling
    &.primaryAction {
        @include button-variant($primary-color, $primary-color); // Primary button style
        color: $white-color; // Override text color if needed

        &:hover { // Ensure primary hover is defined if mixin doesn't cover it fully
             background-color: darken($primary-color, 7.5%);
             border-color: darken($primary-color, 10%);
             color: $white-color;
        }
    }

    svg {
        margin-right: $spacer * 0.4; // Use gap instead if preferred
    }
}
```

---

### pages\NotFoundPage\NotFoundPage.tsx

```typescript
// src/pages/NotFoundPage/NotFoundPage.tsx
import React, { useEffect } from 'react';
import { Link } from 'react-router-dom';
import { FaCompass, FaHome, FaTasks } from 'react-icons/fa'; // Import relevant icons
import styles from './NotFoundPage.module.scss'; // We'll create this SCSS file
import staticStyles from '../StaticPages/StaticPages.module.scss'; // Reuse container/basic styles

const NotFoundPage: React.FC = () => {
 
    useEffect(() => {
        document.title = 'Page Not Found (404) - Examify';
    }, []);


    return (
        // Use static page wrapper for basic centering and padding
        <div className={staticStyles.staticPage}>
             {/* Use container for content width control */}
            <div className={staticStyles.container}>
                 {/* Specific styling container for 404 content */}
                <div className={styles.notFoundContainer}>
                    <FaCompass className={styles.notFoundIcon} size={80} /> {/* Large icon */}

                    <h1 className={styles.notFoundTitle}>404 - Page Not Found</h1>

                    <p className={styles.notFoundMessage}>
                        Oops! It seems you've navigated uncharted territory. The page you were looking for doesn't exist or may have been moved.
                    </p>

                    <p className={styles.suggestionMessage}>
                        Don't worry, let's get you back on track. You can try:
                    </p>

                    <div className={styles.actionsContainer}>
                        <Link to="/" className={styles.actionButton}>
                            <FaHome /> Go to Homepage
                        </Link>
                        <Link to="/select-exam" className={`${styles.actionButton} ${styles.primaryAction}`}>
                            <FaTasks /> Go to Practice Selection
                        </Link>
                    </div>
                </div>
            </div>
        </div>
    );
};

export default NotFoundPage;
```

---

## pages\ProfilePage


### pages\ProfilePage\ProfilePage.module.scss

```scss
@import '../../styles/variables';
@import '../../styles/mixins';

.profilePage {
    padding: $spacer * 1.5 0;

    h1 {
        text-align: center;
        margin-bottom: $spacer * 2.5;
        color: $primary-color;
        display: flex;
        align-items: center;
        justify-content: center;
        gap: $spacer;
        .icon {
            font-size: $h2-font-size; // Slightly smaller than h1 text
        }
    }
}
.accountManagementSection {
     @extend .userInfo; // Reuse general section styling from .userInfo
    
     p { 
         margin-bottom: $spacer * 1.5; 
         font-size: $font-size-base;
         color: $text-color;
         line-height: 1.6;
     }
    }
    
    .portalProfileButton {
     @include button-variant($primary-color, $primary-color); 
     padding: $spacer * 0.75 $spacer * 1.5; 
     font-size: $font-size-base;
     font-weight: $font-weight-medium;
     text-decoration: none; 
     display: inline-flex; 
     align-items: center;
     gap: $spacer * 0.75; // Increased gap slightly for better icon spacing
    
     &:hover {
         text-decoration: none; 
     }
     svg { // If FaExternalLinkAlt needs specific sizing
         font-size: $font-size-base * 0.9; // Example size adjustment
     }
    }

.userInfo, .historySection {
    background-color: $component-bg;
    border: 1px solid $border-color;
    border-radius: $border-radius-lg;
    padding: $spacer * 1.5 $spacer * 2;
    margin-bottom: $spacer * 2;
    box-shadow: 0 2px 6px rgba($black-color, 0.07);

    h2 {
        font-size: $font-size-base * 1.3;
        color: $dark-color;
        margin-top: 0;
        margin-bottom: $spacer * 1.5;
        font-weight: 600;
        border-bottom: 1px solid $border-color;
        padding-bottom: $spacer * 0.75;
         display: flex;
         align-items: center;
         gap: $spacer * 0.75;
    }
}

.userInfo {
     ul {
         list-style: none;
         padding: 0;
         margin-bottom: $spacer * 1.5;
         li {
            margin-bottom: $spacer * 0.5;
            font-size: $font-size-base;
            color: $text-muted;
            strong {
                color: $text-color;
                margin-right: $spacer * 0.5;
                min-width: 120px; // Align values roughly
                display: inline-block;
            }
         }
     }
}

.logoutButton {
    @include button-variant($danger-color, $danger-color);
    padding: $spacer * 0.6 $spacer * 1.2;
     font-size: $font-size-base * 0.9;
}

.perkExpiry {
    font-size: $font-size-base * 0.8;
    // color: $text-muted; // Handled inline for conditional error color
    margin-left: $spacer * 0.5;
}

.tierFeaturesSummary {
    margin-top: $spacer * 0.75;
    padding-top: $spacer * 0.5;
    border-top: 1px dotted lighten($border-color, 5%);
    font-size: $font-size-base * 0.9;

    strong {
        color: $text-color;
    }
    ul {
        list-style: disc;
        padding-left: $spacer * 1.5; // Indent list items
        margin-top: $spacer * 0.25;
        margin-bottom: $spacer * 0.5;
        li {
            font-size: $font-size-base * 0.85;
            color: $text-muted;
            margin-bottom: $spacer * 0.2;
        }
    }
}

.upgradeLink { // Optional style for an upgrade link
    display: inline-block;
    font-size: $font-size-base * 0.85;
    font-weight: 500;
    color: $link-color;
    margin-top: $spacer * 0.25;
    &:hover {
        color: $link-hover-color;
    }
}

.statusMessage {
    padding: $spacer * 2 0;
    text-align: center;
    font-size: $font-size-base;
    color: $text-muted;

    &.error {
        color: $danger-color;
        font-weight: 500;
    }
}
.historyHeader {
    display: flex;
    flex-direction: column; // Stack on mobile
    gap: $spacer * 0.75;
    margin-bottom: $spacer * 1.5; // Space below header group
    padding-bottom: $spacer;
    border-bottom: 1px solid $border-color;


    @include media-breakpoint-up(md) {
        flex-direction: row; // Side by side on larger screens
        justify-content: space-between;
        align-items: center;
         margin-bottom: $spacer * 1.5;
    }
}

.limitInfo {
    display: flex;
    flex-direction: column;
    gap: $spacer * 0.3;
    width: 100%; // Full width on mobile

    @include media-breakpoint-up(md) {
        width: auto; // Auto width on larger screens
        min-width: 200px; // Ensure it has some space
        align-items: flex-end; // Align right
    }
}

.limitText {
    font-size: $font-size-base * 0.9;
    color: $text-muted;
    font-weight: 500;
    cursor: help; // Indicate tooltip presence
    display: inline-flex;
    align-items: center;
    gap: $spacer * 0.4;
}

.infoIcon {
    font-size: $font-size-base * 0.95;
    color: $secondary-color;
    margin-bottom: -1px; // Fine-tune alignment
}

.limitProgressBar {
    width: 100%;
    height: 10px; // Adjust height as needed
    border-radius: $border-radius-lg; // Match container rounding
    overflow: hidden; // Ensure value doesn't overflow border radius
    border: 1px solid darken($border-color, 5%);
    background-color: lighten($light-color, 2%); // Track background


    // Webkit styling (Chrome, Safari, Edge)
    &::-webkit-progress-bar {
        background-color: lighten($light-color, 2%);
        border-radius: $border-radius-lg;
    }

    &::-webkit-progress-value {
        border-radius: $border-radius-lg; // Apply to value bar as well
        transition: background-color 0.3s ease-in-out; // Smooth color transition
    }

    // Firefox styling
    &::-moz-progress-bar {
        border-radius: $border-radius-lg;
        transition: background-color 0.3s ease-in-out;
    }

    // Apply color classes to the value bar
    &.progressBarGreen {
        &::-webkit-progress-value { background-color: $success-color; }
        &::-moz-progress-bar { background-color: $success-color; }
    }
    &.progressBarYellow {
        &::-webkit-progress-value { background-color: $warning-color; }
        &::-moz-progress-bar { background-color: $warning-color; }
    }
    &.progressBarRed {
        &::-webkit-progress-value { background-color: $danger-color; }
        &::-moz-progress-bar { background-color: $danger-color; }
    }
}

.historyTableContainer {
     overflow-x: auto; // Make table horizontally scrollable on small screens
}

.historyTable {
    width: 100%;
    border-collapse: collapse;
    margin-top: $spacer;

    th, td {
        padding: $spacer $spacer * 1.2;
        text-align: left;
        border-bottom: 1px solid $border-color;
         vertical-align: middle;
    }

    th {
        background-color: lighten($light-color, 3%);
        font-weight: 600;
        font-size: $font-size-base * 0.9;
        color: $text-muted;
        text-transform: uppercase;
         white-space: nowrap;
    }

    tbody tr {
        transition: background-color 0.15s ease-in-out;
        &:hover {
            background-color: lighten($light-color, 4%);
        }
    }

    td {
        font-size: $font-size-base * 0.95;
         color: $text-color;
         white-space: nowrap; // Prevent wrapping by default

         // Allow title to wrap if necessary
         &:first-child {
            white-space: normal;
             font-weight: 500;
             min-width: 180px; // Ensure title column has some width
         }
          // Target specific columns if needed for wrapping or alignment
    }

    // Responsive Table: Use data-label for mobile view (optional but good UX)
    @media (max-width: map-get($grid-breakpoints, md)) {
        thead {
            display: none; // Hide table header
        }
         tr {
             display: block; // Stack rows
             margin-bottom: $spacer * 1.5;
             border: 1px solid $border-color;
             border-radius: $border-radius;
             padding: $spacer;
             box-shadow: 0 1px 3px rgba($black-color, 0.08);
         }
         td {
             display: block; // Stack cells
             text-align: right; // Align value to the right
             padding: $spacer * 0.6 0; // Adjust padding
             border-bottom: 1px dotted lighten($border-color, 5%); // Dotted line between "cells"
             white-space: normal; // Allow wrapping in mobile view

             &::before { // Add the label using data-label attribute
                content: attr(data-label);
                float: left; // Position label to the left
                font-weight: bold;
                margin-right: $spacer;
                text-transform: uppercase;
                font-size: $font-size-base * 0.85;
                color: $text-muted;
             }

              &:last-child {
                 border-bottom: none; // Remove border from last cell in stack
                 padding-bottom: 0;
              }
               // Ensure link aligns right correctly
               &:last-child a {
                   display: inline-block; // Treat link as block for alignment
               }
         }
    }
}

.viewResultLink {
    @include button-variant($info-color, $info-color);
     padding: $spacer * 0.4 $spacer * 0.8;
     font-size: $font-size-base * 0.85;
     text-decoration: none;
     display: inline-flex; // Align icon and text
     align-items: center;
     gap: $spacer * 0.4;

     &:hover {
        text-decoration: none;
     }
}

.actionCell {
    display: flex;
    gap: $spacer * 0.75;
    align-items: center;

    // Adjust for mobile stacked view if using data-label
    @media (max-width: map-get($grid-breakpoints, md)) {
       justify-content: flex-end; // Align buttons to the right
       padding-top: $spacer * 0.5; // Add some space above buttons
       // Reset flex direction if needed based on parent cell styling
    }
}

.deleteButton {
    @include button-variant($danger-color, $danger-color);
    padding: $spacer * 0.4 $spacer * 0.8;
    font-size: $font-size-base * 0.85;
    display: inline-flex; // Align icon and text
    align-items: center;
    gap: $spacer * 0.4;
    border: none; // Override potential default button borders
    white-space: nowrap; // Prevent wrapping

    &:disabled {
        cursor: not-allowed;
        opacity: 0.6;
         // Explicitly disable hover effects when disabled
         &:hover {
            background-color: $danger-color; // Keep original color
            border-color: $danger-color;
         }
    }
}

.newExamAction {
    text-align: center;
    margin-top: $spacer * 2;
    padding-top: $spacer * 1.5;
     border-top: 1px solid $border-color;
}

.newExamButton {
     @include button-variant($primary-color, $primary-color);
     padding: $spacer $spacer * 2;
     font-size: $font-size-base;
     text-decoration: none;
      &:hover {
         text-decoration: none;
     }
}

/* Modal Styles */
.modalOverlay {
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background-color: rgba($black-color, 0.5);
    display: flex;
    align-items: center;
    justify-content: center;
    z-index: 1000;
    backdrop-filter: blur(2px);
}

.modalContent {
    background-color: $component-bg;
    border-radius: $border-radius-lg;
    padding: $spacer * 2;
    box-shadow: 0 4px 12px rgba($black-color, 0.15);
    width: 100%;
    max-width: 450px;
    position: relative;
    
    h4 {
        margin-top: 0;
        margin-bottom: $spacer;
        color: $dark-color;
        font-size: $font-size-base * 1.2;
        font-weight: 600;
        padding-bottom: $spacer * 0.75;
        border-bottom: 1px solid $border-color;
    }
    
    p {
        margin-bottom: $spacer * 1.5;
        font-size: $font-size-base;
        color: $text-color;
        line-height: 1.5;
    }
}

.modalActions {
    display: flex;
    justify-content: flex-end;
    gap: $spacer;
    margin-top: $spacer * 1.5;
}

.modalButton {
    padding: $spacer * 0.6 $spacer * 1.5;
    border-radius: $border-radius;
    font-size: $font-size-base;
    font-weight: 500;
    cursor: pointer;
    transition: all 0.2s ease;
    
    &.cancel {
        @include button-variant(transparent, $border-color);
        color: $text-color;
        
        &:hover {
            background-color: lighten($light-color, 2%);
        }
    }
    
    &.confirm {
        @include button-variant($danger-color, $danger-color);
        color: white;
    }
}

/* Animation for spinner icon */
@keyframes spin {
    0% { transform: rotate(0deg); }
    100% { transform: rotate(360deg); }
}

.spin-icon {
    animation: spin 1s linear infinite;
}
.emptyStateContainer { 
    padding: $spacer * 3 0;
    text-align: center;
    color: $text-muted;
    border: 1px dashed $border-color; // Optional dashed border
    border-radius: $border-radius;
    margin: $spacer 0; // Add some margin
    background-color: lighten($light-color, 3%); // Subtle background
}

.emptyStateIcon {
    color: $primary-color; // Or a muted color
    margin-bottom: $spacer;
    opacity: 0.7;
}

.emptyStateText {
    font-size: $font-size-base * 1.05;
    font-weight: 500;
    margin-bottom: $spacer * 0.5;
     color: darken($text-muted, 10%);
}

.emptyStateSubtext {
    font-size: $font-size-base * 0.9;
    margin-bottom: 0;
}
```

---

### pages\ProfilePage\ProfilePage.tsx

```typescript
// src/pages/ProfilePage/ProfilePage.tsx
import React, { useState, useEffect, useCallback, useMemo } from 'react';
import { Link } from 'react-router-dom';
import { useAuth } from '../../contexts/AuthContext'; // Corrected path
import { 
    getAllUserAttempts, 
    deleteAttemptResult,
    checkGroupExamExists,
    deleteGroupParticipantRecord 
} from '../../services/firestoreService';
import { AttemptResult } from '../../types'; // ATTEMPT_LIMIT removed
import styles from './ProfilePage.module.scss';
import { FaUser, FaHistory, FaExternalLinkAlt, FaTrash, FaInfoCircle, FaPlayCircle, FaCog } from 'react-icons/fa'; // Added FaCog
import { formatDuration, formatTimestamp } from '../../utils/formatters';
import { toast } from 'react-toastify';
import Spinner from '../../components/Spinner/Spinner'; // Corrected path
import { Timestamp } from 'firebase/firestore'; // Ensure Timestamp is imported

// Import useUserPerks from Examify's hooks
import { useUserPerks } from '../../hooks/useUserPerks'; // Corrected path

// Add id to AttemptResult type for local use
type AttemptResultWithId = AttemptResult & { id: string; groupSessionId?: string };

// ConfirmationModal Component (Assuming it's local to ProfilePage or moved to common modal)
interface ConfirmationModalProps {
    isOpen: boolean;
    onConfirm: () => void;
    onCancel: () => void;
    title: string;
    message: string;
    confirmButtonType?: 'primary' | 'danger';
}

const ConfirmationModal: React.FC<ConfirmationModalProps> = ({ 
    isOpen, 
    onConfirm, 
    onCancel, 
    title, 
    message,
    confirmButtonType = 'primary'
}) => {
    if (!isOpen) return null;

    return (
        <div className={styles.modalOverlay} onClick={onCancel}>
            <div className={styles.modalContent} onClick={(e) => e.stopPropagation()}>
                <h4>{title}</h4>
                <p>{message}</p>
                <div className={styles.modalActions}>
                    <button onClick={onCancel} className={`${styles.modalButton} ${styles.cancel}`}>Cancel</button>
                    <button 
                        onClick={onConfirm} 
                        className={`${styles.modalButton} ${confirmButtonType === 'danger' ? styles.danger : styles.confirm}`}
                    >
                        Confirm
                    </button>
                </div>
            </div>
        </div>
    );
};

const ProfilePage: React.FC = () => {
    const { currentUser, userData, logout } = useAuth();
    // *** USE THE EXAMIFY useUserPerks HOOK ***
    const { limits: perkLimits, isLoadingPerks, currentTier, hasActivePerk: userHasActivePaidPerk, features:perkFeatures } = useUserPerks();
    
    const [attempts, setAttempts] = useState<AttemptResultWithId[]>([]);
    const [isLoadingHistory, setIsLoadingHistory] = useState<boolean>(true); // Renamed for clarity
    const [error, setError] = useState<string | null>(null);
    const [isDeleting, setIsDeleting] = useState<boolean>(false);
    const [showConfirmModal, setShowConfirmModal] = useState(false);
    const [actionAttemptId, setActionAttemptId] = useState<string | null>(null);
    const [modalConfig, setModalConfig] = useState<{ 
        title: string; 
        message: string; 
        onConfirm: () => void; 
        isDanger?: boolean 
    } | null>(null);
    
    useEffect(() => {
        document.title = currentUser ? `${userData?.displayName || 'User'}'s Profile - Examify` : 'Profile - Examify';
    }, [currentUser, userData?.displayName]);
    
    useEffect(() => {
        const fetchHistory = async () => {
            if (!currentUser) {
                setError("User not logged in.");
                setIsLoadingHistory(false);
                return;
            }

            setIsLoadingHistory(true);
            setError(null);
            try {
                const userAttempts = await getAllUserAttempts(currentUser.uid);
                setAttempts(userAttempts);
            } catch (err: any) {
                setError(err.message || "Failed to load attempt history.");
            } finally {
                setIsLoadingHistory(false);
            }
        };

        fetchHistory();
    }, [currentUser]);

    const calculatePercentage = (score: number, maxScore: number): string => {
        if (maxScore <= 0) return 'N/A';
        return ((score / maxScore) * 100).toFixed(1) + '%';
    };

    const handleLogout = async () => {
        try {
            await logout();
        } catch (error: any) {
            toast.error(error.message || "Logout Failed");
        }
    }

    const handleDeleteAttempt = useCallback(async (attempt: AttemptResultWithId) => {
        if (!currentUser || isDeleting) return;

        setActionAttemptId(attempt.id);
        setIsDeleting(true);
        setError(null);

        let proceedToDelete = false;
        let participantRecordToDelete: { sessionId: string; userId: string } | null = null;
        let confirmationMessage = `Are you sure you want to delete this attempt from your history? This action cannot be undone.`;
        let confirmationTitle = "Confirm Delete Attempt";

        try {
            if (attempt.groupSessionId) {
                const sessionExists = await checkGroupExamExists(attempt.groupSessionId);

                if (sessionExists) {
                    toast.warn("This attempt is part of an active group session. It can only be deleted after the host removes the session configuration.");
                    setIsDeleting(false);
                    setActionAttemptId(null);
                    return;
                } else {
                    proceedToDelete = true;
                    participantRecordToDelete = { sessionId: attempt.groupSessionId, userId: currentUser.uid };
                    confirmationMessage = `The host has deleted the original group session configuration. Deleting this attempt from your history will also remove your participation record from that session. This action cannot be undone.`;
                    confirmationTitle = "Confirm Delete Group Attempt";
                }
            } else {
                proceedToDelete = true;
            }

            if (proceedToDelete) {
                setModalConfig({
                    title: confirmationTitle,
                    message: confirmationMessage,
                    isDanger: true,
                    onConfirm: async () => {
                        setShowConfirmModal(false);
                        try {
                            if (participantRecordToDelete) {
                                await deleteGroupParticipantRecord(
                                    participantRecordToDelete.sessionId,
                                    participantRecordToDelete.userId
                                );
                            }
                            await deleteAttemptResult(currentUser.uid, attempt.id);
                            setAttempts(prevAttempts => prevAttempts.filter(att => att.id !== attempt.id));
                            toast.success("Attempt deleted successfully.");
                        } catch (deleteError: any) {
                            const userFriendlyDeleteError = deleteError.message?.includes("group session") 
                                ? deleteError.message 
                                : "Failed to delete the attempt. Please try again.";
                            toast.error(userFriendlyDeleteError);
                            setError(userFriendlyDeleteError);
                        } finally {
                            setIsDeleting(false);
                            setActionAttemptId(null);
                        }
                    },
                });
                setShowConfirmModal(true);
            }

        } catch (checkError: any) {
            toast.error(checkError.message || "Could not verify group session status.");
            setError(checkError.message || "Could not verify group session status.");
            setIsDeleting(false);
            setActionAttemptId(null);
        }
    }, [currentUser, isDeleting]); // Removed addToast as it's called directly

    const closeConfirmationModal = () => {
        setShowConfirmModal(false);
        setIsDeleting(false);
        setActionAttemptId(null);
        setModalConfig(null);
    };

    const getProgressBarClass = (count: number, limit: number): string => {
        if (limit === Infinity || limit <= 0) return styles.progressBarGreen;
        const percentage = (count / limit) * 100;
        if (percentage >= 90) return styles.progressBarRed;
        if (percentage >= 70) return styles.progressBarYellow;
        return styles.progressBarGreen;
    };
    
    const currentAttemptCount = attempts.length;
    // *** MODIFIED: Use perkLimits from Examify's useUserPerks ***
    const attemptLimit = perkLimits.examAttempts === null ? Infinity : perkLimits.examAttempts;
    // *** MODIFIED: Account for isLoadingPerks ***
    const progressBarClass = isLoadingPerks ? styles.progressBarGreen : getProgressBarClass(currentAttemptCount, attemptLimit);

    // Format expiry date from UserData if perk is active
    const perkExpiryDateFormatted = useMemo(() => {
        if (userHasActivePaidPerk && userData?.perkExpiry) {
            const expiry = userData.perkExpiry instanceof Timestamp ? userData.perkExpiry.toDate() : userData.perkExpiry;
            return formatTimestamp(expiry);
        }
        return null;
    }, [userHasActivePaidPerk, userData?.perkExpiry]);


    if (isLoadingPerks && !userData) { // Show primary loading if perks and user data are still loading
        return (
            <div className={styles.profilePage}>
                <div className={styles.statusMessage}><Spinner text="Loading profile..." size={24} /></div>
            </div>
        );
    }

    return (
        <div className={styles.profilePage}>
            <h1><FaUser className={styles.icon}/> User Profile & History</h1>

            <section className={styles.userInfo}>
                <h2>My Information</h2>
                {isLoadingPerks && !userData && <Spinner text="Loading user info..." />} {/* Show loading if only perks are loading but no user data yet */}
                {userData ? (
                    <ul>
                        <li><strong>Display Name:</strong> {userData.displayName || 'N/A'}</li>
                        <li><strong>Email:</strong> {userData.email || 'N/A'}</li>
                        <li><strong>Username:</strong> {userData.username || 'N/A'}</li>
                        <li>
                            <strong>Membership Tier:</strong>{' '}
                            {isLoadingPerks ? (
                                <Spinner size="0.8em" />
                            ) : (
                                <>
                                    {/* *** MODIFIED: Display currentTier.name from Examify's useUserPerks *** */}
                                    <span style={{ fontWeight: 'bold', color: currentTier?.id === 'free' ? 'var(--text-muted-color)' : 'var(--success-color)' }}>
                                        {currentTier?.name || 'Free Plan'} 
                                    </span>
                                    {/* *** MODIFIED: Use userHasActivePaidPerk and perkExpiryDateFormatted for expiry display *** */}
                                    {userHasActivePaidPerk && perkExpiryDateFormatted && (
                                        <small className={styles.perkExpiry}>
                                            (Expires: {perkExpiryDateFormatted})
                                        </small>
                                    )}
                                    {/* Logic for displaying reverted to Free due to expiry can be added if needed based on effectiveTier vs userData.perkLevel */}
                                </>
                            )}
                        </li>
                        {/* *** MODIFIED: Display key limits from Examify's useUserPerks *** */}
                        {currentTier && !isLoadingPerks && (
                            <li className={styles.tierFeaturesSummary}>
                                <strong>Key Limits for Your Current Tier ({currentTier.name}):</strong>
                                <ul>
                                    <li>Attempt History Saved: {perkLimits.examAttempts === null ? 'Unlimited' : perkLimits.examAttempts}</li>
                                    {/* Hosted Sessions limit displayed on Host Dashboard */}
                                </ul>
                                <Link to="https://bcaexamprep.web.app/perks" target="_blank" rel="noopener noreferrer" className={styles.upgradeLink}> {/* Changed to MyServices Portal perks page */}
                                     {currentTier.id === 'free' ? 'View Plans / Upgrade' : 'Manage Subscription'}
                                </Link>
                            </li>
                        )}
                    </ul>
                ) : (
                    !isLoadingPerks && <p>User data not available. Please try logging in again.</p>
                )}
                <button onClick={handleLogout} className={styles.logoutButton}>Logout</button>
            </section>

  <section className={styles.accountManagementSection}>
      <h2><FaCog style={{ marginRight: '8px' }} />Account Management</h2>
      <p>
          For enhanced security and to manage your display name, password, or other account settings, 
          please visit your unified profile on the MyServices Portal.
      </p>
      <a
          href="https://bcaexamprep.web.app/profile" // URL to MyServices Portal Profile
          target="_blank"
          rel="noopener noreferrer"
          className={styles.portalProfileButton}
      >
          <FaExternalLinkAlt />
          Go to MyServices Portal Profile
      </a>
  </section>

            <section className={styles.historySection}>
                <div className={styles.historyHeader}>
                    <h2><FaHistory className={styles.icon}/> Attempt History</h2>
                    <div className={styles.limitInfo}>
                        {isLoadingPerks || isLoadingHistory ? ( // Combined loading check
                            <Spinner size="0.9em" text="Loading limits..." />
                        ) : (
                            <>
                                {/* *** MODIFIED: Tooltip text to use currentTier.name from Examify's useUserPerks *** */}
                                <span
                                    className={styles.limitText}
                                    title={`Your current tier (${currentTier?.name || 'Free'}) allows you to save ${attemptLimit === Infinity ? 'unlimited' : attemptLimit} attempts.`}
                                >
                                    History Saved: {currentAttemptCount} / {attemptLimit === Infinity ? 'Unlimited' : attemptLimit}
                                    <FaInfoCircle className={styles.infoIcon} />
                                </span>
                                {attemptLimit !== Infinity && (
                                    <progress
                                        className={`${styles.limitProgressBar} ${progressBarClass}`}
                                        max={attemptLimit}
                                        value={currentAttemptCount}
                                        title={`${currentAttemptCount}/${attemptLimit} attempts saved`}
                                    ></progress>
                                )}
                            </>
                        )}
                    </div>
                </div>

                {(isLoadingHistory || isLoadingPerks) && !error && <p className={styles.statusMessage}><Spinner text="Loading history..." size={24} /></p>}
                {error && <p className={`${styles.statusMessage} ${styles.error}`}>{error}</p>}

                {!isLoadingHistory && !isLoadingPerks && !error && (
                    attempts.length === 0 ? (
                        <div className={styles.emptyStateContainer}>
                            <FaPlayCircle size={30} className={styles.emptyStateIcon} />
                            <p className={styles.emptyStateText}>You haven't completed any practice sessions yet.</p>
                            <p className={styles.emptyStateSubtext}>Start practicing to see your results here!</p>
                        </div>
                    ) : (
                        <div className={styles.historyTableContainer}>
                            <table className={styles.historyTable}>
                                <thead>
                                    <tr>
                                        <th>Exam Title</th>
                                        <th>Date</th>
                                        <th>Score</th>
                                        <th>Percentage</th>
                                        <th>Time Taken</th>
                                        <th>Action</th>
                                    </tr>
                                </thead>
                                <tbody>
                                    {attempts.map((attempt) => (
                                        <tr key={attempt.id}>
                                            <td data-label="Exam Title">{attempt.examTitle} {attempt.isUserUploaded && '(Custom)'} {attempt.groupSessionId && <Link to={`/group-exam/dashboard?highlight=${attempt.groupSessionId}`} title="View Group Session (Host Dashboard)">(Group)</Link>}</td>
                                            <td data-label="Date">{formatTimestamp(
                                               attempt.attemptTimestamp instanceof Date
                                                   ? attempt.attemptTimestamp
                                                   : (attempt.attemptTimestamp as any)?.toDate ? (attempt.attemptTimestamp as any).toDate() : undefined
                                           )}</td>
                                            <td data-label="Score">{attempt.score} / {attempt.maxScore}</td>
                                            <td data-label="Percentage">{calculatePercentage(attempt.score, attempt.maxScore)}</td>
                                            <td data-label="Time Taken">{formatDuration(attempt.timeTakenSeconds)}</td>
                                            <td data-label="Action" className={styles.actionCell}>
                                                {/* Ensure Review link considers if questions are available for review based on source */}
                                                { (attempt.examPath || (attempt.isUserUploaded && attempt.questionJsonString && perkFeatures.canReviewCustomUploads)) ? (
                                                    <Link
                                                        to={`/review/${attempt.id}`}
                                                        className={styles.viewResultLink}
                                                        title="Review Answers & Explanations"
                                                    >
                                                        Review <FaExternalLinkAlt size={12}/>
                                                    </Link>
                                                ) : (
                                                    <span className={styles.viewResultLink} style={{opacity:0.5, cursor:'not-allowed'}} title={attempt.isUserUploaded && !perkFeatures.canReviewCustomUploads ? `Review for custom uploads is a premium feature. (Your tier: ${currentTier?.name})` : "Review not available for this attempt."}>
                                                        Review (N/A)
                                                    </span>
                                                )}
                                                <Link
                                                    to={`/results/${attempt.id}`}
                                                    className={styles.viewResultLink}
                                                    style={{backgroundColor: '#6c757d', borderColor: '#6c757d', color: 'white'}} /* Secondary style */
                                                    title="View Results Summary"
                                                >
                                                    Summary <FaExternalLinkAlt size={12}/>
                                                </Link>
                                                <button
                                                    onClick={() => handleDeleteAttempt(attempt)}
                                                    className={styles.deleteButton}
                                                    disabled={isDeleting && actionAttemptId === attempt.id}
                                                    title="Delete Attempt"
                                                >
                                                    {(isDeleting && actionAttemptId === attempt.id) ? <Spinner size="0.85em" /> : <FaTrash size={12}/>}
                                                    {(isDeleting && actionAttemptId === attempt.id) ? '' : ' Delete'}
                                                </button>
                                            </td>
                                        </tr>
                                    ))}
                                </tbody>
                            </table>
                        </div>
                    )
                )}
                {(!isLoadingHistory || !isLoadingPerks) && (
                    <div className={styles.newExamAction}>
                        <Link to="/select-exam" className={styles.newExamButton}>Start New Practice</Link>
                    </div>
                )}
            </section>

            {modalConfig && (
                <ConfirmationModal
                    isOpen={showConfirmModal}
                    onConfirm={modalConfig.onConfirm}
                    onCancel={closeConfirmationModal}
                    title={modalConfig.title}
                    message={modalConfig.message}
                    confirmButtonType={modalConfig.isDanger ? 'danger' : 'primary'}
                />
            )}
        </div>
    );
};

export default ProfilePage;
```

---

## pages\ResultsPage


### pages\ResultsPage\ResultsPage.module.scss

```scss
// src/pages/ResultsPage/ResultsPage.module.scss
@import '../../styles/variables';
@import '../../styles/mixins';

.resultsPage {
  padding: map-get($spacers, 4) 0 map-get($spacers, 5); // py-4 my-5

  h1 {
    text-align: center;
    margin-bottom: map-get($spacers, 5); // mb-5, more space below main title
    color: $primary-color;
    font-weight: $font-weight-semibold; // Bolder title
  }
}

.statusMessage { // For loading/error states
  padding: map-get($spacers, 6) map-get($spacers, 4);
  text-align: center;
  min-height: 60vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  gap: map-get($spacers, 3);

  &.error {
    // Using new ErrorMessage component conventions is better, but if local:
    background-color: lighten($red-500, 50%);
    border: 1px solid lighten($red-500, 30%);
    border-radius: $border-radius-lg; // Softer radius
    padding: map-get($spacers, 5);     // p-5
    color: darken($red-500, 15%);
    max-width: 600px;
    margin: 0 auto; // Center error box
    h2 {
      color: $red-500;
      margin-bottom: map-get($spacers, 2);
      font-size: $h4-font-size;
    }
    p { font-size: $font-size-base; }
  }
}

.summaryGrid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); // Min width for cards
  gap: map-get($spacers, 4); // gap-4 (24px)
  margin-bottom: map-get($spacers, 5); // mb-5
}

.summaryBox {
  background-color: $component-bg; // $white-color
  border: 1px solid $gray-200;    // Lighter border
  border-radius: $border-radius-lg; // 8px
  padding: map-get($spacers, 4);    // p-4 (24px)
  box-shadow: $box-shadow-md;     // Softer shadow than -lg
  display: flex;
  flex-direction: column;
  // align-items: center; // Let content align naturally, center text where needed
  // text-align: center; // Remove default text-align center
  transition: transform $transition-fast, box-shadow $transition-medium;

  &:hover { // Subtle hover lift
    transform: translateY(-3px);
    box-shadow: $box-shadow-lg; // Slightly more prominent shadow on hover
  }

  h2 { // Titles within summary boxes (e.g., "Score", "Performance")
    font-size: $font-size-base * 1.15; // Slightly larger (1.15rem)
    color: $gray-700; // Dark gray text
    margin-top: 0;
    margin-bottom: map-get($spacers, 3); // mb-3 (16px)
    font-weight: $font-weight-semibold; // Bolder box titles
    width: 100%;
    padding-bottom: map-get($spacers, 2); // pb-2 (8px)
    border-bottom: 1px solid $gray-100; // Very subtle separator
    text-align: left; // Align box titles left for a more standard card layout
  }

  // For boxes where content should be centered (like ScoreBox)
  &.textCenteredContent {
    align-items: center;
    text-align: center;
    h2 { text-align: center; } // Center title too if content is centered
  }
}

.scoreBox { // Specific styling for the main score box
  // Make it stand out more
  background-color: lighten($primary-color, 56%); // Very light primary background
  border-color: $primary-color; // Primary border
  color: darken($primary-color, 10%); // Text color to contrast with light primary bg

  h2 {
    color: $primary-color; // Title uses primary color
    border-bottom-color: lighten($primary-color, 40%); // Lighter primary separator
  }
}

.scoreValue {
  font-size: $h1-font-size * 0.9; // Large score (e.g., 2.25rem * 0.9)
  font-weight: $font-weight-bold; // Very bold
  line-height: 1.1;
  margin-bottom: map-get($spacers, 1); // mb-1
  color: $primary-color; // Score value in primary color
}

.percentage {
  font-size: $font-size-base * 1.2; // Larger percentage
  font-weight: $font-weight-medium;
  color: $gray-600; // Muted color for percentage normally

  .scoreBox & { // Percentage within the score box
    color: darken($primary-color, 5%); // Less muted for score box
  }
}

.detailsList {
  list-style: none;
  padding: 0;
  margin: 0;
  width: 100%;
  display: flex;
  flex-direction: column;
  gap: map-get($spacers, 2); // gap-2 (8px)

  li {
    display: flex;
    justify-content: space-between; // Label left, value right
    align-items: center;
    font-size: $font-size-base * 0.95; // Slightly smaller list item text
    padding: map-get($spacers, 1) 0; // py-1, some vertical padding for each item
    border-bottom: 1px solid $gray-100; // Subtle separator for list items

    &:last-child {
      border-bottom: none;
    }

    .itemLabel { // Explicit class for the label part (Correct, Incorrect, etc.)
      display: flex;
      align-items: center;
      gap: map-get($spacers, 2); // gap-2 for icon and text
      color: $text-color;
    }

    .itemValue { // Explicit class for the value part
      font-weight: $font-weight-semibold; // Bolder value
      color: $gray-700; // Dark gray for values
    }
  }
}
// --- Styles for NEW Subject & Topic Performance Box ---
.subjectTopicPerformanceBox { // Can inherit from .summaryBox
  // If you need specific styles different from general .summaryBox or .chartBox
  h2 { // Shared title style
      display: flex;
      align-items: center;
      svg { margin-right: map-get($spacers, 2); }
  }
}

.subjectTopicListContainer {
  margin-top: map-get($spacers, 3); // Space below the title
  // maxHeight and overflowY are set inline for now, can be moved here
}

.subjectGroup {
  margin-bottom: map-get($spacers, 3); // Space between subjects
  padding-bottom: map-get($spacers, 2);
  border-bottom: 1px dotted $gray-200; // Separator between subjects

  &:last-child {
      margin-bottom: 0;
      border-bottom: none;
      padding-bottom: 0;
  }
}

.subjectTitleInList {
  font-size: $font-size-base * 1.05; // Slightly larger than base
  font-weight: $font-weight-semibold;
  color: $gray-800;
  margin-bottom: map-get($spacers, 2); // Space between subject title and its topics
  display: flex;
  justify-content: space-between; // Pushes overall score to the right
  align-items: baseline;
}

.subjectOverallScore {
  font-size: $font-size-base * 0.85;
  font-weight: $font-weight-normal;
  color: $text-muted;
  background-color: $gray-100;
  padding: 2px map-get($spacers, 2);
  border-radius: $border-radius-sm;
}

.topicList {
  list-style: none;
  padding-left: map-get($spacers, 3); // Indent topics under subject
  margin: 0;
}

.topicItem {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: map-get($spacers, 1) 0; // Vertical padding for topic items
  font-size: $font-size-base * 0.9;
  color: $gray-700;
  border-bottom: 1px solid $gray-100; // Very subtle separator between topics

  &:last-child {
      border-bottom: none;
  }
}

.topicIcon {
  margin-right: map-get($spacers, 1);
  color: $secondary-color; // Or primary-color
  font-size: $font-size-base * 0.8;
}

.topicName {
  // flex-grow: 1; // Allow topic name to take available space if needed
  display: flex;
  align-items: center;
}

.topicScore {
  font-weight: $font-weight-medium;
  color: $gray-600;
  white-space: nowrap; // Prevent score from wrapping
  margin-left: map-get($spacers, 2);
}

.chartBox {
  // Padding and background are handled by .summaryBox
  // h2 styling also inherited from .summaryBox h2
  & > div { // Targets the direct div child (often the ResponsiveContainer wrapper)
    margin-top: map-get($spacers, 1); // Add some space below title before chart
  }
}

// Icons for details list
.icon {
  font-size: $font-size-base * 1.1; // Icon size
  flex-shrink: 0;
  width: 20px;
  text-align: center;
  margin-right: map-get($spacers, 1); // Added consistent right margin to all icons in list
}

.correctIcon { color: $success-color; }
.incorrectIcon { color: $danger-color; }
.unattemptedIcon { color: $secondary-color; }
.detailsIcon { color: $info-color; } // Changed from primary to info for distinction

.actions {
  text-align: center;
  display: flex;
  justify-content: center;
  gap: map-get($spacers, 3); // gap-3 (16px)
  flex-wrap: wrap;
  margin-top: map-get($spacers, 5); // mt-5
  padding-top: map-get($spacers, 4); // pt-4
  border-top: 1px solid $gray-200; // Lighter top border
}

.actionButton { // Base styles for action buttons below summary
  padding: map-get($spacers, 2) map-get($spacers, 4); // py-2 px-4
  font-size: $font-size-base;
  font-weight: $font-weight-medium;
  min-width: 200px; // Ensure good width for main actions
  gap: map-get($spacers, 2);

  &.primary { // "Start New Exam"
    @include button-variant($primary-color);
  }
  &.secondary { // "Review Answers" - make it visually distinct
    // Using a secondary/info color solid button
    @include button-variant($info-color);
    // Or an outline primary button:
    // @include button-variant(transparent, $primary-color, $primary-color, $is-outline: true);
  }
  &.default { // "View Full History" - subtle outline button
     @include button-variant(
      transparent, $gray-400, $gray-700, $is-outline: true
    );
  }
  // Disabled state handled by mixin
}
```

---

### pages\ResultsPage\ResultsPage.tsx

```typescript
// src/pages/ResultsPage/ResultsPage.tsx
import React, { useEffect, useState, useMemo } from 'react';
import { useParams, useLocation, Link } from 'react-router-dom';
import {
    PieChart, Pie, Cell, Tooltip, Legend, ResponsiveContainer,
    BarChart, Bar, XAxis, YAxis, CartesianGrid, LabelList // Added LabelList for BarChart
} from 'recharts';
import { useAuth } from '../../contexts/AuthContext';
import { getAttemptResult, getGroupExam } from '../../services/firestoreService';
import { AttemptResult, GroupExam, Question } from '../../types';
import styles from './ResultsPage.module.scss';
import { 
    FaCheckCircle, FaTimesCircle, FaMinusCircle, FaClock, FaCog, FaCalendarAlt, 
    FaChartPie, FaExternalLinkAlt, FaBook, FaTags, FaStarHalfAlt // Added FaStarHalfAlt
} from 'react-icons/fa';
import { formatDuration, formatTimestamp } from '../../utils/formatters';
import Leaderboard from '../../components/Leaderboard/Leaderboard';
import Spinner from '../../components/Spinner/Spinner';
// Import useUserPerks to check reviewability of custom uploads based on perks
import { useUserPerks } from '../../hooks/useUserPerks';

// Helper to check if end time has passed (remains the same)
const hasEndTimePassed = (endTime: Date | null | undefined): boolean => {
    if (!endTime) return true;
    return new Date() > endTime;
};

// Interface for subject performance data
interface SubjectPerformanceData {
    subject: string;
    correct: number;
    incorrect: number;
    unattempted: number;
    total: number;
    topics: TopicPerformanceData[]; // NEW: Nested topics
}

// NEW: Interface for topic performance data
interface TopicPerformanceData {
    topic: string;
    correct: number;
    incorrect: number;
    unattempted: number;
    total: number;
}

// NEW: Interface for difficulty performance data
interface DifficultyPerformanceData {
    difficulty: string; // "Easy", "Medium", "Hard", "Not Specified"
    correct: number;
    incorrect: number;
    unattempted: number;
    total: number;
}

const ResultsPage: React.FC = () => {
    const { attemptId } = useParams<{ attemptId: string }>();
    const location = useLocation();
    const { currentUser } = useAuth();
    const { features: perkFeatures, isLoadingPerks } = useUserPerks(); // Get perk features

    const [attemptResult, setAttemptResult] = useState<AttemptResult | null>(null);
    const [groupExamDetails, setGroupExamDetails] = useState<GroupExam | null>(null);
    const [questions, setQuestions] = useState<Question[] | null>(null); // NEW: State for questions
    const [isLoading, setIsLoading] = useState<boolean>(true);
    const [error, setError] = useState<string | null>(null);

    const QUESTIONS_REPO_BASE_URL = 'https://raw.githubusercontent.com/Samkarya/online-exam-questions/refs/heads/main/';


    useEffect(() => {
        let isMounted = true;
        const fetchResultAndQuestionData = async () => {
            if (!attemptId) {
                if(isMounted) {setError("Invalid attempt ID."); setIsLoading(false);}
                return;
            }
            // Don't proceed if perks are still loading, as they might be needed for question access decisions
            if (isLoadingPerks) {
                // setIsLoading(true); // Or keep existing isLoading true
                return;
            }

            setIsLoading(true); setError(null); setGroupExamDetails(null); setQuestions(null);
            let fetchedAttempt: AttemptResult | null = null;
            let needsGroupDetailsFetch = false;

            const stateResult = location.state?.resultData as AttemptResult | undefined;
            if (stateResult && (stateResult.id === attemptId || attemptId.startsWith('local_'))) {
                fetchedAttempt = stateResult;
                if (fetchedAttempt?.groupSessionId) needsGroupDetailsFetch = true;
            } else if (currentUser) {
                 try {
                     fetchedAttempt = await getAttemptResult(currentUser.uid, attemptId);
                     if (!isMounted) return;
                     if (!fetchedAttempt) throw new Error(`Attempt result not found for ID: ${attemptId}`);
                     if (fetchedAttempt.groupSessionId) needsGroupDetailsFetch = true;
                 } catch (err: any) {
                      if (isMounted) { setError(err.message || "Failed to fetch results."); setIsLoading(false); }
                      return;
                 }
            } else {
                 if (isMounted) { setError("You must be logged in to view past results."); setIsLoading(false); }
                 return;
            }

            if (!isMounted || !fetchedAttempt) {
                if(isMounted && !fetchedAttempt && !error) setError("Attempt data could not be loaded.");
                if(isMounted) setIsLoading(false);
                return;
            }
            
            if (isMounted) setAttemptResult(fetchedAttempt);

            // Fetch questions if path or JSON string exists
            let fetchedQuestions: Question[] | null = null;
            if (fetchedAttempt.examPath && !fetchedAttempt.isUserUploaded) {
                try {
                    const fetchUrl = `${QUESTIONS_REPO_BASE_URL}${fetchedAttempt.examPath}`;
                    const response = await fetch(fetchUrl);
                    if (!isMounted) return;
                    if (!response.ok) throw new Error(`Failed to fetch question paper (${response.status}) for results page.`);
                    fetchedQuestions = await response.json();
                } catch (qError: any) {
                    if(isMounted) console.error("Error fetching official questions for results:", qError.message);
                    // Proceed without questions for now, breakdowns will be limited
                }
            } else if (fetchedAttempt.isUserUploaded && fetchedAttempt.questionJsonString && perkFeatures.canReviewCustomUploads) {
                try {
                    fetchedQuestions = JSON.parse(fetchedAttempt.questionJsonString);
                } catch (qError: any) {
                    if(isMounted) console.error("Error parsing custom questions for results:", qError.message);
                }
            }
            if (isMounted) setQuestions(fetchedQuestions);


            if (needsGroupDetailsFetch && fetchedAttempt.groupSessionId) {
                try {
                    const groupDetails = await getGroupExam(fetchedAttempt.groupSessionId);
                    if (isMounted) setGroupExamDetails(groupDetails);
                } catch (groupErr: any) {
                     if (isMounted) console.error("Error fetching group session details for results:", groupErr);
                }
            }
            
            if (isMounted) setIsLoading(false);
        };

        fetchResultAndQuestionData();
        return () => { isMounted = false; };
        // eslint-disable-next-line
    }, [attemptId, currentUser, location.state, isLoadingPerks, perkFeatures.canReviewCustomUploads]); // Added isLoadingPerks


    // --- MODIFIED: Subject & Topic Performance Calculation ---
    const subjectAndTopicPerformance = useMemo((): SubjectPerformanceData[] => {
        if (!attemptResult || !questions || questions.length === 0) return [];

        const performanceMap: Record<string, {
            correct: number;
            incorrect: number;
            unattempted: number;
            total: number;
            topics: Record<string, TopicPerformanceData>; // Nested topics
        }> = {};

        questions.forEach(q => {
            const subject = q.subject || "Uncategorized";
            const topic = q.topic || "General"; // Default topic if missing

            if (!performanceMap[subject]) {
                performanceMap[subject] = { correct: 0, incorrect: 0, unattempted: 0, total: 0, topics: {} };
            }
            if (!performanceMap[subject].topics[topic]) {
                performanceMap[subject].topics[topic] = { topic, correct: 0, incorrect: 0, unattempted: 0, total: 0 };
            }

            // Increment subject total
            performanceMap[subject].total++;
            // Increment topic total
            performanceMap[subject].topics[topic].total++;

            const userAnswer = attemptResult.userAnswers[q.question_number];

            if (!userAnswer || userAnswer.selectedOption === null) {
                performanceMap[subject].unattempted++;
                performanceMap[subject].topics[topic].unattempted++;
            } else if (userAnswer.selectedOption.toLowerCase() === q.correct_answer.toLowerCase()) {
                performanceMap[subject].correct++;
                performanceMap[subject].topics[topic].correct++;
            } else {
                performanceMap[subject].incorrect++;
                performanceMap[subject].topics[topic].incorrect++;
            }
        });
        
        return Object.entries(performanceMap).map(([subjectName, data]) => ({
            subject: subjectName,
            correct: data.correct,
            incorrect: data.incorrect,
            unattempted: data.unattempted,
            total: data.total,
            topics: Object.values(data.topics).sort((a,b) => a.topic.localeCompare(b.topic)), // Sort topics
        })).sort((a,b) => a.subject.localeCompare(b.subject)); // Sort subjects
    }, [attemptResult, questions]);

    // NEW: Difficulty Performance Calculation
    const difficultyPerformance = useMemo((): DifficultyPerformanceData[] => {
        if (!attemptResult || !questions || questions.length === 0) return [];

        const performanceMap: Record<string, DifficultyPerformanceData> = {
            "Easy": { difficulty: "Easy", correct: 0, incorrect: 0, unattempted: 0, total: 0 },
            "Medium": { difficulty: "Medium", correct: 0, incorrect: 0, unattempted: 0, total: 0 },
            "Hard": { difficulty: "Hard", correct: 0, incorrect: 0, unattempted: 0, total: 0 },
            "Not Specified": { difficulty: "Not Specified", correct: 0, incorrect: 0, unattempted: 0, total: 0 }
        };

        questions.forEach(q => {
            const difficulty = q.difficulty || "Not Specified";
            if (!performanceMap[difficulty]) { 
                performanceMap[difficulty] = { difficulty, correct: 0, incorrect: 0, unattempted: 0, total: 0 };
            }
            performanceMap[difficulty].total++;
            const userAnswer = attemptResult.userAnswers[q.question_number];
            if (!userAnswer || userAnswer.selectedOption === null) {
                performanceMap[difficulty].unattempted++;
            } else if (userAnswer.selectedOption.toLowerCase() === q.correct_answer.toLowerCase()) {
                performanceMap[difficulty].correct++;
            } else {
                performanceMap[difficulty].incorrect++;
            }
        });
        const difficultyOrder: Record<string, number> = { "Easy": 1, "Medium": 2, "Hard": 3, "Not Specified": 4 };
        return Object.values(performanceMap)
            .filter(d => d.total > 0)
            .sort((a, b) => (difficultyOrder[a.difficulty] || 99) - (difficultyOrder[b.difficulty] || 99));
    }, [attemptResult, questions]);


    // --- Visibility, EndTime, CanReview logic (mostly unchanged, ensure they use latest state) ---
    const visibilityStatus = useMemo(() => {
        if (isLoading) return 'loading';
        if (!attemptResult) return 'error';
        if (!attemptResult.groupSessionId || !groupExamDetails) return 'visible';
        const visibilityRule = groupExamDetails.resultVisibility || 'Self Only Immediate';
        const endTimeDate = groupExamDetails.endTime instanceof Date
            ? groupExamDetails.endTime
            : (groupExamDetails.endTime as any)?.toDate ? (groupExamDetails.endTime as any).toDate() : null;
        const isAfterEndTimeValue = hasEndTimePassed(endTimeDate);
        switch (visibilityRule) {
            case 'Self Only Immediate': return 'visible';
            case 'Self Only After End Time': return isAfterEndTimeValue ? 'visible' : 'hidden_until_end';
            case 'Leaderboard After End Time': return isAfterEndTimeValue ? 'leaderboard_only' : 'hidden_until_end';
            case 'Full Review After End Time': return isAfterEndTimeValue ? 'visible_full_review' : 'visible_no_review';
            default: return 'visible';
        }
    }, [attemptResult, groupExamDetails, isLoading]);

    const endTimeDate = useMemo(() => {
        if (!groupExamDetails?.endTime) return null;
        return groupExamDetails.endTime instanceof Date
            ? groupExamDetails.endTime
            : (groupExamDetails.endTime as any)?.toDate ? (groupExamDetails.endTime as any).toDate() : null;
    }, [groupExamDetails]);
    
    const isAfterEndTime = useMemo(() => hasEndTimePassed(endTimeDate), [endTimeDate]);

    const canReview = useMemo(() => {
        if (isLoadingPerks || !attemptResult) return false;

        // For user-uploaded exams, check if perk allows review AND if question JSON is present
        if (attemptResult.isUserUploaded) {
            return perkFeatures.canReviewCustomUploads && !!attemptResult.questionJsonString;
        }
        // For official exams (individual or group)
        if (!attemptResult.groupSessionId) return true; // Individual official exam, review allowed

        // Group session, visibility depends on rule
        return visibilityStatus === 'visible_full_review' || visibilityStatus === 'visible';
    }, [attemptResult, visibilityStatus, isLoadingPerks, perkFeatures.canReviewCustomUploads]);


    // --- Render logic ---
    if (isLoading || isLoadingPerks) { // Check both
        return <div className={styles.statusMessage}><Spinner text="Loading results..." size={24} /></div>;
    }

    if (error) {
        return (
            <div className={`${styles.statusMessage} ${styles.error}`}>
                <h2>Error</h2>
                <p>{error}</p>
                <Link to="/profile" className={styles.actionButton}>View My History</Link>
                <Link to="/select-exam" className={styles.actionButton}>Start New Exam</Link>
            </div>
        );
    }

    if (!attemptResult) {
        return <div className={styles.statusMessage}>No result data found.</div>;
    }

    if (visibilityStatus === 'hidden_until_end' && !isAfterEndTime) {
         return (
            <div className={styles.resultsPage}>
                <h1>{attemptResult.examTitle} - Results Pending</h1>
                <div className={styles.statusMessage}>
                    <FaClock size={24} style={{ color: styles.primaryColor || '#007bff' }} />
                    <p>Detailed results and performance breakdown will be available after the session's entry deadline.</p>
                    {endTimeDate && <p>Deadline: <strong>{formatTimestamp(endTimeDate)}</strong></p>}
                    <Link to="/profile" className={styles.actionButton}>View My History</Link>
                </div>
            </div>
        );
    }

    const percentage = attemptResult.maxScore > 0
        ? ((attemptResult.score / attemptResult.maxScore) * 100).toFixed(2)
        : 'N/A';
        
    const pieData = [
        { name: 'Correct', value: attemptResult.correctCount ?? 0 },
        { name: 'Incorrect', value: attemptResult.incorrectCount ?? 0 },
        { name: 'Unattempted', value: attemptResult.unattemptedCount ?? 0 },
    ].filter(entry => entry.value > 0);

    const COLORS = ['#28a745', '#dc3545', '#6c757d'];

    const RADIAN = Math.PI / 180;
    const renderCustomizedLabel = ({ cx, cy, midAngle, innerRadius, outerRadius, percent }: any) => {
        const radius = innerRadius + (outerRadius - innerRadius) * 0.5;
        const x = cx + radius * Math.cos(-midAngle * RADIAN);
        const y = cy + radius * Math.sin(-midAngle * RADIAN);
        if (percent < 0.05) return null;
        return (
            <text x={x} y={y} fill="white" textAnchor={x > cx ? 'start' : 'end'} dominantBaseline="central" fontSize="12px" fontWeight="bold">
                {`${(percent * 100).toFixed(0)}%`}
            </text>
        );
    };
    
    const showLeaderboard = (
        attemptResult.groupSessionId &&
        groupExamDetails &&
        ( visibilityStatus === 'leaderboard_only' || visibilityStatus === 'visible_full_review' ) &&
        isAfterEndTime
    );

    // Determine bar chart height for subject/topic performance
    const calculateBarChartHeight = (itemCount: number) => {
        const minHeight = 150; // Minimum height for the chart area
        const heightPerBar = 40; // Pixels per bar (adjust as needed for label readability)
        const legendHeight = 30; // Approximate height for legend
        return Math.max(minHeight, (itemCount * heightPerBar) + legendHeight + 20); // +20 for margins
    };

    return (
        <div className={styles.resultsPage}>
            <h1>Exam Result: {attemptResult.examTitle} {attemptResult.groupSessionId ? '(Group)' : ''}</h1>
            
            {(visibilityStatus !== 'hidden_until_end' || isAfterEndTime) && (
                <div className={styles.summaryGrid}>
                    {/* Score Box (Unchanged) */}
                    <div className={`${styles.summaryBox} ${styles.scoreBox} ${styles.textCenteredContent}`}>
                        <h2>Score</h2>
                        <div className={styles.scoreValue}>
                            {attemptResult.score} / {attemptResult.maxScore}
                        </div>
                        <div className={styles.percentage}>
                            ({percentage}%)
                        </div>
                    </div>

                    {/* Details Box (Unchanged) */}
                    <div className={styles.summaryBox}>
                        <h2>Performance</h2>
                        <ul className={styles.detailsList}>
                        <li>
                            <span className={styles.itemLabel}>
                                <FaCheckCircle className={`${styles.icon} ${styles.correctIcon}`} /> Correct:
                            </span>
                            <span className={styles.itemValue}>{attemptResult.correctCount}</span>
                        </li>
                        <li>
                            <span className={styles.itemLabel}>
                                <FaTimesCircle className={`${styles.icon} ${styles.incorrectIcon}`} /> Incorrect: 
                            </span>
                            <span className={styles.itemValue}>{attemptResult.incorrectCount}</span>
                        </li>
                        <li>
                            <span className={styles.itemLabel}>
                                <FaMinusCircle className={`${styles.icon} ${styles.unattemptedIcon}`} /> Unattempted: 
                            </span>
                            <span className={styles.itemValue}>{attemptResult.unattemptedCount}</span>
                        </li>
                        <li>
                            <span className={styles.itemLabel} style={{ marginLeft: 'calc(20px + 0.5rem)'}}> {/* Align with text, not icon */}
                                Total Questions:
                            </span>
                            <span className={styles.itemValue}>{attemptResult.totalQuestions}</span>
                        </li>
                        </ul>
                    </div>

                    {/* Time & Date Box (Unchanged) */}
                    <div className={styles.summaryBox}>
                        <h2>Details</h2>
                        <ul className={styles.detailsList}>
                            <li>
                                <span className={styles.itemLabel}><FaClock className={`${styles.icon} ${styles.detailsIcon}`} />Time Taken:</span>
                                <span className={styles.itemValue}>{formatDuration(attemptResult.timeTakenSeconds)}</span>
                            </li>
                            <li>
                                <span className={styles.itemLabel}><FaCalendarAlt className={`${styles.icon} ${styles.detailsIcon}`} />Attempted On:</span>
                                <span className={styles.itemValue}>{formatTimestamp(attemptResult.attemptTimestamp as any)}</span>
                            </li>
                            {attemptResult.isUserUploaded && (
                                <li><span className={styles.itemLabel} style={{ marginLeft: 'calc(20px + 0.5rem)'}}>Source:</span> <span className={styles.itemValue}>User Uploaded Set</span></li>
                            )}
                            {attemptResult.groupSessionId && groupExamDetails && (
                                <li><span className={styles.itemLabel} style={{ marginLeft: 'calc(20px + 0.5rem)'}}>Session:</span> <span className={styles.itemValue}>{groupExamDetails.sessionName || "Group Exam"}</span></li>
                            )}
                        </ul>
                    </div>

                    {/* Settings Box (Unchanged) */}
                    <div className={`${styles.summaryBox} ${styles.settingsBox}`}>
                        <h2>Settings Used</h2>
                        <ul className={styles.detailsList}>
                            <li>
                                <span className={styles.itemLabel}><FaCog className={`${styles.icon} ${styles.detailsIcon}`} />Time Limit:</span>
                                <span className={styles.itemValue}>{attemptResult.settingsUsed.timeLimitMinutes ? `${attemptResult.settingsUsed.timeLimitMinutes} mins` : 'None'}</span>
                            </li>
                            <li><span className={styles.itemLabel} style={{ marginLeft: 'calc(20px + 0.5rem)'}}>Marks/Correct:</span> <span className={styles.itemValue}>{attemptResult.settingsUsed.marksPerCorrect}</span></li>
                            <li>
                                <span className={styles.itemLabel} style={{ marginLeft: 'calc(20px + 0.5rem)'}}>Negative Marking:</span>
                                <span className={styles.itemValue}>{attemptResult.settingsUsed.negativeMarkingEnabled ? `Yes (-${attemptResult.settingsUsed.negativeMarksPerIncorrect})` : 'No'}</span>
                            </li>
                        </ul>
                    </div>
                    
                    {/* Pie Chart Box (Unchanged) */}
                    <div className={`${styles.summaryBox} ${styles.chartBox}`}>
                        <h2><FaChartPie className={styles.icon} /> Question Breakdown</h2>
                        <div style={{ width: '100%', height: 250 }}>
                        <ResponsiveContainer>
                                <PieChart>
                                    <Pie data={pieData} cx="50%" cy="50%" labelLine={false} label={renderCustomizedLabel} outerRadius={85} fill="#8884d8" dataKey="value" >
                                        {pieData.map((entry, index) => (
                                            <Cell key={`cell-${index}`} fill={COLORS[index % COLORS.length]} />
                                        ))}
                                    </Pie>
                                    <Tooltip formatter={(value: number, name: string) => [`${value} questions`, name]} />
                                    <Legend align="center" verticalAlign="bottom" height={36}/>
                                </PieChart>
                        </ResponsiveContainer>
                        </div>
                    </div>

                    {/* --- MODIFIED: Subject & Topic Performance Box --- */}
                    {subjectAndTopicPerformance.length > 0 && (
                        <div className={`${styles.summaryBox} ${styles.subjectTopicPerformanceBox}`}> {/* Add a new specific class if more styling needed */}
                            <h2><FaBook className={styles.icon} /> Subject & Topic Performance</h2>
                            <div className={styles.subjectTopicListContainer} style={{ maxHeight: '300px', overflowY: 'auto', marginTop: '1rem' }}>
                                {subjectAndTopicPerformance.map(subjectData => (
                                    <div key={subjectData.subject} className={styles.subjectGroup}>
                                        <h4 className={styles.subjectTitleInList}>
                                            {subjectData.subject}
                                            <span className={styles.subjectOverallScore}>
                                                ({subjectData.correct}/{subjectData.total} - {((subjectData.correct / subjectData.total) * 100 || 0).toFixed(0)}%)
                                            </span>
                                        </h4>
                                        {subjectData.topics && subjectData.topics.length > 0 && (
                                            <ul className={styles.topicList}>
                                                {subjectData.topics.map(topicData => (
                                                    <li key={topicData.topic} className={styles.topicItem}>
                                                        <span className={styles.topicName}><FaTags className={styles.topicIcon} />{topicData.topic}</span>
                                                        <span className={styles.topicScore}>
                                                            {topicData.correct}/{topicData.total} ({((topicData.correct / topicData.total) * 100 || 0).toFixed(0)}%)
                                                        </span>
                                                    </li>
                                                ))}
                                            </ul>
                                        )}
                                    </div>
                                ))}
                            </div>
                        </div>
                    )}

                    {/* --- NEW: Difficulty Performance Box --- */}
                    {difficultyPerformance.length > 0 && (
                        <div className={`${styles.summaryBox} ${styles.chartBox}`}>
                            <h2><FaStarHalfAlt className={styles.icon} /> Difficulty Performance</h2>
                            <div style={{ width: '100%', height: calculateBarChartHeight(difficultyPerformance.length), marginTop: '1rem' }}>
                            <ResponsiveContainer>
                                    <BarChart data={difficultyPerformance} layout="vertical" margin={{ top: 5, right: 35, left: 20, bottom: 5 }}>
                                        <CartesianGrid strokeDasharray="3 3" />
                                        <XAxis type="number" domain={[0, (dataMax: number) => Math.ceil(Math.max(1, dataMax) / 5) * 5]} allowDecimals={false} />
                                        <YAxis type="category" dataKey="difficulty" width={85} interval={0} />
                                        <Tooltip
                                            formatter={(value: any, name: string, props: any) => {
                                                const numValue = Number(value); // Ensure value is a number
                                                if (isNaN(numValue)) return [value, name]; // Fallback if not a number

                                                const { payload } = props; // Get the full data point for this bar segment
                                                if (!payload || typeof payload.total !== 'number' || payload.total === 0) {
                                                    return [`${numValue}`, name]; // Fallback if total is missing or zero
                                                }
                                                
                                                const percentage = ((numValue / payload.total) * 100).toFixed(0);
                                                let labelPrefix = name; // 'Correct', 'Incorrect', 'Unattempted'
                                                if (name === 'correct') labelPrefix = 'Correct';
                                                else if (name === 'incorrect') labelPrefix = 'Incorrect';
                                                else if (name === 'unattempted') labelPrefix = 'Unattempted';

                                                return [`${numValue} (${percentage}%)`, labelPrefix];
                                            }}
                                        />
                                        <Legend />
                                        <Bar dataKey="correct" stackId="a" fill={COLORS[0]} name="Correct">
                                            <LabelList dataKey="correct" position="center" formatter={(value: number) => value > 0 ? value : ''} style={{ fill: '#fff', fontWeight: 'bold', textShadow: '1px 1px 2px rgba(0,0,0,0.7)' }} />
                                        </Bar>
                                        <Bar dataKey="incorrect" stackId="a" fill={COLORS[1]} name="Incorrect">
                                            <LabelList dataKey="incorrect" position="center" formatter={(value: number) => value > 0 ? value : ''} style={{ fill: '#fff', fontWeight: 'bold', textShadow: '1px 1px 2px rgba(0,0,0,0.7)' }} />
                                        </Bar>
                                        <Bar dataKey="unattempted" stackId="a" fill={COLORS[2]} name="Unattempted">
                                            <LabelList dataKey="unattempted" position="center" formatter={(value: number) => value > 0 ? value : ''} style={{ fill: '#fff', fontWeight: 'bold', textShadow: '1px 1px 2px rgba(0,0,0,0.7)' }} />
                                        </Bar>
                                    </BarChart>
                                </ResponsiveContainer>
                            </div>
                        </div>
                    )}
                </div>
            )}

            {showLeaderboard && (
                <Leaderboard sessionId={attemptResult.groupSessionId!} />
            )}

            {(visibilityStatus !== 'hidden_until_end' || isAfterEndTime) && (
                <div className={styles.actions}>
                    <Link
                        to={canReview ? `/review/${attemptId}` : '#'}
                        className={`${styles.actionButton} ${styles.secondary} ${!canReview ? styles.disabled : ''}`}
                        onClick={(e) => !canReview && e.preventDefault()}
                        title={
                            isLoadingPerks ? "Checking review eligibility..." :
                            !canReview
                                ? (attemptResult.isUserUploaded && !perkFeatures.canReviewCustomUploads)
                                    ? `Review for custom uploads is a premium feature. (Your tier: ${perkFeatures})` // TODO: replace perkFeatures with currentTier.name
                                    : 'Review not permitted or available yet (Check session rules/deadline)'
                                : attemptResult.isUserUploaded
                                    ? 'Review Answers (Explanations may be missing for custom tests)'
                                    : 'Review your answers'
                        }
                        aria-disabled={!canReview}
                    >
                        Review Answers {canReview ? <FaExternalLinkAlt size={12} /> : (isLoadingPerks ? '(Checking...)' : '(N/A)')}
                    </Link>

                    <Link to="/profile" className={`${styles.actionButton} ${styles.default}`}>
                        View Full History
                    </Link>
                    <Link to="/select-exam" className={`${styles.actionButton} ${styles.primary}`}>
                        Start New Exam
                    </Link>
                </div>
            )}

        </div>
    );
};

export default ResultsPage;
```

---

## pages\ReviewPage


### pages\ReviewPage\ReviewPage.module.scss

```scss
// src/pages/ReviewPage/ReviewPage.module.scss
@import '../../styles/variables';
@import '../../styles/mixins';

// --- Status Message (Loading/Error) ---
.statusMessage { // Reused from ResultsPage or define similarly
  padding: map-get($spacers, 6) map-get($spacers, 4);
  text-align: center;
  min-height: 60vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  gap: map-get($spacers, 3);

  &.error {
    background-color: lighten($red-500, 50%);
    border: 1px solid lighten($red-500, 30%);
    border-radius: $border-radius-lg;
    padding: map-get($spacers, 5);
    color: darken($red-500, 15%);
    max-width: 600px;
    margin: 0 auto;
    h2 {
      color: $red-500;
      margin-bottom: map-get($spacers, 2);
      font-size: $h4-font-size;
    }
    p { font-size: $font-size-base; }
  }
}
.actionButton { // For buttons in error state (e.g. "Back to Results")
  @include button-variant($primary-color); // Or a secondary style
  margin-top: map-get($spacers, 3);
}


// --- Main Page Styles ---
.reviewPage {
  padding: map-get($spacers, 4) 0 map-get($spacers, 5); // py-4 my-5

  h1 {
    text-align: center;
    margin-bottom: map-get($spacers, 3); // mb-3
    color: $primary-color;
    font-size: $h3-font-size; // Consistent with ResultsPage or slightly smaller
    font-weight: $font-weight-semibold;
  }
}

.backLink { // Link to go back to Results Summary
  display: inline-flex;
  align-items: center;
  gap: map-get($spacers, 2); // gap-2
  margin-bottom: map-get($spacers, 4); // mb-4
  color: $link-color;
  text-decoration: none;
  font-weight: $font-weight-medium;
  padding: map-get($spacers, 1) map-get($spacers, 2); // Add some padding for easier click
  border-radius: $border-radius; // Slight radius
  transition: background-color $transition-fast, color $transition-fast;

  &:hover {
    color: $link-hover-color;
    background-color: $gray-100; // Subtle hover background
    text-decoration: none; // No underline on hover for button-like links
  }
  @include focus-outline($primary-color);
  // Position it if needed (e.g. in a header bar within the review page)
  // For now, assumes it's flow content
}

// --- Layout (Question Panel + Palette Panel) ---
.reviewLayout {
  display: flex;
  flex-direction: column;
  gap: map-get($spacers, 4); // gap-4 (24px)

  @include media-breakpoint-up(lg) {
    flex-direction: row;
  }
}

.questionPanel { // Contains ReviewQuestionDisplay and AI Actions
  flex-grow: 1;
  min-width: 0; // Prevent overflow issues
  background-color: $component-bg; // Panel background
  border: 1px solid $gray-200;
  border-radius: $border-radius-lg;
  padding: map-get($spacers, 4); // p-4
  box-shadow: $box-shadow-sm; // Subtle shadow for panel
}

.palettePanel { // Contains ReviewPalette
  flex-shrink: 0;
  width: 100%;
  background-color: $component-bg;
  border: 1px solid $gray-200;
  border-radius: $border-radius-lg;
  padding: map-get($spacers, 3); // p-3
  box-shadow: $box-shadow-sm;

  @include media-breakpoint-up(lg) {
    width: 320px; // Fixed width like ExamPage right panel
    // max-height: 80vh; // Allow internal scrolling for palette if needed
    // overflow-y: auto; // Handled by ReviewPalette's internal .paletteGrid
  }
}

// --- Filter Controls ---
.filterControls {
  margin-bottom: map-get($spacers, 4);
  padding: map-get($spacers, 2) map-get($spacers, 3);
  background-color: $gray-50;
  border: 1px solid $gray-200;
  border-radius: $border-radius;
  display: flex;
  gap: map-get($spacers, 2);
  align-items: center;
  justify-content: flex-start; // Align filters to the start
  flex-wrap: wrap;

  .filterLabel {
    font-weight: $font-weight-medium;
    color: $gray-700;
    margin-right: map-get($spacers, 1);
    display: flex; // For icon alignment
    align-items: center;
    gap: map-get($spacers, 1); // Gap between icon and text if icon is used
  }
}

.filterButton {
  @include button-variant(
    transparent, $gray-300, $gray-700, $gray-100, $gray-400,
    $gray-800, $gray-200, $gray-500, 0.65, true
  );
  padding: map-get($spacers, 1) map-get($spacers, 3);
  font-size: $font-size-base * 0.85;

  // .active class is now added directly for styling
  &.active { // Combined with :disabled for visual cue
    @include button-variant($primary-color); // Solid primary when active
    border-color: $primary-color;
    color: $white-color !important; // Ensure text color is white for active button
    cursor: default;
    opacity: 1;
  }
   &:disabled:not(.active) { // If disabled but NOT active (e.g. button for current filter)
     opacity: 0.5; // Standard disabled opacity
     cursor: not-allowed;
   }
}

// Style for filter dropdown (can reuse .jumpDropdown styles if they fit)
.filterDropdown {
  // Inherit from .jumpDropdown if suitable or define new
  @extend .jumpDropdown; // If .jumpDropdown style from navigationControls is suitable
  max-width: 200px; // Adjust max-width as needed for topics
}
// --- Navigation Controls (Prev/Next, Jump) ---
.navigationControls {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-top: map-get($spacers, 4); // mt-4
  padding: map-get($spacers, 3) map-get($spacers, 4); // p-3 px-4
  background-color: $gray-50; // Light bg for nav controls
  border: 1px solid $gray-200;
  border-radius: $border-radius-lg;
  box-shadow: $box-shadow-sm;
}

.navButton { // For Previous/Next buttons
  // Use secondary outline button style
  @include button-variant(
    transparent, $gray-400, $gray-700, $is-outline: true
  );
  padding: map-get($spacers, 2) map-get($spacers, 3); // py-2 px-3
  font-size: $font-size-base * 0.9;
  gap: map-get($spacers, 2);
  min-width: 120px; // Ensure decent width
  // Disabled state handled by mixin
  svg { font-size: $font-size-base * 0.9; } // Adjust icon size if needed
}

.questionCounter {
  font-weight: $font-weight-medium;
  color: $text-muted;
  font-size: $font-size-base * 0.9;
  text-align: center; // Ensure counter is centered if space allows
  flex-grow: 1; // Allow it to take space between buttons/dropdown
  padding: 0 map-get($spacers, 2);
}

.jumpDropdown { // For the select element
  // Inherit base select styles from _base.scss
  padding: map-get($spacers, 2) map-get($spacers, 3); // py-2 px-3
  font-size: $font-size-base * 0.9;
  max-width: 180px; // Limit width of jump dropdown
  border-radius: $border-radius;
  border-color: $gray-300;
  background-position: right #{map-get($spacers, 2)} center; // Ensure arrow pos is good
}

// --- AI Actions (within ReviewQuestionDisplay header) ---
.aiActionsContainer { // Already styled in ReviewQuestionDisplay if used there directly
  position: relative;
  // margin-left: auto; // Keep if it's inside a flex header in ReviewQuestionDisplay
  // align-self: center;
}

.aiMainButton { // The "Explain with AI" button
  @include button-variant(
    lighten($info-color, 50%),
    lighten($info-color, 35%),
    darken($info-color, 15%),
    lighten($info-color, 45%),
    lighten($info-color, 30%),
    darken($info-color, 10%)
  );
  padding: map-get($spacers, 1) map-get($spacers, 2); // py-1 px-2
  font-size: $font-size-base * 0.85;
  border-radius: $border-radius;
  gap: map-get($spacers, 2);
  svg { font-size: $font-size-base * 0.95; }
}

.aiOptionsDropdown { // The dropdown menu
  position: absolute;
  top: calc(100% + #{map-get($spacers, 1)}); // Position below button with small gap
  right: 0;
  background-color: $component-bg;
  border: 1px solid $gray-200; // Lighter border for dropdown
  border-radius: $border-radius;
  box-shadow: $box-shadow-lg; // Prominent shadow for dropdown
  z-index: $zindex-dropdown;
  min-width: 180px; // Min width for dropdown items
  padding: map-get($spacers, 1) 0; // py-1

  button { // Individual options in dropdown
    @include button-text-variant($gray-700, $gray-100, $primary-color);
    width: 100%;
    text-align: left;
    padding: map-get($spacers, 2) map-get($spacers, 3); // py-2 px-3
    font-size: $font-size-base * 0.9;
    border-radius: 0; // No radius for items inside
    border: none;

    // Specific hover already handled by button-text-variant
    // &:hover { ... }
  }
}
.aiOptionDivider { // Separator in AI dropdown
  height: 1px;
  background-color: $gray-100; // Very subtle divider
  margin: map-get($spacers, 1) 0; // my-1
}

// Empty State (copied from HostDashboard, good for reuse)
.emptyStateContainer {
  padding: map-get($spacers, 5) map-get($spacers, 3);
  text-align: center;
  color: $text-muted;
  border: 1px dashed $gray-300;
  border-radius: $border-radius-lg;
  margin: map-get($spacers, 4) 0;
  background-color: $gray-50;
}
.emptyStateIcon {
  color: $primary-color;
  margin-bottom: map-get($spacers, 3);
  opacity: 0.7;
}
.emptyStateText {
  font-size: $font-size-base * 1.1;
  font-weight: $font-weight-medium;
  margin-bottom: map-get($spacers, 2);
  color: $gray-700;
}
.emptyStateSubtext {
  font-size: $font-size-base * 0.9;
  margin-bottom: 0;
}
```

---

### pages\ReviewPage\ReviewPage.tsx

```typescript
import React, { useState, useEffect, useCallback, useMemo } from 'react';
import { useParams, Link, useNavigate } from 'react-router-dom';
import { useAuth } from '../../contexts/AuthContext'; // Corrected path
import { getAttemptResult, getGroupExam } from '../../services/firestoreService';
import { AttemptResult, Question, UserAnswer, GroupExam } from '../../types';
import ReviewQuestionDisplay from '../../components/ReviewQuestionDisplay/ReviewQuestionDisplay'; // Corrected path
import ReviewPalette from '../../components/ReviewPalette/ReviewPalette'; // Corrected path
import styles from './ReviewPage.module.scss';
import { FaArrowLeft, FaArrowRight, FaFilter, FaListAlt, FaMagic, FaCopy, FaTags, FaStarHalfAlt } from 'react-icons/fa'; // Added FaTags and FaStarHalfAlt
import { formatTimestamp } from '../../utils/formatters';
import Spinner from '../../components/Spinner/Spinner'; // Corrected path
import { toast } from 'react-toastify';
import { Timestamp } from 'firebase/firestore'; // Ensure Timestamp is imported

// Import useUserPerks from Examify's hooks
import { useUserPerks } from '../../hooks/useUserPerks'; // Corrected path

// Helper to check if end time has passed
const hasEndTimePassed = (endTime: Date | null | undefined): boolean => {
    if (!endTime) return true;
    return new Date() > endTime;
};

const generateAiPrompt = (question: Question): string => {
    const optionsString = Object.entries(question.options)
                              .map(([key, text]) => `  ${key.toUpperCase()}) ${text}`)
                              .join('\n');
    return `Explain the solution for the following multiple-choice question:\n\nQuestion:\n${question.question_text}\n\nOptions:\n${optionsString}\n\nCorrect Answer: ${question.correct_answer.toUpperCase()}\n${question.explanation ? `Reference Explanation (Optional):\n${question.explanation}\n` : ''}Provide a step-by-step explanation for why the correct answer is right and briefly why the other options might be wrong. Format the explanation clearly.`.trim();
};

const openAiTool = (prompt: string, tool: 'chatgpt' | 'claude' | 'perplexity' | 'you' | 'phind' = 'chatgpt') => {
    let url = '';
    const encodedPrompt = encodeURIComponent(prompt);
    switch(tool) {
        case 'claude': url = `https://claude.ai/new?q=${encodedPrompt}`; break;
        case 'perplexity': url = `https://www.perplexity.ai/search?q=${encodedPrompt}`; break;
        case 'you': url = `https://you.com/search?q=${encodedPrompt}`; break;
        case 'phind': url = `https://www.phind.com/search?q=${encodedPrompt}`; break;
        case 'chatgpt': default: url = `https://chat.openai.com/?q=${encodedPrompt}`; break;
    }
    window.open(url, '_blank', 'noopener,noreferrer');
};

// Define Difficulty type for filter state
type DifficultyFilter = 'all' | 'Easy' | 'Medium' | 'Hard' | 'Not Specified';

const ReviewPage: React.FC = () => {
    const { attemptId } = useParams<{ attemptId: string }>();
    const { currentUser } = useAuth();
    // *** USE THE EXAMIFY useUserPerks HOOK ***
    const { features: perkFeatures, isLoadingPerks, currentTier } = useUserPerks();
    const navigate = useNavigate();

    const [attemptResult, setAttemptResult] = useState<AttemptResult | null>(null);
    const [, setGroupExamDetails] = useState<GroupExam | null>(null); // Keep state for potential future use if group details become relevant here
    const [questions, setQuestions] = useState<Question[]>([]);
    const [userAnswers, setUserAnswers] = useState<UserAnswer | null>(null);
    
    const [statusFilter, setStatusFilter] = useState<'all' | 'incorrect' | 'unattempted'>('all');
    const [topicFilter, setTopicFilter] = useState<string>('all'); // NEW: Topic filter state
    const [difficultyFilter, setDifficultyFilter] = useState<DifficultyFilter>('all'); // NEW: Difficulty filter state
    
    const [showAiOptionsForQuestion, setShowAiOptionsForQuestion] = useState<number | null>(null);
    const [isLoading, setIsLoading] = useState<boolean>(true);
    const [error, setError] = useState<string | null>(null);
    const [accessDeniedMessage, setAccessDeniedMessage] = useState<string | null>(null);

    useEffect(() => {
        document.title = `Review Exam - ${attemptResult?.examTitle || attemptId || ''} - Examify`;
    }, [attemptResult, attemptId]);

    // NEW: Memoize unique topics for the dropdown
    const availableTopics = useMemo(() => {
        if (!questions || questions.length === 0) return [];
        const topics = new Set<string>();
        questions.forEach(q => {
            if (q.topic) topics.add(q.topic);
        });
        return Array.from(topics).sort();
    }, [questions]);

    // NEW: Memoize available difficulties
    const availableDifficulties = useMemo((): DifficultyFilter[] => {
        if (!questions || questions.length === 0) return [];
        const difficulties = new Set<DifficultyFilter>();
        let hasNotSpecified = false;
        questions.forEach(q => {
            if (q.difficulty) difficulties.add(q.difficulty);
            else hasNotSpecified = true; // Track if any question has no difficulty set
        });
        const sortedDifficulties = Array.from(difficulties).sort((a, b) => {
            const order: Record<DifficultyFilter, number> = { Easy: 1, Medium: 2, Hard: 3, 'Not Specified': 4, all: 0 };
            return order[a] - order[b];
        });
        if (hasNotSpecified) sortedDifficulties.push('Not Specified');
        return sortedDifficulties;
    }, [questions]);

    const filteredIndices = useMemo(() => {
        if (!userAnswers || questions.length === 0) return [];
        return questions
            .map((q, index) => ({ q, index }))
            .filter(({ q }) => {
                // Topic filter
                if (topicFilter !== 'all') {
                    const questionTopic = q.topic || "General"; // Treat undefined/null topic as "General"
                    if (topicFilter === "General" && questionTopic !== "General") return false;
                    if (topicFilter !== "General" && questionTopic !== topicFilter) return false;
                }

                // NEW: Difficulty filter
                if (difficultyFilter !== 'all') {
                    const questionDifficulty = q.difficulty || 'Not Specified'; // Treat undefined/null as 'Not Specified'
                    if (questionDifficulty !== difficultyFilter) return false;
                }

                // Status filter
                const answerData = userAnswers[q.question_number];
                const userAnswer = answerData?.selectedOption;
                const correctAnswer = q.correct_answer;
                const isIncorrect = userAnswer !== null && userAnswer !== undefined && userAnswer.toLowerCase() !== correctAnswer.toLowerCase();
                const isUnattempted = userAnswer === null || userAnswer === undefined;
                
                if (statusFilter === 'incorrect') return isIncorrect;
                if (statusFilter === 'unattempted') return isUnattempted;
                return true; // 'all' status filter
            })
            .map(({ index }) => index);
    }, [questions, userAnswers, statusFilter, topicFilter, difficultyFilter]); // Added difficultyFilter

    const [currentFilteredIndex, setCurrentFilteredIndex] = useState<number>(0);

    useEffect(() => {
        setCurrentFilteredIndex(0);
        // Reset topic filter if it becomes invalid due to questions changing (less likely here but good practice)
        if (topicFilter !== 'all' && !availableTopics.includes(topicFilter) && availableTopics.length > 0) {
            setTopicFilter('all');
        } else if (topicFilter !== 'all' && availableTopics.length === 0) {
             setTopicFilter('all'); // Reset if no topics available
        }
        // NEW: Reset difficulty filter if it becomes invalid
        if (difficultyFilter !== 'all' && !availableDifficulties.includes(difficultyFilter) && availableDifficulties.length > 0) {
            setDifficultyFilter('all');
        } else if (difficultyFilter !== 'all' && availableDifficulties.length === 0) {
            setDifficultyFilter('all');
        }
    }, [statusFilter, topicFilter, difficultyFilter, filteredIndices.length, availableTopics, availableDifficulties]); // Re-calculate currentFilteredIndex when filters or available data changes

    const currentReviewIndex = filteredIndices[currentFilteredIndex] ?? 0;

    useEffect(() => {
        let isMounted = true;
        const fetchReviewData = async () => {
            // *** MODIFIED: Wait for isLoadingPerks to be false ***
            if (!attemptId || !currentUser || isLoadingPerks) {
                 if (!isLoadingPerks && (!attemptId || !currentUser)) {
                     if(isMounted) { setError("Attempt ID missing or user not logged in."); setIsLoading(false); }
                 }
                 // If only isLoadingPerks is true, we wait, main isLoading state is still true.
                 return;
            }

            setIsLoading(true); setError(null); setAccessDeniedMessage(null);
            let fetchedAttempt: AttemptResult | null = null;
            let fetchedGroupDetails: GroupExam | null = null;

            try {
                fetchedAttempt = await getAttemptResult(currentUser.uid, attemptId);
                if (!isMounted) return;
                if (!fetchedAttempt) throw new Error("Attempt result not found.");
                
                setAttemptResult(fetchedAttempt);
                setUserAnswers(fetchedAttempt.userAnswers || {});

                let canAccessReview = true;
                let denialReason = "";

                // *** MODIFIED: Use perkFeatures.canReviewCustomUploads ***
                if (fetchedAttempt.isUserUploaded) {
                    if (!perkFeatures.canReviewCustomUploads) {
                        canAccessReview = false;
                        // *** MODIFIED: More specific denial reason ***
                        denialReason = `Reviewing custom uploaded exams requires the Basic tier or higher. Your current tier ('${currentTier.name}') does not include this feature.`;
                    } else if (!fetchedAttempt.questionJsonString) { // Check if JSON string exists even if perk allows
                        canAccessReview = false;
                        denialReason = "Question data for this custom uploaded exam is not available for review (JSON string missing).";
                    }
                } else if (fetchedAttempt.groupSessionId) {
                    fetchedGroupDetails = await getGroupExam(fetchedAttempt.groupSessionId);
                    if (!isMounted) return;
                    setGroupExamDetails(fetchedGroupDetails); // Set group details if fetched

                    const visibilityRule = fetchedGroupDetails?.resultVisibility || 'Self Only Immediate';
                    // Ensure endTime is a Date object before comparison
                    const endTimeJSDate = fetchedGroupDetails?.endTime instanceof Timestamp 
                        ? fetchedGroupDetails.endTime.toDate() 
                        : fetchedGroupDetails?.endTime instanceof Date 
                          ? fetchedGroupDetails.endTime 
                          : null;
                    const isAfterEndTime = hasEndTimePassed(endTimeJSDate);

                    if (!(visibilityRule === 'Full Review After End Time' && isAfterEndTime) &&
                        !(visibilityRule === 'Self Only Immediate') &&
                        !(visibilityRule === 'Self Only After End Time' && isAfterEndTime)) {
                        canAccessReview = false;
                        if (visibilityRule === 'Full Review After End Time' && !isAfterEndTime) {
                            denialReason = `Review will be available after the group session deadline (${endTimeJSDate ? formatTimestamp(endTimeJSDate) : 'N/A'}).`;
                        } else {
                            denialReason = "Review access is not permitted for this group session based on its settings.";
                        }
                    }
                }
                // If not a group session and not a user-uploaded (i.e., official individual attempt), review is generally allowed.

                if (!canAccessReview) {
                    setAccessDeniedMessage(denialReason);
                    setIsLoading(false);
                    return;
                }

                if (fetchedAttempt.isUserUploaded && fetchedAttempt.questionJsonString && perkFeatures.canReviewCustomUploads) {
                    try {
                        const questionsData = JSON.parse(fetchedAttempt.questionJsonString);
                        if (!Array.isArray(questionsData) || questionsData.length === 0) throw new Error("Invalid custom question data format for review.");
                        if (isMounted) setQuestions(questionsData);
                    } catch (parseError) {
                       //console.error("Error parsing questionJsonString for review:", parseError);
                        throw new Error("Could not load questions for this custom exam review.");
                    }
                } else if (fetchedAttempt.examPath && !fetchedAttempt.isUserUploaded) {
                    const QUESTIONS_REPO_BASE_URL = 'https://raw.githubusercontent.com/Samkarya/online-exam-questions/refs/heads/main/';
                    const fetchUrl = `${QUESTIONS_REPO_BASE_URL}/${fetchedAttempt.examPath}`;
                    const response = await fetch(fetchUrl);
                    if (!isMounted) return;
                    if (!response.ok) throw new Error(`Failed to fetch question paper (${response.status})`);
                    const questionsData = await response.json();
                    if (!Array.isArray(questionsData) || questionsData.length === 0) throw new Error("Invalid question data format.");
                    if (isMounted) setQuestions(questionsData);
                } else if (fetchedAttempt.isUserUploaded && !perkFeatures.canReviewCustomUploads) {
                    // This case is already handled by the accessDeniedMessage logic.
                    // It's important not to try loading questions if access is denied.
                } else if (!fetchedAttempt.examPath && !fetchedAttempt.questionJsonString) {
                    // This implies it's an official exam but path is missing, or a custom exam where string is missing
                    throw new Error("Question source (path for official, or JSON string for custom) not found in result data. Cannot load questions for review.");
                }

            } catch (err: any) {
                if (isMounted) setError(err.message || "Failed to load review data.");
            } finally {
                if (isMounted) setIsLoading(false);
            }
        };

        // Ensure fetchReviewData runs when isLoadingPerks becomes false
        if (!isLoadingPerks) {
            fetchReviewData();
        }

        return () => { isMounted = false; }
    }, [attemptId, currentUser, isLoadingPerks, perkFeatures.canReviewCustomUploads, currentTier.name]); // Added perkFeatures.canReviewCustomUploads and currentTier.name


    const handleNext = useCallback(() => {
        setCurrentFilteredIndex(prev => Math.min(prev + 1, filteredIndices.length - 1));
    }, [filteredIndices.length]);

    const handlePrevious = useCallback(() => {
        setCurrentFilteredIndex(prev => Math.max(prev - 1, 0));
    }, []);

    const handlePaletteNavigate = useCallback((originalIndex: number) => {
        const filteredNavIndex = filteredIndices.findIndex(idx => idx === originalIndex);
        if (filteredNavIndex !== -1) {
            setCurrentFilteredIndex(filteredNavIndex);
        }
    }, [filteredIndices]);

    const toggleAiOptions = (qNumber: number) => {
        setShowAiOptionsForQuestion(prev => prev === qNumber ? null : qNumber);
    };

    const copyAiPromptToClipboard = (question: Question) => {
        navigator.clipboard.writeText(generateAiPrompt(question))
            .then(() => toast.success("AI Prompt copied!"))
            .catch(() => toast.error("Copy failed."));
    };

    if (isLoading || isLoadingPerks) { // Check both loading flags
        return <div className={styles.statusMessage}><Spinner text="Loading review data..." size={24} /></div>;
    }

    if (accessDeniedMessage) {
        return (
            <div className={`${styles.statusMessage} ${styles.error}`}>
                <h2>Access Denied</h2>
                <p>{accessDeniedMessage}</p>
                <button onClick={() => navigate(attemptResult ? `/results/${attemptId}` : '/profile')} className={styles.actionButton}>
                    {attemptResult ? 'Back to Results Summary' : 'Back to Profile'}
                </button>
            </div>
        );
    }

    if (error) {
        return (
            <div className={`${styles.statusMessage} ${styles.error}`}>
                <h2>Error Loading Review</h2>
                <p>{error}</p>
                <Link to={attemptResult ? `/results/${attemptId}` : '/profile'} className={styles.actionButton}>
                    {attemptResult ? 'Back to Results' : 'Back to Profile'}
                </Link>
            </div>
        );
    }
    
    // Check for empty questions array *after* loading and access checks are done
    if (!attemptResult || questions.length === 0) {
         return (
            <div className={styles.reviewPage}>
                <h1>Reviewing: {attemptResult?.examTitle || ''} {attemptResult?.groupSessionId ? '(Group)' : ''}</h1>
                 <Link to={`/results/${attemptId}`} className={styles.backLink}>
                    <FaListAlt /> Back to Summary
                </Link>
                <div className={styles.filterControls}>
                     {/* Filters remain, but message specific to no questions */}
                </div>
                <div className={`${styles.statusMessage} ${styles.emptyStateContainer}`}>
                     <FaFilter size={30} className={styles.emptyStateIcon} />
                     <p className={styles.emptyStateText}>No Questions Available for Review</p>
                     <p className={styles.emptyStateSubtext}>
                         {attemptResult?.isUserUploaded 
                            ? "This might be a custom uploaded exam where detailed review is not available with your current plan." 
                            : "The questions for this exam could not be loaded."}
                     </p>
                </div>
            </div>
         );
    }
    
    // Handle case where filter results in no questions (but questions array itself is not empty)
    if (questions.length > 0 && filteredIndices.length === 0) {
        return (
            <div className={styles.reviewPage}>
                <h1>Reviewing: {attemptResult?.examTitle || ''} {attemptResult?.groupSessionId ? '(Group)' : ''}</h1>
                <Link to={`/results/${attemptId}`} className={styles.backLink}>
                    <FaListAlt /> Back to Summary
                </Link>
                <div className={styles.filterControls}>
                    <span className={styles.filterLabel}>Status:</span>
                    <button onClick={() => setStatusFilter('all')} disabled={statusFilter === 'all'} className={`${styles.filterButton} ${statusFilter === 'all' ? styles.active : ''}`}>All</button>
                    <button onClick={() => setStatusFilter('incorrect')} disabled={statusFilter === 'incorrect'} className={`${styles.filterButton} ${statusFilter === 'incorrect' ? styles.active : ''}`}>Incorrect</button>
                    <button onClick={() => setStatusFilter('unattempted')} disabled={statusFilter === 'unattempted'} className={`${styles.filterButton} ${statusFilter === 'unattempted' ? styles.active : ''}`}>Unattempted</button>
                    
                    {/* Topic Filter Dropdown */}
                    {availableTopics.length > 0 && (
                        <>
                            <span className={styles.filterLabel} style={{marginLeft: '1rem'}}><FaTags /> Topic:</span>
                            <select
                                value={topicFilter}
                                onChange={(e) => setTopicFilter(e.target.value)}
                                className={styles.filterDropdown} // Add new style class if needed or reuse existing
                            >
                                <option value="all">All Topics</option>
                                {availableTopics.map(topic => (
                                    <option key={topic} value={topic}>{topic}</option>
                                ))}
                                <option value="General">General (No Topic)</option> {/* For untagged */}
                            </select>
                        </>
                    )}
                    
                    {/* NEW: Difficulty Filter Buttons */}
                    {availableDifficulties.length > 0 && (
                        <>
                            <span className={styles.filterLabel} style={{marginLeft: '1rem'}}><FaStarHalfAlt /> Difficulty:</span>
                            <button onClick={() => setDifficultyFilter('all')} disabled={difficultyFilter === 'all'} className={`${styles.filterButton} ${difficultyFilter === 'all' ? styles.active : ''}`}>All</button>
                            {['Easy', 'Medium', 'Hard'].map(diff => 
                                availableDifficulties.includes(diff as DifficultyFilter) && (
                                    <button key={diff} onClick={() => setDifficultyFilter(diff as DifficultyFilter)} disabled={difficultyFilter === diff} className={`${styles.filterButton} ${difficultyFilter === diff ? styles.active : ''}`}>{diff}</button>
                                )
                            )}
                            {/* Button for 'Not Specified' if any such questions exist */}
                            {availableDifficulties.includes('Not Specified') && (
                                <button onClick={() => setDifficultyFilter('Not Specified')} disabled={difficultyFilter === 'Not Specified'} className={`${styles.filterButton} ${difficultyFilter === 'Not Specified' ? styles.active : ''}`}>Not Specified</button>
                            )}
                        </>
                    )}
                </div>
                <div className={`${styles.statusMessage} ${styles.emptyStateContainer}`}>
                    <FaFilter size={30} className={styles.emptyStateIcon} />
                    <p className={styles.emptyStateText}>No Questions Found</p>
                    <p className={styles.emptyStateSubtext}>
                        There are no '{statusFilter}' questions
                        {topicFilter !== 'all' ? ` in topic '${topicFilter}'` : ''}
                        {difficultyFilter !== 'all' ? ` with difficulty '${difficultyFilter}'` : ''}
                        in this attempt. Try different filters.
                    </p>
                </div>
            </div>
        );
    }


    const currentQuestion = questions[currentReviewIndex];
    // Ensure currentQuestion exists before trying to access its properties
    if (!currentQuestion) {
        // This case should ideally be rare if filteredIndices logic is correct and questions array is not empty
        return <div className={styles.statusMessage}>Error: Could not load the current question for review.</div>;
    }
    const currentAnswerData = userAnswers?.[currentQuestion.question_number];
    const showTimeSpent = attemptResult?.settingsUsed?.trackQuestionTime === true;

    return (
        <div className={styles.reviewPage}>
            <h1>Reviewing: {attemptResult.examTitle} {attemptResult.groupSessionId ? '(Group)' : ''}</h1>
            <Link to={`/results/${attemptId}`} className={styles.backLink}>
                <FaListAlt /> Back to Summary
            </Link>

            <div className={styles.filterControls}>
                <span className={styles.filterLabel}>Status:</span>
                <button onClick={() => setStatusFilter('all')} disabled={statusFilter === 'all'} className={`${styles.filterButton} ${statusFilter === 'all' ? styles.active : ''}`}>All</button>
                <button onClick={() => setStatusFilter('incorrect')} disabled={statusFilter === 'incorrect'} className={`${styles.filterButton} ${statusFilter === 'incorrect' ? styles.active : ''}`}>Incorrect</button>
                <button onClick={() => setStatusFilter('unattempted')} disabled={statusFilter === 'unattempted'} className={`${styles.filterButton} ${statusFilter === 'unattempted' ? styles.active : ''}`}>Unattempted</button>
                
                {/* Topic Filter Dropdown */}
                {availableTopics.length > 0 && (
                    <>
                        <span className={styles.filterLabel} style={{marginLeft: '1rem'}}><FaTags /> Topic:</span>
                        <select
                            value={topicFilter}
                            onChange={(e) => setTopicFilter(e.target.value)}
                            className={styles.jumpDropdown} // Reusing jumpDropdown style for select
                        >
                            <option value="all">All Topics</option>
                            {availableTopics.map(topic => (
                                <option key={topic} value={topic}>{topic}</option>
                            ))}
                            <option value="General">General (No Topic)</option> {/* Option for untagged Qs */}
                        </select>
                    </>
                )}

                {/* NEW: Difficulty Filter Buttons */}
                {availableDifficulties.length > 0 && (
                    <>
                        <span className={styles.filterLabel} style={{marginLeft: '1rem'}}><FaStarHalfAlt /> Difficulty:</span>
                        <button onClick={() => setDifficultyFilter('all')} disabled={difficultyFilter === 'all'} className={`${styles.filterButton} ${difficultyFilter === 'all' ? styles.active : ''}`}>All</button>
                        {['Easy', 'Medium', 'Hard'].map(diff => 
                            availableDifficulties.includes(diff as DifficultyFilter) && (
                                <button key={diff} onClick={() => setDifficultyFilter(diff as DifficultyFilter)} disabled={difficultyFilter === diff} className={`${styles.filterButton} ${difficultyFilter === diff ? styles.active : ''}`}>{diff}</button>
                            )
                        )}
                        {/* Button for 'Not Specified' if any such questions exist */}
                        {availableDifficulties.includes('Not Specified') && (
                            <button onClick={() => setDifficultyFilter('Not Specified')} disabled={difficultyFilter === 'Not Specified'} className={`${styles.filterButton} ${difficultyFilter === 'Not Specified' ? styles.active : ''}`}>Not Specified</button>
                        )}
                    </>
                )}
            </div>

            <div className={styles.reviewLayout}>
                <div className={styles.questionPanel}>
                    <ReviewQuestionDisplay
                        question={currentQuestion}
                        userAnswerData={currentAnswerData}
                        showTimeSpent={showTimeSpent}
                    >
                        <div className={styles.aiActionsContainer}>
                            <button
                                onClick={() => toggleAiOptions(currentQuestion.question_number)}
                                className={styles.aiMainButton}
                                title="AI Explanation Options"
                            >
                                <FaMagic /> Explain with AI
                            </button>
                            {showAiOptionsForQuestion === currentQuestion.question_number && (
                                <div className={styles.aiOptionsDropdown}>
                                    <button onClick={() => openAiTool(generateAiPrompt(currentQuestion), 'chatgpt')} title="Explain with ChatGPT">ChatGPT</button>
                                    <button onClick={() => openAiTool(generateAiPrompt(currentQuestion), 'perplexity')} title="Explain with Perplexity">Perplexity</button>
                                    <button onClick={() => openAiTool(generateAiPrompt(currentQuestion), 'phind')} title="Explain with Phind">Phind</button>
                                    <button onClick={() => openAiTool(generateAiPrompt(currentQuestion), 'claude')} title="Open Claude.ai (Paste Prompt)">Claude</button>
                                    <div className={styles.aiOptionDivider}></div>
                                    <button onClick={() => copyAiPromptToClipboard(currentQuestion)} title="Copy prompt for other AI tools">
                                        <FaCopy /> Copy Prompt
                                    </button>
                                </div>
                            )}
                        </div>
                    </ReviewQuestionDisplay>
                </div>
                <div className={styles.palettePanel}>
                    {userAnswers && (
                        <ReviewPalette
                            questions={questions}
                            userAnswers={userAnswers}
                            currentReviewIndex={currentReviewIndex} // Pass the original index
                            onNavigate={handlePaletteNavigate}
                        />
                    )}
                </div>
            </div>

            <div className={styles.navigationControls}>
                <select
                    value={currentReviewIndex} // The original index of the current question
                    onChange={(e) => handlePaletteNavigate(parseInt(e.target.value))}
                    className={styles.jumpDropdown}
                >
                     {/* Populate options based on filteredIndices mapped back to original questions */}
                     {filteredIndices.map((originalQIndex, idxInFilteredList) => (
                         <option key={idxInFilteredList} value={originalQIndex}>
                            Q {questions[originalQIndex].question_number}
                         </option>
                     ))}
                </select>

                <button onClick={handlePrevious} disabled={currentFilteredIndex === 0} className={styles.navButton}>
                    <FaArrowLeft /> Previous
                </button>
                <span className={styles.questionCounter}>
                    Question {currentFilteredIndex + 1} of {filteredIndices.length} 
                    (Status: '{statusFilter}'
                    {topicFilter !== 'all' ? `, Topic: '${topicFilter}'` : ''})
                </span>
                <button onClick={handleNext} disabled={currentFilteredIndex >= filteredIndices.length - 1} className={styles.navButton}>
                    Next <FaArrowRight />
                </button>
            </div>
        </div>
    );
};

export default ReviewPage;
```

---

## pages\StaticPages


### pages\StaticPages\AboutPage.tsx

```typescript
// src/pages/StaticPages/AboutPage.tsx
import React, { useEffect } from 'react';
import styles from './StaticPages.module.scss';
import { FaChalkboardTeacher, FaGithub, FaHeart, FaUserGraduate, FaUsers } from 'react-icons/fa';
const GITHUB_REPO_URL = "https://github.com/Samkarya/online-exam-questions";

const AboutPage: React.FC = () => {
    useEffect(() => {
        document.title = 'About Examify';
    }, []);

    return (
        <div className={styles.staticPage}>
            <div className={styles.container}>
                {/* START: Paste content below */}

                <h1>About Examify: Your Exam Simulator</h1>

                <p>Preparing for competitive entrance exams like NIMCET or CUET MCA? Examify is your dedicated practice platform, meticulously designed to provide a realistic simulation environment and help you conquer your exams.</p>

                <h2>Our Mission: Empowering Your Preparation</h2>
                <p>We aim to bridge the gap between studying and performing under pressure. Examify provides the tools to not just test your knowledge, but to master exam patterns, optimize your time management, analyze your weaknesses, and build the confidence needed for success.</p>

                <h2>Why Practice with Examify?</h2>
                <ul>
                    <li><strong>Realistic Simulation:</strong> Experience authentic test conditions with timed sessions, interactive question palettes, marking for review, section navigation (if applicable), and standard controls – mirroring the actual exam interface.</li>
                    <li><strong>Flexible Question Sources:</strong> Practice with official past papers sourced transparently from our open GitHub repository, or upload/paste your own custom question sets in JSON format for targeted preparation.</li>
                    <li><strong>Individual & Group Sessions:</strong> Practice solo at your own pace, or create/join timed group sessions (<FaUsers style={{ verticalAlign: 'middle', marginLeft: '4px' }}/>) for collaborative learning or classroom quizzes.</li>
                    <li><strong>Configurable Sessions:</strong> Tailor your practice by setting time limits, enabling/disabling negative marking, and defining marks per question before you start.</li>
                    <li><strong>In-Depth Analysis:</strong> Move beyond simple scores. Get instant results with detailed breakdowns (correct, incorrect, unattempted) and visual charts.</li>
                    <li><strong>Detailed Answer Review:</strong> (Available for official tests) Understand your mistakes by reviewing questions, your answers, the correct answers, and available explanations.</li>
                    <li><strong>Track Your Progress:</strong> Log in with your MyServices Portal account to save your attempt history and monitor your performance over time via your profile.</li>
                    <li><strong>Host Dashboard:</strong> Easily create, manage, monitor participants in real-time, and configure result visibility for your hosted group sessions.</li>
                </ul>

                <h2>Who Can Benefit?</h2>
               <div style={{ display: 'flex', gap: '1rem', flexWrap: 'wrap', justifyContent: 'space-around', margin: '1.5rem 0' }}>
                  <div style={{ textAlign: 'center', maxWidth: '250px' }}>
                       <FaUserGraduate size={30} style={{ marginBottom: '0.5rem', color: styles.primaryColor || '#007bff' }}/>
                       <p><strong>Individual Students</strong> practicing for entrance exams.</p>
                   </div>
                   <div style={{ textAlign: 'center', maxWidth: '250px' }}>
                      <FaUsers size={30} style={{ marginBottom: '0.5rem', color: styles.primaryColor || '#007bff' }}/>
                       <p><strong>Study Groups</strong> looking to take timed tests together.</p>
                   </div>
                  <div style={{ textAlign: 'center', maxWidth: '250px' }}>
                       <FaChalkboardTeacher size={30} style={{ marginBottom: '0.5rem', color: styles.primaryColor || '#007bff' }}/>
                       <p><strong>Educators/Tutors</strong> needing a quick way to administer custom quizzes.</p>
                   </div>
               </div>


                <h2>Open Source Questions Transparency <FaGithub style={{ marginLeft: '5px', verticalAlign: 'middle'}}/></h2>
                <p>We believe in transparency. The official question papers used on Examify are maintained in a public GitHub repository. This allows you to verify the source and format, and even contribute new questions or improvements for the benefit of the community.</p>
                <p style={{ textAlign: 'center', margin: `1.5rem 0`}}>
                    <a href={GITHUB_REPO_URL} target="_blank" rel="noopener noreferrer" className={styles.githubButton}> {/* Ensure you have a .githubButton style */}
                        <FaGithub /> View Question Repository
                    </a>
                </p>

                <h2>Part of the MyServices Ecosystem</h2>
                <p>Examify seamlessly integrates with the <a href="https://bcaexamprep.web.app" target="_blank" rel="noopener noreferrer">MyServices Portal</a>. Use your single portal account to log in, access Examify, and store your attempt history alongside other connected services.</p>

                <h2>Technology Stack</h2>
                <p>Examify leverages modern technologies for a smooth and reliable experience, including React, TypeScript, SASS, Firebase, KaTeX, Recharts, and more.</p>

                <h2>Feedback Welcome!</h2>
                <p>We're constantly working to improve Examify. If you encounter any issues, have suggestions, or want to share your experience, please reach out via the <a
  href="https://bcaexamprep.web.app/contact/?subject=Examify%20[your%20subject%20here]"
  target="_blank"
  rel="noopener noreferrer"
>
  Contact Page
</a>
.</p>

                <p style={{ textAlign: 'center', marginTop: "2rem"}}>
                   Built with <FaHeart style={{ color: 'red' }}/> by Samkarya to help you succeed!
                </p>

                 {/* END: Paste content above */}
            </div>
        </div>
    );
};

export default AboutPage;
```

---

### pages\StaticPages\ContactPage.tsx

```typescript
// src/pages/StaticPages/ContactPage.tsx
import React, { useEffect } from 'react';
import styles from './StaticPages.module.scss'; // Use the static page styles
import { FaExternalLinkAlt, FaGithub } from 'react-icons/fa'; // Import icons

const PORTAL_CONTACT_URL = "https://bcaexamprep.web.app/contact/?subject=Examify%20[Your-subject-here]"; // Central contact page URL
const GITHUB_PROFILE_URL = "https://github.com/Samkarya/";         // Your GitHub URL

const ContactPage: React.FC = () => {
    useEffect(() => {
        document.title = 'Contact Us - Examify';
    }, []);

    return (
        <div className={styles.staticPage}>
            <div className={styles.container}>
                 {/* Apply the container style */}
                <div className={styles.staticPageContainer}>

                 {/* START: Paste content below this line inside staticPageContainer */}

                    <h1>Contact Us</h1>

                    <p>
                        Need assistance with Examify, encountered an issue, or have some feedback to share? We appreciate you reaching out!
                    </p>

                    <h2>Centralized Support</h2>
                    <p>
                        To ensure all inquiries are handled efficiently, we centralize our support and contact requests through the main MyServices Portal.
                    </p>
                    <p>
                        Please visit the link below to access the contact form:
                    </p>

                    {/* Clear Call to Action Link/Button */}
                    <div style={{ textAlign: 'center', margin: `${styles['spacing-lg']} 0` }}>
                        <a
                            href={PORTAL_CONTACT_URL}
                            target="_blank" // Open in new tab is often good for directing away
                            rel="noopener noreferrer"
                            className={styles.contactRedirectButton} // Define this style or use a common Button style
                            style={{
                                // Basic inline styles if no Button component/class exists
                                display: 'inline-flex',
                                alignItems: 'center',
                                padding: '10px 20px',
                                backgroundColor: '#1976d2', // Example primary color
                                color: 'white',
                                borderRadius: '4px',
                                textDecoration: 'none',
                                fontWeight: '500',
                            }}
                        >
                           Go to Central Contact Form
                           <FaExternalLinkAlt style={{ marginLeft: '8px', fontSize: '0.9em' }} />
                        </a>
                    </div>

                    <hr />

                    <h2>Connect on GitHub</h2>
                     <div style={{ display: 'flex', alignItems: 'center', gap: styles['spacing-sm'] }}>
                        <FaGithub size="1.5em" />
                        <p style={{ margin: 0 }}>
                           You can also explore our related projects and contributions on GitHub:
                           <a href={GITHUB_PROFILE_URL} target="_blank" rel="noopener noreferrer" style={{ marginLeft: '5px' }}>
                                {GITHUB_PROFILE_URL.replace('https://', '')}
                           </a>
                        </p>
                     </div>

                     {/* END: Paste content above this line */}
                 </div>
            </div>
        </div>
    );
};

export default ContactPage;
```

---

### pages\StaticPages\PrivacyPolicyPage.tsx

```typescript
// src/pages/StaticPages/PrivacyPolicyPage.tsx
import React, { useEffect } from 'react';
import styles from './StaticPages.module.scss';

const PORTAL_PRIVACY_URL = "https://bcaexamprep.web.app/privacy-policy"; // Link to main privacy policy
const PORTAL_CONTACT_URL = "https://bcaexamprep.web.app/contact";   // Link to main contact

const PrivacyPolicyPage: React.FC = () => {
    useEffect(() => {
        document.title = 'Privacy Policy - Examify';
    }, []);

    const lastUpdatedDate = "May 16, 2025"; // <-- UPDATED DATE

    return (
        <div className={styles.staticPage}>
            <div className={styles.container}>
                <div className={styles.staticPageContainer}>
                    <h1>Examify - Privacy Information</h1>
                    <p className={styles.lastUpdated}>Last updated: {lastUpdatedDate}</p>

                    <p className={styles.disclaimer} style={{ borderLeftColor: '#17a2b8', backgroundColor: '#d1ecf1' }}>
                        <strong>Relationship to Portal Policy:</strong> Examify is part of the MyServices Portal ecosystem. Your use of Examify is subject to this notice AND the comprehensive <a href={PORTAL_PRIVACY_URL} target="_blank" rel="noopener noreferrer">MyServices Portal Privacy Policy</a>, which covers your account information, core data rights, security practices, and contact procedures. This notice details data handling specific to the Examify simulator service.
                    </p>

                    <h2>1. Information Specific to Examify</h2>
                    <p>In addition to the data covered by the main Portal Privacy Policy, using Examify involves collecting:</p>
                    <ul>
                        <li>
                            <strong>Individual Exam Attempt Data:</strong> When you take an individual exam, we securely store information about your attempt linked to your MyServices Portal account. This includes:
                            <ul>
                                <li>Your selected answers for each question.</li>
                                <li>The calculated score, maximum possible score.</li>
                                <li>Counts of correct, incorrect, and unattempted questions.</li>
                                <li>Total time taken for the attempt.</li>
                                <li>Time spent per question (if this feature is enabled in settings).</li>
                                <li>The specific settings used for that attempt (time limit, marking scheme).</li>
                                <li>An identifier for the exam question set used (official path or indicator of custom upload).</li>
                            </ul>
                            This data is used to provide you with results, allow answer review (for official tests), and populate your attempt history on your Portal profile.
                        </li>
                        <li>
                            <strong>User-Uploaded/Pasted Content (Individual Practice):</strong>
                            If you upload or paste a custom JSON question set for individual practice, Examify processes this data to deliver the exam simulation service during that session.
                            If your account tier includes the feature to review custom uploaded exams, the JSON content you provided for an individual practice session <strong>will be stored</strong> as `questionJsonString` alongside your attempt result data in your personal history. This is solely to enable the review functionality for that specific attempt. If you delete the attempt from your history, this stored question data will also be deleted.
                            If your tier does not include this review feature, or if this feature is disabled, the custom question JSON is not persistently stored with your attempt history.
                            You are responsible for the content you upload/paste.
                        </li>
                       <li>
                           <strong>Group Session Data:</strong>
                           <ul>
                               <li><strong>For Hosts:</strong> When you create a group session, we store the session configuration (name, timing, source type, result visibility rules, marking scheme, monitoring settings, and any geolocation restrictions) linked to your Host UID. If using custom JSON, the JSON content itself is stored as part of the session configuration for Participants to access. This custom JSON content is deleted if the Host deletes the session configuration from their dashboard.</li>
                               <li><strong>For Participants:</strong> When you join a group session, a record of your participation is created within that session's data, linked to your Participant UID. This record includes:
                                   <ul>
                                       <li>Your status (joined, started, completed).</li>
                                       <li>Timestamps for joining, starting, and completing the exam.</li>
                                       <li>Your display name (if provided during registration).</li>
                                       <li>Your final score and the maximum possible score (added upon completion).</li>
                                   </ul>
                                   Your specific answers within a group session attempt are stored as part of your *individual* attempt record (linked to your personal history, see above), similar to solo practice, but this attempt record will also contain the `groupSessionId`.
                               </li>
                           </ul>
                       </li>
                        <li>
                            <strong>Group Session Monitoring Data (Anti-Cheating):</strong> If a Host enables monitoring features for a group session, and you consent to participate:
                            <ul>
                                <li>Specific events during your exam attempt may be logged. These events are associated with your participant record for that session.</li>
                                <li>Logged events can include:
                                    <ul>
                                        <li>Instances where the exam tab/window loses focus, and when focus is regained (potentially including duration).</li>
                                        <li>Attempts to copy content from or paste content into the exam interface.</li>
                                        <li>Use of certain restricted keyboard shortcuts (e.g., PrintScreen attempts, Print dialog invocation).</li>
                                    </ul>
                                </li>
                                <li>This monitoring data is made available to the Host of that specific group session for review.</li>
                            </ul>
                        </li>
                        <li>
                            <strong>Simulator Usage Data (Analytics):</strong> We may collect anonymized or aggregated data about how features within Examify are used (e.g., frequency of filter use, session creation frequency, types of exams taken) via Google Analytics to help us improve the simulator's functionality and user experience. This is distinct from your personal attempt results or session participation records.
                        </li>
                    </ul>

                    <h2>2. How Examify Uses Your Information</h2>
                    <p>Examify-specific data is used primarily to:</p>
                    <ul>
                        <li>Provide the core exam simulation functionality (individual and group).</li>
                        <li>Manage group session creation, joining, status tracking, and participation.</li>
                        <li>Deliver group exam sessions, including any enabled monitoring features.</li>
                        <li>Provide Hosts with data regarding participant engagement and potential integrity flags if monitoring is enabled for their session.</li>
                        <li>Calculate and display your exam results and performance breakdowns.</li>
                        <li>Enable the answer review feature (based on session settings and exam type).</li>
                        <li>Display relevant information to Hosts (participant status, scores based on visibility settings).</li>
                        <li>Display leaderboards (if configured by the Host and session has ended).</li>
                        <li>Populate and maintain your attempt history accessible via your Examify <a href="/profile" target="_blank" rel="noopener noreferrer">Profile</a>.</li>
                        <li>Analyze simulator usage patterns (anonymously/aggregated) to identify areas for improvement.</li>
                    </ul>

                   <h2>3. Data Sharing within Group Sessions</h2>
                   <p>By participating in a group session, you acknowledge and agree that the following information related to your participation in *that specific session* may be visible:</p>
                   <ul>
                       <li><strong>To the Host:</strong> Your display name, join/start/completion status, your score (depending on the Host's `resultVisibility` setting), and, if monitoring was enabled by the Host for that session, a summary or log of any detected monitoring events associated with your participation.</li>
                       <li><strong>To other Participants:</strong> Depending on the Host's `resultVisibility` setting (e.g., 'Leaderboard After End Time'), your display name and score/rank might be visible on a leaderboard *after* the session's end time (if set). Your individual answers are not shared with other participants.</li>
                   </ul>
                   <p>The Host is responsible for choosing appropriate `resultVisibility` settings for their session.</p>

                   <h2>4. Cookies</h2>
                    <p>Examify relies on the authentication cookies set by the MyServices Portal (via Firebase) to keep you logged in. It does not typically set additional third-party tracking or advertising cookies itself.</p>

                   <h2>5. Data Access and Deletion</h2>
                    <p>
                        You can access your individual Examify attempt history (including attempts from group sessions and any associated custom `questionJsonString` if your tier allows its review) through your Examify <a href="/profile" target="_blank" rel="noopener noreferrer">Profile</a> page. You can delete these individual attempt records from your history. Deleting an attempt that included a stored custom `questionJsonString` will also delete that stored JSON.
                    </p>
                   <p>
                       Your participation record within a specific group session (status, score, and any associated monitoring events visible to the host/leaderboard) is part of that session's data.
                       If you delete an attempt from your personal history that was part of a group session, AND the Host has *already deleted* the main configuration for that group session from their dashboard, your specific participation record (including any associated monitoring logs) within that (now-defunct) session's data will also be deleted from the participants subcollection.
                       For active or closed (but not deleted by host) group sessions, your participation data (status, score, monitoring logs) remains as part of that session's records, accessible to the Host, even if you delete the corresponding attempt from your personal history. This data is removed if the Host subsequently deletes the entire session configuration.
                       Deleting your main MyServices Portal account is subject to the main Portal's data deletion processes.
                   </p>

                        <h2>6. Third-Party Services Used by Examify</h2>
                        <p>Beyond the core Firebase services outlined in the main Portal policy, Examify utilizes:</p>
                        <ul>
                            <li><strong>Recharts:</strong> A library used locally in your browser to render charts on the results page. It does not typically send data externally.</li>
                            <li><strong>KaTeX & React Markdown:</strong> Libraries used locally in your browser to render mathematical formulas and formatted text within questions/options/explanations. They do not send data externally.</li>
                        </ul>

                        <hr />

                        <h2>7. Contact Regarding Examify Privacy</h2>
                        <p>
                           For questions specifically about how Examify handles your data, or any privacy concerns, please use the central <a href={PORTAL_CONTACT_URL} target="_blank" rel="noopener noreferrer">MyServices Portal Contact Page</a>.
                        </p>
                </div>
            </div>
        </div>
    );
};

export default PrivacyPolicyPage;
```

---

### pages\StaticPages\StaticPages.module.scss

```scss
// src/pages/StaticPages/StaticPages.module.scss
@import '../../styles/variables';
@import '../../styles/mixins';

.staticPage {
    padding: $spacer * 2 0 $spacer * 3 0; // Top/Bottom padding
    background-color: $component-bg; // Optional: Slightly different background from body
    border-top: 1px solid $border-color; // Optional separator line
    min-height: 60vh; // Ensure page takes up reasonable height

    .container {
        max-width: 900px; // Limit content width for readability
        margin: 0 auto;
        padding: 0 $spacer * 1.5;
    }

    h1 {
        font-size: $h2-font-size; // Use H2 size for page title
        color: $primary-color;
        text-align: center;
        margin-bottom: $spacer * 2.5;
        font-weight: 600;
    }

    h2 {
        font-size: $h4-font-size;
        color: $dark-color;
        margin-top: $spacer * 2;
        margin-bottom: $spacer;
        padding-bottom: $spacer * 0.5;
        border-bottom: 1px solid $border-color;
        font-weight: 500;
    }

    h3 {
        font-size: $h5-font-size;
        color: darken($dark-color, 5%);
        margin-top: $spacer * 1.5;
        margin-bottom: $spacer * 0.5;
        font-weight: 500;
    }

    p {
        line-height: 1.7;
        margin-bottom: $spacer;
        color: $text-color;
    }

    ul, ol {
        margin-left: $spacer * 1.5;
        margin-bottom: $spacer;
        padding-left: $spacer;
        line-height: 1.7;

        li {
            margin-bottom: $spacer * 0.5;
        }
    }

    a {
        // Inherits base link styles, add specifics if needed
        font-weight: 500; // Make links slightly bolder
    }

    strong {
        font-weight: 600;
    }

    // Specifics for Contact Page if needed
    .contactInfo {
        list-style: none;
        padding: 0;
        margin-left: 0; // Reset indent for contact list

        li {
            margin-bottom: $spacer;
            display: flex;
            align-items: center;
            gap: $spacer;
        }

        svg { // Style icons if used
            color: $primary-color;
            font-size: $font-size-base * 1.3;
            flex-shrink: 0;
        }
    }

    // For highlighting disclaimers/important notes
    .disclaimer {
        background-color: lighten($warning-color, 45%);
        border-left: 4px solid $warning-color;
        padding: $spacer $spacer * 1.5;
        margin: $spacer * 1.5 0;
        border-radius: $border-radius-sm;
        font-size: $font-size-base * 0.95;

        p:last-child {
            margin-bottom: 0;
        }
    }
}
```

---

### pages\StaticPages\TermsOfServicePage.tsx

```typescript
// src/pages/StaticPages/TermsOfServicePage.tsx
import React, { useEffect } from 'react';
import styles from './StaticPages.module.scss';

// Constants for URLs
const PORTAL_TERMS_URL = "https://bcaexamprep.web.app/terms-of-service"; // Link to main terms
const PORTAL_PRIVACY_URL = "https://bcaexamprep.web.app/privacy-policy"; // Link to main privacy
const PORTAL_CONTACT_URL = "https://bcaexamprep.web.app/contact/?subject=Examify";   // Link to main contact
const GITHUB_QUESTIONS_URL = "https://github.com/Samkarya/online-exam-questions"; // Link to questions repo

const TermsPage: React.FC = () => {
    useEffect(() => {
        document.title = 'Terms of Service - Examify';
    }, []);

    const lastUpdatedDate = "May 16, 2025"; // Updated date

    return (
        <div className={styles.staticPage}>
            <div className={styles.container}>
                <div className={styles.staticPageContainer}>
                    <h1>Examify - Supplementary Terms of Service</h1>
                    <p className={styles.lastUpdated}>Last updated: {lastUpdatedDate}</p>

                    <h2>1. Acceptance of Terms</h2>
                    <p>
                        Welcome to Examify (the "Simulator", "Service"), operated by Samkarya. These supplementary terms govern your use of the Examify Exam Simulator service.
                    </p>
                    <p className={styles.disclaimer} style={{ borderLeftColor: '#17a2b8', backgroundColor: '#d1ecf1' }}>
                       <strong>Important:</strong> Your use of Examify is conditional upon your acceptance of <strong>both</strong> these supplementary terms <strong>AND</strong> the main <a href={PORTAL_TERMS_URL} target="_blank" rel="noopener noreferrer">MyServices Portal Terms of Service</a>, which cover account creation, general conduct, termination, primary disclaimers, and liability limitations. Please read both documents carefully.
                    </p>

                    <h2>2. Service Description and Intended Use</h2>
                    <p>
                        Examify provides a platform to simulate competitive examination environments for practice purposes. It allows users to take tests individually using official question sets (sourced publicly) or custom question sets uploaded/pasted by the user ("User Content"). It also allows authenticated users ("Hosts") to create timed group sessions using either official or User Content, which other authenticated users ("Participants") can join using a unique Session ID. It is intended as a study aid and preparation tool for individuals and groups.
                    </p>

                    <h2>3. Use Restrictions</h2>
                    <p>In addition to the rules outlined in the main Portal Terms, you agree not to:</p>
                    <ul>
                        <li>Attempt to manipulate, bypass, or exploit the timing mechanisms, scoring logic, session joining/status mechanisms, anti-cheating monitoring features (if active), or other features of the Simulator.</li>
                        <li>Use the Service for any commercial purpose (e.g., reselling access, charging others for use) without explicit written permission from Samkarya.</li>
                        <li>Upload, paste, or distribute content through the Simulator (either for individual use or in a group session) that is illegal, hateful, defamatory, infringing on intellectual property rights, or otherwise violates applicable laws.</li>
                        <li>Use automated means (bots, scrapers) to interact with the exam interface, group session features, or extract question content.</li>
                        <li>Share Session IDs inappropriately or disrupt group sessions you are participating in or hosting.</li>
                        <li>Misrepresent your identity when joining or hosting a group session.</li>
                    </ul>

                    <h2>4. Group Exam Session Monitoring (Anti-Cheating Measures)</h2>
                    <p>
                        For Group Exam Sessions, the Host may choose to enable certain anti-cheating monitoring features. If these features are enabled for a session you join as a Participant:
                    </p>
                    <ul>
                        <li>
                            <strong>Notification and Consent:</strong> You will be notified prior to joining the session if monitoring features are active. Your action of joining the session after such notification, and agreeing to any pre-exam prompts, constitutes your consent to these measures for the duration of that specific exam attempt.
                        </li>
                        <li>
                            <strong>Measures May Include:</strong>
                            <ul>
                                <li><strong>Focus Tracking:</strong> The Simulator may detect if the exam window or browser tab loses focus (e.g., if you switch to another application or tab). Occurrences and durations of focus loss may be logged.</li>
                                <li><strong>Copy/Paste Restriction:</strong> Attempts to copy content from the exam or paste content into it may be blocked and logged.</li>
                                <li><strong>Restricted Key Press Logging:</strong> Attempts to use certain keyboard shortcuts (e.g., related to printing, screen capture) may be logged.</li>
                            </ul>
                        </li>
                        <li>
                            <strong>Purpose:</strong> These measures are intended to help maintain the integrity of the practice session and provide the Host with insights into participant engagement.
                        </li>
                        <li>
                            <strong>Data:</strong> Events detected by these measures (e.g., focus loss events, copy attempts) will be logged and may be made available to the Host of the group session. Please see our Examify Privacy Information for more details on data handling.
                        </li>
                        <li>
                            <strong>Limitations:</strong> While these measures aim to deter academic dishonesty, they are primarily client-side and may not detect all forms of circumvention. They should be considered as deterrents and informational tools for the Host.
                        </li>
                    </ul>

                    <h2>5. Question Content and Accuracy</h2>
                    <ul>
                        <li>
                            <strong>Official Questions:</strong> Questions sourced from our <a href={GITHUB_QUESTIONS_URL} target="_blank" rel="noopener noreferrer">public GitHub repository</a> are provided for practice based on publicly available past papers or contributed materials. While we strive for accuracy, we do not guarantee that these questions or their provided answers/explanations are free from errors. Use them as a study tool and verify information independently if needed.
                        </li>
                        <li>
                            <strong>User Content:</strong> You are solely responsible for the accuracy, legality, and copyright compliance of any question sets you upload or paste into the Simulator ("User Content"), whether for individual practice or as a Host of a group session. You represent and warrant that you have the necessary rights to use this content. Examify processes this content solely to provide the simulation service and does not claim ownership or verify its accuracy.
                            If you use User Content for individual practice, and your account tier includes the feature to review custom uploaded exams, the JSON content may be stored alongside your attempt result to facilitate this review feature. Otherwise, or if the attempt is deleted, it is not persistently stored with your user profile after the session.
                        </li>
                        <li>
                            <strong>License for User Content:</strong> By uploading or pasting User Content, you grant Samkarya a temporary, non-exclusive license to process, store (potentially temporarily), and display that content solely for the purpose of delivering the exam simulation experience back to you.
                        </li>
                    </ul>

                    <h2>6. Group Exam Sessions (General)</h2>
                    <ul>
                        <li>
                            <strong>Hosting:</strong> Hosts are responsible for configuring their sessions appropriately (name, timing, question source, monitoring settings, result visibility). Hosts using User Content for their sessions are responsible for that content's compliance (see Section 5). Hosts can monitor participant status and manage (e.g., close) their sessions via the dashboard. Misuse of hosting features may lead to account restrictions.
                        </li>
                        <li>
                            <strong>Participation:</strong> Participants join sessions using a Session ID provided by the Host. Participation is subject to these terms and any specific timing or rules set by the Host (e.g., start/end times).
                        </li>
                        <li>
                            <strong>Data Sharing in Sessions:</strong> When participating in a group session, your status (joined, started, completed) and potentially your display name and final score (depending on Host's visibility settings and session status) may be visible to the Host and potentially other Participants (e.g., on a leaderboard after the session ends). By joining a session, you consent to this level of sharing within the context of that session. Your individual answers are not typically shared with other participants but are processed to calculate your score.
                        </li>
                    </ul>

                    <h2>7. Results and Disclaimers</h2>
                    <ul>
                        <li>
                            <strong>Practice Aid:</strong> Examify results are intended for personal review and practice analysis. They are not a guaranteed predictor of your performance in actual examinations.
                        </li>
                        <li>
                            <strong>No Warranty:</strong> The Simulator is provided "AS IS". We disclaim all warranties regarding the accuracy of questions, the perfection of the simulation, or the suitability of the Service for achieving specific exam results.
                        </li>
                    </ul>

                    <h2>8. Account Tiers and Feature Availability</h2>
                    <p>
                        Certain features, functionalities, or usage limits within Examify (such as the number of attempts that can be saved to your history, the ability to host group sessions, access to anti-cheating monitoring features, or the ability to review custom uploaded exams) may be dependent on your account's subscription tier ("Perks"). Available tiers, features, and limits are described on our platform or associated pricing information. We reserve the right to modify features and limits associated with different tiers.
                    </p>

                    <h2>9. Data Storage</h2>
                    <p>
                        Your exam attempt history and results generated within Examify are associated with your MyServices Portal account. Data handling, storage, retention, and your rights concerning this data are governed by the main <a href={PORTAL_PRIVACY_URL} target="_blank" rel="noopener noreferrer">MyServices Portal Privacy Policy</a>.
                    </p>

                    <h2>10. Changes to These Terms</h2>
                    <p>
                        We may update these Examify-specific supplementary terms occasionally. We will notify users of significant changes where feasible. Continued use of Examify after changes constitutes acceptance. Major changes affecting your core account are governed by the update process described in the main Portal Terms.
                    </p>

                    <hr />

                    <h2>11. Contact</h2>
                    <p>
                        For any questions regarding Examify or these terms, please use the central <a href={PORTAL_CONTACT_URL} target="_blank" rel="noopener noreferrer">MyServices Portal Contact Page</a>.
                    </p>

                </div>
            </div>
        </div>
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


### routes\AppRoutes.tsx

```typescript
// src/routes/AppRoutes.tsx
import React, { Suspense, lazy, JSX, useEffect } from 'react'; // Import useEffect
import { Routes, Route, useLocation } from 'react-router-dom'; // Import useLocation

// Import Layout and Auth context/hook - These are needed immediately
import Layout from '../components/Layout/Layout';
import { useAuth } from '../contexts/AuthContext';
import Spinner from '../components/Spinner/Spinner'; // Import Spinner for fallback

// --- Lazy Load Page Components ---
const HomePage = lazy(() => import('../pages/HomePage/HomePage'));
const ExamSelectionPage = lazy(() => import('../pages/ExamSelectionPage/ExamSelectionPage'));
const ExamPage = lazy(() => import('../pages/ExamPage/ExamPage'));
const ResultsPage = lazy(() => import('../pages/ResultsPage/ResultsPage'));
const ProfilePage = lazy(() => import('../pages/ProfilePage/ProfilePage'));
const NotFoundPage = lazy(() => import('../pages/NotFoundPage/NotFoundPage'));
const ReviewPage = lazy(() => import('../pages/ReviewPage/ReviewPage'));
const TermsOfServicePage = lazy(() => import('../pages/StaticPages/TermsOfServicePage'));
const PrivacyPolicyPage = lazy(() => import('../pages/StaticPages/PrivacyPolicyPage'));
const ContactPage = lazy(() => import('../pages/StaticPages/ContactPage'));
const AboutPage = lazy(() => import('../pages/StaticPages/AboutPage'));
const BlogListPage = lazy(() => import('../pages/BlogListPage/BlogListPage'));
const BlogPostPage = lazy(() => import('../pages/BlogPostPage/BlogPostPage'));
//const RegistrationPage = lazy(() => import('../pages/RegisterPage/RegisterPage'));
const GroupExamSetupPage = lazy(() => import('../pages/GroupExamSetupPage/GroupExamSetupPage'));
const JoinGroupExamPage = lazy(() => import('../pages/JoinGroupExamPage/JoinGroupExamPage'));
const GroupExamSharePage = lazy(() => import('../pages/GroupExamSharePage/GroupExamSharePage'));
const GroupExamSessionPage = lazy(() => import('../pages/GroupExamSessionPage/GroupExamSessionPage'));
const GroupExamWaitingPage = lazy(() => import('../pages/GroupExamWaitingPage/GroupExamWaitingPage'));
const HostDashboardPage = lazy(() => import('../pages/HostDashboardPage/HostDashboardPage'));
const GroupExamDetailPage = lazy(() => import('../pages/GroupExamDetailPage/GroupExamDetailPage'));

const AntiCheatingSandboxPage = lazy(() => import('../pages/AntiCheatingSandboxPage/AntiCheatingSandboxPage'));
// --- End Lazy Loading ---

// --- Loading Fallback Component ---
const RouteLoadingFallback: React.FC = () => (
    <div style={{ display: 'flex', justifyContent: 'center', alignItems: 'center', minHeight: '70vh', width: '100%' }}>
        <Spinner size={30} text="Loading page..." />
    </div>
);

// --- UPDATED ProtectedRoute component ---
const ProtectedRoute: React.FC<{ children: JSX.Element }> = ({ children }) => {
  // Get auth state AND the modal function
  const { currentUser, isLoading, isLoginModalOpen, openLoginModal } = useAuth();
  const location = useLocation(); // Get current location

  useEffect(() => {
    // Check if loading is done AND user is not logged in AND modal is not already open
    if (!isLoading && !currentUser && !isLoginModalOpen) {
      // Trigger the login modal
      // Include the path they tried to access in the message (optional but helpful)
      openLoginModal(`Please log in to access the '${location.pathname}' page.`);
    }
    // Run this effect when loading state changes or user status changes
  }, [isLoading, currentUser, isLoginModalOpen, openLoginModal, location.pathname]); // Add dependencies

  if (isLoading) {
    // Show loading spinner while checking auth state
    return <RouteLoadingFallback />;
  }

  if (!currentUser) {
    // User is not logged in, and the useEffect has likely triggered the modal.
    // We still shouldn't render the protected children.
    // Returning null might be okay if the modal overlays everything.
    return null;
  }

  // If loading is complete and user exists, render the requested component
  return children;
};

const AppRoutes: React.FC = () => {
  return (
    // Wrap the entire Routes component with Suspense
    <Suspense fallback={<RouteLoadingFallback />}>
        <Routes>
          {/* Routes within the main Layout */}
          <Route path="/" element={<Layout />}>
            <Route index element={<HomePage />} />
            <Route path="select-exam" element={<ExamSelectionPage />} />
            {/*<Route path="/register" element={<RegistrationPage />} />*/}
            <Route path="terms-of-service" element={<TermsOfServicePage />} />
            <Route path="privacy-policy" element={<PrivacyPolicyPage />} />
            <Route path="contact" element={<ContactPage />} />
            <Route path="about" element={<AboutPage />} />
            <Route path="blog" element={<BlogListPage />} />
            <Route path="blog/:slug" element={<BlogPostPage />} />

            {/* Protected Routes within Layout */}
            <Route
                path="results/:attemptId"
                element={<ProtectedRoute><ResultsPage /></ProtectedRoute>}
            />
            <Route
                path="review/:attemptId"
                element={<ProtectedRoute><ReviewPage /></ProtectedRoute>}
            />
            <Route
                path="profile"
                element={<ProtectedRoute><ProfilePage /></ProtectedRoute>}
            />
            <Route path = "group-exam/setup" element={<ProtectedRoute><GroupExamSetupPage /></ProtectedRoute>} />
            <Route path = "/group-exam/join" element={<ProtectedRoute><JoinGroupExamPage /></ProtectedRoute>} />
            <Route path = "/group-exam/wait/:sessionId" element={<ProtectedRoute><GroupExamWaitingPage /></ProtectedRoute>} />
            <Route path = "/group-exam/share/:sessionId" element={<ProtectedRoute><GroupExamSharePage /></ProtectedRoute>} />
            <Route path = "/group-exam/dashboard" element={<ProtectedRoute><HostDashboardPage /></ProtectedRoute>} />
            <Route path = "/group-exam/detail/:sessionId" element={<ProtectedRoute><GroupExamDetailPage /></ProtectedRoute>} />

            <Route path="/tools/anti-cheating-sandbox" element={<ProtectedRoute><AntiCheatingSandboxPage /></ProtectedRoute>} />
          </Route> {/* End of Layout Routes */}

          {/* Standalone Protected Routes */}
           <Route
                path="exam/:examIdentifier"
                element={<ProtectedRoute><ExamPage /></ProtectedRoute>}
            />
           <Route
               path="group-exam/session/:sessionId"
               element={<ProtectedRoute><GroupExamSessionPage /></ProtectedRoute>}
           />

          {/* Catch-all Not Found Route */}
          <Route path="*" element={<NotFoundPage />} />
        </Routes>
    </Suspense> // End Suspense wrapper
  );
};

export default AppRoutes;
```

---

## services


### services\configService.ts

```typescript
// src/services/configService.ts
import { doc, getDoc, DocumentData, DocumentSnapshot } from 'firebase/firestore';
import { db } from './firebase';
import { TierConfig, UserService,} from '../types';

interface TierDetailsDoc {
    tiers: TierConfig[];
}

interface ServicesDoc {
    defaultServices?: UserService[]; // Make optional if sometimes missing
    availableServices?: string[];
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

```

---

### services\firebase.ts

```typescript
// src/services/firebase.ts
import { initializeApp } from 'firebase/app';
import { 
  getAuth, 
  connectAuthEmulator,
  signInWithEmailAndPassword,
  signOut,
  User,
  onAuthStateChanged
} from 'firebase/auth';
import {
  getFirestore,
  doc,
  getDoc,
} from 'firebase/firestore';
import { getAnalytics, Analytics } from 'firebase/analytics';


const firebaseConfig = {
  apiKey: process.env.REACT_APP_FIREBASE_API_KEY,
  authDomain: process.env.REACT_APP_FIREBASE_AUTH_DOMAIN,
  projectId: process.env.REACT_APP_FIREBASE_PROJECT_ID,
  storageBucket: process.env.REACT_APP_FIREBASE_STORAGE_BUCKET,
  messagingSenderId: process.env.REACT_APP_FIREBASE_MESSAGING_SENDER_ID,
  appId: process.env.REACT_APP_FIREBASE_APP_ID,
  measurementId: process.env.REACT_APP_FIREBASE_MEASUREMENT_ID 
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
export const auth = getAuth(app);
export const db = getFirestore(app);
export const analytics: Analytics = getAnalytics(app);
// Option 2: Using window.location.hostname (Simpler, might catch deployed local builds)
if (process.env.NODE_ENV !== 'test' && window.location.hostname === "localhost") {
 //console.log("Connecting to Firebase Emulators (hostname check, non-test env)...");
  try {
    // Connect Auth Emulator
    connectAuthEmulator(auth, "http://localhost:9099");

    // Dynamically import and connect Firestore emulator ONLY in non-test env
    // This avoids importing it when jest.mock('firebase/firestore') is active
    import('firebase/firestore').then(({ connectFirestoreEmulator }) => {
        connectFirestoreEmulator(db, "localhost", 8080);
       //console.log("Firestore Emulator connected.");
    }).catch(err =>console.error("Failed to connect Firestore Emulator:", err));

  } catch (error) {
     //console.error("Error connecting to Firebase Emulators:", error);
  }
}

// User authentication functions
export const loginUser = (email: string, password: string) => {
  return signInWithEmailAndPassword(auth, email, password);
};


export const logoutUser = () => {
  return signOut(auth);
};

export const onAuthUserStateChanged = (callback: (user: User | null) => void) => {
  return onAuthStateChanged(auth, callback);
};

export const getCurrentUser = (): User | null => {
  return auth.currentUser;
};

export const getUserData = async (userId: string) => {
  const userDoc = doc(db, 'users', userId);
  const userSnapshot = await getDoc(userDoc);
  
  if (userSnapshot.exists()) {
    return userSnapshot.data();
  }
  
  return null;
};
```

---

### services\firestoreService.ts

```typescript
// src/services/firestoreService.ts
import { db } from './firebase';
import {
    collection,
    addDoc,
    getDoc,
    doc,
    query,
    getDocs,
    orderBy,
    deleteDoc,
    getCountFromServer ,
    setDoc, 
    updateDoc, 
    serverTimestamp,
    Timestamp,
    where
} from 'firebase/firestore';
import { AttemptResult, GroupExam, GroupExamStatus, MonitoringEvent, ParticipantData} from '../types';

// Firestore type that includes Firestore Timestamp
type AttemptResultInFirestore = AttemptResult & { userId: string };

// Save an attempt result
export const saveAttemptResult = async (result: AttemptResult): Promise<string> => {
    try {
        const { id, ...dataToSaveWithoutId } = result;
        const dataToSave = {
            ...dataToSaveWithoutId, // Spread fields other than 'id'
            attemptTimestamp: serverTimestamp()// Overwrite with correct timestamp type
        };

        const attemptsRef = collection(db, `examSimulator/${result.userId}/attempts`);
        const docRef = await addDoc(attemptsRef, dataToSave);
        return docRef.id;
    } catch (e) {
        //console.error("Error adding document: ", e);
        throw new Error("Failed to save attempt result.");
    }
};

// Fetch a specific attempt result
export const getAttemptResult = async (
    userId: string,
    attemptId: string
): Promise<(AttemptResult & { id: string }) | null> => {
    try {
        const attemptRef = doc(db, `examSimulator/${userId}/attempts`, attemptId);
        const docSnap = await getDoc(attemptRef);

        if (docSnap.exists()) {
            const data = docSnap.data() as AttemptResultInFirestore;
            return {
                ...data,
                id: docSnap.id
            };
        } else {
            //console.log("No such document!");
            return null;
        }
    } catch (error) {
        //console.error("Error fetching attempt result:", error);
        throw new Error("Failed to fetch attempt details.");
    }
};

// Fetch all attempts for a user
export const getAllUserAttempts = async (
    userId: string
): Promise<(AttemptResult & { id: string })[]> => {
    try {
        const attemptsRef = collection(db, `examSimulator/${userId}/attempts`);
        const q = query(attemptsRef, orderBy("attemptTimestamp", "desc"));
        const querySnapshot = await getDocs(q);

        const attempts: (AttemptResult & { id: string })[] = [];
        querySnapshot.forEach((docSnap) => {
            const data = docSnap.data() as AttemptResultInFirestore;
            attempts.push({
                ...data,
                id: docSnap.id
            });
        });
        return attempts;
    } catch (error) {
        //console.error("Error fetching user attempts:", error);
        throw new Error("Failed to fetch attempt history.");
    }
};
// --- Modified deleteAttemptResult ---
/**
 * Deletes a specific attempt result from a user's personal history.
 * IMPORTANT: This ONLY deletes the record in /examSimulator, not the corresponding
 * participant record in a group session (if applicable).
 * @param userId The Firebase Auth UID of the user.
 * @param attemptId The ID of the attempt document to delete.
 */
export const deleteAttemptResult = async (userId: string, attemptId: string): Promise<void> => {
    try {
        const attemptRef = doc(db, `examSimulator/${userId}/attempts`, attemptId);
        await deleteDoc(attemptRef);
        //console.log(`Attempt ${attemptId} deleted successfully from user ${userId}'s history.`);
    } catch (error) {
        //console.error("Error deleting attempt result:", error);
        throw new Error("Failed to delete the attempt from your history.");
    }
};

/**
 * Gets the total number of attempts stored for a specific user.
 * Uses getCountFromServer for efficiency.
 * @param userId The Firebase Auth UID of the user.
 * @returns Promise<number> The total count of attempts.
 */
export const getAttemptsCount = async (userId: string): Promise<number> => {
    try {
        const attemptsRef = collection(db, `examSimulator/${userId}/attempts`);
        const snapshot = await getCountFromServer(attemptsRef);
        return snapshot.data().count;
    } catch (error) {
        //console.error("Error fetching attempts count:", error);
        // Decide how to handle error: rethrow, return 0, return -1?
        // Rethrowing forces the caller to handle it.
        throw new Error("Failed to fetch attempt count.");
    }
};

// --- NEW: Group Exam Functions ---

// Updated createGroupExam
export const createGroupExam = async (groupExamData: Omit<GroupExam, 'id' | 'createdAt' | 'status'> & { hostUid: string } ): Promise<string> => {
    try {
        // Convert JS Dates from potential date pickers to Timestamps before saving
        const startTime = groupExamData.startTime instanceof Date ? Timestamp.fromDate(groupExamData.startTime) : groupExamData.startTime;
        const endTime = groupExamData.endTime instanceof Date ? Timestamp.fromDate(groupExamData.endTime) : groupExamData.endTime;

        const dataToSave = {
            ...groupExamData,
            startTime: startTime, // Use converted timestamp or null
            endTime: endTime,   // Use converted timestamp or null
            createdAt: serverTimestamp(), // Use server timestamp
            // --- Add new fields from payload ---
            ...(groupExamData.marksPerCorrect !== undefined && { marksPerCorrect: groupExamData.marksPerCorrect }),
            ...(groupExamData.negativeMarkingEnabled !== undefined && { negativeMarkingEnabled: groupExamData.negativeMarkingEnabled }),
            ...(groupExamData.negativeMarksPerIncorrect !== undefined && { negativeMarksPerIncorrect: groupExamData.negativeMarksPerIncorrect }),
            status: 'pending' as GroupExam['status'],
            // Ensure resultVisibility defaults or is passed correctly
            resultVisibility: groupExamData.resultVisibility || 'Self Only Immediate', // Default if not provided
            monitoringEnabled: groupExamData.monitoringEnabled ?? false,
            geoRestriction: groupExamData.geoRestriction || null,
        };
        const groupExamsRef = collection(db, 'groupExams');
       //console.log(dataToSave);
        const docRef = await addDoc(groupExamsRef, dataToSave);
        return docRef.id;
    } catch (e) {
       //console.error("Error creating group exam: ", e);
        throw new Error("Failed to create group exam session.");
    }
};

/**
 * Fetches the details of a specific group exam session.
 * @param sessionId The ID of the group exam session.
 * @returns The GroupExam data including the ID, or null if not found.
 */
export const getGroupExam = async (sessionId: string): Promise<GroupExam | null> => {
    try {
        const sessionRef = doc(db, 'groupExams', sessionId);
        const docSnap = await getDoc(sessionRef);

        if (docSnap.exists()) {
            return {
                id: docSnap.id,
                ...docSnap.data()
            } as GroupExam;
        } else {
            //console.log("No such group exam session!");
            return null;
        }
    } catch (error) {
       //console.error("Error fetching group exam session:", error);
        throw new Error("Failed to fetch group exam details.");
    }
};

/**
 * Adds a participant to a group exam session's subcollection.
 * @param sessionId The ID of the group exam session.
 * @param participantUserId The UID of the participant joining.
 * @param participantDisplayName Optional display name to store.
 */
export const addParticipantToGroupExam = async (sessionId: string, participantUserId: string, participantDisplayName?: string): Promise<void> => {
    try {
        const participantRef = doc(db, `groupExams/${sessionId}/participants`, participantUserId);
        // Initialize startedAt as null
        const participantData: Omit<ParticipantData, 'score' | 'maxScore' | 'completionTimestamp'> = {
            status: 'joined',
            joinedAt: serverTimestamp() as Timestamp,
            startedAt: null, // Initialize startedAt
            ...(participantDisplayName && { displayName: participantDisplayName })
        };
        await setDoc(participantRef, participantData);
    } catch (error) {
      //console.error("Error adding participant:", error);
        throw new Error("Failed to join the group session.");
    }
};

// NEW: Function to mark when participant starts the exam
export const startParticipantAttempt = async (sessionId: string, participantUserId: string): Promise<void> => {
    try {
        const participantRef = doc(db, `groupExams/${sessionId}/participants`, participantUserId);
        const updateData: Partial<ParticipantData> = {
            status: 'started',
            startedAt: serverTimestamp() as Timestamp, // Set start time on this update
        };
        await updateDoc(participantRef, updateData);
    } catch (error) {
        //console.error("Error marking participant start:", error);
        throw new Error("Failed to record exam start time.");
    }
};

// Updated completeParticipantAttempt
export const completeParticipantAttempt = async (sessionId: string, participantUserId: string, score: number, maxScore: number): Promise<void> => {
    try {
        const participantRef = doc(db, `groupExams/${sessionId}/participants`, participantUserId);
        // Ensure startedAt will exist based on rules/flow, otherwise fetch doc first to be safe
        const updateData: Partial<ParticipantData> = {
            status: 'completed',
            score: score,
            maxScore: maxScore,
            completionTimestamp: serverTimestamp() as Timestamp,
        };
        await updateDoc(participantRef, updateData);
    } catch (error) {
        //console.error("Error updating participant completion:", error);
        throw new Error("Failed to record participant completion.");
    }
};

/**
 * Fetches all participant records for a given group exam session.
 * Primarily used by the host or for leaderboards.
 * @param sessionId The ID of the group exam session.
 * @returns An array of ParticipantData objects, including their UIDs as 'id'.
 */
export const getGroupExamParticipants = async (sessionId: string): Promise<(ParticipantData & { id: string })[]> => {
    try {
        const participantsRef = collection(db, `groupExams/${sessionId}/participants`);
        const q = query(participantsRef, orderBy("joinedAt", "asc")); // Order by join time
        const querySnapshot = await getDocs(q);

        const participants: (ParticipantData & { id: string })[] = [];
        querySnapshot.forEach((docSnap) => {
            participants.push({
                id: docSnap.id, // Participant UID is the ID
                ...(docSnap.data() as ParticipantData)
            });
        });
        return participants;
    } catch (error) {
       //console.error("Error fetching group exam participants:", error);
        throw new Error("Failed to fetch participant list.");
    }
};
/**
 * Fetches only the status and potentially other minimal data for a specific participant in a session.
 * More efficient than fetching the full list if only status is needed.
 * @param sessionId The ID of the group exam session.
 * @param participantUserId The UID of the participant.
 * @returns The participant data (or minimal data like status), or null if not found.
 */
export const getParticipantStatus = async (sessionId: string, participantUserId: string): Promise<Partial<ParticipantData> | null> => {
    try {
        const participantRef = doc(db, `groupExams/${sessionId}/participants`, participantUserId);
        const docSnap = await getDoc(participantRef);

        if (docSnap.exists()) {
            // Return only needed fields or the whole doc
            return docSnap.data() as Partial<ParticipantData>;
        } else {
            //console.log(`Participant record not found for user ${participantUserId} in session ${sessionId}`);
            return null; // Participant hasn't joined or record deleted?
        }
    } catch (error) {
        //console.error(`Error fetching participant status for user ${participantUserId} in session ${sessionId}:`, error);
        // Decide how to handle - null means maybe they didn't join?
        // Throwing error might be better if expected to exist.
        // throw new Error("Failed to check participant status.");
        return null; // Return null for now, component can decide how to handle
    }
};
// Optional: Function to update session status (e.g., host manually closing)
// export const updateGroupExamStatus = async (sessionId: string, newStatus: GroupExamStatus): Promise<void> => {
//     const sessionRef = doc(db, 'groupExams', sessionId);
//     await updateDoc(sessionRef, { status: newStatus });
// };

/**
 * Fetches all group exam sessions created by a specific host.
 * @param hostUid The UID of the host user.
 * @returns An array of GroupExam objects (including their IDs) hosted by the user.
 */
export const getHostedGroupExams = async (hostUid: string): Promise<GroupExam[]> => {
    try {
        const groupExamsRef = collection(db, 'groupExams');
        // Create a query against the collection.
        const q = query(
            groupExamsRef,
            where("hostUid", "==", hostUid), // Filter by the hostUid field
            orderBy("createdAt", "desc") // Order by creation date, newest first
        );

        const querySnapshot = await getDocs(q);

        const hostedExams: GroupExam[] = [];
        querySnapshot.forEach((doc) => {
            hostedExams.push({
                id: doc.id,
                ...(doc.data() as Omit<GroupExam, 'id'>) // Cast data, id is added manually
            });
        });
        return hostedExams;
    } catch (error) {
        //console.error("Error fetching hosted group exams:", error);
        throw new Error("Failed to retrieve your hosted sessions.");
    }
};
/**
 * Gets the total number of currently active or pending group exam sessions hosted by a specific user.
 * Uses getCountFromServer for efficiency.
 * @param hostUid The Firebase Auth UID of the host user.
 * @returns Promise<number> The total count of non-closed sessions.
 */
export const getHostedSessionsCount = async (hostUid: string): Promise<number> => {
    try {
        const groupExamsRef = collection(db, 'groupExams');
        // Query for sessions hosted by the user that are NOT 'closed'
        const q = query(
            groupExamsRef,
            where("hostUid", "==", hostUid),
            //where("status", "!=", "closed") // Only count pending/active
        );
        const snapshot = await getCountFromServer(q);
        return snapshot.data().count;
    } catch (error) {
        //console.error("Error fetching hosted sessions count:", error);
        throw new Error("Failed to fetch hosted session count.");
    }
};

/**
 * Updates the status of a specific group exam session.
 * @param sessionId The ID of the group exam session to update.
 * @param newStatus The new status ('pending', 'active', 'closed', etc.).
 */
export const updateGroupExamStatus = async (sessionId: string, newStatus: GroupExamStatus): Promise<void> => {
    try {
        const sessionRef = doc(db, 'groupExams', sessionId);
        await updateDoc(sessionRef, {
            status: newStatus
            // Optionally update an 'updatedAt' timestamp if you add one to GroupExam
            // updatedAt: serverTimestamp()
        });
        //console.log(`Session ${sessionId} status updated to ${newStatus}`);
    } catch (error) {
        //console.error(`Error updating session ${sessionId} status to ${newStatus}:`, error);
        throw new Error(`Failed to update session status.`); // Rethrow for handling in component
    }
};

// --- Existing deleteGroupExamDocument (Keep as is for Host "Soft Delete") ---
/**
 * Deletes the main Group Exam document (configuration). Host action.
 * Does NOT delete the participants subcollection or individual user attempt histories.
 * @param sessionId The ID of the group exam session document to delete.
 */
export const deleteGroupExamDocument = async (sessionId: string): Promise<void> => {
    try {
        const sessionRef = doc(db, 'groupExams', sessionId);
        await deleteDoc(sessionRef);
        //console.log(`Group Exam document ${sessionId} deleted successfully.`);
    } catch (error) {
        //console.error(`Error deleting group exam document ${sessionId}:`, error);
        throw new Error(`Failed to delete session configuration.`);
    }
};

// --- NEW Service Functions ---

/**
 * Checks if a group exam session document exists.
 * @param sessionId The ID of the group exam session to check.
 * @returns True if the document exists, false otherwise.
 */
export const checkGroupExamExists = async (sessionId: string): Promise<boolean> => {
    try {
        const sessionRef = doc(db, 'groupExams', sessionId);
        const docSnap = await getDoc(sessionRef);
        return docSnap.exists();
    } catch (error) {
        //console.error(`Error checking existence of group exam ${sessionId}:`, error);
        // Decide how to handle check errors - returning false might block deletion?
        // Maybe rethrow and let the caller handle it.
        throw new Error("Could not verify the original group session status.");
    }
};

/**
 * Deletes a specific participant's record from within a group session's subcollection. Participant action (conditional).
 * @param sessionId The ID of the group exam session.
 * @param participantUserId The UID of the participant record to delete.
 */
export const deleteGroupParticipantRecord = async (sessionId: string, participantUserId: string): Promise<void> => {
    // Note: Rules prevent participants from calling this directly unless conditions met (implicitly handled by client logic check)
    try {
        const participantRef = doc(db, `groupExams/${sessionId}/participants`, participantUserId);
        // Check if doc exists before deleting? Optional, deleteDoc doesn't fail if not found.
        await deleteDoc(participantRef);
         //console.log(`Participant record ${participantUserId} deleted from session ${sessionId}.`);
    } catch (error) {
        //console.error(`Error deleting participant record ${participantUserId} from session ${sessionId}:`, error);
        throw new Error("Failed to delete associated group session record."); // Rethrow
    }
};
export const logAntiCheatEvent = async (
    sessionId: string,
    participantId: string,
    eventData: object // Should define a specific type for eventData later
): Promise<void> => {
    if (!sessionId || !participantId) {
       //console.warn("Cannot log anti-cheat event: Sefdssion ID or Participant ID missing.");
        return;
    }
    try {
        const eventsCollectionRef = collection(db, `groupExams/${sessionId}/participants/${participantId}/monitoringEvents`);
        await addDoc(eventsCollectionRef, {
            ...eventData,
            createdAt: serverTimestamp() // Use serverTimestamp for consistency
        });
    } catch (error) {
       //console.error(`[FirestoreService] Error logging anti-cheat event for session ${sessionId}, user ${participantId}:`, error);
        // Decide if this error should be re-thrown or handled silently
        // For now, log and continue, as failing to log an event shouldn't break the exam.
    }
};

export const getParticipantMonitoringEvents = async (
    sessionId: string,
    participantId: string
): Promise<MonitoringEvent[]> => {
    if (!sessionId || !participantId) return [];
    try {
        const eventsRef = collection(db, `groupExams/${sessionId}/participants/${participantId}/monitoringEvents`);
        const q = query(eventsRef, orderBy("createdAt", "asc")); // Or "desc" if you want newest first
        const querySnapshot = await getDocs(q);

        const events: MonitoringEvent[] = [];
        querySnapshot.forEach((docSnap) => {
            events.push({
                id: docSnap.id,
                ...(docSnap.data() as Omit<MonitoringEvent, 'id'>)
            });
        });
        return events;
    } catch (error) {
       //console.error(`Error fetching monitoring events for participant ${participantId} in session ${sessionId}:`, error);
        // Return empty array or throw, depending on how you want to handle UI
        return [];
    }
};
```

---

## styles


### styles\_base.scss

```scss
// src/styles/_base.scss
@import './variables';
@import './mixins'; // Import mixins if needed for base styles

// Basic Reset & Box Sizing
*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  // Potentially add border-color: inherit or border-style: solid here if using border utilities extensively
}

html {
  font-size: 100%; // Base font size (browser default, usually 16px)
  scroll-behavior: smooth;
  -webkit-text-size-adjust: 100%; // Prevent iOS text scaling
}

body {
  font-family: $font-family-base;
  font-size: $font-size-base;
  line-height: $line-height-base;
  color: $text-color;
  background-color: $body-bg;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-rendering: optimizeLegibility; // May improve font rendering slightly
  overflow-x: hidden; // Prevent accidental horizontal scrollbars on body
}

// Links
a {
  color: $link-color;
  text-decoration: none; // Remove underline by default for cleaner look
  transition: $transition-colors;

  &:hover {
    color: $link-hover-color;
    text-decoration: underline; // Add underline on hover for clarity
  }
  @include focus-outline($primary-color); // Add focus outline to links
}

// Headings
h1, h2, h3, h4, h5, h6 {
  margin-top: 0;
  margin-bottom: $spacer * 1; // Consistent bottom margin for headings
  font-weight: $font-weight-semibold; // Slightly bolder headings
  line-height: 1.3; // Tighter line height for headings
  color: $gray-800; // Use a darker gray for headings for emphasis
}

h1 { font-size: $h1-font-size; }
h2 { font-size: $h2-font-size; }
h3 { font-size: $h3-font-size; }
h4 { font-size: $h4-font-size; }
h5 { font-size: $h5-font-size; }
h6 { font-size: $h6-font-size; }

// Paragraphs
p {
  margin-top: 0;
  margin-bottom: $spacer; // Default paragraph spacing
}

// Images & SVGs
img, svg {
  vertical-align: middle;
  max-width: 100%; // Make images responsive by default
  height: auto;    // Maintain aspect ratio
}

// Form Elements
button,
input,
optgroup,
select,
textarea {
  font-family: inherit;
  font-size: inherit;
  line-height: inherit;
  color: inherit;
  margin: 0; // Reset margin for form elements
}

button {
  cursor: pointer;
  border-radius: $border-radius; // Default border radius for buttons
  border: 1px solid transparent; // Base border, color to be set by variants
  background-color: transparent; // Default buttons are transparent
  padding: map-get($spacers, 2) map-get($spacers, 3); // Default padding
  transition: $transition-base; // Base transition for all buttons

  &:focus {
    outline: none; // Rely on focus-visible mixin
  }
  @include focus-outline($primary-color); // Add focus outline to buttons
}

input:not([type="checkbox"]):not([type="radio"]),
select,
textarea {
  display: block;
  width: 100%;
  padding: map-get($spacers, 2) map-get($spacers, 3);
  background-color: $white-color;
  border: 1px solid $border-color;
  border-radius: $border-radius;
  transition: $transition-base;

  &:focus {
    border-color: $primary-color;
    outline: 0;
    box-shadow: 0 0 0 0.2rem rgba($primary-color, 0.25); // Consistent focus shadow
  }
  &::placeholder {
    color: $text-muted;
    opacity: 1;
  }
  &:disabled {
    background-color: $gray-100;
    opacity: 0.7;
    cursor: not-allowed;
  }
}

textarea {
  resize: vertical; // Allow vertical resize, not horizontal
}

// Lists
ul, ol {
  margin-top: 0;
  margin-bottom: $spacer;
  padding-left: $spacer * 1.5; // Default list indentation

  ul, ol { // Nested lists
    margin-bottom: 0;
  }
}

// Code
code {
  font-family: $font-family-monospace;
  font-size: 0.875em; // Slightly smaller for code
  color: $danger-color; // Example color, can be different
  word-wrap: break-word;
}

pre {
  display: block;
  padding: map-get($spacers, 3);
  margin: 0 0 $spacer;
  font-size: 0.875em;
  color: $gray-800;
  background-color: $gray-100;
  border: 1px solid $gray-200;
  border-radius: $border-radius-sm;
  overflow: auto; // Add scrollbars if content overflows

  code {
    font-size: inherit;
    color: inherit;
    word-wrap: normal; // Let pre handle wrapping/scrolling
    background-color: transparent; // Code inside pre shouldn't have its own bg
    border: 0;
    padding: 0;
  }
}

// Horizontal Rule
hr {
  margin: $spacer * 2 0;
  border: 0;
  border-top: 1px solid $gray-200;
}

// Container (as per existing _base.scss)
.container {
  width: 100%;
  padding-right: map-get($spacers, 3);
  padding-left: map-get($spacers, 3);
  margin-right: auto;
  margin-left: auto;

  @include media-breakpoint-up(sm) { max-width: 540px; }
  @include media-breakpoint-up(md) { max-width: 720px; }
  @include media-breakpoint-up(lg) { max-width: 960px; }
  @include media-breakpoint-up(xl) { max-width: 1140px; }
  @include media-breakpoint-up(xxl) { max-width: 1320px; }
}

// Custom Scrollbar (as per existing _base.scss, but using new variables)
// Optional: If you prefer native scrollbars, remove this section.
::-webkit-scrollbar {
  width: 10px; // Slightly wider for easier grabbing
  height: 10px;
}
::-webkit-scrollbar-track {
  background: $gray-100; // Lighter track
  border-radius: $border-radius-pill;
}
::-webkit-scrollbar-thumb {
  background-color: $gray-400; // More contrast for thumb
  border-radius: $border-radius-pill;
  border: 2px solid $gray-100; // Creates padding around thumb
  &:hover {
     background-color: $gray-500; // Darker on hover
  }
}

// For Firefox scrollbars (basic color, less customization than WebKit)
// html {
//   scrollbar-color: $gray-400 $gray-100;
//   scrollbar-width: thin;
// }
```

---

### styles\_mixins.scss

```scss
// src/styles/_mixins.scss
@import './variables';

// --- Media Queries ---
@mixin media-breakpoint-up($name, $breakpoints: $grid-breakpoints) {
  $min: map-get($breakpoints, $name);
  @if $min != 0 {
    @media (min-width: $min) {
      @content;
    }
  } @else {
    @content; // No media query needed for xs
  }
}

// --- Flexbox ---
@mixin flex-center($direction: row, $justify: center, $align: center) {
  display: flex;
  flex-direction: $direction;
  justify-content: $justify;
  align-items: $align;
}

// --- Truncate Text ---
@mixin truncate-text {
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
}

// --- Focus Outline (More robust) ---
@mixin focus-outline($color: $primary-color, $offset: 2px, $width: 2px, $style: solid, $alpha: 0.45) {
  // Use focus-visible for keyboard users, provides a clear outline
  &:focus-visible {
    outline: $width $style rgba($color, $alpha);
    outline-offset: $offset;
    // Optional: If you want a specific border radius to match, uncomment
    // border-radius: inherit; // Or specify the radius if known
  }
  // Remove default outline for mouse focus if :focus-visible is supported
  &:focus:not(:focus-visible) {
    outline: none;
  }

}

// --- Modern Button Variant Mixin ---
@mixin button-variant(
  $bg-color,
  $border-color: $bg-color,         // Border defaults to bg color for solid buttons
  $text-color: $white-color,
  $hover-bg-color: darken($bg-color, 8%),
  $hover-border-color: darken($border-color, 10%),
  $hover-text-color: $text-color,   // Text color on hover defaults to original
  $active-bg-color: darken($bg-color, 12%),
  $active-border-color: darken($border-color, 15%),
  $disabled-opacity: 0.65,
  $is-outline: false                // New parameter for outline style
) {
  // Base styles applied to all buttons using this mixin
  display: inline-flex;           // For icon alignment and proper padding
  align-items: center;
  justify-content: center;
  padding: map-get($spacers, 2) map-get($spacers, 3); // Default padding
  font-weight: $font-weight-medium;
  text-align: center;
  vertical-align: middle;
  cursor: pointer;
  user-select: none;              // Prevent text selection on click
  border: $border-width solid $border-color;
  border-radius: $border-radius;  // Use variable for consistency
  transition: $transition-colors, transform 0.1s ease-out, box-shadow $transition-fast;
  line-height: $line-height-base; // Ensure consistent line height

  // --- Solid Button Styles ---
  @if not $is-outline {
    background-color: $bg-color;
    color: $text-color;

    &:hover:not(:disabled) {
      background-color: $hover-bg-color;
      border-color: $hover-border-color;
      color: $hover-text-color;
      // Optional: subtle lift effect
      // transform: translateY(-1px);
      // box-shadow: $box-shadow-sm;
    }

    &:active:not(:disabled) {
      background-color: $active-bg-color;
      border-color: $active-border-color;
      transform: scale(0.98); // Click feedback
    }
  }
  // --- Outline Button Styles ---
  @else {
    background-color: transparent;
    color: $border-color; // Outline text color is the border color
    border-color: $border-color; // Use $border-color for initial outline

    &:hover:not(:disabled) {
      background-color: $border-color; // Fill with border color on hover
      color: $white-color;            // Text becomes white (or a contrasting color)
      border-color: $border-color;    // Border remains same (or darkens if bg doesn't change)
      // Optional:
      // transform: translateY(-1px);
      // box-shadow: $box-shadow-sm;
    }

    &:active:not(:disabled) {
      background-color: darken($border-color, 5%);
      border-color: darken($border-color, 5%);
      transform: scale(0.98);
      color: $white-color;
    }
  }

  // --- Focus State (applies to both solid and outline) ---
  // The @include focus-outline will handle the :focus-visible state.
  // We pass $border-color to it so the focus ring uses the button's primary color.
  @include focus-outline($border-color);

  // --- Disabled State (applies to both solid and outline) ---
  &:disabled,
  &.disabled {
    opacity: $disabled-opacity;
    cursor: not-allowed;
    // Ensure no transformations or shadows on disabled state
    transform: none;
    box-shadow: none;
    // Optional: if you want a grayscale effect for disabled outline buttons
    // @if $is-outline {
    //   filter: grayscale(50%);
    // }
  }
}

// --- Text Button Variant (Ghost/Link-like) ---
@mixin button-text-variant(
  $text-color: $primary-color, // Defaults to primary color
  $hover-bg-color: rgba($text-color, 0.08), // Very subtle background on hover
  $hover-text-color: darken($text-color, 10%),
  $active-bg-color: rgba($text-color, 0.12)
) {
  @include button-variant(
    transparent,                    // bg-color
    transparent,                    // border-color
    $text-color,                    // text-color
    $hover-bg-color,                // hover-bg-color
    transparent,                    // hover-border-color
    $hover-text-color,              // hover-text-color
    $active-bg-color,               // active-bg-color
    transparent,                    // active-border-color
    0.65,                           // disabled-opacity
    false                           // is-outline (false, but irrelevant due to transparent bg/border)
  );
  // Override padding for text buttons to be tighter if needed
  // padding: map-get($spacers, 1) map-get($spacers, 2);
  box-shadow: none !important; // Text buttons usually don't have shadows

  &:hover:not(:disabled) {
    box-shadow: none; // Ensure no shadow on hover for text buttons
  }
}
```

---

### styles\_palette-common.scss

```scss
// src/styles/_palette-common.scss (NEW FILE - or merge into _mixins.scss if small)
@import './variables';
@import './mixins';

// Common styles for both Navigation and Review Palettes
%paletteWrapperBase { // Using placeholder selector for extend
  display: flex;
  flex-direction: column;
  height: 100%; // Fill container (e.g., .paletteArea)
  // Padding handled by parent .paletteArea
}

%paletteTitleBase {
  text-align: center;
  font-size: $font-size-base * 1.05; // Slightly smaller than previous
  font-weight: $font-weight-semibold; // Bolder title
  margin-bottom: map-get($spacers, 3); // mb-3
  color: $gray-700; // Darker title
  flex-shrink: 0;
  padding-bottom: map-get($spacers, 2);
  border-bottom: 1px solid $gray-200; // Subtle separator below title
}

%legendBase {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(110px, 1fr)); // Responsive columns
  gap: map-get($spacers, 1) map-get($spacers, 2); // row-gap col-gap
  margin-bottom: map-get($spacers, 3);
  padding: map-get($spacers, 2); // p-2
  background-color: $gray-50;   // Very light background for legend
  border: 1px solid $gray-200;
  border-radius: $border-radius; // Standard radius
  font-size: $font-size-base * 0.8; // Smaller legend text
  flex-shrink: 0;
  color: $gray-600; // Default text color for legend items
}

%legendItemBase {
  display: flex;
  align-items: center;
  gap: map-get($spacers, 2); // gap-2 (8px)
}

%legendColorBoxBase {
  display: inline-block;
  width: 15px; // Slightly smaller
  height: 15px;
  border-radius: $border-radius-sm; // Slightly rounded square
  border: 1px solid rgba($black-color, 0.15); // Darker, more defined border
  flex-shrink: 0;
}

%paletteGridBase {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(40px, 1fr)); // Slightly smaller min button size
  gap: map-get($spacers, 2); // gap-2 (8px)
  overflow-y: auto;
  flex-grow: 1;
  padding: map-get($spacers, 1) 2px; // Small padding, and 2px for scrollbar clearance
}

%paletteButtonBase {
  display: flex;
  justify-content: center;
  align-items: center;
  aspect-ratio: 1 / 1;
  border: 1px solid $gray-300; // Default border
  border-radius: $border-radius-sm; // Slightly rounded square
  font-weight: $font-weight-semibold; // Bolder numbers
  font-size: $font-size-base * 0.9;
  cursor: pointer;
  transition: background-color $transition-fast, border-color $transition-fast, transform $transition-fast, box-shadow $transition-fast, color $transition-fast;
  background-color: $white-color; // Default background
  color: $gray-700; // Default text color

  &:hover:not(:disabled):not(.current) { // Don't apply hover if current or disabled
    transform: scale(1.08); // Slightly more noticeable hover
    border-color: $primary-color;
    // background-color: lighten($primary-color, 58%); // Optional: light primary tint on hover
    z-index: 1;
    box-shadow: $box-shadow-sm;
  }
  @include focus-outline($primary-color);

  &.disabled { // When exam is not active for NavigationPalette
    cursor: not-allowed;
    opacity: 0.6;
    filter: grayscale(50%);
    background-color: $gray-100;
    border-color: $gray-200;
    color: $gray-400;
  }
}
```

---

### styles\_utilities.scss

```scss
// src/styles/_utilities.scss
@import './variables';
@import './mixins';

// Margin & Padding helpers (using the $spacers map)
@each $prop, $abbrev in (margin: m, padding: p) {
  @each $size, $length in $spacers {
    .#{$abbrev}-#{$size} { #{$prop}: $length !important; } // All sides
    .#{$abbrev}t-#{$size} { #{$prop}-top: $length !important; }
    .#{$abbrev}r-#{$size} { #{$prop}-right: $length !important; }
    .#{$abbrev}b-#{$size} { #{$prop}-bottom: $length !important; }
    .#{$abbrev}l-#{$size} { #{$prop}-left: $length !important; }
    .#{$abbrev}x-#{$size} { // Horizontal
      #{$prop}-right: $length !important;
      #{$prop}-left: $length !important;
    }
    .#{$abbrev}y-#{$size} { // Vertical
      #{$prop}-top: $length !important;
      #{$prop}-bottom: $length !important;
    }
  }
}

// Text Alignment
.text-left { text-align: left !important; }
.text-center { text-align: center !important; }
.text-right { text-align: right !important; }

// Display
.d-block { display: block !important; }
.d-flex { display: flex !important; }
.d-inline-block { display: inline-block !important; }
.d-none { display: none !important; }

// Add more utilities as needed (e.g., flex grow, shrink, wrap, justify, align, etc.)
```

---

### styles\_variables.scss

```scss
// src/styles/_variables.scss

// --- Font ---
$font-family-sans-serif: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, 'Noto Sans', sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol', 'Noto Color Emoji';
$font-family-monospace: SFMono-Regular, Menlo, Monaco, Consolas, 'Liberation Mono', 'Courier New', monospace;
$font-family-base: $font-family-sans-serif;

// --- Colors ---
// Inspired by Tailwind CSS default palette for a modern feel
$blue-500: #3B82F6;   // New Primary
$gray-50:  #F9FAFB;   // Lightest Gray (Body BG)
$gray-100: #F3F4F6;   // Light Gray (Component Alt BG)
$gray-200: #E5E7EB;   // Light Gray (Borders Light)
$gray-300: #D1D5DB;   // Gray (Borders)
$gray-400: #9CA3AF;   // Mid Gray (Muted Text)
$gray-500: #6B7280;   // Darker Gray (Secondary Text / Icons)
$gray-600: #646a79;
$gray-700: #374151;   // Dark Gray (Text)
$gray-800: #1F2937;   // Darkest Gray (Headings)
$gray-900: #11182C;   // Near Black

$green-500: #10B981;  // Success
$red-500:   #EF4444;  // Danger
$amber-500: #F59E0B;  // Warning (was yellow, amber often works better)
$sky-500:   #0EA5E9;  // Info (lighter blue)

$primary-color: $blue-500;
$secondary-color: $gray-500;
$success-color: $green-500;
$danger-color: $red-500;
$warning-color: $amber-500;
$info-color: $sky-500;
$light-color: $gray-100;  // Was #f8f9fa, now a slightly different shade
$dark-color: $gray-800;   // Was #343a40
$white-color: #ffffff;
$black-color: #000000;

// Text Colors
$text-color: $gray-700;
$text-muted: $gray-400;
$link-color: $primary-color;
$link-hover-color: darken($primary-color, 10%);
$text-color-subtle: $gray-400; // Replaced lighten with a specific shade

// Backgrounds
$body-bg: $gray-50; // Changed from $light-color to a dedicated very light gray
$component-bg: $white-color;
$border-color: $gray-300; // Was #dee2e6
$background-color-hover: $gray-100; // More distinct hover

// Buttons (example, will be further refined in mixins)
$button-primary-bg: $primary-color;
$button-primary-text: $white-color;

// Shadows (subtle and modern)
$box-shadow-sm: 0 1px 2px 0 rgba($black-color, 0.05);
$box-shadow-md: 0 4px 6px -1px rgba($black-color, 0.1), 0 2px 4px -1px rgba($black-color, 0.06);
$box-shadow-lg: 0 10px 15px -3px rgba($black-color, 0.1), 0 4px 6px -2px rgba($black-color, 0.05);
$box-shadow-xl: 0 20px 25px -5px rgba($black-color, 0.1), 0 10px 10px -5px rgba($black-color, 0.04);
$box-shadow-inset: inset 0 2px 4px 0 rgba($black-color, 0.05);

// --- Typography ---
$font-size-base: 1rem; // 16px
$line-height-base: 1.6; // Increased for better readability

// Updated typographic scale (example)
$h1-font-size: $font-size-base * 2.25;  // 36px
$h2-font-size: $font-size-base * 1.875; // 30px
$h3-font-size: $font-size-base * 1.5;    // 24px
$h4-font-size: $font-size-base * 1.25;   // 20px
$h5-font-size: $font-size-base * 1.125;  // 18px
$h6-font-size: $font-size-base;          // 16px

$font-weight-light: 300;
$font-weight-normal: 400;
$font-weight-medium: 500; // Useful for UI elements
$font-weight-semibold: 600; // Added for emphasis
$font-weight-bold: 700;

// --- Spacing ---
$spacer: 1rem;
$spacers: (
  0: 0,
  1: $spacer * .25,  // 4px
  2: $spacer * .5,   // 8px
  3: $spacer,        // 16px
  4: $spacer * 1.5,  // 24px
  5: $spacer * 2,    // 32px (Adjusted from 3rem for finer control)
  6: $spacer * 2.5,  // 40px
  7: $spacer * 3,    // 48px
  8: $spacer * 4     // 64px
);

// --- Borders ---
$border-width: 1px;
$border-radius-sm: 0.25rem;  // 4px
$border-radius: 0.375rem; // 6px (Softer default)
$border-radius-lg: 0.5rem;   // 8px
$border-radius-xl: 0.75rem;  // 12px
$border-radius-pill: 50rem;

// --- Breakpoints ---
// (Keep existing, they are standard)
$grid-breakpoints: (
  xs: 0,
  sm: 576px,
  md: 768px,
  lg: 992px,
  xl: 1200px,
  xxl: 1400px
);

// --- Transitions ---
$transition-base: all .2s ease-in-out;
$transition-fast: all 0.15s ease-out;
$transition-medium: all 0.25s ease-in-out;
$transition-colors: background-color .15s ease-in-out, border-color .15s ease-in-out, color .15s ease-in-out, fill .15s ease-in-out, stroke .15s ease-in-out;

// --- Z-index ---
// (Keep existing, they are standard)
$zindex-dropdown: 1000;
$zindex-sticky: 1020;
$zindex-fixed: 1030;
$zindex-modal-backdrop: 1040;
$zindex-modal: 1050;
$zindex-popover: 1060;
$zindex-tooltip: 1070;
```

---

## types


### types\index.tsx

```typescript
// src/types/index.ts

import { Timestamp } from 'firebase/firestore';
// --- AuthContext related types (you provided these, but good to have them referenced) ---
import { User as FirebaseUser } from 'firebase/auth'; 

export const CONFIG_URL = 'https://raw.githubusercontent.com/Samkarya/online-exam-questions/refs/heads/main/config.json';
export const ATTEMPT_LIMIT = 10;
export const HOSTED_SESSION_LIMIT = 1;
// --- Question Data Structure (from JSON) ---
export interface QuestionOption {
  [key: string]: string; // e.g., "a": "Option A", "b": "Option B"
}

export interface Question {
  question_number: number;
  subject?: string; // Optional field
  topic?: string; // Optional field
  question_text: string;
  options: QuestionOption;
  correct_answer: string; // Key corresponding to the correct option in 'options' (e.g., "a")
  explanation?: string; // Optional, for future use
  difficulty?: 'Easy' | 'Medium' | 'Hard' | null; // Optional, for future use
  section_id?: string | null; // Optional, for exams with sections
}

// --- Exam Configuration/Settings ---
export interface ExamSettings {
  timeLimitMinutes: number | null; // null for self-paced
  negativeMarkingEnabled: boolean;
  marksPerCorrect: number;
  negativeMarksPerIncorrect: number;
  trackQuestionTime: boolean;
  // sectionTimers?: Record<string, number>; // Optional: Section-specific time limits (future enhancement)
}

// --- During Exam State ---
export type QuestionStatus = 'answered' | 'notAnswered' | 'markedForReview' | 'notVisited';

export interface UserAnswer {
  [questionNumber: number]: {
    selectedOption: string | null; // e.g., "a", "b", or null if cleared/skipped
    status: QuestionStatus;
    timeSpentSeconds: number;
    // CONSIDERATION for Phase 2:
    // subject?: string | null;
    // topic?: string | null;
    // difficulty?: 'Easy' | 'Medium' | 'Hard' | null;
    // section_id?: string | null;
  };
}

// --- Post-Exam Result Structure (What we store in Firestore) ---
export interface AttemptResult {
  id: string;
  userId: string; // ID of the user who took the attempt
  examIdentifier: string; // Unique ID for the question set (e.g., "nimcet_2023", "user_upload_...")
  examTitle: string; // User-friendly title
  isUserUploaded: boolean;
  attemptTimestamp?: Timestamp | Date; // Firestore timestamp
  score: number;
  maxScore: number;
  correctCount: number;
  incorrectCount: number;
  unattemptedCount: number;
  totalQuestions: number;
  timeTakenSeconds: number;
  settingsUsed: ExamSettings; // Store the settings for this attempt
  userAnswers: UserAnswer;
  examPath: string | null;
  sectionBreakdown?: Record<string, SectionResult>; // Optional: section-wise results
  groupSessionId?: string; //Id of group session if the atttempt was the part of one 
  questionJsonString?: string;
}

export interface SectionResult {
  score: number;
  correct: number;
  incorrect: number;
  unattempted: number;
  timeSeconds: number;
}
// Structure for a service linked to a user
export interface UserService {
  id: string;         // e.g., 'blog', 'exam-simulator'
  name: string;       // e.g., 'Google Blogger', 'Exam Simulator'
  description: string;
  url: string;        // External URL or internal path
  icon: string;       // Identifier for the icon (e.g., 'blog', 'exam') or path
}

export type PaidTierId = 'basic' | 'pro' | 'elite'; 

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
export interface TierPricingOption {
  billingCycle: 'monthly' | 'yearly';
  priceINR: number;
  durationMonths: number; // 1 for monthly, 12 for yearly
  // Optional fields for display:
  displaySuffix?: string; // e.g., "/mo" or "/yr"
  savingsText?: string; // e.g., "Save 20%"
}
export interface TierLimitConfig { // Define limits structure clearly
  examAttempts: number | null;
  hostedSessions: number | null;
  //maxParticipantsPerSession: number | null;
}

export interface AuthContextType {
    currentUser: FirebaseUser | null;
    userData: UserData | null;
    isLoading: boolean;
    login: (email: string, password: string) => Promise<void>;
    logout: () => Promise<void>;
}
//--- NEW Blog Post Type ---
export interface BlogPostMeta {
  slug: string;           // Unique identifier derived from filename (e.g., "what-is-examify")
  title: string;          // Main title of the post
  date: string;           // Publication date (e.g., "2023-10-27")
  author?: string;        // Optional author name
  excerpt: string;        // Short summary/preview text
  tags?: string[];        // Optional tags/categories
  mdFilePath: string;     // Relative path to the markdown file from project root
}

export interface BlogPost extends BlogPostMeta {
    content: string; // The full markdown content (loaded dynamically)
}

export interface ExamConfig {
  id: string;
  category: string;
  year: number;
  session?: string | number | null; // Session can be string or number
  date?: string | null;             // Date is typically a string
  shift?: string | number | null;   // Shift can be string or number
  paperType?: string | null;        // Subject or specific paper name
  title: string;                    // Overall title for the config entry
  description: string;              // Description (might be less used now)
  path: string;                     // Path to the JSON file
}

// --- NEW: Group Exam Types ---

export type GroupExamStatus = 'pending' | 'active' | 'closed'; // Add more as needed (e.g., 'finished_calculating')
export type ExamSourceType = 'custom_json' | 'official';
export type ResultVisibility =
    | 'Self Only Immediate'         // Participants see own results right after submit
    | 'Self Only After End Time'    // Participants see own results only after session endTime
    | 'Leaderboard After End Time'  // Participants see leaderboard (Rank, Name, Score) after endTime
    | 'Full Review After End Time'; // Participants see own results + can review answers after endTime


export interface GroupExam {
    id: string;                 // Firestore document ID
    hostUid: string;            // UID of the user who created the session
    sessionName: string;        // User-defined name for the session
    timeLimitMinutes: number | null; // Duration of the exam for each participant
    createdAt: Timestamp;       // When the session was created
    status: GroupExamStatus;    // Current status of the session
    examSourceType: ExamSourceType; // Where the questions come from

    // Source details (conditional based on examSourceType)
    questionJsonString?: string; // Stored for custom_json type
    examSourceId?: string;      // The 'id' from ExamConfig for official type
    examSourcePath?: string;    // The 'path' from ExamConfig for official type
    monitoringEnabled?: boolean;
    startTime?: Timestamp |Date | null;
    endTime?: Timestamp | Date | null;
    resultVisibility?: ResultVisibility;
    marksPerCorrect?: number;           // Points for correct answer
    negativeMarkingEnabled?: boolean;   // Is negative marking active?
    negativeMarksPerIncorrect?: number; // Points to deduct (positive value)
    geoRestriction?: { // NEW
      latitude: number;
      longitude: number;
      radiusMeters: number;
  } | null;
    // passwordHash?: string;
}

export interface MonitoringEvent {
  id: string; // Firestore document ID of the event
  type: string;
  createdAt: Timestamp;
  // Add other potential fields based on your event types
  reason?: string;
  durationMs?: number;
  keyDetail?: string;
  path?: string;
  from?: string;
  to?: string;
}

export interface Participant {
    // The participant's UID is the document ID in the subcollection
    status: 'joined' | 'started' | 'completed'; 
    joinedAt: Timestamp;        // When the participant joined
    startedAt?: Timestamp | null; //When they actually started the exam
    score?: number;             // Added upon completion
    maxScore?: number;          // Added upon completion (from attempt)
    completionTimestamp?: Timestamp; // When the participant submitted
    displayName?: string;       // Optional: Denormalize for easier display on leaderboard/host view
    // other performance metrics could be added later (time taken, correct %, etc.)
}

// Type for the data stored in the Participant subcollection
export interface ParticipantData extends Participant {
    // Include other fields if you denormalize them
}
```

---

## utils


### utils\formatters.ts

```typescript
// src/utils/formatters.ts

/**
 * Formats a duration given in total seconds into a human-readable string (e.g., "1h 5m 30s", "45s").
 * @param totalSeconds The total duration in seconds.
 * @returns A formatted string representation of the duration, or 'N/A' if input is invalid.
 */
export const formatDuration = (totalSeconds: number | undefined | null): string => {
    if (totalSeconds === undefined || totalSeconds === null || totalSeconds < 0) return 'N/A';

    if (totalSeconds === 0) return '0s';

    const hours = Math.floor(totalSeconds / 3600);
    const minutes = Math.floor((totalSeconds % 3600) / 60);
    const seconds = totalSeconds % 60;

    let result = '';
    if (hours > 0) result += `${hours}h `;
    if (minutes > 0) result += `${minutes}m `; // Always show minutes if > 0
    if (seconds > 0 || result === '') result += `${seconds}s`; // Show seconds if > 0 or if hours/mins were 0

    return result.trim();
};

/**
 * Formats a Firestore Timestamp or JavaScript Date into a readable string.
 * @param timestamp The Date or Timestamp object.
 * @returns A formatted date/time string (e.g., "Aug 23, 2023, 10:30 AM") or 'N/A'.
 */
export const formatTimestamp = (timestamp: Date | undefined | null): string => {
    if (!timestamp) return 'N/A';

    // Basic check if it might be a Firestore Timestamp-like object before conversion
    const dateToFormat = timestamp instanceof Date
        ? timestamp
        : (timestamp as any)?.toDate instanceof Function
          ? (timestamp as any).toDate()
          : undefined;

    if (!dateToFormat) return 'N/A';

    try {
        return dateToFormat.toLocaleString('en-US', {
            year: 'numeric',
            month: 'short',
            day: 'numeric',
            hour: 'numeric',
            minute: '2-digit',
            hour12: true,
        });
    } catch (e) {
        //console.error("Error formatting timestamp:", e);
        return 'Invalid Date';
    }
};
```

---
