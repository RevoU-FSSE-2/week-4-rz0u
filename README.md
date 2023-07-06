Certainly! Here's a markdown guide on how to deploy a website with Netlify, starting from signing up for Netlify and ending with buying a domain from Niagahoster:

## Deploying a Website with Netlify and Buying a Domain from Niagahoster

### Step 1: Sign up for Netlify

Follow the instructions in the previous documentation to sign up for Netlify. If you haven't signed up yet, please refer to the documentation on how to sign up for Netlify.

### Step 2: Create a New Site

1. After signing in to Netlify, click on the "New site from Git" button on the Netlify dashboard.
2. Choose your preferred Git platform (GitHub, GitLab, or Bitbucket) or select "Continuous Deployment" if you prefer another Git provider or a local repository.
3. Authenticate and authorize Netlify to access your Git repository.
4. Select the repository that contains the website you want to deploy.
5. Configure the basic settings for your site, such as the branch to deploy, build command, and publish directory.
6. Click on the "Deploy site" button to initiate the deployment process.

### Step 3: Configure Custom Domain

1. Once your site is deployed, navigate to the Netlify dashboard.
2. Select your site from the list of deployed sites.
3. In the site settings, click on "Domain settings" or "Settings" followed by "Domain management."
4. Click on "Add custom domain" to configure a custom domain for your website.
5. Enter the desired domain name you want to use (e.g., `www.example.com`) and click on "Verify."
6. Netlify will provide you with DNS configuration instructions. Keep this information handy as you'll need it in the next step.

### Step 4: Buy a Domain from Niagahoster

1. Visit the Niagahoster website at [https://www.niagahoster.co.id/](https://www.niagahoster.co.id/).
2. Use the domain search feature on the Niagahoster homepage to check the availability of your desired domain name.
3. Once you find an available domain, select it and proceed to the domain registration page.
4. Follow the steps to complete the domain registration process, providing the necessary details such as your personal information and contact details.
5. During the checkout process, select the desired domain registration period and any additional services you may need.
6. Proceed to make the payment to finalize the domain purchase.

### Step 5: Configure DNS Settings in Niagahoster

1. After completing the domain purchase, log in to your Niagahoster account.
2. Locate the domain management section and access the DNS management settings.
3. Follow the instructions provided by Netlify (from Step 3) to configure the DNS settings for your custom domain.
4. Typically, you'll need to add a CNAME or ANAME record pointing to the Netlify domain (e.g., `example.netlify.app`) and possibly configure other DNS records like MX, TXT, or SPF if needed.
5. Save the changes to update the DNS configuration.

### Step 6: Wait for DNS Propagation

After updating the DNS settings, it may take some time for the changes to propagate across the internet. DNS propagation can vary and may take up to 24-48 hours, although it often happens much faster.

### Step 7: Verify Custom Domain in Netlify

1. Once DNS propagation is complete, go back to the Netlify dashboard and navigate to your site's domain settings.
2. Click on "Verify DNS configuration" or similar options to check if the DNS configuration is successfully set up.
3. Netlify will verify the domain configuration