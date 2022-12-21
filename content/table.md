---
title: "Table"
---




# DemoArq Table
<style>
.markdown-table {
    max-width: 500%;
	padding: 20px;
}
</style>

<div class="markdown-table">

|    | DEMOARQCOBOL.YAML	|	DEMOARQBPI.YAML	| 	DEMOARQNNNOF.YAML DEMOARQNNNOFNET.YAML	|	DEMOARQINTEGRATION.YAML|DEMOARQBPM.YAML| 	 DEMOARQNOSQL.YAML|
| --- | -------------     | -------------   | ---------------------------------------   | -------------          |-----          | -------------      |
|	API	|	demoArqCobol	|	demoArqBPI	|	demoArqNnnof	|	demoArqIntegration	|	demoArqBPM	|	demoArqNoSQL	|
|	Resources	|	weather	|	weather annotations	|	pet	|	iban …	|	clientEvalProcess	|	weather	|
|	Operations|		<ul><li>getWeatherForecast</li><li>getWeatherForecastByid </li><li>addWeatherForecast (post)</li><li>updateWeatherForecast(put) </li><li>deleteWeatherForecast</li></ul>	|	<ul><li>getWeatherForecast</li><li>getWeatherForecastByid </li><li>addWeatherForecast (post)</li><li>updateWeatherForecast(put) </li><li>deleteWeatherForecast</li></ul>	|	<ul><li>getOneOfPets</li><li>getAnyOfPets</li><li>postOneOfPets </li><li>postAnyOfPet</li></ul>	|	<ul><li>getGEOSIBAM</li><li>getSM…</li></ul>	|	<ul><li>postinicialProcessoAvaliacao </li><li>getProcessosAvaliacaoClientes</li><li>putDescricaoCliente</li><li>getClientStatus</li></ul> |	<ul><li>getWeatherForecast</li><li>getWeatherForecastByid </li><li>addWeatherForecast (post)</li><li>updateWeatherForecast(put) </li><li>deleteWeatherForecast</li></ul>	|
|	API	|	demoArqCobol	|	demoArqBPI	|	demoArqNnnof	|	demoArqIntegration	|	demoArqBPM	|	demoArqNoSQL	|
|	Resources	|	weather	|	weather annotations	|	pet	|	iban …	|	clientEvalProcess	|	weather	|
|	Capacidades	| <ul><li>Annotations:white_check_mark:</li><li>Hateoas:white_check_mark:</li><li>Errors:white_check_mark:</li><li>SCA:x:</li><li>Scopes wip</li></ul>| <ul><li>Dbs (PostgreSQL)?</li><li>Annotations:white_check_mark:</li><li>Hateoas?</li><li>Errors:white_check_mark:</li><li>SCA:white_check_mark:</li><li>API->API:white_check_mark:</li><li>Scopes wip</li></ul> | <ul><li>OneOf:white_check_mark:</li><li>AnyOf:white_check_mark:</li><li>AllOf:white_check_mark:</li><li>Hateoas:white_check_mark:</li><li>Errors:white_check_mark:</li></ul>	|	<ul><li>Geos</li><li>ServiceModel:x:</li><li>Stored Procedures T-SQL (SQLSERVER)?</li><li>StoredProcedures PL/SQL</li><li>(Oracle)?</li></ul>	|	Camunda :x:	|	mongoDB?	|
|	Descrição	|	Exemplos de utilização de capacidade na Pluggable COBOL	|	Exemplos de utilização de capacidades na Pluggable .NET	|	Exemplos de utilização de capacidades na Pluggable .NET e Pluggable COBOL	|	Exemplos de integração	|	<DELAYED>	|	Exemplos de utilização de capacidades na Pluggable .NET	|
|	Âmbito	|	Equipa PluggableCOBOL	|	Equipa Omni	|	Equipa Pluggable .NET e COBOL	|	Equipa Pluggable .NET	|		|	Equipa Pluggable .NET |
|	Endpoint	|	https://api.bancobpi.pt/demoarqcobol/v1/weatherforecast	|	https://api.bancobpi.pt/demoarqbpi/v1/weatherforecast	|	https://api.bancobpi.pt/demoarqnnnofcobol/v1/xxxxpets	|	https://api.bancobpi.pt/demoarqbpi/v1/???	|		|	https://api.bancobpi.pt/demoarqbpi/v1/weatherforecast	|

</div>

	
Each demoArq illustrates the capabilities of the pluggable in different technologies.

The "Insight"[^1] sections are optional, but advisable to be familiar with it.

[^1]: The insight sections are optional-readable pages filled with domain-knowledge. 
	E.g.,  the designing API section contains an insight sub-section where it explains what an API is and its best pratices.