Under 3G throttling, the initial document request showed increased load time (~2 seconds). However, most resources were served from memory cache (0 ms), limiting full observation of slow network impact.

<img width="1728" height="950" alt="image" src="https://github.com/user-attachments/assets/8cf7f368-515b-49ca-ab31-18dbfa4f7d18" />

## TC-1: Verify application behavior under slow network conditions
**Tool:** Chrome DevTools Network (3G + Disable Cache)

### Steps
1. Open website
2. Open Network tab
3. Enable "Disable cache"
4. Set network to "Slow 3G"
5. Refresh page

### Expected Result
Application should load progressively under slow network conditions without breaking layout or functionality.

### Actual Result
Pass – Initial document loaded in ~2 seconds, while images and resources loaded significantly slower (up to ~1 minute). Several requests remained in "Pending" state due to network throttling. Page remained functional and layout did not break.
<img width="1728" height="950" alt="image" src="https://github.com/user-attachments/assets/4f552ece-b286-4156-a248-8594f9fd7ce4" />
