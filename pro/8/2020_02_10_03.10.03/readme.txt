joint-interpolation: True
imitation-weight: 0.4
replay-buffer-size: 1000000
loss-output-diff-coeff: 0
LLC-frequency: 500
critic-weight-decay: 1e-06
action-dim: 12
max-episode-num: 5000000
actor-activation-fn: ['relu', 'relu', 'None']
epoch-num: 500
loss-output-bound-coeff: 0.0
interpolation: False
categorical-distribution: {'v_min': -10, 'v_max': 250, 'n_atoms': 51}
actor-weight-decay: 1e-06
n-step: 1
critic-layer-size: [256, 256]
prioritized-exp-replay: True
gating-layer-size: [128, 128]
squash-action: True
tau: 0.001
state-dim: 25
total-step-num: 2500000000
loss-output-smooth-coeff: 2.0
gating-mask: [[1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0]]
task-weight: 0.2
batch-size: 128
record-start-size: 10000.0
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
replay-start-size: 10000
max-train-time: 10
expert-num: 8
render-eval: False
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-lr: 0.0003
dsr-gait-freq: 1.667
filter-action: True
gating-activation-fn: ['relu', 'relu', 'None']
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
train-step-num: 1
actor-l2-reg: 0.0003
reward-scale: 0.1
action-bounds: [[-0.39  -2.79   0.66  -0.39  -2.79   0.66  -0.39  -1.884  0.66  -0.39
  -1.884  0.66 ]
 [ 0.39   0.348  2.73   0.39   0.348  2.73   0.39   0.348  2.73   0.39
   0.348  2.73 ]]
rollout-step-num: 1
actor-layer-size: [256, 256]
epoch-step-num: 5000000
goal-weight: 0.4
HLC-frequency: 25
loss-entropy-coeff: 0.0
critic-l2-reg: 0.0003
bullet-default-PD: False
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
critic-activation-fn: ['relu', 'relu', 'None']
replay-ratio: 1
dsr-gait-period: 0.6
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
max-path-step: 5000
max-step-num: 2500000000
max-path-num: 20
gamma: 0.986
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
Physics-frequency: 1000
test-num: 4
filter-torque: False
env-id: HumanoidBalanceFilter-v0
critic-lr: 0.0003
max-test-time: 10
