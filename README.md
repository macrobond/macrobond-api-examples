<!-- markdownlint-disable -->
<div align="center">
    <a href="https://www.macrobond.com/">
        <img loading="lazy" aria-roledescription="brand logo" alt="Macrobond logo" src="https://macrobond.github.io/macrobond-data-api/assets/Macrobond_logo_Color.svg" width="30%">
    </a>
</div>

<h1 align="center">Macrobond API Examples</h1>


This repository contains examples of how to use Macrobond products by its API. You have to be a licensed user to the corresponding product to use the API.


## Chart Server

The Macrobond Chart Server delivers images of Macrobond charts in either PNG or SVG format. The server uses the same components as the Macrobond client application and will render exactly the same image over http as you would see in the client application. The server runs as a Windows Service. 

For more information, please refer to the [Chart Server Help Page](https://help.macrobond.com/technical-information/the-macrobond-chart-server/).

## Macrobond Data API

The Macrobond Data API for Python uses either the
[Macrobond Web REST API](https://help.macrobond.com/technical-information/the-macrobond-data-web-api-feed/)
or the [Macrobond Client data API](https://help.macrobond.com/technical-information/the-macrobond-api-for-python/)
to obtain time series with values and metadata.
The API consists of a set of functions in common between the underlying APIs as well as specialized functions unique to each implementation. Both APIs users have access to all endpoints mentioned in folder `Python Data API - Data+ & Data Feed`, but only Data Feed Users have access to the endpoints in the folder `Python Data API - Data Feed Exclusive`.

For more technical information, please refer to the [Macrobond Data API Github Repository](https://github.com/macrobond/macrobond-data-api/tree/main) or [Macrobond Data API Documentation](https://macrobond.github.io/macrobond-data-api/)

## Contributing

We welcome community pull requests for bug fixes, enhancements, and documentation.

## Getting support

[Support options](https://help.macrobond.com/support/)
