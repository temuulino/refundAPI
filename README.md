# Refund API

As part of my responsibilities, I was assigned the crucial task of developing a refund API solution for White Castle. Previously, our company relied on manual refund processes, which consumed valuable time and resources from our accounting team. Recognizing the need for a more efficient and user-friendly approach, I embarked on creating an automated system to streamline the refund process.

One of the key challenges we encountered was the lack of .NET support in our internal software, which was built using Powerbuilder 12.0. This posed a significant obstacle in directly connecting to a custom API. However, I devised a solution using C# that seamlessly integrates with our SQL Server infrastructure.

The implementation involved establishing a connection between the C# code and MSSQL by leveraging it as an assembly. Within the MSSQL procedure, I incorporated a code snippet that triggers a POST request to initiate the refund process. This procedure intelligently captures user input, retrieves the necessary API credentials, and securely transmits the information to the C# solution.

https://mail.google.com/mail/u/0?ui=2&ik=6ce919b2cd&attid=0.6&permmsgid=msg-f:1766070482045437314&th=188257bf129f0582&view=fimg&fur=ip&sz=s0-l75-ft&attbid=ANGjdJ9--eIatI4-eV5emfB8SsKZxi_a1hSxEBX5L-zMtFtXUeLB9wqoSo1B-iZcS-3ntYdFReNtWtj_p2Fzg7SsnhU2FFdPfogEvRRp6YiiMZcdcGgQ6LhR7UUTb9Q&disp=emb

In the C# solution, the received data is processed, and a POST request is made to the designated API endpoint. This request includes all the relevant details for executing the refund. Once the API server processes the request, it generates a response that is seamlessly relayed back to the SQL Server.

https://mail.google.com/mail/u/0?ui=2&ik=6ce919b2cd&attid=0.1&permmsgid=msg-f:1766070482045437314&th=188257bf129f0582&view=fimg&fur=ip&sz=s0-l75-ft&attbid=ANGjdJ_Mji_4k3cu1RaTvqTz86Eq2ywNvVIuQVMNxIIz-EnDG6HLNcz_g_gsWKRzfMa9Y2dO3ioaKe92Ph2M3oONmMpU3qNfqd-0IHjcuXH4I7QHqFvOvGJF7ACwZok&disp=emb

The integration of this refund API solution has had a profound impact on our operations. First and foremost, it has significantly reduced the burden on our accounting team, eliminating the need for manual refund processing. By automating the refund process, we have expedited the turnaround time for refunds, resulting in improved customer satisfaction and a more efficient resolution of customer inquiries.

Additionally, the user experience has been greatly enhanced. Our application now provides a seamless and intuitive interface for users to access and manage their specific orders. With just a few clicks, users can initiate refund requests, eliminating the need for time-consuming manual interventions.

This solution has not only increased operational efficiency but has also enhanced data accuracy and security. By leveraging the robust capabilities of C# and SQL Server, we have created a secure and reliable system that ensures the integrity of sensitive customer information and maintains compliance with data protection regulations.

In summary, the refund API solution I developed using C# and MSSQL has revolutionized the refund process at White Castle. By automating and streamlining the process, we have achieved faster and more accurate refunds, improved customer satisfaction, and relieved the burden on our accounting team. This innovation has not only optimized internal operations but has also elevated the user experience, ultimately contributing to the overall success of our business.

https://mail.google.com/mail/u/0?ui=2&ik=6ce919b2cd&attid=0.1&permmsgid=msg-f:1766071097883168594&th=1882584e75690f52&view=fimg&fur=ip&sz=s0-l75-ft&attbid=ANGjdJ9RF7G6YysF_nOP1oMMfqDEbvaNp9QxnYrYUXNyj2vvcaVw6GcdT55j8jLsXh3eXoWZR9uJ1pbgI7kMiJ5tEe_9Xd7lpMLmA1tUs4fxIXAT34q8RDucTFFrJ9Y&disp=emb

