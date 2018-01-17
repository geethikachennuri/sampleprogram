# sampleprogram
angular js programhh
<!doctype html>
<html>
<head>
  <script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.3.0-beta.17/angular.min.js"></script>
  </head>
  <body ng-app="myapp">
    <div ng-coontroller="hellocontroller">
      < h2>welcome {{helloTo.title}} to the world of tutorialspoint</h2>
      </div>
    <script>
      angular.module("myapp",[])
      .controller("Hellocontroller",function($scope){
      $scope.helloTo={};
      $scope.helloTo.title="angularjs";
      });
      </script>
    </body>
  </html>
