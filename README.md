
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <!-- The above 3 meta tags *must* come first in the head; any other head content must come *after* these tags -->
    <title>QWS Dataset</title>

    <link href="https://fonts.googleapis.com/css?family=Merriweather|Open+Sans" rel="stylesheet">
    <!-- Bootstrap -->
    <link href="./css/bootstrap.min.css" rel="stylesheet">
    <link href="./css/a-gradient.css" rel="stylesheet">
    <link href="./css/gradients.min.css" rel="stylesheet">
    <link rel="stylesheet" href="./font-awesome/css/font-awesome.min.css">
    <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
    <!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
    <!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/html5shiv/3.7.3/html5shiv.min.js"></script>
      <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
    <![endif]-->
  </head>
  <body data-spy="scroll" data-target="#topnav">
    <!-- MAIN CONTAINER -->
    <!-- Fixed navbar -->
      <nav class="navbar navbar-default navbar-fixed-top" id="topnav">
        <div class="container">
          <div class="navbar-header">
            <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar" aria-expanded="false" aria-controls="navbar">
            <span class="sr-only">Toggle navigation</span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            </button>
            <a class="navbar-brand" href="#">QWS Dataset</a>
          </div>
          <div id="navbar" class="navbar-collapse collapse">
            <ul class="nav navbar-nav">
            </ul>
            <ul class="nav navbar-nav navbar-right">
              <li><a href="#section1">About</a></li>
              <li><a href="#section2">Description</a></li>
              <li><a href="#section3">Definitions</a></li>
              <li><a href="#section4">Download</a></li>
              <li><a href="#section5">Applications</a></li>
              <li><a href="#section6">Contact</a></li>
            </ul>
          </div><!--/.nav-collapse -->
        </div>
      </nav>

    <div class="container-fluid">
      <!-- START SECTION 1 -->
      <div class="row"  >
        <div class="col-md-12 leadsection innershadow sea-blue" id="section1" >

        <div class="col-md-1">
        </div>
        <div class="col-md-10">
          <!-- START SECTION 1 CONTENT -->
          <h1>About QWS Dataset</h1>
          <p class="lead" style="text-align:justify">Thank you for your interest in the QWS Dataset,
                          the first web services' dataset that measured real web services' Quality of Service (QoS)
                          introduced in 2007 and is part of is part of Eyhab Al-Masri's PhD thesis work.
                          The QWS Dataset has been widely accepted across the research community and downloaded over
                          <strong style="color: #ded9bd">19,000</strong> times since its first introduction in 2007.
                          The main goal of this dataset is to offer a basis for web service researchers.
                          The web services were collected using the <strong><a target="_blank"  style="color: #ded9bd" href="https://dl.acm.org/citation.cfm?id=1367605">
                          Web Service Crawler Engine (WSCE)</a></strong> and the majority of these services were
                          obtained from public sources on the web including Universal Description, Discovery, and
                          Integration (UDDI) registries, search engines and service portals.</p>&nbsp;
          <p class="lead" style="text-align:justify">The QWS Dataset includes a set of <strong style="color: #ded9bd">2,507</strong> web services and their <strong style="color: #ded9bd"><a target="_blank"  style="color: #ded9bd" href="https://ieeexplore.ieee.org/document/4317873">Quality of Web Service
                          (QWS)</a></strong> measurements that were conducted during the year of 2008 using our <strong><a target="_blank"  style="color: #ded9bd" href="https://dl.acm.org/citation.cfm?id=1853973">Web Service
                          Broker (WSB)</a></strong> framework. Each row in this dataset represents a Web service and its
                          corresponding nine QWS measurements (separated by commas). The first nine elements are
                          QWS metrics that were measured using multiple Web service benchmark tools over a six-day
                          period. The QWS values represent averages of the measurements collected during that period.
                          The last two parameters represent the service name and reference to the WSDL document.</p>&nbsp;
          <!-- END SECTION 1 CONTENT -->
        </div>
        <div class="col-md-1">
        </div>


        </div><!--/md-12 -->
      </div><!--/row-->
      <!-- END SECTION 1 -->

      <!-- START SECTION 2 -->
      <div class="row">
      <div class="col-md-12 section innershadow sea-blue" id="section2">

      <div class="col-md-1">
      </div>
      <div class="col-md-10">
      <!-- START SECTION 2 CONTENT -->
      <h1>Description of the QWS Dataset</h1>
      <p class="lead" style="text-align:left">Each row in the dataset corresponds to an existing Web service implementation. The dataset contains a collection of web services from our service repository that were continuously monitored for particular service qualities including:</p>
      <div class="alert alert-warning" role="alert">
      <table border="0" width="100%" id="table9" cellspacing="2" cellpadding="4" >
        <tr style="text-align:left">
          <td width="10%"><strong><p>ID</p></strong></td>
          <td width="20%"><strong><p>Parameter Name</p></strong></td>
          <td width="50%"><strong><p>Description</p></strong></td>
          <td width="20%"><strong><p>Units</p></strong></td>
        </tr>
        <tr style="text-align:left" bgcolor="#F7F6F3">
          <td><p>1</p></td>
          <td><p>Response Time</p></td>
          <td><p>Time taken to send a request and receive a response</p></td>
          <td><p>ms</p></td>
        </tr>
        <tr style="text-align:left" bgcolor="#FFFFFF">
          <td><p>2</p></td>
          <td><p>Availability</p></td>
          <td><p>Number of successful invocations/total invocations</p></td>
          <td><p>%</td>
        </tr>

        <tr style="text-align:left" bgcolor="#F7F6F3">
          <td><p>3</p></td>
          <td><p>Throughput</p></td>
          <td><p>Total Number of invocations for a given period of time</p></td>
          <td><p>invokes/second</p></td>
        </tr>
        <tr style="text-align:left" bgcolor="#FFFFFF">
          <td><p>4</p></td>
          <td><p>Successability</p></td>
          <td><p>Number of response / number of request messages</p></td>
          <td><p>%</p></td>
        </tr>

        <tr style="text-align:left" bgcolor="#F7F6F3">
          <td><p>5</p></td>
          <td><p>Reliability</p></td>
          <td><p>Ratio of the number of error messages to total messages</p></td>
          <td><p>%</p></td>
        </tr>
        <tr style="text-align:left" bgcolor="#FFFFFF">
          <td><p>6</p></td>
          <td><p>Compliance</p></td>
          <td><p>The extent to which a WSDL document follows <a style="color: #5c6a7d;padding: 4px 4px;text-align: center;text-decoration: none; display: inline-block;" target="_blank" href="http://www.w3.org/TR/wsdl">WSDL specification</a></p></td>
          <td><p>%</p></td>
        </tr>

        <tr style="text-align:left" bgcolor="#F7F6F3">
          <td><p>7</p></td>
          <td><p>Best Practices</p></td>
          <td><p>The extent to which a Web service follows <a style="color: #5c6a7d;padding: 4px 4px;text-align: center;text-decoration: none; display: inline-block;" target="_blank" href="http://www.ws-i.org/Profiles/BasicProfile-2_0(WGD).html">WS-I Basic Profile</a></p></td>
          <td><p>%</p></td>
        </tr>
        <tr style="text-align:left" bgcolor="#FFFFFF">
          <td><p>8</p></td>
          <td><p>Latency</p></td>
          <td><p>Time taken for the server to process a given request</p></td>
          <td><p>ms</p></td>
        </tr>

        <tr style="text-align:left" bgcolor="#F7F6F3">
          <td><p>9</p></td>
          <td><p>Documentation</p></td>
          <td><p>Measure of documentation (i.e. description tags) in WSDL</p></td>
          <td><p>%</p></td>
        </tr>
        <tr style="text-align:left" bgcolor="#FFFFFF">
          <td><p>10</p></td>
          <td><p>WsRF</p></td>
          <td><p>Web Service Relevancy Function: a rank for Web Service Quality</p></td>
          <td><p>%</p></td>
        </tr>

        <tr style="text-align:left" bgcolor="#F7F6F3">
          <td><p>11</p></td>
          <td><p>Service Classification</p></td>
          <td><p>Levels representing service offering qualities (1 through 4)</p></td>
          <td><p>Classifier</p></td>
        </tr>
        <tr style="text-align:left" bgcolor="#FFFFFF">
          <td><p>12</p></td>
          <td><p>Service Name</p></td>
          <td><p>Name of the Web service</p></td>
          <td><p>-</p></td>
        </tr>

        <tr style="text-align:left" bgcolor="#F7F6F3">
          <td><p>13</p></td>
          <td><p>WSDL Address</p></td>
          <td><p>Location of the Web Service Definition Language (WSDL) file on the Web</p></td>
          <td><p>-</p></td>
        </tr>
        </table>
            </div>
            </td>
          </tr>
        </table>

      </div>

      <!-- END SECTION 2 CONTENT -->
      </div>
      <div class="col-md-1">
      </div>
      </div><!--/md-12 -->
      </div><!--/row-->
      <!-- END SECTION 2 -->

      <!-- START SECTION 3 -->
      <div class="row">
      <div class="col-md-12 section innershadow sea-blue" id="section3">

      <div class="col-md-1">
      </div>
      <div class="col-md-10">
        <!-- START SECTION 3 CONTENT -->
        <h1>Definitions</h1>
        <p >This section defines key concepts used in the QWS dataset.</p>
        <p style="text-align:justify" class="lead"><code>Quality of Web Service (QWS)</code> &nbsp;Web service’s ability to provide selective treatment to various clients in the most effective manner.</p>&nbsp;
        <p style="text-align:justify" class="lead"><code>Web Service Relevancy Function (WsRF)</code> &nbsp;WsRF is used to measure the quality ranking of a Web service based on quality metrics (1 through 9 above).</p>&nbsp;
        <p style="text-align:justify" class="lead"><code>Documentation</code> &nbsp;One of the main properties of Web services is having proper documentation. The documentation QWS property provides a measure to the extent of which a Web service is self-describable and is based on examining WSDL documents including service name, description, operation name, description, message name, and message description tags.</p>&nbsp;
        <p style="text-align:justify" class="lead"><code>Service Classification</code> &nbsp;The service classification represents various levels of service offering qualities. There are four service classifications:
          <ol style="text-align:left" class="lead">
            <li>Platinum (High quality)</li>
            <li>Gold</li>
            <li>Silver</li>
            <li>Bronze (Low quality)</li>
          </ol>
          <p style="text-align:justify" >The classification is based on the overall quality rating provided by our WsRF. Using WsRF values obtained for each Web services, we use a classification scheme to associate each Web services to a particular service group. The classification can be helpful to differentiate between various services that offer the same functionality.</p>

        <!-- END SECTION 3 CONTENT -->
        </div>
        <div class="col-md-1">
        </div>
        </div><!--/md-12 -->
        </div><!--/row-->
        <!-- END SECTION 3 -->


      <!-- START SECTION 4 -->
      <div class="row">
      <div class="col-md-12 section innershadow sea-blue" id="section4">

      <div class="col-md-1">
      </div>
      <div class="col-md-10">
      <!-- START SECTION 4 CONTENT -->
      <h1>Download</h1>
      <p style="text-align:justify" class="lead">The QWS dataset is available free of charge for educational and non-commercial purposes. In exchange, we kindly request that you make available to us the results of running the QWS dataset. Please use the following references in citing the dataset:</p>
      &nbsp;
      <ul>
        <li>
          <p style="text-align:justify;color:#e3e8c5">Al-Masri, E., and Mahmoud Q. H., "Investigating web services on the world wide web", ACM 17th international conference on World Wide Web (WWW '08), pp.795-804.</p>
        </li>
        <li>
          <p style="text-align:justify;color:#e3e8c5">Al-Masri, E., and Mahmoud, Q. H., "QoS-based Discovery and Ranking of Web Services", IEEE 16th International Conference on Computer Communications and Networks (ICCCN), 2007, pp. 529-534.</p>
        </li>
        <li>
          <p style="text-align:justify;color:#e3e8c5">Al-Masri, E., and Mahmoud, Q. H., "Discovering the best web service", ACM 16th International Conference on World Wide Web (WWW), 2007, pp. 1257-1258.</p>
        </li>
      </ul>
      &nbsp;
      <div class="col-md-6 contact-right">
          <p class="lead" style="text-align:justify;color:#e0d9a6">Downloading and using the QWS Data will indicate your acceptance to enter into a <a style="color: #5c6a7d; background-color:#c9c8bf; padding: 4px 4px;text-align: center;text-decoration: none; display: inline-block;" target="_blank" href="http://www.gnu.org/copyleft/gpl.html">GNU General Public License</a> agreement. Should the QWS Data be used in any scientific or educational study/research the authors will be accredited as the source of the data with any of the references listed above in citing the data. Redistribution of this data to any other third party or on the Web is not permitted.</p>
      </div>
        <div class="form-group">
          <a href="https://qwsdata.github.io/qws/qws2.html" target="_blank"><label class="btn btn-success btn-lg btn-trans"><p class="lead">Download QWS Dataset ver 2.0 (<strong style="color:#e3d586">2507 web services</strong>)</p></label></a>
        </div>
        <p>&nbsp;</p>
        <p>&nbsp;</p>

        <div class="form-group">
          <a href="https://qwsdata.github.io/qws/qws1.html" target="_blank"><label class="btn btn-success btn-lg btn-trans">[old] Download QWS Dataset ver 1.0 (365 web services)</label></a>
        </div>

        <!--END CONTACT FORM-->
      </div>
      </div> <!-- /row -->
      <!-- END SECTION 4 CONTENT -->
      </div>
      <div class="col-md-1">
      </div>
      </div><!--/md-12 -->
      </div><!--/row-->
      <!--END SECTION 4 -->



      <!-- START SECTION 5 -->
      <div class="row">
      <div class="col-md-12 section innershadow sea-blue" id="section5">

      <div class="col-md-1">
      </div>
      <div class="col-md-10">
      <!-- START SECTION 5 CONTENT -->
      <h1>Applications</h1>
      <p style="text-align:justify" class="lead">The QWS dataset has been applied to a wide range of research projects/theses in areas covered by services computing including (but not limited to) the following:</p>
      &nbsp;

      <ul style="text-align:center;list-style-type:none" class="lead">
        <li>
            <code style="background-color: #c9c8bf; color:#415782"><b>Web Service Classification</b></code>&emsp;&emsp;
            <code style="background-color: #c9c8bf; color:#415782"><b>Web Service Composition</b></code>&emsp;&emsp;
            <code style="background-color: #c9c8bf; color:#415782"><b>Web Service QoS Performance </b></code>
        </li>&nbsp;

        <li>
            <code style="background-color: #c9c8bf; color:#415782"><b>Web Service QoS Prediction</b></code>&emsp;&emsp;
            <code style="background-color: #c9c8bf; color:#415782"><b>Web Service Ranking</b></code>&emsp;&emsp;
            <code style="background-color: #c9c8bf; color:#415782"><b>Web Service Discovery</b></code>
        </li>&nbsp;

        <li>
            <code style="background-color: #c9c8bf; color:#415782"><b>Web Service Modeling</b></code>&emsp;&emsp;
            <code style="background-color: #c9c8bf; color:#415782"><b>Web Services' Resource Management</b></code>&emsp;&emsp;
            <code style="background-color: #c9c8bf; color:#415782"><b>Web Service Coordination</b></code>
        </li>&nbsp;

        <li>
            <code style="background-color: #c9c8bf; color:#415782"><b>Service Orientated Analysis</b></code>&emsp;&emsp;
            <code style="background-color: #c9c8bf; color:#415782"><b>Web Service Transaction</b></code>&emsp;&emsp;
            <code style="background-color: #c9c8bf; color:#415782"><b>Business process Integration and Management</b></code>
        </li>&nbsp;

      </ul>


        <!--END CONTACT FORM-->
      </div>
      </div> <!-- /row -->
      <!-- END SECTION 5 CONTENT -->
      </div>
      <div class="col-md-1">
      </div>
      </div><!--/md-12 -->
      </div><!--/row-->
      <!--END SECTION 5 -->

      <!-- START SECTION 6 -->
      <div class="row">
      <div class="col-md-12 section innershadow sea-blue" id="section6">

      <div class="col-md-1">
      </div>
      <div class="col-md-10">
      <!-- START SECTION 5 CONTENT -->
      <h1>Contact</h1>
      <a style="text-align:center" class="btn btn-info btn-lg bigger-btn btn-trans" href="https://qwsdata.github.io/qws/">QWS Dataset website</a>&nbsp;&nbsp;&nbsp;&nbsp;
      <p style="text-align:center" class="lead">Your comments and suggestions are welcome.</p>&nbsp;
      <p style="text-align:center; color:#e3e8c5" class="lead">Please send your comments by email: Eyhab Al-Masri (qwsdata[AT]yahoo.com)</p>&nbsp;
      <p style="text-align:center" class="lead"> Copyright (c) 2007-2020 QWS Dataset, University of Guelph & University of Washington Tacoma.</p>&nbsp;&nbsp;
        <!--END CONTACT FORM-->
      </div>
      </div> <!-- /row -->
      <!-- END SECTION 5 CONTENT -->
      </div>
      <div class="col-md-1">
      </div>
      </div><!--/md-12 -->
      </div><!--/row-->
      <!--END SECTION 5 -->


      <div class="row">
      <div class="col-md-12 footer">
      Copyright &copy; 2007-2020 <a href="#">QWS Dataset</a> | University of Guelph & University of Washington Tacoma | <a href="https://qwsdata.github.io/qws/">QWS Dataset</a>
      </div>
      </div>

    </div><!--/container final closing tag-->

      <!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->
      <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
      <!-- Include all compiled plugins (below), or include individual files as needed -->
      <script src="./js/bootstrap.min.js"></script>
      <script>

        $(function () {
          $(document).scroll(function () {
            var $nav = $(".navbar-fixed-top");
            $nav.toggleClass('scrolled', $(this).scrollTop() > 200);
          });
        });

        $('body').scrollspy({ target: '#topnav' })

        // DELETE THIS SECTION START
        // DEMO GRADIENTS
        $('.demowell').hover(
           function(){ $(this).addClass('gradient-inverse') },
           function(){ $(this).removeClass('gradient-inverse') }
        )
        //DELETE THIS SECTION END

      </script>
  </body>
</html>
