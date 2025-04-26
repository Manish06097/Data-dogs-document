[Docs](https://docs.datadoghq.com/) > [API
Reference](https://docs.datadoghq.com/api/latest/)

Language

English

[English](https://docs.datadoghq.com/api/latest/?lang_pref=en)
[Français](https://docs.datadoghq.com/fr/api/latest/?lang_pref=fr)
[日本語](https://docs.datadoghq.com/ja/api/latest/?lang_pref=ja)
[한국어](https://docs.datadoghq.com/ko/api/latest/?lang_pref=ko)
[Español](https://docs.datadoghq.com/es/api/latest/?lang_pref=es)

Datadog Site

[![Site help](https://datadog-docs.imgix.net/images/icons/help-
druids.svg)](https://docs.datadoghq.com/getting_started/site/)

US1 US3 US5 EU AP1 US1-FED

## API Reference

The Datadog API is an HTTP REST API. The API uses resource-oriented URLs to
call the API, uses status codes to indicate the success or failure of
requests, returns JSON from all requests, and uses standard HTTP response
codes. Use the Datadog API to access the Datadog platform programmatically.

### Getting started

Authenticate to the API with an [API
key](https://docs.datadoghq.com/account_management/api-app-keys/#api-keys)
using the header `DD-API-KEY`. For some endpoints, you also need an
[Application key](https://docs.datadoghq.com/account_management/api-app-
keys/#application-keys), which uses the header `DD-APPLICATION-KEY`.

To try out the API [![Run in
Postman](https://run.pstmn.io/button.svg)](https://god.gw.postman.com/run-
collection/20651290-809b13c1-4ada-46c1-af65-ab276c434068?action=collection%2Ffork&source=rip_markdown&collection-
url=entityId%3D20651290-809b13c1-4ada-46c1-af65-ab276c434068%26entityType%3Dcollection%26workspaceId%3Dbf049f54-c695-4e91-b879-0cad1854bafa)

**Note** : To authenticate to the Datadog API through Postman, add your
Datadog API and Application key values to the **Collection variables** of the
Datadog API collection.

[Using the API](https://docs.datadoghq.com/api/v1/using-the-api/) is a guide
to the endpoints.

**Notes** :

  * Add your API and application key values to the **Variables** tab of the Datadog API Collection.
  * cURL code examples assume usage of BASH and GNU coreutils. On macOS, you can install coreutils with the [Homebrew package manager](https://brew.sh): `brew install coreutils`

### Client libraries

By default, the Datadog API Docs show examples in cURL. Select one of our
official [client
libraries](https://docs.datadoghq.com/developers/community/libraries/)
languages in each endpoint to see code examples from that library. To install
each library:

  * [Java](?code-lang=java#)
  * [Python](?code-lang=python#)
  * [Ruby](?code-lang=ruby#)
  * [Go](?code-lang=go#)
  * [Typescript](?code-lang=typescript#)
  * [Rust](?code-lang=rust#)
  * [Python [legacy]](?code-lang=python-legacy#)
  * [Ruby [legacy]](?code-lang=ruby-legacy#)

#### Installation

Maven - Add this dependency to your project’s POM:

    
    
    <dependency>
      <groupId>com.datadoghq</groupId>
      <artifactId>datadog-api-client</artifactId>
      <version>2.33.1</version>
      <scope>compile</scope>
    </dependency>
    

Gradle - Add this dependency to your project’s build file:

    
    
    compile "com.datadoghq:datadog-api-client:2.33.1"
    

#### Usage

    
    
    import com.datadog.api.client.ApiClient;
    import com.datadog.api.client.ApiException;
    import com.datadog.api.client.Configuration;
    import com.datadog.api.<VERSION>.client.api.*;
    import com.datadog.api.<VERSION>.client.model.*;
    

**Note** : Replace `<VERSION>` with v1 or v2, depending on which endpoints you
want to use.

#### Examples

Maven `pom.xml` for running examples:

    
    
    <project>
      <modelVersion>4.0.0</modelVersion>
      <groupId>com.example</groupId>
      <artifactId>example</artifactId>
      <version>1</version>
      <dependencies>
        <dependency>
          <groupId>com.datadoghq</groupId>
          <artifactId>datadog-api-client</artifactId>
          <version>2.33.1</version>
          <scope>compile</scope>
        </dependency>
      </dependencies>
    </project>
    

Make sure that `CLASSPATH` variable contains all dependencies.

    
    
    export CLASSPATH=$(mvn -q exec:exec -Dexec.executable=echo -Dexec.args="%classpath")
    

Gradle `build.gradle` for running examples:

    
    
    plugins {
        id 'java'
        id 'application'
    }
    
    repositories {
        jcenter()
    }
    
    dependencies {
        implementation 'com.datadoghq:datadog-api-client:2.33.1'
    }
    
    application {
        mainClassName = 'Example.java'
    }
    

Execute example by running `gradle run` command.

#### Installation

    
    
    pip install datadog
    

#### Usage

    
    
    import datadog
    

#### Installation

    
    
    pip3 install datadog-api-client
    

#### Usage

    
    
    import datadog_api_client
    

#### Installation

    
    
    gem install dogapi
    

#### Usage

    
    
    require 'dogapi'
    

#### Installation

    
    
    gem install datadog_api_client -v 2.31.1
    

#### Usage

    
    
    require 'datadog_api_client'
    

#### Installation

    
    
    go mod init main && go get github.com/DataDog/datadog-api-client-go/v2/api/datadog
    

#### Usage

    
    
    import (
            "github.com/DataDog/datadog-api-client-go/v2/api/datadog"
            "github.com/DataDog/datadog-api-client-go/v2/api/datadog<VERSION>"
    )
    

**Note** : Replace `<VERSION>` with `V1` or `V2`, depending on which endpoints
you want to use.

#### Installation

The package is under [@datadog/datadog-api-
client](https://www.npmjs.com/package/@datadog/datadog-api-client) and can be
installed through NPM or Yarn:

    
    
    # NPM
    npm install @datadog/datadog-api-client
    
    # Yarn
    yarn add @datadog/datadog-api-client
    

#### Usage

    
    
    import { <VERSION> } from 'datadog-api-client';
    

**Note** : Replace `<VERSION>` with v1 or v2, depending on which endpoints you
want to use.

#### Installation

Run `cargo add datadog-api-client`, or add the following to `Cargo.toml` under
`[dependencies]`:

    
    
    datadog-api-client = "0"
    

#### Usage

Try the following snippet to validate your Datadog API key:

    
    
    use datadog_api_client::datadog::Configuration;
    use datadog_api_client::datadogV1::api_authentication::AuthenticationAPI;
    
    #[tokio::main]
    async fn main() {
        let configuration = Configuration::new();
        let api = AuthenticationAPI::with_config(configuration);
        let resp = api.validate().await;
        if let Ok(value) = resp {
            println!("{:#?}", value);
        } else {
            println!("{:#?}", resp.unwrap_err());
        }
    }
    

Or check out the libraries directly:

[](https://github.com/DataDog/datadog-api-client-java)

[](https://github.com/DataDog/datadog-api-client-python)

[](https://github.com/DataDog/datadog-api-client-ruby)

[](https://github.com/DataDog/datadog-api-client-go)

[](https://github.com/DataDog/datadog-api-client-typescript)

[](https://github.com/DataDog/datadog-api-client-rust)

Trying to get started with the application instead? Check out Datadog’s
general [Getting Started
docs](https://docs.datadoghq.com/getting_started/application/).

## Further reading

Additional helpful documentation, links, and articles:

[Using the APIDOCUMENTATION ](https://docs.datadoghq.com/api/latest/using-the-
api/)[Authorization ScopesDOCUMENTATION
](https://docs.datadoghq.com/api/latest/scopes/)[Rate LimitsDOCUMENTATION
](https://docs.datadoghq.com/api/latest/rate-limits/)

