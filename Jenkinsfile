pipeline {
    agent any
    stage('Clone Repo') {
        steps {
            echo "Cloning Repo..."
        }
    }
    stage('Execute Sanity Test') {
        steps {
            bat "C:\\Users\\ajink\\Downloads\\apache-jmeter-5.6.2\\apache-jmeter-5.6.2\\bin\\jmeter -j jmeter.save.saveservice.output_format=xml -n -t C:\\Users\\ajink\\Downloads\\apache-jmeter-5.6.2\\apache-jmeter-5.6.2\\bin\\Demo5.jmx -l C:\\Users\\ajink\\Downloads\\apache-jmeter-5.6.2\\apache-jmeter-5.6.2\\bin\\demo5.jtl"
        }
    }
    stage('Execute Load Test') {
        steps {
            bat "C:\\Users\\ajink\\Downloads\\apache-jmeter-5.6.2\\apache-jmeter-5.6.2\\bin\\jmeter -j jmeter.save.saveservice.output_format=xml -n -t C:\\Users\\ajink\\Downloads\\apache-jmeter-5.6.2\\apache-jmeter-5.6.2\\bin\\Demo5.jmx -l C:\\Users\\ajink\\Downloads\\apache-jmeter-5.6.2\\apache-jmeter-5.6.2\\bin\\demo5.jtl"
        }
    }
    stage('Execute Regression Test') {
        steps {
            bat "C:\\Users\\ajink\\Downloads\\apache-jmeter-5.6.2\\apache-jmeter-5.6.2\\bin\\jmeter -j jmeter.save.saveservice.output_format=xml -n -t C:\\Users\\ajink\\Downloads\\apache-jmeter-5.6.2\\apache-jmeter-5.6.2\\bin\\Demo5.jmx -l C:\\Users\\ajink\\Downloads\\apache-jmeter-5.6.2\\apache-jmeter-5.6.2\\bin\\demo5.jtl"
        }
    }
}