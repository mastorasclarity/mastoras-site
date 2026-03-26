# Google Search Console Setup Guide

## Why Google Search Console?

Google Search Console (GSC) is essential for monitoring your website's presence in Google Search results. It provides:

- **Indexing Status** - See which pages are indexed
- **Search Performance** - Impressions, clicks, CTR, positions
- **Crawl Errors** - Identify and fix crawling issues
- **Mobile Usability** - Mobile-friendliness reports
- **Rich Results** - Structured data validation
- **AI Search Insights** - How AI features display your content

## Step-by-Step Setup

### 1. Create Google Search Console Account
1. Go to [search.google.com/search-console](https://search.google.com/search-console)
2. Sign in with your Google account
3. Click "Add Property"

### 2. Add Your Property
Choose "URL prefix" method:
- **URL:** `https://mastoras.netlify.app`
- Click "Continue"

### 3. Verify Ownership
Select "HTML tag" verification method:
1. Copy the meta tag provided
2. Add it to your `index.html` head section
3. Click "Verify"

### 4. Submit Sitemap
1. Go to "Sitemaps" in the left sidebar
2. Enter: `sitemap.xml`
3. Click "Submit"

### 5. Request Indexing
1. Go to "URL inspection" tool
2. Enter your homepage URL
3. Click "Request indexing"

## Essential Monitoring Tasks

### Daily Checks
- Review crawl errors
- Check indexing status
- Monitor search performance

### Weekly Tasks
- Submit new blog posts for indexing
- Review mobile usability issues
- Check rich results status

### Monthly Reviews
- Analyze search query performance
- Review top pages and queries
- Identify content gaps

## Key Metrics to Monitor

### Search Performance
- **Impressions** - How often your site appears in search
- **Clicks** - How often people click your results
- **CTR** - Click-through rate (clicks ÷ impressions)
- **Position** - Average ranking position

### Index Coverage
- **Valid pages** - Successfully indexed
- **Excluded pages** - Why pages aren't indexed
- **Crawled but not indexed** - Temporary issues

### Enhancements
- **Rich results** - Structured data validation
- **Mobile usability** - Mobile-friendly status
- **Core Web Vitals** - Page experience signals

## AI Search Monitoring

### Bard/Google AI Features
- Check if your content appears in AI responses
- Monitor featured snippets
- Review knowledge panels

### Search Generative Experience (SGE)
- Test SGE with your target queries
- Ensure structured data supports AI summaries

## Troubleshooting Common Issues

### Pages Not Indexed
- Check robots.txt blocking
- Verify meta noindex tags
- Ensure page is linked internally
- Submit manually via URL inspection

### Drop in Rankings
- Check for manual penalties
- Review Core Web Vitals
- Analyze content quality
- Monitor competitor changes

### Crawl Errors
- Fix broken internal links
- Update redirected URLs
- Remove deleted pages from sitemap
- Check server response codes

## Advanced Features

### Search Appearance
- Monitor how your site appears in search
- Check AMP status (if applicable)
- Review video indexing

### Links Report
- See which sites link to you
- Identify top linking pages
- Monitor link growth over time

### Manual Actions
- Check for manual penalties
- Review reconsideration requests
- Monitor spam reports

## Integration with Other Tools

### Google Analytics
- Link GSC with GA4 for combined insights
- Cross-reference search and behavior data

### Google Tag Manager
- Implement tracking codes
- Monitor conversion tracking

### AI Search Tools
- Use tools like Bard to test AI responses
- Monitor AI-generated snippets

## Best Practices

### Content Optimization
- Focus on user intent
- Create comprehensive content
- Use natural language
- Optimize for featured snippets

### Technical SEO
- Maintain fast loading times
- Ensure mobile-friendliness
- Use HTTPS security
- Implement proper redirects

### Monitoring Schedule
- **Daily:** Error checks, performance overview
- **Weekly:** Detailed analysis, content updates
- **Monthly:** Strategic reviews, goal assessment

## Emergency Response

### If Rankings Drop Significantly
1. Check for penalties in GSC
2. Review recent changes
3. Analyze competitor performance
4. Contact Google support if needed

### If Site Goes Down
1. Check server status
2. Verify DNS settings
3. Monitor uptime services
4. Communicate with users

This setup ensures comprehensive monitoring of your AI search visibility and technical performance.