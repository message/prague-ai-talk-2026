# Gumploop Workflow

## Practice Activity

Create an automated workflow using Gumploop to generate AI-powered weekly email digests.

### What is Gumploop?

Gumploop is a no-code automation platform that lets you build AI-powered workflows using natural language. Instead of manually connecting APIs and writing code, you describe what you want in plain English, and Gumploop creates the workflow for you.

### Task

Create an automated email digest that sends you the top news and trends every Monday for your chosen sector, powered by Perplexity AI.

### Steps to Try

#### 1. Access Gumploop Platform
1. Go to https://www.gumloop.com/pipeline
2. Sign in or create a free account
3. You'll land on the pipeline/workflow creation page

#### 2. Create Your Workflow Using AI

**The Magic Prompt:**

Replace the placeholders `[email]` and `[sector/category/topic]` with your actual values, then paste this prompt into Gumploop:

```
Send me an email notification to [email] with 20 latest news and trends for the past week in [sector/category/topic]. Use Perplexity as the source and Haiku 4.5 model for text processing. Email body as HTML.
```

**Example with actual values:**
```
Send me an email notification to john.doe@example.com with 20 latest news and trends for the past week in artificial intelligence. Use Perplexity as the source and Haiku 4.5 model for text processing. Email body as HTML.
```

**Placeholder Guide:**
- `[email]` - Your email address where you want to receive the digest
- `[sector/category/topic]` - Choose a topic you're interested in:
  - "artificial intelligence"
  - "healthcare technology"
  - "renewable energy"
  - "cryptocurrency"
  - "startup funding"
  - Or any other area you want to track

#### 3. Let Gumploop Build Your Workflow
1. Paste your customized prompt into Gumploop's workflow builder
2. Gumploop will automatically create the workflow components:
   - **Perplexity node** - To fetch latest news
   - **AI processing node** - Using Haiku 4.5 to format content
   - **Email node** - To send you the digest
3. Review the generated workflow visually
4. You may need to authorize connections (email, Perplexity API if required)

#### 4. Test Your Workflow
1. Click "Run" or "Test" to execute the workflow immediately
2. Check your email inbox for the digest
3. Review the HTML formatting and content quality
4. Verify all 20 news items are relevant to your chosen topic

### Tips for Better Results

- **Be specific with your topic** - "AI in healthcare" is better than just "technology"
- **Choose topics you genuinely care about** - You'll be getting these emails weekly!
- **Test** - Run the workflow manually first to ensure quality

### Advanced Customizations to Try

Once you have the basic workflow running, experiment with:

- **Multiple topics**: Create separate workflows for different interests
- **Different formats**: Change "HTML" to "plain text" or "markdown"
- **Add filters**: "Only include news from the past 3 days"
- **Summaries**: "Provide a 2-sentence summary for each news item"
- **Categorization**: "Group news by sub-topics"
- **Different AI models**: Try other models besides Haiku 4.5

### Troubleshooting

**If the workflow doesn't run:**
- Verify all required connections are authorized
- Check that your email address is correct
- Ensure Perplexity integration is properly configured

**If emails don't arrive:**
- Check spam/junk folder
- Verify the email node is configured correctly
- Test with a different email address

**If content quality is poor:**
- Make your topic more specific
- Adjust the prompt to request specific types of content
- Try a different AI model for processing

### Tool Used
- **Gumploop** (Free tier available): https://www.gumloop.com/pipeline

### Expected Outcome
By the end of this practice, you'll have:
- Created an AI-powered automation workflow using natural language
- Set up automated weekly email digests with curated news
- Experienced how Gumploop combines multiple AI services (Perplexity + Claude)
- Learned to build no-code workflows that would typically require programming

---
**Time Allocated**: Part of 20-minute hands-on practice session