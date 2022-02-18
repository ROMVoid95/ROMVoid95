<!-- SVGs -->
[star]: https://cdn.jsdelivr.net/gh/Readme-Workflows/Readme-Icons@main/icons/octicons/StarredRepository.svg
[fork]: https://cdn.jsdelivr.net/gh/Readme-Workflows/Readme-Icons@main/icons/octicons/ForkedRepository.svg

## <img alt="emoji" src="https://raw.githubusercontent.com/twitter/twemoji/master/assets/svg/1f4ca.svg" height="30em"> Statistics
{%- await embed(`stats-base`, {base:"activity, community, repositories, metadata"}) %}

{%- await embed(`stats-commits-iso`, {isocalendar: true, isocalendar_duration:"half-year"}) %}

{%- await embed(`stats-issues-prs`, {plugin_followup: true, followup_sections:"repositories, user"}) %}

### <img alt="emoji" src="https://raw.githubusercontent.com/twitter/twemoji/master/assets/svg/2b50.svg" height="25em"> Recently starred
{%- await embed(`stats-stars`, {stars: true, stars_limit: 5}) %}

### <img alt="emoji" src="https://raw.githubusercontent.com/twitter/twemoji/master/assets/svg/1f5c2.svg" height="25em"> Most used languages
{%- await embed(`stats-languages`, {languages: true, languages_analysis_timeout: 15, languages_categories:"markup, programming", languages_colors:"github", languages_details:"percentage", languages_ignored:"shell, hack", languages_limit: 8, languages_recent_categories:"markup, programming", languages_recent_days: 14, languages_recent_load: 300, languages_sections:"most-used", languages_threshold:"0%"}) %}
