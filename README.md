
<h1>Technical Indicators API - Finnworlds</h1>

<p>The <a href="https://finnworlds.com/finance-data/technical-indicators-api/">Technical indicator API</a> is a fast and accurate REST API to get data on the most widely used Technical Indicators. The API uses the industry standard formulas to calculate the indicators.
What API does is to provide detailed and analysis-oriented technical indicator data based on historical prices of stocks. The API takes into account candlesticks of 1m, 5m, 15m, 30m, 1h, 2h, 4h, 12h, 1d and 1w to accurately produce technical indicator data. 
You can choose any of these candlesticks to get the API to calculate the intended indicator by using them as filters.</p>



<p><a href="https://finnworlds.com/">Finnworlds</a> is a data hub for finance APIs. The clients are mostly developers working for broker platforms, hedge funds, and other platform developers. 
You use the financial data to develop your platforms without having to worry about maintaining an actual database. 
We take care of this so that you can focus on your core business.</p>




<p><a href="https://finnworlds.com/pricing">Sign up for an API key</a> to get started with the technical indicators data immediately. We don't have free packages on the website but for students we can do something. Just email us and lets talk about it.</p>


	 
 
	 
	 
	 
	 
	 
	 
	 
	 
	 
	 
	 
	 
	 
	 
	 
	 



<h2>API Features</h2>

<ul><li><strong>stochastic_indicator</strong></li>
<li><strong>bollinger_bands</strong></li>
<li><strong>ichimoku_cloud</strong></li>
<li><strong>moving_average_convergence_divergence</strong></li>
<li><strong>relative_strength_index</strong></li>
<li><strong>fibonacci_retracement</strong></li>
<li><strong>average_directional_index</strong></li>
<li><strong>parabolic_stop_and_reverse</strong></li>
<li><strong>money_flow_index</strong></li>
<li><strong>average_true_range</strong></li>
<li><strong>simple_moving_average</strong></li>
<li><strong>exponential_moving_average</strong></li>
<li><strong>on_balance_volume</strong></li>
<li><strong>pivot_points</strong></li>
<li><strong>dynamic_momentum_index</strong></li>
<li><strong>directional_movement_index</strong></li>
<li><strong>aroon_indicator</strong></li>
<li><strong>klinger_oscillator</strong></li>
<li><strong>percentage_price_oscillator</strong></li>
</ul>


<p>We have many more technical indicators and we can also develop any technical indicator that you are missing. Just contact us</p>


<h2>How to access the data</h2>


<ul><li><strong>JSON rest API</strong></li></ul>



<h2>Documentation</h2>



Our <a href="https://finnworlds.com/documentation">documentation</a> includes input parameters, output objects with explanation of their meaning, we also provide clear examples on the documentation page of various endpoints and their output. On top of this we have SDKs for Javascript, JQuery, VueJS, Angular, JAVA, PHP, NodeJS, Python, Go, Ruby, C#, R, Strest, Rust, Swift and Scala</p>


<h2>Examples</h2>



<p><strong>RSI</strong><p>
<p><a href="https://finnworlds.com/documentation">https://finnworlds.com/api/v1/technicalindicators?key=YOUR-KEY&stock_ticker_symbol=aapl&technical_indicator=relative_strength_index</a></p>



    "status": {
        "message": "Success"
    },
    "results": [
        {
        "basics": {
            "name": "Apple Inc",
            "stock_ticker_symbol": "AAPL"
            "isin_identifier": "US0378331005"
            "exchange": "nasdaq"
            },

        "output": {
            "value": 70.03713323772295,
            "backtrack": 0
            },
            {
            "value": 68.55107952179476,
            "backtrack": 1
            },
            {
            "value": 72.55100476679559,
            "backtrack": 2
            },
            {
            "value": 73.51409814264913,
            "backtrack": 3
            },
            {
            "value": 69.91451308499144,
            "backtrack": 4
            },
            {
            "value": 65.17308969691057,
            "backtrack": 5
            },
            {
            "value": 66.17910755701931,
            "backtrack": 6
            },
            {
            "value": 68.41845715627683,
            "backtrack": 7
            },
            {
            "value": 64.71596338703083,
            "backtrack": 8
            },
            {
            "value": 70.76586249275925,
            "backtrack": 9
            }
            },
        }
    [



<p><strong>Stalled Pattern</strong><p>
<p><a href="https://finnworlds.com/documentation">https://finnworlds.com/api/v1/technicalindicators?key=YOUR-KEY&stock_ticker_symbol=aapl&technical_indicator=stalled_pattern</a></p>



    "status": {
        "message": "Success"
    },
    "results": [
        {
        "basics": {
            "name": "Apple Inc",
            "stock_ticker_symbol": "AAPL"
            "isin_identifier": "US0378331005"
            "exchange": "nasdaq"
            },

        "output": {
            {
            value: "100" // stalled_pattern pattern found at this candle
            }

            {
            value: "0" // stalled_pattern pattern NOT found at this candle
            }
            },
        }
    [





<h2>Customer Support</h2>

<p>Need help, have questions? <a href="mailto:support@finnworlds.com">Get in touch with Support</a>.</p>

<h2>Legal</h2>

<p>Use of the Finnworlds website, services like API and database are subject to the&nbsp;<a href="https://finnworlds.com/legal/terms-and-conditions-on-finnworlds-data/">Finnworlds terms &amp; Conditions</a></p>
