<!-- src/App.vue -->
<template>
  <div class="privacy-policy-page">
    <h1>Privacy Policy</h1>
    <p><strong>Last updated: February 2025</strong></p>

    <section>
      <h2>1. Introduction</h2>
      <p>
        This Privacy Policy describes how we collect, use, and protect your information when you use
        our
        <strong>Weather App</strong> (the “Extension”), which provides weather updates and includes
        certain “HelpMeOut” features. By installing or using the Extension, you agree to the
        collection and use of information in accordance with this policy.
      </p>
    </section>

    <section>
      <h2>2. Information We Collect</h2>
      <ul>
        <li>
          <strong>Geolocation Data:</strong> If you allow location access, we may collect your
          device’s geographic location to deliver accurate, real-time weather updates. You can
          disable location permissions anytime through your browser or device settings.
        </li>
        <li>
          <strong>Usage Data:</strong> We collect information about your interaction with the
          Extension, such as features accessed or general usage statistics. This data helps us
          troubleshoot issues and improve performance.
        </li>
        <li>
          <strong>Browser-Related Information:</strong> We may gather minimal browser details (e.g.,
          extension settings, anonymized analytics) necessary to personalize or optimize your
          Extension experience. We <strong>do not</strong> collect or store your full browsing
          history unless explicitly stated and permitted by you.
        </li>
        <li>
          <strong>Account Information (Firebase):</strong> If you sign up or log in within the
          Extension (e.g., for “HelpMeOut” functionality), we use <strong>Firebase</strong> to
          authenticate your account. Firebase stores your email address, hashed password, or other
          necessary credentials.
        </li>
      </ul>
    </section>

    <section>
      <h2>3. Use of Third-Party Services</h2>
      <ul>
        <li>
          <strong>OpenWeather API:</strong> We use the <strong>OpenWeather API</strong> to fetch
          local and forecasted weather data. When you request weather information, your approximate
          or exact location may be transmitted to OpenWeather to provide precise forecasts.
        </li>
        <li>
          <strong>Firebase:</strong>
          <ul>
            <li>
              <em>Authentication &amp; Storage:</em> We rely on <strong>Firebase</strong> to
              register and authenticate your account, store extension data (e.g., user preferences,
              documents), and maintain core “HelpMeOut” features.
            </li>
            <li>
              Firebase implements security measures (token-based authentication, security rules) to
              help protect user data.
            </li>
          </ul>
        </li>
      </ul>
    </section>

    <section>
      <h2>4. How We Use Your Information</h2>
      <ul>
        <li>
          <strong>Weather Updates:</strong> We use your location data to display accurate weather
          forecasts via the Extension.
        </li>
        <li>
          <strong>Extension Features (“HelpMeOut”):</strong> Usage data and (if applicable) your
          account details are used to provide or customize the “HelpMeOut” tools, which may store
          certain data in Firebase.
        </li>
        <li>
          <strong>Improving the Extension:</strong> We analyze aggregated usage data to identify
          errors, develop new features, and enhance user experience.
        </li>
        <li>
          <strong>Notifications &amp; Alerts:</strong> If enabled, we may send alerts about
          significant weather conditions or important Extension updates.
        </li>
      </ul>
    </section>

    <section>
      <h2>5. Data Sharing &amp; Disclosure</h2>
      <p>
        We <strong>do not</strong> sell, trade, or otherwise share your personal data to any third
        party for marketing or other commercial purposes. We only disclose your information in the
        following limited scenarios:
      </p>
      <ul>
        <li>
          <strong>Essential Service Providers:</strong> We work with
          <strong>OpenWeather</strong> (for weather data) and <strong>Firebase</strong>
          (for authentication, data storage, and backend support). These providers act on our behalf
          and are contractually obligated to use your data only for service delivery.
        </li>
        <li>
          <strong>Legal Obligations:</strong> We may disclose information if required by law (e.g.,
          subpoena, court order) or if we believe it is necessary to protect our legal rights.
        </li>
      </ul>
    </section>

    <section>
      <h2>6. Data Security</h2>
      <p>
        We employ reasonable measures—such as <strong>Firebase security rules</strong>, encryption
        at rest, and secure communication—to protect your personal data against unauthorized access
        or disclosure. However, no method of data transmission or storage can guarantee 100%
        security.
      </p>
    </section>

    <section>
      <h2>7. Your Rights</h2>
      <ul>
        <li>
          <strong>Access &amp; Update:</strong> You may request access to, or correction of, any
          personal data we hold about you. If you use an account (e.g., for “HelpMeOut”), you can
          often update information in the Extension settings or your Firebase profile.
        </li>
        <li>
          <strong>Delete &amp; Withdraw Consent:</strong> You can disable location services at any
          time through browser or device settings. You may uninstall the Extension to stop all data
          collection. You can request deletion of data where technically feasible (e.g., removing
          user-generated content from Firebase).
        </li>
      </ul>
      <p>To exercise your rights, please contact us at the email below.</p>
    </section>

    <section>
      <h2>8. Changes to This Privacy Policy</h2>
      <p>
        We may update this Privacy Policy as needed. The “Last Updated” date at the top will be
        revised accordingly. By continuing to use the Extension after changes become effective, you
        agree to the updated Policy.
      </p>
    </section>

    <section>
      <h2>9. Contact Us</h2>
      <p>For questions, concerns, or to exercise your privacy rights, please reach out:</p>
      <p>
        <strong>Email:</strong>
        <a href="mailto:abdulmuiz.olatunbosun@gmail.com">abdulmuiz.olatunbosun@gmail.com</a>
      </p>
      <!-- <p><strong>Entity Name:</strong> Hyper Icon</p> -->
      <p>We value your privacy and will address inquiries as promptly as possible.</p>
    </section>
  </div>
</template>

<script setup>
// No JavaScript logic is needed for a static privacy policy page.
</script>

<style scoped>
.privacy-policy-page {
  max-width: 800px;
  margin: 40px auto;
  padding: 0 20px;
  line-height: 1.6;
  font-family: Arial, sans-serif;
}

h1 {
  margin-bottom: 8px;
  font-size: 2rem;
}

h2 {
  margin-top: 24px;
  font-size: 1.2rem;
  color: #333;
}

ul {
  list-style: disc;
  margin-left: 2rem;
}

.privacy-policy-page p,
.privacy-policy-page li {
  margin-bottom: 12px;
}

strong {
  font-weight: 600;
}

a {
  color: #007bff;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}
</style>
