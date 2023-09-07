<ul>
  <li>Meetup: <a href="https://www.meetup.com/es/rubyba/" target="_blank">Buenos Aires</a></li>
  <li>
    Slack: <a href="https://join.slack.com/t/rubysur/shared_invite/zt-22ukw3n1t-w8k65wRscQO9t_GuHMh5WA" target="_blank">Rubysur</a>
  </li>

  <li>Sponsors: <a href="/sponsors">Listado</a> | <a href="/sponsorship_details">Detalles de sponsoreo</a></li>
  <li>Github: <a href="https://github.com/cperezabo/rubysur" target="_blank">Repo</a></li>
</ul>

## Meetups

<ul>
{% for meetup in site.meetups reversed %}
    <li><a href="{{ meetup.url }}"> {{ meetup.date | date_to_string }} - {{ meetup.title }} </a></li>
{% endfor %}
</ul>
