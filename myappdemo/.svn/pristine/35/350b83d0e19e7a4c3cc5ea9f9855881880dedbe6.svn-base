using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Xml;

namespace demoXml
{
    class Program
    {
        static void Main(string[] args)
        {
            XmlDocument xdoc = new XmlDocument();
            XmlNode root = xdoc.CreateElement("Users");
            xdoc.AppendChild(root);
            XmlNode nodex = xdoc.CreateElement("user");
            XmlAttribute atribute = xdoc.CreateAttribute("age");
            atribute.Value = "34";
            nodex.InnerText = "Dao Ngoc Huy";
            nodex.Attributes.Append(atribute);
            root.AppendChild(nodex);
            XmlNode nodex2 = xdoc.CreateElement("user");
            XmlAttribute atribute2 = xdoc.CreateAttribute("age");
            atribute2.Value = "33";
            nodex2.InnerText = "Nguyen Thi Man";
            nodex2.Attributes.Append(atribute2);
            root.AppendChild(nodex2);
            xdoc.Save("user.xml");
            Console.ReadKey();
        }
        
    }
}
