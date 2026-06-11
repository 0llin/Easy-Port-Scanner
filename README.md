# EZ-C-Port-Scanner
# This is a scripted port scanner written in C programming language for quick port scanning in a Linux environment during an ethical hacking vulnerability test. 

# Permissions must be changed in order to run script
# Once typed and saved on a text editor, go to terminal, cd to file location, and input the following
# 


#include <stdio.h>
/* port.scan.c */

int main()
{
    int port_number;

    printf("Enter a port number to scan: ");

    /* scanf() reads input and stores it in a variable */
    scanf("%d", &port_number);

    printf("Scanning port: %d\n", port_number);

    // port canning logic code will be entered 

    return 0;
}

