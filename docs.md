# Radio Stations Docs
### Endpoint: https://afrikdotorg.herokuapp.com/api/radios

### Route: /agba-details
### POST
### ONLY AGBA DETAILS
#### Post body

```javascript
  {}
```

### RESPONSE
OnSuccess<Response>
```javascript
{
  name: "A-G-B-A Radio",
  streamingLink: "http://edge.mixlr.com/channel/eerso",
  other: {
    location: "Ablekuma - Fanmilk, Accra Ghana"
  }
}

```

### Route: /all
### POST
### ALL RADIO STATIONS
#### Post body

```javascript
  {}
```

### RESPONSE
OnSuccess<Response>
```javascript
[
    {
      name: "Koobi Radio",
      streamingLink: "https://koobi.com",
      other: {
        location: "darkuman Accra"
      }
    },
    {
      name: "Koobi Radio",
      streamingLink: "https://koobi.com",
      other: {
        location: "darkuman Accra"
      }
    },
    {
      name: "Koobi Radio",
      streamingLink: "https://koobi.com",
      other: {
        location: "darkuman Accra"
      }
    },
    {
      name: "Koobi Radio",
      streamingLink: "https://koobi.com",
      other: {
        location: "darkuman Accra"
      }
    },
]
