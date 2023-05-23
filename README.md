# Refund API

As part of my responsibilities, I was assigned the crucial task of developing a refund API solution for White Castle. Previously, our company relied on manual refund processes, which consumed valuable time and resources from our accounting team. Recognizing the need for a more efficient and user-friendly approach, I embarked on creating an automated system to streamline the refund process.

One of the key challenges we encountered was the lack of .NET support in our internal software, which was built using Powerbuilder 12.0. This posed a significant obstacle in directly connecting to a custom API. However, I devised a solution using C# that seamlessly integrates with our SQL Server infrastructure.

The implementation involved establishing a connection between the C# code and MSSQL by leveraging it as an assembly. Within the MSSQL procedure, I incorporated a code snippet that triggers a POST request to initiate the refund process. This procedure intelligently captures user input, retrieves the necessary API credentials, and securely transmits the information to the C# solution.

![assembly](https://github.com/temuulino/refundAPI/assets/72473361/7eab73d2-ec46-4205-89dd-666ece8dd992)

![exec](https://github.com/temuulino/refundAPI/assets/72473361/cb19147b-66e5-41bd-9859-0222ed997ac3)

In the C# solution, the received data is processed, and a POST request is made to the designated API endpoint. This request includes all the relevant details for executing the refund. Once the API server processes the request, it generates a response that is seamlessly relayed back to the SQL Server.

![c#](https://github.com/temuulino/refundAPI/assets/72473361/50fc7f42-bcee-4a1a-8f98-665b23969c9e)

The integration of this refund API solution has had a profound impact on our operations. First and foremost, it has significantly reduced the burden on our accounting team, eliminating the need for manual refund processing. By automating the refund process, we have expedited the turnaround time for refunds, resulting in improved customer satisfaction and a more efficient resolution of customer inquiries.

Additionally, the user experience has been greatly enhanced. Our application now provides a seamless and intuitive interface for users to access and manage their specific orders. With just a few clicks, users can initiate refund requests, eliminating the need for time-consuming manual interventions.

This solution has not only increased operational efficiency but has also enhanced data accuracy and security. By leveraging the robust capabilities of C# and SQL Server, we have created a secure and reliable system that ensures the integrity of sensitive customer information and maintains compliance with data protection regulations.

In summary, the refund API solution I developed using C# and MSSQL has revolutionized the refund process at White Castle. By automating and streamlining the process, we have achieved faster and more accurate refunds, improved customer satisfaction, and relieved the burden on our accounting team. This innovation has not only optimized internal operations but has also elevated the user experience, ultimately contributing to the overall success of our business.

![ticket](https://github.com/temuulino/refundAPI/assets/72473361/b38faa81-3964-4db4-a9d0-a3b2c88628ca)

