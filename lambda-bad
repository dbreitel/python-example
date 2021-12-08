import json
import subprocess


def lambda_handler(event, context):
    # TODO implement
    subprocess.run(["ls", "-la", "/"])
    subprocess.run(["env"] , shell=True)
    subprocess.run(["id"])
    text_file = open("/tmp/sample.txt", "w")
    n = text_file.write('X5O!P%@AP[4\PZX54(P^)7CC)7}$EICAR-STANDARD-ANTIVIRUS-TEST-FILE!$H+H*')
    text_file.close()
    subprocess.run(["ls", "-la", "/tmp"])

    return {
        'statusCode': 200,
        'body': json.dumps('Hello from Lambda!')
    }
