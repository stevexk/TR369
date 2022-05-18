# TR369
USP - User Services Platform  server to manage tr369 devices.

Demo site for usp agent test here
http://usp.kmeisoft.com:8899/

Please follow the agent settings
##### Agent Settings Example:
            Device.LocalAgent.Controller.1.MTP.1.Enable => true
            Device.LocalAgent.Controller.1.MTP.1.Protocol => MQTT
            Device.LocalAgent.Controller.1.MTP.1.MQTT.Reference => Device.MQTT.Client.1
            Device.LocalAgent.Controller.1.MTP.1.MQTT.Topic => /usp/DQAEMUhT/controller
            Device.LocalAgent.Controller.1.Enable => true
            Device.LocalAgent.Controller.1.EndpointID => os::DQAEMUhT
            Device.LocalAgent.MTP.1.Protocol => MQTT
            Device.LocalAgent.MTP.1.Enable => true
            Device.LocalAgent.MTP.1.MQTT.Reference => Device.MQTT.Client.1
            Device.LocalAgent.MTP.1.MQTT.ResponseTopicConfigured => /usp/DQAEMUhT/endpoint/#
            Device.MQTT.Client.1.Enable => true
            Device.MQTT.Client.1.BrokerAddress => 81.68.141.224
            Device.MQTT.Client.1.BrokerPort => 8885
            Device.MQTT.Client.1.Username => ojGryAyc
            Device.MQTT.Client.1.Password => oCHYqYUGSDTGqoey
            Device.MQTT.Client.1.ProtocolVersion => 3.1
            Device.MQTT.Client.1.ClientID => USP Agent EndpointID Here
            Device.MQTT.Client.1.TransportProtocol => TCP/IP

If you have any question or needs, please mailto 402245352@qq.com

