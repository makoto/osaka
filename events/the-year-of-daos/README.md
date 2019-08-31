---
####################
### INSTRUCTIONS ###
####################
# This file is a template to create new events.
# _Don't_ remove any text before the colons at the beginning of each line,
# only edit what is after the colon. Example:
# Don't remove the word nor colon on 'description:'
#
# Every line starting with a hash symbol (#) is a comment. It will be ignored
# and can be safely removed, including these instructions.
###############


###########
### SEO ###
###########
# The title of the page, displayed by the browser on the title of the window.
# Ideally this is the same as the name of the event.
title: "The year of DAOs"

# Description for this event. This will be rendered as a <meta> tag in the HTML,
# and displayed on the /events page. Keep it short.
# Linebreaks are ignored, but they _must_ start with two spaces.
description: "Now that all the major DAO frameworks (Aragon, Moloch, DaoStack, and Colony.io) are on mainnet, we want to celebrate the success of the many DAOs"



#####################
### EVENT DETAILS ###
#####################
# The name of the event you're creating.
# Ideally this is the same as the title.
name: "The year of DAOs"

# There _needs_ to be one hyphen before each paragraph.
# Linebreaks are ignored, but they _must_ start with two spaces.
# Indentation is crucial:
# Two spaces before the hyphen, four spaces before the text. _No_ tabs allowed.
# Add or remove paragraphs as needed, but remember the hyphen before each entry.
synopsis:
  -  "Now that all the major DAO frameworks (Aragon, Moloch, DaoStack, and Colony.io) are on mainnet, we want to celebrate the success of the many DAOs by having an evening session inviting they key members of each DAO and talk about their projects as well as how we can collaborate to strengthen the DAO communities. "
  -  
    'Speakers come from:'
  - list:  
    - MolochDAO
    - MetaCartelDAO
    - And more to come

  - "Max 100 ppl"

  - "The registration page to be announced soon."
  - "This event is currently under planning by Osaka Blockchain Week. [Join our telegram channel](https://t.me/joinchat/IzDHHxeJvuuFH78uXTf4HA) to find out more"
  - "[日本語案内]"
  - "DAO（Decentralised Autonomous Organisation, 自律分散型組織）は特定の管理者や主体を持たない分散型の組織で、組織内の階層構造もなく、構成員一人一人によって自律的に運営されているのが特徴です。イーサリアムコミュティ内では2016年に集団投資スキームをDAOで管理するTheDAOが150億円相当を集めたあと、ハッキングにあった事件が有名です。TheDAOの悲劇から3年経った今、イーサリアムコミュニティは過去の教訓を元によりセキュアなシステムを作り上げてきました。イーサリアムスマートコントラクト開発者が簡単にDAOシステムを導入するための様々なツールを開発するAragonとDAOstack。イーサリアム開発の助成金を募るために作られ1.5億ドル以上を各界の有力者たちから調達することに成功したMolochDAO。シェアリングエコノミーを実現することを目的に作られたColony などはすでに実用可能な段階になっています。"
  - "今回のイベントではそれらのフレームワーク開発企業をスピーカーとして招待するとともに、実際にこれらのDAOを使っている人達の生の声を聞くことで「DAOの最前線」を体感していただくイベントです。"
  - "セッションは全て英語になります"


# The date should be in the format year-month-day (ISO 8601).
# Example: 2018-02-28
date:
# The date when the event ends. Can be left empty or set to the same day the
# event starts.
endDate:

# Set the time in 24 hours format, surrounded by quotes.
# _Only_ the starting time!
# Example: '18:00'
time: '10:00'
# Time when the event ends. Can be left empty.
endTime: '18:00'

# The URL where to akquire the tickets. Can be left empty.
tickets: 

# If the entrance is free, set zero (0) as the price, or leave it empty.
# _Don't_ write the currency symbol (€ symbol will be used).
price: 'Free'

# The name of the venue where the event will be held. Can be left empty.
venue:

# The address to link to a Google map. Please test the address on Google Maps.
# Example: 5. května 1640/65, 140 21 Praha 4
address: 

# The category of the event. Valid options:
# - conference
# - event
# - hackathon
# - workshop
# - party
# Use _only_ one, and don't capitalize.
category: event


#################
### SPEAKERS ####
#################
# There _needs_ to be one hyphen before each entry.
# Linebreaks are ignored, but they _must_ start with two spaces.
# Indentation is crucial:
# Two spaces before the hyphen, four spaces before the text. _No_ tabs allowed.
# Add or remove speakers as needed, but remember the hyphen before each entry.
# speakers:
# -
#   # Required.
#   name: Carlos E. Salazar
#   picture: https://avatars.io/twitter/makoto_inoue/medium
#   # Can be left empty.
#   title: Lead Front-end Developer

#   # Can be left empty.
#   company: Least Authority

#   # The full URL, including http(s)://. Can be left empty.
#   companyURL: https://leastauthority.com



### DON'T MAKE CHANGES BELOW THIS LINE! ###
---
<!-- ### DON'T MAKE CHANGES BELOW THIS LINE! ### -->

<Event-Content/>
