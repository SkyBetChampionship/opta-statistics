# Get competition matches between two time stamps
OptaSD::Soccer::Match.new.competition('722fdbecxzcq9788l6jqclzlw').time_range(Time.now - 86400, Time.now + 86400).get

# Get Statistics Of Match with more details
OptaSD::Soccer::MatchStatistics.new.fixture('bsu6pjne1eqz2hs8r3685vbhl').detailed.get

# Get Match Events
OptaSD::Soccer::MatchEvent.new.fixture('bsu6pjne1eqz2hs8r3685vbhl').get

# Get Match Matrix
OptaSD::Soccer::PassMatrix.new.fixture('bsu6pjne1eqz2hs8r3685vbhl').get

# Get Possession Throughout A Match
OptaSD::Soccer::Possession.new.fixture('bsu6pjne1eqz2hs8r3685vbhl').get

# Get Match Commentary
OptaSD::Soccer::Commentary.new.fixture('bsu6pjne1eqz2hs8r3685vbhl').get

# Get Match Facts
OptaSD::Soccer::MatchFacts.new.fixture('bsu6pjne1eqz2hs8r3685vbhl').get

# Get Seasonal Stats by Competition Contestants
OptaSD::Soccer::SeasonalStats.new.competition('722fdbecxzcq9788l6jqclzlw').contestant('884uzyf1wosc7ykji6e18gifp').get

# Get Detailed Squads
OptaSD::Soccer::Squads.new.tournament('408bfjw6uz5k19zk4am50ykmh').detailed.get

# Get Team Standings With Live Data
OptaSD::Soccer::TeamStandings.new.tournament('408bfjw6uz5k19zk4am50ykmh').live.get

# Get Preview of Match
OptaSD::Soccer::MatchPreview.new.fixture('bsu6pjne1eqz2hs8r3685vbhl').get

# Build the request hit the api
match = OptaSD::Soccer::Match.new.resource('bsu6pjne1eqz2hs8r3685vbhl').live.lineups.get

# retrieve the response data
match.data['match']
