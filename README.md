<div align="center">

# Raditya Arganta Anantio

**Backend Engineer** · Go · Concurrency · API Design · Security

[![GitHub](https://img.shields.io/badge/GitHub-argnta-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/argnta)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-radityaarganta-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/radityaarganta)

</div>


---

## Summary

Backend engineer specializing in Go, with a strong interest in system design, performance, and security. My work focuses on services that separate concerns, process work concurrently, and fail gracefully under load. These are systems where the HTTP handler never blocks on business logic, where work is distributed through bounded queues, and where failure modes are documented rather than hidden behind optimistic defaults.

My public repositories center on four themes: asynchronous worker pools with buffered channels; event-driven pipelines with retry and dead-letter handling; API-key authentication with time-window rate limiting and mutex-guarded shared state; and HTTP inspection tooling built on the Go standard library. Each project is scoped deliberately as a well-understood subset of a production pattern, implemented with explicit limitations and a documented path toward production readiness, such as Redis for rate-limit state, encryption for stored credentials, and persistent queues for dispatch.

Alongside backend work, I use Python for classical machine learning on text, including sentiment classification with TF-IDF and Logistic Regression, topic modeling with LDA, and integrations such as ESC/POS thermal printing and public geocoding and weather APIs. The common thread across all of this is consistent: build the thing, understand the trade-offs, and leave behind a README that explains both.

---

## Language Profile

<div align="center">

<a href="https://github.com/stats-organization/github-stats-extended">
  <picture>
    <source media="(prefers-color-scheme: dark)"  srcset="https://github-stats-extended.vercel.app/api/top-langs/?username=argnta&layout=compact&card_width=495&hide_border=true&langs_count=6&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9" />
    <img alt="Language distribution across repositories" src="https://github-stats-extended.vercel.app/api/top-langs/?username=argnta&layout=compact&card_width=495&hide_border=true&langs_count=6" />
  </picture>
</a>

</div>

---

## Core Areas

**Concurrency and Messaging.** Buffered channels and worker pools, event queues and dispatchers, retry logic and dead-letter queues, non-blocking HTTP handlers.

**API Design and Security.** API-key authentication, time-window rate limiting, mutex-protected shared state, HTTP redirect inspection.

**Data and Integrations.** TF-IDF and Logistic Regression, topic modeling with LDA, ESC/POS thermal printing, Nominatim and Open-Meteo APIs.

---

## Selected Work

<table>
  <tr>
    <td width="50%" align="center">
      <a href="https://github.com/argnta/Event-Driven-Notification-Service">
        <picture>
          <source media="(prefers-color-scheme: dark)"  srcset="https://github-stats-extended.vercel.app/api/pin/?username=argnta&repo=Event-Driven-Notification-Service&theme=tokyonight&hide_border=true" />
          <img alt="Event-Driven-Notification-Service" src="https://github-stats-extended.vercel.app/api/pin/?username=argnta&repo=Event-Driven-Notification-Service&theme=default&hide_border=true" />
        </picture>
      </a>
    </td>
    <td width="50%" align="center">
      <a href="https://github.com/argnta/Async-Feedback-Service">
        <picture>
          <source media="(prefers-color-scheme: dark)"  srcset="https://github-stats-extended.vercel.app/api/pin/?username=argnta&repo=Async-Feedback-Service&theme=tokyonight&hide_border=true" />
          <img alt="Async-Feedback-Service" src="https://github-stats-extended.vercel.app/api/pin/?username=argnta&repo=Async-Feedback-Service&theme=default&hide_border=true" />
        </picture>
      </a>
    </td>
  </tr>
  <tr>
    <td width="50%" align="center">
      <a href="https://github.com/argnta/API-Rated-Limiter">
        <picture>
          <source media="(prefers-color-scheme: dark)"  srcset="https://github-stats-extended.vercel.app/api/pin/?username=argnta&repo=API-Rated-Limiter&theme=tokyonight&hide_border=true" />
          <img alt="API-Rated-Limiter" src="https://github-stats-extended.vercel.app/api/pin/?username=argnta&repo=API-Rated-Limiter&theme=default&hide_border=true" />
        </picture>
      </a>
    </td>
    <td width="50%" align="center">
      <a href="https://github.com/argnta/redirect-stopper">
        <picture>
          <source media="(prefers-color-scheme: dark)"  srcset="https://github-stats-extended.vercel.app/api/pin/?username=argnta&repo=redirect-stopper&theme=tokyonight&hide_border=true" />
          <img alt="redirect-stopper" src="https://github-stats-extended.vercel.app/api/pin/?username=argnta&repo=redirect-stopper&theme=default&hide_border=true" />
        </picture>
      </a>
    </td>
  </tr>
  <tr>
    <td width="50%" align="center">
      <a href="https://github.com/argnta/Simple-Ticketing-System">
        <picture>
          <source media="(prefers-color-scheme: dark)"  srcset="https://github-stats-extended.vercel.app/api/pin/?username=argnta&repo=Simple-Ticketing-System&theme=tokyonight&hide_border=true" />
          <img alt="Simple-Ticketing-System" src="https://github-stats-extended.vercel.app/api/pin/?username=argnta&repo=Simple-Ticketing-System&theme=default&hide_border=true" />
        </picture>
      </a>
    </td>
    <td width="50%" align="center">
      <a href="https://github.com/argnta/Simple-Sentimen-Review-Film">
        <picture>
          <source media="(prefers-color-scheme: dark)"  srcset="https://github-stats-extended.vercel.app/api/pin/?username=argnta&repo=Simple-Sentimen-Review-Film&theme=tokyonight&hide_border=true" />
          <img alt="Simple-Sentimen-Review-Film" src="https://github-stats-extended.vercel.app/api/pin/?username=argnta&repo=Simple-Sentimen-Review-Film&theme=default&hide_border=true" />
        </picture>
      </a>
    </td>
  </tr>
</table>

---

## Tech Stack

<div align="center">

<p>
  <img src="https://skillicons.dev/icons?i=go,py,flask,sklearn,mysql,postgres,bootstrap&perline=13" alt="Core stack" />
</p>

<p>
  <img alt="httprouter" src="https://img.shields.io/badge/httprouter-00ADD8?style=flat-square&logo=go&logoColor=white" />
  <img alt="REST" src="https://img.shields.io/badge/REST-1F6FEB?style=flat-square&logo=fastapi&logoColor=white" />
  <img alt="Jinja2" src="https://img.shields.io/badge/Jinja2-B41717?style=flat-square&logo=jinja&logoColor=white" />
  <img alt="NLTK" src="https://img.shields.io/badge/NLTK-154F5B?style=flat-square&logo=python&logoColor=white" />
  <img alt="Kivy" src="https://img.shields.io/badge/Kivy-1F6FEB?style=flat-square&logo=kivy&logoColor=white" />
  <img alt="Tkinter" src="https://img.shields.io/badge/Tkinter-3776AB?style=flat-square&logo=python&logoColor=white" />
  
</p>

</div>

---

## Demonstrated Competencies

- **Concurrency in Go.** [Async-Feedback-Service](https://github.com/argnta/Async-Feedback-Service): buffered channel and worker pool. [Event-Driven-Notification-Service](https://github.com/argnta/Event-Driven-Notification-Service): parallel workers over an event queue.
- **Resilience patterns.** Retry logic and dead-letter queue in Event-Driven-Notification-Service.
- **API authentication and rate limiting.** [API-Rated-Limiter](https://github.com/argnta/API-Rated-Limiter): `X-API-Key` validation, time-window limits, HTTP 429 responses, mutex-guarded store.
- **HTTP and security tooling.** [redirect-stopper](https://github.com/argnta/redirect-stopper): redirect tracing with status, Content-Type, and protocol version using only the standard library.
- **Third-party API integration.** [justweather](https://github.com/argnta/justweather): Nominatim geocoding and Open-Meteo forecasts with timeout and fallback handling.
- **Hardware integration.** [Simple-Ticketing-System](https://github.com/argnta/Simple-Ticketing-System): USB thermal printing through ESC/POS.
- **Classical NLP and ML.** [Simple-Sentimen-Review-Film](https://github.com/argnta/Simple-Sentimen-Review-Film): TF-IDF and Logistic Regression. [Automated-News-Categorizer-LDA](https://github.com/argnta/Automated-News-Categorizer-LDA): topic modeling with LDA.
- **Technical documentation.** READMEs describe architecture, run instructions, known limitations, and planned improvements.

---

## Working Style

- **Separate concerns.** Handlers accept and validate; workers process. Request lifecycle and business logic do not share a thread of execution.
- **State limitations openly.** Where a project is in-memory, unauthenticated, or unencrypted, the README says so and lists the production path, for example Redis for rate-limit state and encryption for stored credentials.
- **Prefer the standard library** when it is sufficient, and add dependencies deliberately.
- **Document for the next reader.** Each project explains what it does, how to run it, and what comes next.

---

## Contribution

<div align="center">

![Contribution history rendered as a growing bonsai](output/bonsai-growth.gif)

*Contribution history rendered as a growing bonsai.*

</div>
