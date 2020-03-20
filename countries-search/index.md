# Search box to search for and display country details

## Key points

### API Endpoint - https://restcountries.eu/#api-endpoints
### Example search box with results - https://www.nutritionix.com/
    Type in eg., "Biryani" - and notice the search results, which displays the search item and an image beside it. The countries search should work in a similar way.

## Requirements

1. Search box to search for countries
2. Options to search by - Name OR Currency OR Capital City
3. The results of the search should always return - Country name and Flag beside it (refer to Key Points section)
4. Limit the search results to top 5
5. Selecting/Clicking on the search result should populate country details below the search box. This is a separate API call to get details by passing country code
6. Next steps:
    * Show popular searches in the side bar
    * Show recent searches below the search box as hyperlinks, which when clicked will directly fetch the country details
    * Throttle/Debounce the search for better UX

## Additional Info

1. Any required icons can be downloaded from https://feathericons.com/ or https://iconmonstr.com/
