## Medium Blog
- https://medium.com/swlh/erp-pentest-metasploit-writeup-e65de8ece7d1  ( sap rputer exploitatioin )
- https://resources.infosecinstitute.com/topic/pen-stesting-sap-applications-part-1/
- 

## Test Cases 
- https://github.com/Jean-Francois-C/SAP-Security-Audit/blob/master/SAP%20security%20audit%20and%20penetration%20test
- https://github.com/vah13/SAP_exploit (netviewer)
- https://github.com/vah13/SAP_exploit/blob/master/Hardcore-SAP-Penetration-Testing.pdf
- 

## Default Credential

+ List of default SAP accounts and passwords

    Login		 Password		Clients/Mandants
    =================================================
    SAP* 		PASS or 06071992   	000, 001, 066  
    DDIC 		19920706		000, 001
    TSMADM 		PASSWORD		000, 001
    EARLYWATCH 		SUPPORT			066
    SAPCPIC 		ADMIN   		000, 001
    SAPR3 		SAP 			(SAP Local Database)

	RISK 				USER 				PASSWORD 				CLIENT/Mandants 	REMARK
	==========================================================================================================================================================================
	Very High 			SAP* 				06071992 / PASS 			001,066,etc… 		Hardcoded kernel user
	Very High 			IDEADM 				admin					Almost all IDES		clients Only in IDES systems
	Very High 			DDIC 				19920706 				000,001,… 		User has SAP_ALL
	High 				CTB_ADMIN 			sap123 					N.A. 			Java user
	High 				EARLYWATCH 			SUPPORT 				066			Has rights to get password hash for SAP* from USR02 table and sometimes OS execution
	Medium 				TMSADM				PASSWORD / $1Pawd2&     		000, 			sometimes copied to others
	Medium /Low 			SAPCPIC 			ADMIN 					000,001			Can be used for information retrieval and in some cases for vulnerabilities where only
																	authentication is needed
																						
	RISK 				USER 				TYPE 				PASSWORD 				SOLMAN SATELLITE
	==============================================================================================================
	HIGH 				SMD_ADMIN 			System 				init1234 				X
	HIGH 				SMD_BI_RFC 			System 				init1234 				X
	HIGH 				SMD_RFC 			System 				init1234 				X
	HIGH 				SOLMAN_ADMIN 			Dialog 				init1234 				X
	HIGH 				SOLMAN_BTC 			System 				init1234 				X
	HIGH 				SAPSUPPORT 			Dialog 				init1234 				X 		X
	HIGH 				SOLMAN<SID><CLNT> 		Dialog 				init1234 				X
	MED/HIGH 			SMDAGENT_<SID> 			System 				init1234 				X 		X
	MED 				CONTENTSERV 			System 				init1234 				X
	MED 				SMD_AGT 			System 				init1234 
