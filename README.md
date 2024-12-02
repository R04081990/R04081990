let queryContext = CSUserQueryContext()
queryContext.fetchAttributes = ["title", "textContent", "authorNames", "contentDescription"]
queryContext.maxSuggestionCount = 10
queryContext.enableRankedResults = true


let query = CSUserQuery(userQueryString: searchText, userQueryContext: queryContext)

